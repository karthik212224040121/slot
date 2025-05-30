# Ex04 Time Table

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
```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Course Schedule</title>
</head>
<body bgcolor="6499E9">
    <center>
        <img src="logo.png" height="90" width="800">
    </center>
    <br>
    <table align="center" width="800" cellspacing="2" cellpadding="4" border="5" bgcolor= "6499E9">
    <caption><b>SLOT TIMETABLE - Roopak C S (212223220088)</b></caption>
        <tr align="center">
            <th bgcolor="9EDDFF">Day/Time</th>
            <th bgcolor="9EDDFF">Monday</th>
            <th bgcolor="9EDDFF">Tuesday</th>
            <th bgcolor="9EDDFF">Wednesday</th>
            <th bgcolor="9EDDFF">Thursday</th>
            <th bgcolor="9EDDFF">Friday</th>
            <th bgcolor="9EDDFF">Saturday</th>
        </tr>
        <tr align="center">
            <th bgcolor="9EDDFF">08:00 - 10:00</th>
            <td bgcolor="A6F6FF">Logic and Combinatorics</td>
            <td bgcolor="A6F6FF">Computer Newtworks</td>
            <td bgcolor="A6F6FF">Fundamentals of Web Application Development</td>
            <td bgcolor="A6F6FF">Free Slot</td>
            <td bgcolor="A6F6FF">Free Slot</td>
            <td bgcolor="A6F6FF">Free Slot</td>
        </tr>
        <tr align="center">
            <th bgcolor="9EDDFF">10:00 - 12:00</th>
            <td bgcolor="A6F6FF">Introduction to Machine Learning</td>
            <td bgcolor="A6F6FF">Generative AI Application Development</td>
            <td bgcolor="A6F6FF">Quantative Ability I</td>
            <td bgcolor="A6F6FF">Free Slot</td>
            <td bgcolor="A6F6FF">Free Slot</td>
            <td bgcolor="A6F6FF">Compiler Design</td>
        </tr>
        <tr align="center">
            <th bgcolor="9EDDFF">12:00 - 01:00</th>
            <td bgcolor="BEFFF7" colspan=6 align="center">L U N C H</td>
            
        </tr>
        <tr align="center">
            <th bgcolor="9EDDFF">01:00 - 03:00</th>
            <td bgcolor="A6F6FF">Free Slot</td>
            <td bgcolor="A6F6FF">Compiler Design</td>
            <td bgcolor="A6F6FF">Mentor Meet</td>
            <td bgcolor="A6F6FF">Free Slot</td>
            <td bgcolor="A6F6FF">Introduction to Machine Learning</td>
            <td bgcolor="A6F6FF">Free Slot</td>
        </tr>
        <tr align="center">
            <th bgcolor="9EDDFF">03:00 - 05:00</th>
            <td bgcolor="A6F6FF">Free Slot</td>
            <td bgcolor="A6F6FF">Free Slot</td>
            <td bgcolor="A6F6FF">Computer Networks</td>
            <td bgcolor="A6F6FF">Free Slot</td>
            <td bgcolor="A6F6FF">Free Slot</td>
            <td bgcolor="A6F6FF">Logic and Combinatorics</td>
        </tr>
    </table>
    <br>
    <table align="center" cellspacing="2" cellpadding="4" border="2">
        <tr>
            <th bgcolor="9EDDFF">S.No</th>
            <th bgcolor="9EDDFF">Subject Name</th>
            <th bgcolor="9EDDFF">Subject Code</th>
        </tr>
        <tr>
            <td bgcolor="9EDDFF" align="center">1.</td>
            <td bgcolor="A6F6FF" align="center">19AI410</td>
            <td bgcolor="A6F6FF">Introduction to Machine Learning</td>
        </tr>
        <tr>
            <td bgcolor="9EDDFF" align="center">2.</td>
            <td bgcolor="A6F6FF" align="center">19AI414</td>
            <td bgcolor="A6F6FF">Fundamentals of Web Application Development</td>
        </tr>
        <tr>
            <td bgcolor="9EDDFF" align="center">3.</td>
            <td bgcolor="A6F6FF" align="center">19AI406</td>
            <td bgcolor="A6F6FF" >Computer Networks</td>
        </tr>
        <tr>
            <td bgcolor="9EDDFF" align="center">4.</td>
            <td bgcolor="A6F6FF" align="center">19AI409</td>
            <td bgcolor="A6F6FF">Compiler Design</td>
        </tr>
        <tr>
            <td bgcolor="9EDDFF" align="center">5.</td>
            <td bgcolor="A6F6FF" align="center">19CS579</td>
            <td bgcolor="A6F6FF">Generative AI Application Development</td>
        </tr>
        <tr>
            <td bgcolor="9EDDFF" align="center">6.</td>
            <td bgcolor="A6F6FF" align="center">19EY710</td>
            <td bgcolor="A6F6FF">Quantative Ability I</td>
        </tr>
        <tr>
            <td bgcolor="9EDDFF" align="center">7.</td>
            <td bgcolor="A6F6FF" align="center">19MA206</td>
            <td bgcolor="A6F6FF">Logic and Combinatorics</td>
        </tr>
        <tr>
            <td bgcolor="9EDDFF" align="center">8.</td>
            <td bgcolor="A6F6FF" align="center">19AI305</td>
            <td bgcolor="A6F6FF">Advanced C Programming</td>
        </tr>
        <tr>
            <td bgcolor="9EDDFF"align="center">9.</td>
            <td bgcolor="A6F6FF" align="center">ECA-M</td>
            <td bgcolor="A6F6FF">Mentor Meet</td>
        </tr>
    </table>
</body>
</html>
```
## OUTPUT
![Screenshot 2025-03-12 114307](https://github.com/user-attachments/assets/d293ce5e-92fd-49a3-8610-bae8f8f30427)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
