## The picture of MassageBox

- This code is used to clear the information entered by the user from three TextBox controls.

* `txtname.Text = ""` sets the name field to an empty string.
* `txtDepartment.Text = string.Empty` removes the text from the department field.
* `txtSemester.Clear()` clears all text inside the semester field.

When this code runs, all three TextBox fields become empty, allowing the user to enter new information.



## The picture of MassageBox


- This code gets information from the input fields and displays it in the output label.

- The 'var' keyword is used to create variables for the name, student ID, department, and semester. 'int.Parse()' converts the Student ID and Semester values from text into integers.

- The 'output' variable combines all the information into two lines using '\n'. Finally, 'bloutput.Text = output' displays the complete information in the output label.



## The picture of parse


- This code is used to get the numeric day and year entered by the user.

- ' txtmonthNumeric.Text ' and ' txtyear.Text ' contain the values as text because they come from TextBox controls. 
- ' int.Parse() ' converts these text values into integers so they can be used as numbers in calculations or other operations.

- The numeric day is stored in ' numeric_day ', while the year is stored in ' Year '.



## The picture of trycatch


- This code uses ' try-catch ' to safely process student information and handle errors.

- Inside the ' try ' block, the program gets the student's name, ID, department, and semester from the TextBox fields. 

- The ' int.Parse() ' method converts the Student ID and Semester into numbers. 

- The information is then combined and displayed in the ' lbloutput ' label.

- If the user enters invalid numbers, the ' catch ' block handles the error and displays a message asking the user to enter valid numbers.

