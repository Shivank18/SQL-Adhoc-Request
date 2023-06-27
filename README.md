# SQL-Adhoc-Request

We conductd Olympiad exam for our partner schools every year to evaluate the standard of the students. Here we have provided you with the sample data for the exam. To get a proper insight about the exam you need all the 4 tables, data for all those 4 tables are given in the csv file. 

List of tables:
Student_list
Student_response
Correct_answers
Question_paper_code

Table 1: student_list - List of students who attended the Olympiad exam from Google Public School.
Table 2: student_response - The Learn Basics Olympiad is an objective exam, student response for every question was recorded in this table.
5 options ("A', 'B', 'C, 'D' and 'E') are provided for each question
Out of 5 options only "A', 'B', 'C' and D' are the valid options, students can pick E' option when they think they haven't learnt the concept yet.
Table 3: correct_answers - This table has the correct answer for all the questions in math and science.
Table 4: question_paper_code - Since we are dealing with 3 classes and 2 subjects, we are maintaining a separate question paper code for each class and each subject.

Required output of task 1:
Now, the objective is to validate the student response and present it in a single table with list of columns mentioned below using SQL. 
Required output table with column data:

roll_number,
student_name,
class,
section,
school_name,
math_correct,
math_wrong,
math_yet_to_learn,
Math_score,
Math_percentage,
Math_percentage,
Science_wrong,
Science_yet_learn,
Science_score,
Science_percentage
