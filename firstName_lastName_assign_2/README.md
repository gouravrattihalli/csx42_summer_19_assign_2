# CSX42: Assignment 2
## Name: 

-----------------------------------------------------------------------
-----------------------------------------------------------------------


Following are the commands and the instructions to run ANT on your project.
#### Note: build.xml is present in racingDrivers/src folder.

-----------------------------------------------------------------------
## Instruction to clean:

####Command: 
ant -buildfile racingDrivers/src/build.xml clean

Description: It cleans up all the .class files that were generated when you
compiled your code.

-----------------------------------------------------------------------
## Instruction to compile:

####Command: ant -buildfile racingDrivers/src/build.xml all

Description: Compiles your code and generates .class files inside the BUILD folder.

-----------------------------------------------------------------------
## Instruction to run:

####Command: 
ant -buildfile racingDrivers/src/build.xml run -Darg0=<inputFile.txt> -Darg1=<outputFile.txt> -Darg2=<Logger-Value> 

Example:

ant -buildfile racingDrivers/src/build.xml run -Darg0=inputFile.txt -Darg1=outputFile.txt -Darg2=3



-----------------------------------------------------------------------
## Description:


-----------------------------------------------------------------------
### Academic Honesty statement:
-----------------------------------------------------------------------

"I have done this assignment completely on my own. I have not copied
it, nor have I given my solution to anyone else. I understand that if
I am involved in plagiarism or cheating I will have to sign an
official form that I have cheated and that this form will be stored in
my official university record. I also understand that I will receive a
grade of 0 for the involved assignment for my first offense and that I
will receive a grade of F for the course for any additional
offense.""

Date: -- 


