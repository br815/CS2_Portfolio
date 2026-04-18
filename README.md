<!-- To preview this markdown file in VSCode: Ctrl+Shift+V -->

# CS2 Portfolio - Bushra Rahman
## CS 2336 (Computer Science II) - UTD Spring 2020

GitHub Pages link: https://br815.github.io/CS2_Portfolio/

This repository contains university programming assignments from my [Computer Science II course](/CS2336).

The purpose of this repository is archival and educational:
- to track my progress learning Java
- to practice writing clear, correct, and well-structured code
- to reflect on design decisions and showcase my improved understanding of the language

## Highlights
- Recursive algorithms
- Implementation of fundamental data structures like linked lists, stacks, and queues
- Implementation and use of advanced data structures like binary trees, hash tables, and graphs

## Instructions to Install MinGW
Compilers for C and C++ are necessary to run these assignments (eg. the gcc and g++ compilers in MinGW, a Microsoft Windows port of the GNU Compiler Collection).

To install MinGW on Windows 11 or less, follow these instructions:
1. Download the latest version of the MinGW installer from [this SourceForge link](https://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win64/Personal%20Builds/mingw-builds/).
2. Run the installer. On the second installer screen, make sure to select the X86_64 architecture. Don’t make any other changes with the installer.
3. Add the MinGW compiler the “Path” Environment Variable. [This YouTube video](https://www.youtube.com/watch?v=uadGsNA6h5Q) has the steps to follow:
    * Open Control Panel >> System and Security >> System >> Advanced System Settings.\
    (Alternatively, open Settings >> System >> About >> Advanced System Settings.)
    * In Advanced System Settings, go to Environment Variables. In Environment Variables, look down at System Variables and scroll until you reach “Path”. Select “Path” and hit Edit.
    * Once you’ve opened Edit Environment Variable, find the file path for MinGW’s bin folder in your File Explorer. It should look similar to:
    <!-- CODE START -->
    ```
    C:\Program Files\mingw-w64\x86_64-8.1.0-posix-seh-rt_v6-rev0\mingw64\bin
    ```
    <!-- CODE END -->
    * Copy the file path for bin, go back to Edit Environment Variable, hit “New” and paste the file path for bin.
    * Then hit OK in Edit Environment Variable, hit OK in Environment Variables, and hit OK in System Properties.
    * MinGW should now be properly installed and locatable within Path. To test in Command Prompt, run:
    <!-- CODE START -->
    ```
    g++ --version
    ```
    <!-- CODE END -->
    You should see output similar to:
    <!-- CODE START -->
    ```
    g++ (MinGW.org GCC-6.3.0-1) 6.3.0
    Copyright (C) 2016 Free Software Foundation, Inc.
    This is free software; see the source for copying conditions.  There is NO
    warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
    ```
    <!-- CODE END -->

## Homework Instructions & READMEs
* ...

## READMEs
* ...

## Notes
As a learning exercise, some of my code explores alternative designs that go beyond what was required for this course.

This code is not intended as production software.
