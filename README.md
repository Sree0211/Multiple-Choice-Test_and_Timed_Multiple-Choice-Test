# Multiple-Choice-Test_and_Timed_Multiple-Choice-Test

This C++ program demonstrates the implementation of classes for a multiple-choice test and a timed multiple-choice test. The program defines two classes, MultipleChoiceTest and TimedMultipleChoiceTest, which allow users to set and retrieve answers and times for multiple-choice questions.

## Overview

The program defines two classes:

MultipleChoiceTest: Represents a basic multiple-choice test. Users can set and retrieve answers for each question.

TimedMultipleChoiceTest: Inherits from MultipleChoiceTest and adds the capability to set and retrieve times for each question.

## Classes
MultipleChoiceTest
Constructor: Accepts the number of questions and initializes the answers vector.
setAnswer(int questionIndex, int answer): Sets the answer for a given question index.
getAnswer(int questionIndex) const: Retrieves the answer for a given question index.
TimedMultipleChoiceTest
Constructor: Accepts the number of questions and initializes the answers and times vectors.
setTime(int questionIndex, int time): Sets the time for a given question index.
getTime(int questionIndex) const: Retrieves the time for a given question index.

## Usage
Compile the program using a C++ compiler (e.g., g++).

Run the compiled executable.

## Example
The provided main function demonstrates the usage of the classes. It creates instances of MultipleChoiceTest and TimedMultipleChoiceTest, sets answers and times, and retrieves the stored information.

