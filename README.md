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
4. Add __C:\masm32\bin\__ to your PATH in device manager environment variables
5. $FILENAME is the name of your .asm file

=======================
COMPILATION AND LINKING
=======================

ml -c -Zd -coff $FILENAME.asm
Link -SUBSYSTEM:CONSOLE $FILENAME.obj

Use following commands to compile and link your .asm files respectively

```
