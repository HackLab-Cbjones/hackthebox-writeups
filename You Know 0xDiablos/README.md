# HTB: You Know 0xDiablos

## Overview
The objective of this lab was to use a buffer overflow attack on the network HTB gave us

## Skills Demonstrated
-Linux Commands
-Reverse Enginering
-Coding

## Tools used
-Ghidra
-GNU gdb
-Python
-Command Terminal

## Process of Completion
First you download the file given on HTB and unzip it. If you cat the file you gain a hint saying try again on the server side.
Then you open up a Ghidra to analyze the code and search for some kinda code thats vulnerable and keep track of the memory address of a flag function.
Next I downloaded and used Gnu gdb and find out we need 180 character limit to perform the buffer overflow attack on the vulnerable code.
I then run the file on vuln to get the pattern offset and then try to run the payload and extract the flag.


## Explotation
-Buffer Overflow

## Proof
Diablos 1-8 PNG
