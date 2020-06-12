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
