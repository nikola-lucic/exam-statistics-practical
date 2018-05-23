# exam-statistics-practical
exam-statistics-practical

# Exam statistics


The goal of this exercise is to write a code for the web application that helps with the exam statistics. 

The application should be developed with the following use-case scenario on mind. Firstly, a user can select the name of the subject from the select list provided in the left part of the form. Then, the user can type in the name and surname of the student. Finally, the user can select a grade from the list provided in the right part of the form. When the user clicks on the ADD button, the information about the student and the subject appears on the list titled passed or failed depending on their score. Synchronously, the exam statistics in the page header is updated. That is the number of students that have passed the exam, and both the number and the percentage of the students who have failed the exam.

If provided input is not valid, appropriate error messages should be shown. 
Both name and surname should be provided and both should start with capitals. A grade should be a valid numerical value from 1 to 10. 


You should organize your working directory in the following manner: 
CSS:
    main.css
JS:
    subject.js
    student.js
    exam.js
    form.js
    app.js
index.html

In index.html file write all code relevant for the given page structure. 

In main.css file write all CSS code relevant for the given page design. 

In subject.js file: 
write a constructor function with one argument that represents the name of the subject
add to its prototype a method getSubjectName that returns the subject name

In student.js file:
write a constructor function with two arguments that represent the name and the surname of a student 
add to its prototype a method getStudentData that returns the name and the surname of the student

In exam.js file: 
write a constructor function with three arguments that represent a subject, a student, and a grade. 
add to its prototype a method getExamInfo that returns the name of the subject and the name and the surname of the student.
add to its prototype a method hasPassed that checks if the student has passed the exam. A student has passed the exam if their grade is greater than 5.
  
In form.js file:
write a function that collects all the data from the form
write a function that validates all collected data
write a function that updates the given list so it adds the new item at the end of the list
write a function that updates the part of the page with the statistics


In app.js file: 
Declare all necessary variables for managing passed and failed exams as well as their statistics.
Write all code that connects user’s behaviour with application logic.   


