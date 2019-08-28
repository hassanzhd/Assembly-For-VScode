# Assembly Language(x86) Programming Setup For Visual Studio Code

## Description

Clone the repository and follow the steps mentioned below.

## Steps:-

```
==========
EXTRACTION
==========

1. Extract masm32 and Irvine folder to C:\ drive.
2. Use Includes and program structure like sample.asm
3. Make sure to have all files in different folders to make them work properly like projects

=======================
COMPILATION AND LINKING
=======================

C:\masm32\bin\ml /c /Zd /coff *.asm
C:\masm32\bin\Link /SUBSYSTEM:CONSOLE *.obj

Use following commands to compile and link your .asm files respectively

```
