---
layout: default
title: Tools and Links
nav: tools
---

### Supplemental Logic Design Lecture videos
Links to Prof. Redekopps's [online logic design course lectures](https://marksee101.appspot.com/)

### Practice Exams
#### Exam 1
 - [Don't Make These Mistakes](http://ee.usc.edu/~redekopp/ee209/EE209LogicMistakes.pdf) - Student mistakes from previous exams...No solutions (try them and compare with friends).
 - [Sample Combinational Questions](http://ee.usc.edu/~redekopp/ee209/SampleLogicExam1.pdf)
 - [Sample Combinational Questions Solutions](http://ee.usc.edu/~redekopp/ee209/SampleLogicExam1Sol.pdf)
 - [Sample Midterm](http://ee.usc.edu/~redekopp/ee209/SampleCumulativeExam.pdf)
 - [Sample Midterm Solutions](http://ee.usc.edu/~redekopp/ee209/SampleCumulativeExamSol.pdf)

#### Exam 2
 - [Sample Midterm](http://ee.usc.edu/~redekopp/ee209/SampleMidterm2.pdf)
 - [Sample Midterm Solutions](http://ee.usc.edu/~redekopp/ee209/SampleMidterm2Sol.pdf)

### Logic Trainer Board
See the description [here](http://ee.usc.edu/~redekopp/ee101/LogicTrainerUserManual.pdf).

### Xilinx Setup

#### Using Xilinx on the Viterbi Virtual Desktop (VDI) System
As an engineering student enrolled in this EE course, we will give you access to the Viterbi Virtual Desktop Interface (VDI) system which allows you to open a remote desktop/virtual machine with all the engineering software preloaded.  You will need to follow [these directions](http://viterbi.usc.edu/assets/195/94372.pdf) to first install the VDI client and connect.  Once connected you can find Xilinx `ISE Design Suite 14.7` icon on the desktop or search for it in the programs menu.  Remember your files only persist in your `Documents` folder and are lost after each semester.
 
#### Install Modelsim Webpack on your Windows PC 
Follow [these directions](http://ee.usc.edu/~redekopp/ee209/Xilinx14_7Install_2015.pdf)

  - For those running Windows 8 or 10 you might try this [link](http://www.eevblog.com/forum/microcontrollers/guide-getting-xilinx-ise-to-work-with-windows-8-64-bit/) for tips on getting the installation to work on your OS.

#### Run Xilinx on the Viterbi IT Virtual Desktop Interface.
You can use an Mac or Windows client PC and VMWare's Horizon Client software to connect to a virtual (remote) desktop system where you can run the Xilinx software.  Follow the directions linked below.

  - [Directions for installing VMWare's Horizon Client and connecting to the remote desktop servers](http://viterbi.usc.edu/assets/195/94372.pdf)
  - Notes:
    + Sometimes you have to connect twice (or enter your login info twice).
    + You should save your work in the `U:` drive which will persist from session to session for the length of the semester.  **Any work saved in any other area will usually be deleted nightly**.
    + Let us know if you encounter errors by posting on Piazza.    
    
#### Xilinx Introductory Tutorial Videos
Please watch the following 4 videos to learn the basics of using the Xilinx tools:

  1. [Project Creation](http://ee.usc.edu/~redekopp/Streaming/ee101_xilinx13_project_creation/ee101_xilinx13_project_creation.html)
  1. [Schematic Entry](http://ee.usc.edu/~redekopp/Streaming/ee101_xilinx13_schematic_entry/ee101_xilinx13_schematic_entry.html)
  1. [Testbench Creation](http://ee.usc.edu/~redekopp/Streaming/ee101_xilinx13_tb_entry/ee101_xilinx13_tb_entry.html)
  1. [Simulation with ISim](http://ee.usc.edu/~redekopp/Streaming/ee101_xilinx13_isim/ee101_xilinx13_isim.html)
  
#### Xilinx "Advanced" Tutorial Videos
Please watch the following 3 videos to learn the basics of using the Xilinx tools:

  1. [Advanced Schematic Entry](http://ee.usc.edu/~redekopp/Streaming/ee101_xilinx13_adv_entry/ee101_xilinx13_adv_entry.html)
  1. [Advanced Testbench Creation](http://ee.usc.edu/~redekopp/Streaming/ee101_xilinx13_adv_sim/ee101_xilinx13_adv_sim.html)
  1. [Synthesis Creation](http://ee.usc.edu/~redekopp/Streaming/ee101_xilinx13_adv_synth/ee101_xilinx13_adv_synth.html)

  
### Digilent Adept Software Installation
The Digilent Adept software is used to download the HW configuration files produced by Xilinx onto our Nexys-2 boards so we can see our design run.  Follow the link below and install the software:

  1. [Adept for Windows](http://www.digilentinc.com/Data/Products/adept2/digilent.adept.system_v2.16.1.exe)
  1. [Adept for Linux](http://www.digilentinc.com/Products/Detail.cfm?Prod=ADEPT2)


### Cadence Virtuoso Setup
Cadence is a major technology company in the electronic design automation (EDA) industry.  Its Virtuoso tool is an industry standard tool that we will teach you a bit about.  Please go through the following documents to get the software setup. It only runs on USC's UNIX servers so you'll need to setup your account.  You can use your USC username and email to login to the UNIX servers but will need some kind of remote access software PuTTY, VNC, X-Win Server, etc.  Go through the following documents.  If you have any problems, just post on Piazza.

  1. [USC Unix Account Setup](http://ee.usc.edu/~redekopp/ee209/virtuoso/setup/UnixAccountSetup.pdf)
  1. [USC Virtuoso Tutorial](http://ee.usc.edu/~redekopp/ee209/virtuoso/setup/USCVLSI-VirtuosoTutorial.pdf)
     - [cshrc login script](http://ee.usc.edu/~redekopp/ee209/virtuoso/setup/cshrc_linux)
     - [tsmc.spice technology-specific file](http://ee.usc.edu/~redekopp/ee209/virtuoso/setup/tsmc.spice)
     - [vlsi_tools.csh](http://ee.usc.edu/~redekopp/ee209/virtuoso/setup/vlsi_tools.csh)

### Using VNC to Remote-Desktop to aludra
The Cadence tools are accessible only on USC's UNIX servers (student server is `aludra.usc.edu`).  While you can use tools like X11 or X-Win to remote desktop to aludra, VNC is a thin remote-desktop client that is very fast and requires minimal network bandwidth.  

To install and use VNC, follow [these instructions](http://ee.usc.edu/~redekopp/ee209/VNC_setup.pdf)
  - Note:  To login to aludra to just start VNC, you need not use X-Win but can use PuTTy on Windows machines and Terminal/`ssh` on Mac.