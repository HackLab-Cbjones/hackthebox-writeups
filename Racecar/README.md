# HTB: Racecar

## Overview
The objective of this lab was to reverse engineer the code and find the vulnerability within the code to then extract the flag and decode it.

## Skills Demonstrated
-Linux Commands
-Reverse Enginering
-Coding

## Tools used
-Command Terminal
-Ghidra
-Sublime text
-Python

## Process of Completion
First I downloaded file off of hack the box, then I unzipped the file, then played the mini game and noticed the text file was not working.
I then created a flag.txt file to then open up the text box after you win.
After opening the text file, I then use the %p to map out the memory addresss of where the flag is stored.
Next I used Ghidra to open the file and read the code.
After finding out where the flags string was located in the code I created a payload to extract the flag.

## Explotation
-Array of strings in the code

## Proof
Racecar 1-5 PNG
