# Ex03 Time Table
## Date: 16.11.2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM

```
<html>

<head>

<title>Slot Timetable</title>

</head>

<body>

<center>

<img src="logo.png" height="100" width="540">

</center>

<br>

<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">

<caption><b>SLOT TIME TABLE - EZHILARASI N (24901074)</b></caption>

<tr align="center">

<th bgcolor="yellow">Day/Time</th>

<th bgcolor="yellow">Monday</th>

<th bgcolor="yellow">Tuesday</th>

<th bgcolor="yellow">Wednesday</th>

<th bgcolor="yellow">Thursday</th>

<th bgcolor="yellow">Friday</th>

<th bgcolor="yellow">Saturday</th>

</tr>

<tr align="center">

<th bgcolor="yellow">8-10</th>

<td >FREE SLOT</td>

<td>FREE SLOT</td>

<td>FREE SLOT</td>

<td>FREE SLOT</td>

<td>FREE SLOT</td>

<td>DIGITAL ELECTRONICS</td>

</tr>

<tr align="center">

<th bgcolor="yellow">10-12</th>

<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>

<td> CALCULUS AND MATRIX ALGEBRA</td>

<td>DIGITAL ELECTRONICS</td>

<td>FUNDAMENTALS OF C PROGRAMMING</td>

<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>

<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>

</tr>

<tr>

    <th bgcolor="yellow">12-1</th>
    <td colspan="6" align="center">L U N C H</td>
</tr>

<tr align="center">

<th bgcolor="yellow">1-3</th>
<td> CAREER DEVELOPMENT SKILLS</td>

<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>

<td>MENTOR MEET</td>

<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>

<td>FUNDAMENTALS OF C PROGRAMMING</td>

<td>CALCULUS AND MATRIX ALGEBRA</td>

</tr>

<tr>
</table>
<br>

<table align="center" cellspacing="2" cellpadding="4" border="1">

<tr align="center">

<th>S.No</th>

<th>Subject code</th>

<th>Subject Name</th>

</tr>

<tr>

<td align="center">1.</td>

<td align="center">19A1414</td>

<td>Fundamentals of web Application Development (FWAD)</td>

</tr>

<tr>

<td align="center">2.</td>

<td align="center">19A1304</td>

<td>Fundamentals Of C Programming(C PROGRAM)</td>

</tr>

<tr>

<td align="center">3.</td>

<td align="center">19A1404</td>

<td>Digital Electronics  (DE)</td>

</tr>

<tr>

<td align="center">4.</td>

<td align="center">19CV205</td>

<td>Principles of Chemistry in Engineering (CHE)</td>

</tr>

<tr>

<td align="center">5.</td>

<td align="center">19MA209</td>

<td>Calculus and Matrix Algebra (MAT)</td>

</tr>

<tr>

<td align="center">6.</td>

<td align="center">19EY708</td>


<td>Career Development Skills (SS)</td>
</tr>

</table>

</body>

</html>
```
## OUTPUT

![Screenshot 2024-11-16 203731](https://github.com/user-attachments/assets/ff953dff-ad34-4226-beb8-8e00f3987881)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
