# Ex03 Time Table
## Date:06.04.2024

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
<title>slot Timetable</title>    
</head>
<body>

<br>
<table align="center" width="540" cellspacing="2" cellpadding="5" border="7" bgcolor="pink">
    <center>
    <img src="/static/logo.png" height="100" width="540">
</center><br>
<caption><b>SLOT TIME TABLE - VIGNESH M (212223040235)</b></caption>
<tr align="center">
<th bgcolor="cyan">Day/Time</th>
<th bgcolor="cream">Monday</th>
<th bgcolor="cream">Tuesday</th>
<th bgcolor="cream">Wednesday</th>
<th bgcolor="cream">Thursday</th>
<th bgcolor="cream">Friday</th>
<th bgcolor="cream">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="lavender">8-10</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION </td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
</tr>
<tr align="center">
<th bgcolor="lavender">10-12</th>
<td>FREE SLOT</td>
<td>FUNDAMENTAL OF C PROGRAMMING</td>
<td>FREE SLOT</td>
<td>FUNDAMENTAL OF C PROGRAMMING</td>
<td>PRINCIPLE OF CHEMISTRY</td>
<td>PYTHON AND LINEAR ALGEBRA</td>

</tr>
<tr>
<th bgcolor="lavender">12-1</th>

<td colspan="4" align="center">L U N C H</td>
<td>MENTOR MEET</td>
</tr>
<tr align="center">
<th bgcolor="lavender">1-3</th>
<td>PRINCIPLE OF CHEMISTRY</td>
<td>PYTHON AND LINEAR ALGEBRA</td>
<td>STATISTICS AND NUMERICAL METHODS</td>
<td>PYTHON AND LINEAR ALGEBRA</td>
<td>PYTHON AND LINEAR ALGEBRA</td>
<td>STATISTICS AND NUMERICAL METHODS</td>

</tr>
<tr align="center">
<th bgcolor="lavender">3-5</th>
<td>FREE SLOT</td>
<td>FUNDAMENTAL OF WEB APPLICATION</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="3" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19A1304</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19A1301C</td>
<td>PYTHON AND LINEAR ALGEBRA</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>

<tr>
<td align="center">5.</td>
<td align="center">19CY305</td>
<td>PRINCIPLE OF CHEMISTRY</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19MA211</td>
<td>STATISTICS AND NUMERICAL METHODS</td>
</tr>
<td align="center">7.</td>
<td align="center">ECAM</td>
<td>MENTOR MEET</td>
</tr>
</table>
</body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2024-04-06 194025.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
