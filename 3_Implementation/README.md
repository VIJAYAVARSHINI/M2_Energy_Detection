## Components
Component     | Description
--------------| ----------------------------------------------
Current Source| Acts as input for current from user
Atmega328     | Microcontroller with source code
LED bulb      | To sense the over current
Hd44780-6     | To display the output

## Manual

### Setup to run Project

- An integrated development environment (Suggesting Visual Studio Code).
- GCC compiler to compile the project.
- "make" to run the Makefile smoothly.

### Steps To run Project

1. First clone the repository from the Github.
2. Open the repository in an IDE (Suggesting Visual Studio Code).
3. The next step is to build the project with the help of make command :
   - make all
4. Next step is to run the project with help of make command :
   - make run
5. If you want to run the test cases then run the following command :
   - make test
6. Clean all executable files by the following command :
   - make clean
