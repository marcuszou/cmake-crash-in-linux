# CMake Crash Course in Linux



## Introduction

As per [Wikipedia](https://en.wikipedia.org/wiki/CMake), In software development, CMake is cross-platform free and open-source software for build automation, testing, packaging and installation of software by using a compiler-independent method. CMake is not a build system itself; it generates another system's build files. It supports directory hierarchies and applications that depend on multiple libraries. It can invoke native build environments such as Make, Qt Creator, Ninja, Android Studio, Apple's Xcode, and Microsoft Visual Studio. It has minimal dependencies, requiring only a C++ compiler on its own build system.

CMake is distributed as free and open-source software under a permissive BSD-3-Clause license.

Historically CMake was conceived with the following major features in mind:

- depending only on system C++ compiler, meaning no third-party libraries
- to be able to generate Visual Studio IDE input files
- capable of producing executable and linkable binary libraries (static and shared)
- to be able to run build-time code generators
- separate source/build file trees
- system checks and introspection (similar to Autotools): what system could and could not do
- automatically scan C/C++ dependencies
- cross-platform



## Install CMake in Linux

very easy-

```
sudo apt install cmake
## another lib used in the example
sudo apt install libfmt-dev
```

Check the version:

```
cmake --version
```



## CMake Crash Course by PunchedTape

Resource: [Introduction to CMake Crash Course](https://www.youtube.com/watch?v=7YcbaupsY8I) by PunchedTape

18,526 views  Jun 11, 2022
CMake introduction for absolute beginners.  How to install CMake, create a CMake Project, use sub-directories, and link to libraries.

00:00 Overview
00:30 Installation
00:48 What does CMake do?
01:21 Quickstart CMake Project
02:32 Building with CMake
03:31 CMake variables, PROJECT_NAME
04:38 Building executables & libraries (static and shared)
06:02 Using project libraries
07:37 Using subdirectories
10:58 Finding and linking to external libraries
12:30 Setting C++ standard