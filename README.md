# Ex02 Time Table
## Date: 04-02-2026

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
```
<html></html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png"height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" border="5" bgcolor="gold">
<caption><b>SLOT TIMETABLE - SATHIYA MURTHY K (212225100047)</b></caption>
<tr align="center">
	<th bgcolor="blue">Day/Time</th>
	<th bgcolor="blue">Monday</th>
	<th bgcolor="blue">Tuesday</th>
	<th bgcolor="blue">Wednesday</th>
	<th bgcolor="blue">Thursday</th>
	<th bgcolor="blue">Friday</th>
    <th bgcolor="blue">Saturday</th>
</tr>
<tr align="center">
	<th bgcolor="blue">8-10</th>
	<td>FWAD</td>
	<td>FREE</td>
	<td>FWAD</td>
	<td>FREE</td>
	<td>FWAD</td>
    <td>FREE</td>
</tr>
<tr align="center">
	<th bgcolor="blue">10-12</th>
	<td>ML</td>
	<td>FWAD</td>
	<td>ML</td>
	<td>FWAD</td>
	<td>ML</td>
    <td>ML</td>
</tr>
<tr>
	<th bgcolor="blue">12-1</th>
	<td colspan="5" align="center">L U N C H   B R E A K</td>
</tr>
<tr align="center">
	<th bgcolor="blue">1-3</th>
	<td>PYTHON</td>
	<td>PYTHON</td>
	<td>MENTOR MEET</td>
	<td>FREE</td>
	<td>PYHTON</td>
    <td>ML</td>
</tr>
<tr align="center">
	<th bgcolor="blue">3-5</th>
	<td>FREE</td>
	<td>FREE</td>
	<td>FREE</td>
	<td>ML</td>
	<td>FREE</td>
    <td>PYTHON</td>
</tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>19AI414-Fundamentals of Web Application Development</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI410</td>
<td>Introduction to Machine Learning</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI301</td>
<td>Python Programming</td>
</tr>
<tr>


</table>
</body>
</html>

```

## OUTPUT

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/42d9d1d9-b604-42cf-979f-ad42a80bb3b4" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
