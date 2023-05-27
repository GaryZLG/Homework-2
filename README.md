# Homework-2

Create 2 different .c files for the 2 parts provided below. Push the files in your repo and submit the GitHub repository link on Gradescope.  
Part 1: Structure  
Write in C code, to create a student database that has altering functions.  
1) Use structure to define the student details: Student ID (int), Student Name, GPA (float). 

2) Keep a check on the GPA for it to be less than or equal to 4. If the GPA is not less than 4, print a message saying that GPA is greater than 4, and initialize the GPA to 0 (Only in this case).

3) Create a function to alter the student record, based on the input given by the user. The user should be able to change the name, ID and GPA. You could create a single function to alter each of these or three different functions to alter each of them differently. 

4) Use the main function, firstly to instantiate the structure with a single student record and then call the defined function in step 3, in order to manipulate the student record. 

5) The submission for this homework should be done using a .c file upload on Github.


Part 2: Stack  
Given a string s containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.  
An input string is valid if:  
Open brackets must be closed by the same type of brackets.  
Open brackets must be closed in the correct order.  
Every close bracket has a corresponding open bracket of the same type.  
E.g. Valid string = { { [ ( ) ] ( ) } }  
Invalid string = { ( [ ] } )  

Hint: Use stack for this question. When you encounter an open bracket in the string, push it in the stack. When you encounter a closed bracket in the string, pop an element from the stack. If the closed bracket and the popped bracket matches, continue. Otherwise the string is invalid.   
