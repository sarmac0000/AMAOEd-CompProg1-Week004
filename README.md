AMAOEd-CompProg1-Laboratory Exercises
Exercise, C++ application.

C++ Programming Language | VS Code
This repository contains a development environment for Visual Studio code to be used by C++ Programming Language of AMA Online Education.

Requirements
Download and install Visual Studio Code integrated development environment.

I am using MacOs, so we need the XCode extension (clang). To check if g++ is already installed run below command in using the terminal:

  g++ --version
If XCode extension is not yet installed, it will automatically initiate the install for clang.

Recommended Extensions
The following are recommended extensions for VS Code ( Mac: ⌘P ):

EditorConfig for VS Code by EditorConfig:

 ext install EditorConfig.editorconfig
C/C++ by Microsoft:

 ext install ms-vscode.cpptools
Install the g++ compiler
Install clang or g++ by installing the xcode command line tool. To check if already installed, run below command.

  g++ --version
If not yet installed, in my case it automatically download and install the xcode command line tool. I am using Macos Sierra.

After install run the g++ --version again

Code submission / application:
1. Week004 - Hello World
Run below command to compile the code.

  g++ -g src/Week004/hello.cpp -o output/Week004/hello -lm
Run below to test the application you should see Hello World!

  ./output/Week004/hello
1.a Task 1
Run below command to compile the code.

  g++ -g src/Week004/hello1.cpp -o output/Week004/hello1 -lm
Run below to test the application

  ./output/Week004/hello1
1.b Task 2
Run below command to compile the code.

  g++ -g src/Week004/hello2.cpp -o output/Week004/hello2 -lm
Run below to test the application

  ./output/Week004/hello2
1.c Task 3
Run below command to compile the code.

  g++ -g src/Week004/hello3.cpp -o output/Week004/hello3 -lm
Run below to test the application

  ./output/Week004/hello3
  
  
2. Week005 - Getting Input from User

2.a. Write a program that accepts user’s section, and display them back with the format “*** Section: user’s section ***”.
Run below command to compile the code.

  g++ -g src/Week005/section.cpp -o output/Week005/section -lm
Run below to test the application

  ./output/Week005/section
2.b. Write a program that accepts user’s daily budget and display the product of the daily budget and itself.
Run below command to compile the code.

  g++ -g src/Week005/budget.cpp -o output/Week005/budget -lm
Run below to test the application

  ./output/Week005/budget
2.c. Write a program that accepts user’s name, password and address and display them back using the format “Hi, I am user’s name. I live at user’s address.”.
Restrictions:
	Use only three variables.
	Make sure you support spaces. (need to use string library and getline method)
Run below command to compile the code.

  g++ -g src/Week005/userdetail.cpp -o output/Week005/userdetail -lm
Run below to test the application

  ./output/Week005/userdetail
  
  3. Week006 - Condition (IF and SWITCH statements)
3.1. Write a program that will accept an integer and execute one of the following based on the input using IF statements:
a. If 0, display only “Hello World”.
b. If 1, display only “I am Groot”.
c. If 2, display only “To the Top”.
d. If 3, display only “Where is the horizon”.
e. If 4, display only “I do not know”.
f. If none of the above, display only “Yeah, I will.”.
Run below command to compile the code.

  g++ -g src/Week006/if.cpp -o output/Week006/if -lm
Run below to test the application

  ./output/Week006/if
3.2. Write a program that will accept an integer and execute one of the following based on the input using SWITCH statements:
a. If 0, display only “Hello World”.
b. If 1, display only “I am good”.
c. If 2, display only “To the Top”.
d. If 3, display only “Where is the horizon”.
e. If 4, display only “I do not know”.
f. If none of the above, display only “Yeah, I will.”.
Run below command to compile the code.

  g++ -g src/Week006/switch.cpp -o output/Week006/switch -lm
Run below to test the application

  ./output/Week006/switch
3.3. Write a program that will divide the two floating points entered by the user (first number entered divided by the second number entered). Make sure your application handles all possible scenarios with floating points.
Float limits:

    maximum limit = 3.40282e+38  = std::numeric_limits<float>::max()
    minimum limit = -3.40282e+38 = std::numeric_limits<float>::lowest()
Run below command to compile the code.

  g++ -g src/Week006/division.cpp -o output/Week006/division -lm
Run below to test the application

  ./output/Week006/division
  
  4. Week007 - Looping (For, While and Do WHile statements)
4.1. Write a program using WHILE statement that displays a right triangle using asterisks where the height is at the left corner of the application. The height will depend on the user input.
Run below command to compile the code.

  g++ -g src/Week007/while.cpp -o output/Week007/while -lm
Run below to test the application

  ./output/Week007/while
4.2. Write a program using FOR statement that displays a right triangle using asterisks where the height is at the right corner of the application.The height will depend on the user input.
Run below command to compile the code.

  g++ -g src/Week007/for.cpp -o output/Week007/for -lm
Run below to test the application

  ./output/Week007/for
4.3. Write a program using DO WHILE statement that displays an inverted equilateral triangle using asterisks. No asterisk should be adjacent to one another. The height will depend on the user input.
[Hint]  You can use an IF statement to eliminate the initial space for the first row.

