Project Report: Math Quiz Game
Introduction
This report outlines the development and implementation of a math quiz game application. The primary objective of the project was to create an interactive and educational tool that challenges users with arithmetic problems at varying difficulty levels. The game incorporates fundamental arithmetic operations (addition, subtraction, multiplication, and division) and offers customizable settings for users to tailor the quiz experience to their preferences.




Project Overview
The math quiz game is a console-based application developed in C++. It presents users with a series of arithmetic problems, ranging from easy to hard. Users can select the desired difficulty level, operation type (addition, subtraction, multiplication, division, or a mix), and the number of questions. The application generates random arithmetic problems based on the user's selections and provides immediate feedback on the correctness of the answers.



System Design and Implementation


The application's core components include:



Data Structures:


enQuestionsLevel and enOperationType enums for representing question difficulty and operation types.


stQuestion struct to store information about each question (numbers, operation, correct answer, player answer, and result).



stQuizz struct to manage quiz settings, questions, and results.


Functions:


RandomNumber: Generates random numbers within a specified range.



ReadOpType, ReadQuestionsLevel, and ReadHowManyQuestions: Handle user input for quiz settings.



SimpleCalculator: Performs arithmetic calculations based on given operands and operation.






GenerateQuestion: Creates a random arithmetic question based on difficulty and operation type.




GenerateQuizzQuestions: Populates the quiz structure with generated questions.




PrintTheQuestion: Displays a question to the user.




CorrectTheQuestionAnswer: Evaluates the user's answer and provides feedback.




AskAndCorrectQuestionListAnswers: Manages the quiz flow, asking questions and correcting answers.




PrintQuizzResults: Displays final quiz results.




Functionality




The math quiz game provides the following functionalities:









Customizable quiz settings (difficulty level, operation type, number of questions)




Randomly generated arithmetic problems




Immediate feedback on answer correctness




vFinal quiz results, including number of correct and incorrect answers




Replay option




Testing and Evaluation




The application has been tested with various input values and combinations to ensure correct functionality. The random number generator has been verified to produce a wide 



range of values. The arithmetic calculations have been tested for accuracy across different operation types. User interface elements have been evaluated for clarity and 



user-friendliness.









Conclusion




The developed math quiz game effectively fulfills its intended purpose of providing an interactive and educational arithmetic practice tool. The application's modular 



design and clear code structure enhance maintainability and potential for future enhancements.




