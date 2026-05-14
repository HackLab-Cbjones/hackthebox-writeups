# HTB:Restaurant

## Overview
The objective of this lab is to buffer overflow the code to then leak the input through a puts function.

## Skills Demonstrated
-Linux Commands
-Buffer Overflow
-Coding

## Tools used
-Command Terminal
-Ghidra
-PWN
-Python

## Process of Completion
First you have to run the executable from the file I unzip from Hackthebox.
Next I see no PIE or Stack. I then run the program and enter different answers to see what comes back.
Additionaly I open the code up on Ghidra to analyze the code for a flag file or vulnerable strings/commands/code.
Another hint given by this exercise was "Dont over do it" hinting at a buffer overflow attack.
I then created a payload to send execution flow to the "bin/sh" which then reads me the flag.

## Explotation
-Buffer overflow
-Vulnerable code

## Proof
Restaurant 1-7 PNG
