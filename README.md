# CUP: C++ Unified Project
============================

Overview
--------------
This quick start for writing C++ programming  on linux and Windows.
It contains gtest framework. It also contains mockcpp framework on Linux.

### Windows requirements ###
There is only support gtest only, and requirement as followed:
* cmake 12.8 or later
*  VS2005 or VS2008 or VS2010

### Linux requirements ###
* cmake 12.8 or later
* gcc 4.8 or later

### Windows Quick start  ###
build.bat YourProjectName  ##to be checked

### Linux Quick Start ###

1.  mkdir -p 3th/lib 3th/include
2.  ./config.sh   YourProjectName   YourProjectBitsSupported
3.  ./install.sh
4.  ./build.sh

YourProjectBitsSupported: 32Bits  or 64Bits
