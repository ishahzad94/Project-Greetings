Project : calculator_project/
          |-- main/
          |   |-- main.cpp
          |   |-- CMakeLists.txt
          |-- src/
          |   |-- Calculator.cpp
          |   |-- Calculator.h
          |   |-- CMakeLists.txt
          |-- tests/
          |   |-- CMakeLists.txt
          |   |-- calculator_test.cpp
          |-- robot_tests/
          |   |-- calculator.robot
          |-- build/
          |-- bin/
          |-- lib_gtest/ (Downloaded Google Test will be placed here)
          |-- CMakeList

calculator_project/ (root directory):

The main project directory that contains the entire project structure.
main/:

Directory for the main application source code and build configuration.
main.cpp: The main source code file for your calculator application.
CMakeLists.txt: The CMake configuration file for building the main application.
src/ (source code directory):

Directory for the source code and build configuration for your calculator class.
Calculator.cpp: Source code for your calculator class.
Calculator.h: Header file for your calculator class.
CMakeLists.txt: The CMake configuration file for building the calculator class.
tests/:

Directory for unit tests.
CMakeLists.txt: The CMake configuration file for building the unit tests.
calculator_test.cpp: Source code for unit tests for your calculator class.
robot_tests/:

Directory for Robot Framework tests.
calculator.robot: A Robot Framework test suite for your calculator application.
build/:

Directory where CMake build files and intermediate build artifacts are typically generated when you build the project.
bin/:

Directory where you can place the compiled binary/executable of your calculator application once it's built.
lib_gtest/:

Directory to store the downloaded Google Test (gtest) library, which is a popular C++ testing framework.
CMakeLists.txt (assuming this is a typo and should be CMakeLists.txt):

This file should be the top-level CMake configuration file for your project, defining how to build the entire project and set up dependencies.
