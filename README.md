# BTP-Allocation
Find the predicted BTP allocation that you will get based on the choice list of students and the Project list provided by the Department. The allocation prediction is strictly made on the Department rank of the student and the actual policy used by the department may differ.

Issued in interest of all present and future 3rd year students of across all departments of IIT Kharagpur.
What is it ?
Find out what BTP you will be allocated based on other students' choice and your preference. Just input your DR (department rank) followed by your choices along with you batchmates, and it will pour out the list of alloted projects.

How it works ?
Modify the choicesActual.txt file with your actual choices.
Compile using "make" and run using "make run".
The allocation file and projectsLeft file gets generated automatically.
How to customize ?
Change the generateChoices method and include all projects currently offered in your dep or year.
Change the choicesActual.txt file.
Change the values initially in the capacity array to the actual capacity of that particular project in lookUp file.
If you dont get it, contact me anyways !!
Future
Create a makefile. (DONE)
Automate the generation of choices file from the projects' actual code directly without having to manually use lookUp. (DONE)
Make the capacity filing process more intiutive for general public. (Almost Done!)
Extend functionality to more domains.
