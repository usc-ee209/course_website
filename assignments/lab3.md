---
layout: default
title: Lab3
nav: assignments
---

##Lab 3

Please do all parts of this lab

Part 1 Due Sat. 7/5 (electronic submission) before midnight
Part 2  (electronic submission)

    Due Sat. 7/19 before midnight [Extra Credit: 20% addition for this lab]
    Due Tues. 7/22 before midnight [Full credit for the lab]
    Due Thurs. 7/24 before midnight [Max 70% possible for the lab]


Submit Commands (replace the ... below with all other .v files for your design):

  Part 1 

  submit -user ee457lab -tag ee457_lab3_p1 ee457_scpu.v ... names.txt  

 Part 2 

  submit -user ee457lab -tag ee457_lab3_p2 ee457_scpu.v ... names.txt 

Single Cycle CPU Verilog Code Single Cycle CPU Verilog Code item options
Hide Details
Attached Files: 	

    File Single Cycle.rar (8.184 KB) 

Skeleton Codes Skeleton Codes item options
Hide Details
Attached Files: 	

    File ee457_scpu_FOR_STUDENTS.rar (1.741 KB) 

The register file is complete
The HDU needs to be completed
The pipeline register needs to be completed
Instruction Breakdown Excel Instruction Breakdown Excel item options
Hide Details
Attached Files: 	

    File Instruction Break down.xlsx (10.641 KB) 

 Not required to finish the lab, might help you in debugging
Summer 2014 Fixes to Lab 3 code Summer 2014 Fixes to Lab 3 code item options
Hide Details
 Replace your versions of these files with the ones in this zip file.  All of them can be replaced as is, except the ee457_HDU file should only be replaced if you HAVE NOT already modified it.  If you have modified it, just look at what I changed to produce the stall signal as well as IRWRITE and PCWRITE and not flush (since flush should be '1' based on a taken branch).

Changes:
ee457_alu.v  => Fixed 'SLT' instruction bug
ee457_scpu_cu.v => Added support for ADDI instruction so you don't have to.
ee457_regfile_2r1w.v => Internal forwarding now correctly checks if 'wen' is 1
ee457_HDU.v => Changed I/O ports (removing flush)

Feel free to post any questions on Piazza.
