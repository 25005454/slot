# Ex02 Time Table
## Date:30.11.2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
'''
<html>
<head>
<title>Slot Timetable</title>    
</head>    
<body>
<center>
<img src="/static/logo.png.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="green">
<caption><b>Slot Time Table - Vamsi Krishna E (25005454)</b></caption> 
<tr align="center">
<th bgcolor="blue">Day/Time</th>
<th bgcolor="blue">Monday</th>
<th bgcolor="blue">Tuesday</th>
<th bgcolor="blue">Wednesday</th>
<th bgcolor="blue">Thursday</th>
<th bgcolor="blue">Friday</th>   
</tr> 
<tr align="center">
<th bgcolor="blue">8-10</th>
<td>Free slot</td>
<td>Free slot</td>
<td>Free slot</td>
<td>Digital Electronics</td>
<td>Priciple of Chemistry Engineering</td>
</tr>
<tr align="center">
<th bgcolor="blue">10-12</th>
<td>Communicative English</td>
<td>Communicative English</td>
<td>Free slot</td>
<td>Fundamentals of web applications development</td>
<td>Free slot</td>
</tr>
<tr>
<th bgcolor="blue">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>    
<tr align="center">
<th bgcolor="blue">1-3</th>
<td>Digital Electronics</td>
<td>Communicative English</td>
<td>Fundamentals of web applications development</td>
<td>Free slot</td>
<td>Principles of Chemistry Engineering</td>   
</tr>
<tr align="center">
<th bgcolor="blue">3-5</th>
<td>Fundamentals of web applications development</td>
<td>Principles of Chemistry Engineering</td>
<td>Communicative English</td>
<td>Free slot</td>
<td>Digital Electronics</td>    
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S.No.</th>
<th>Subject Code</th>
<th>Subject Name</th>    
</tr>   
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of web application development (FWAD)</td>   
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI301</td>
<td>Communicative English (C.E)</td>   
</tr> 
<tr>
<td align="center">3.</td>
<td align="center">19CY205</td> 
<td>Principles of chemistry Engineering (CHE)</td>   
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EE404</td> 
<td>Digital Electronics (DE)</td>   
</tr>
</table>   
</body>
</html>
'''

## OUTPUT
![alt text](<time table.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
