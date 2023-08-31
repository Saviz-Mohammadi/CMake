# CMake template project

This CMake template enables the setup of C++ projects. Please bear in mind that while this project isn't flawless, it's designed to help new programmers establish C++ projects swiftly and effectively. We plan to periodically enhance its features, so stay tuned for updates. We hope you find it valuable!

<br>
<br>

## Getting Started

Follow these instructions to set up a C++ project using this template.

<br>

### Prerequisites

Ensure that you have the following set of tools installed on your personal machine:

```diff
CMake
C++ Compiler (e.g., g++, clang++, MSVC)
```

<br>

### Usage

In the 'source' directory, please make sure the following set of directories exists. If they are missing, create them before utilizing the project:
```diff
src        # Place source files in this folder.
include    # Place header files in this folder.
lib        # Place third-party libraries in this folder.
```

<br>

In the 'build' directory, please make sure the following set of directories exists. If they are missing, create them before utilizing the project:
```diff
temp       # CMake will place project and temporary files in this folder.
bin        # CMake will place targets in this folder after building them.
```

<br>

You are now prepared to configure and build your project using CMake. Please navigate your terminal to the 'temp' folder and execute the instructions provided in the 'instructions.txt' file.
