<!-- To preview this markdown file in VSCode: Ctrl+Shift+V -->

# CS2 Portfolio - Bushra Rahman
## CS 2336 (Computer Science II) | UTD Spring 2020

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

## Instructions to Install Java
The Java Development Kit (JDK) is necessary to run these assignments (since it contains the `javac` bytecode compiler and the Java Runtime Environment (JRE), which is used to run Java applications and which contains the Java Virtual Machine (JVM), which is used to execute Java bytecode).

To install Java JDK on Windows 11 or less, follow [these instructions](https://github.com/br815/CS1_Portfolio/blob/main/CS1337/Eclipse_for_Windows_with_MinGW.pdf) (jump to Pages 1-2 of the linked PDF):
1. Download the x64 installer (`.exe` extention) for the latest version of the Standard Java SE Development Kit from [this Oracle link](https://www.oracle.com/java/technologies/downloads/).
2. Run the installer. Don’t make any changes with the installer.
3. Add the Java JDK the `Path` Environment Variable. [This YouTube video](https://www.youtube.com/watch?v=uadGsNA6h5Q) has the steps to follow:
    * Open `Control Panel >> System and Security >> System >> Advanced System Settings`.\
    (Alternatively, open `Settings >> System >> About >> Advanced System Settings`.)\
    This opens a window for `System Properties`.
    * In `System Properties`, go to `Environment Variables`.\
    In `Environment Variables`, look down at `System variables` and scroll until you reach `Path`.\
    Select `Path` and hit `Edit`.
    * Once you’ve opened `Edit environment variable`, find the file path for Java JDK’s `/bin` folder in your File Explorer and copy it.\
    It should look similar to:
    <!-- CODE START -->
    ```
    C:\Program Files\Java\jdk-12\bin
    ```
    <!-- CODE END -->
    * Go back to `Edit environment variable`, hit `New`, and paste the file path for `/bin`.
    * Then hit `OK` in `Edit environment variable`, hit `OK` in `Environment Variables`, and hit `OK` in `System Properties`.
    * Java JDK should now be properly installed and locatable within `Path`. To test in Command Prompt, run:
    <!-- CODE START -->
    ```
    java --version
    ```
    <!-- CODE END -->
    You should see output similar to:
    <!-- CODE START -->
    ```
    java version "12" 2019-03-19
    Java(TM) SE Runtime Environment (build 12+23)
    Java HotSpot(TM) 64-Bit Server VM (build 12+23, mixed mode, sharing)
    ```
    <!-- CODE END -->

## Homework Instructions & READMEs
* ...

## READMEs
* ...

## Notes
As a learning exercise, some of my code explores alternative designs that go beyond what was required for this course.

This code is not intended as production software.
