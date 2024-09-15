## StudentGradeTracker

## Overview

`StudentGradeTracker` is a simple Java application that allows users to input student grades and calculates basic statistics from them. The program reads grades from the console until the user types 'done'. It then computes and displays the average, highest, and lowest grade.

## Features

- **Grade Input:** Allows users to input multiple grades.
- **Error Handling:** Provides error messages for invalid inputs.
- **Statistics Calculation:** Computes and displays the average, highest, and lowest grade.

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- A command-line interface (CLI) for running the Java application

## Installation

1. Clone this repository to your local machine using Git:
   ```sh
   git clone https://github.com/yourusername/StudentGradeTracker.git

2. Navigate to the project directory:
   cd StudentGradeTracker

## Usage

1. Compile the Java Program:
   javac StudentGradeTracker.java

2. Run the Compiled Java Program:
   java StudentGradeTracker

3. Follow the Prompts:
   -Enter grades one by one.
   -Type done when you are finished entering grades.

4. View Results: The program will output the average, highest, and lowest grade.

## Example
    Enter student grades (type 'done' to finish):
85
90
78
92
done
Average: 86.25
Highest: 92.00
Lowest: 78.00

## Error Handling

If a non-numeric input is entered, the program will prompt the user to enter a valid number or type 'done' to finish.
