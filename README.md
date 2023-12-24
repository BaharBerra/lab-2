# Online Examination System with Formula Calculation

This repository contains the source code and documentation for an Online Examination System with Formula Calculation developed as a part of the Software Engineering course at KHPI.

## Table of Contents

- [Introduction](#ıntroduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Lab Reports](#lab-Reports)
  - [Lab 1: Modelling of Domain](#lab-1-modelling-of-domain)
  - [Lab 2: Coding of Domain](#lab-2-coding-of-domain)
  - [Lab 5: Testing C++ Code](#lab-5-testing-c++-code)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project documents the process of developing an Online Examination System with Formula Calculation. The system involves actors such as Students, Instructors, and the System itself. The main flow includes actions like logging in, selecting exams, answering questions, and evaluating results.

## Features

1. **Online Examination System**
   - Users (Students, Instructors, System) can log in and interact with the system.
   - Students can take exams, answer questions, and view results.
   - Instructors can view student results.

2. **Formula Calculation**
   - The system includes formula-based questions in exams.
   - Supports the entry of required values for formula calculation.

3. **Use Case and Activity Diagrams**
   - Visual Paradigm diagrams illustrating system interactions and flow.

4. **C++ Implementation**
   - Basic C++ program calculating values based on a predefined formula.
   - Illustrates the use of if-else statements and loops.

## Getting Started

Before you begin, ensure you have the following installed:

- C++ compiler (e.g., GCC)
- Visual Studio Code or any C++ IDE
- Visual Paradigm for modeling diagrams (optional)
- Google Test framework for unit testing (optional)

To run the Online Examination System locally, follow these steps:

- Install a C++ compiler on your computer.
- Open the project in your preferred C++ development environment.
- Clone the repository: `git clone https://github.com/BaharBerra/online-exam-system.git`
- Navigate to the project directory: `cd online-exam-system`
- Compile and run the code to see the results.
  
## Lab Reports

## Lab 1: Modelling of Domain
In Lab 1, the focus was on learning how to create use case and activity diagrams using Visual Paradigm. The diagrams represent the interactions and flows within the system, helping to identify and describe the system's functionalities.

### Use Case Diagram

Online Examination System with Formula Calculation 

![image](https://github.com/BaharBerra/lab-2/assets/119218082/4b2a5365-0eb0-4830-9449-4f51de873356)

The use case diagram illustrates the interactions between the system, students, and instructors. It helps in understanding the main functionalities and boundaries of the system.

### Activity Diagram

![image](https://github.com/BaharBerra/lab-2/assets/119218082/23b2d0f5-4aa6-43b5-bc95-8748c4beb46b)

The activity diagram depicts the flow of activities within the system, including the main flow and alternate flows. It provides insights into the sequential or parallel execution of tasks.

## Lab 2: Coding of Domain

Lab 2 aimed at learning the basic principles of C++ programming language. The task involved developing a computational algorithm based on a given formula. The code was implemented in Visual Studio, and the report details the learning process.

![image](https://github.com/BaharBerra/lab-2/assets/119218082/9b38a208-6d96-4c4e-9ebc-649a1344882b)

Input Requirements:

Ensure n is greater than 1.
Provide a value for x.

Build and Run:

Compile and run the program.

Results:

The program will output the computed result based on the provided inputs.

### Program Logic
The program employs conditional statements to determine the calculation method based on the value of x. If x is less than or equal to 0, it performs a product calculation; otherwise, it utilizes nested loops to compute a sum.

Input Examples

Input n>1, n=3
Input x = 2

Output Example

x= 2; y= 0 Result: 32

![image](https://github.com/BaharBerra/lab-2/assets/119218082/e7876019-727d-47ad-9766-1fe75a4dac4d)
![image](https://github.com/BaharBerra/lab-2/assets/119218082/5dc03b58-7302-4d7c-929c-c19aa433d8ed)


## Lab 5: Testing C++ Code

Lab 5 delves into the principles of testing C++ code. The report discusses the importance of testing, background on different testing methods, and the methodology followed to practice writing effective test cases.

### Background

Testing C++ code involves various methods such as manual testing, automated testing, and unit testing. Each method has its own advantages and drawbacks, and the choice depends on the project's requirements.

### Methodology

To learn the principles of testing C++ code, the following steps were followed:

1. Researching best practices and guidelines for testing C++ code.
2. Studying examples of tests for C++ code to understand their structure and purpose.
3. Writing tests for C++ code by creating test cases for a simple program.
4. Receiving feedback on tests and incorporating improvements.

### Refactor and Integration Tests

The code was refactored for improved efficiency, maintainability, and readability. Integration tests were run to verify that the program still produces the expected output.

### Continuous Testing and Integration

Establishing continuous testing and integration is crucial for maintaining program reliability. Utilize CI/CD tools such as Jenkins or Travis CI to automatically run tests and detect issues early.

## Contributing

Contributions are welcome! If you find any issues or have improvements to suggest, feel free to open an issue or submit a pull request.


## License

This project is free and open-source, and you are welcome to use, modify, and distribute the code for any purpose without any restrictions. Feel free to incorporate it into your projects.

Happy coding!