Run below command to compile the code.

  g++ -g src/Week007/dowhile.cpp -o output/Week007/dowhile -lm
Run below to test the application

  ./output/Week007/dowhile
  
  5. Week008 - Dimensions of Data Types (Arrays)
5.1. Write a program that will accept five (5) integers and display them to the users. You are limited to using only two (2) variables (including the array).
Run below command to compile the code.

  g++ -g src/Week008/array2var.cpp -o output/Week008/array2var -lm
Run below to test the application

  ./output/Week008/array2var
5.2. Write a program that will display an equilateral triangle with a height depending on the user. The minimum height is 1, the maximum height is 10. Use an array to display the specific character on the specific row. The array will be: { 0 := “A”, 1:= “B”, 2 := “C”, 3 := “D”, 4 := “E”, 5 := “F”, 6 := “G”, 7 := “H”, 8 := “I”, 9 := “J” }. You are limited to four (4) variables only (including the array).
Run below command to compile the code.

  g++ -g src/Week008/arrayTriangle.cpp -o output/Week008/arrayTriangle -lm
Run below to test the application

  ./output/Week008/arrayTriangle
5.3. Write a program that will ascendingly sort six (6) integers from the user. Use only four (4) variables (including the array).
Run below command to compile the code.

  g++ -g src/Week008/arraySort.cpp -o output/Week008/arraySort -lm
Run below to test the application

  ./output/Week008/arraySort
  
  6. Week009 - Introduction to Functions Procedures
6.1. Write a program that can divide six non-zero integers (two integers per division) from the user and display the result to the user. Create a function that will perform the division operation. Display only the non-decimal part of the quotient.
Run below command to compile the code.

  g++ -g src/Week009/functionDivision.cpp -o output/Week009/functionDivision -lm
Run below to test the application

  ./output/Week009/functionDivision
6.2. Write a program that will accept a short value from 10 to 99 and display them per digit (separated by a space).
Run below command to compile the code.

  g++ -g src/Week009/functionDigit.cpp -o output/Week009/functionDigit -lm
Run below to test the application

  ./output/Week009/functionDigit
6.3. Write a program that will display the nth Fibonacci number. Create a function that will generate the nth Fibonacci number. Fibonacci numbers are numbers from the Fibonacci sequence which follows the pattern of 1, 1, 2, 3, 5, 8, 13, 21, 33, 54…
Run below command to compile the code.

  g++ -g src/Week009/functionFibonacci.cpp -o output/Week009/functionFibonacci -lm
Run below to test the application

  ./output/Week009/functionFibonacci
  
  7. Week010 - Object-Oriented Programming 1
7.1. Write a class that will represent a legged mammal. Consider the number of legs, kind of fur, presence of tail.
Run below command to compile the code.

  g++ -g src/Week010/task1/main.cpp -o output/Week010/mammal -lm
Run below to test the application

  ./output/Week010/mammal
7.2. Write a class that will represent a person. Consider the name, address, gender, age and occupation.
Run below command to compile the code.

  g++ -g src/Week010/task2/main.cpp -o output/Week010/person -lm
Run below to test the application

  ./output/Week010/person
7.3. Write a class that will represent polygon. Consider the name, number of sides and color.
Run below command to compile the code.

  g++ -g src/Week010/task3/main.cpp -o output/Week010/polygon -lm
Run below to test the application

  ./output/Week010/polygon
  
  8. Week011 - Object-Oriented Programming 2
8.1. Write a class that extends the LeggedMammal class from the previous laboratory exercise. The class will represent a dog. Consider the breed, size and is registered. Initialize all properties of the parent class in the new constructor. This time, promote the use of accessors and mutators for the new properties.
Run below command to compile the code.

  g++ -g src/Week011/task1/main.cpp -o output/Week011/dog -lm
Run below to test the application

  ./output/Week011/dog
8.2. Write a class that extends the Person class from the previous laboratory exercise. The class will represent a student. Consider the academic program, year in college and enrolled university. Initialize all the properties of the parent class in the new constructor. This time, promote the use of accessors and mutators for the new properties.
Run below command to compile the code.

  g++ -g src/Week011/task2/main.cpp -o output/Week011/student -lm
Run below to test the application

  ./output/Week011/student
  
  9. Week012 - It's All about Pointers and References 1
9.1. Write a program that will display the value and logical address of an integer variable with an initial value of 900.
Run below command to compile the code.

  g++ -g src/Week012/integer.cpp -o output/Week012/integer -lm
Run below to test the application

  ./output/Week012/integer
9.2. Write a program that will display the value and logical address of an uninitialized character array with size ten (10) and a pointer pointing to the array. (Hint: you may need to perform some casting.)
Run below command to compile the code.

  g++ -g src/Week012/char.cpp -o output/Week012/char -lm
Run below to test the application

  ./output/Week012/char
9.3. Write a program that will display the value and logical address of an uninitialized float array with size twenty (20) and a reference pointing to the array.
Run below command to compile the code.

  g++ -g src/Week012/float.cpp -o output/Week012/float -lm
Run below to test the application

  ./output/Week012/float
