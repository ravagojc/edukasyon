# Edukasyon Demo
This is a demo project for Edukasyon.

**Project Description**<br>
This is a simple grade-book program that accepts students’ names and grades, and then computes the
class average.

**Functionalities**
<li>Tester can input the students’ name and grade. 
<li>The updated list of grades will be shown after input
<li>Tester can press Get Average button to compute and show the average grade.
<li>Tester can clear all grades
  
**How to use the project**
Open the file index.html in the browser

**Technologies Used**
<li>HTML
<li>CSS
<li>JavaScript

**Technical Descriptions**
<li>HTML was used to create Form, Inputs, Buttons, Table, and general text descriptions.
<li>CSS is used to show border of the Table for easier visibility
<li>JavaScript for functions

**Functions List**
  <li>getInput - getting input is done by listening to form submit that contains the name and grade this is then inserted as a row in the table. 
  <li>getAverage - this put the 2nd column values (excluding the header) to an Array and use reduce function to get the sum of parsedFloat numbers. Which is then used to calculate the average using the rowlength-1 as the divisor. 
  <li>clearRows - Takes the length of the table minus the header and use it in a loop to clear the rows. 
