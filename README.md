# Ex03 Time Table
## Date:

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
</body>
</html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Document</title>

</head>

<body>

    <center><h4>SLOT TIME TABLE - KARTHIK I (24010766)</TABLE></h4></center>
    
    <center><table border="5"</center>

        <caption></caption>

        <tr>

            <th bgcolor="yellow">DAY/TIME</th>

            <th bgcolor="yellow">MONDAY</th>

            <th bgcolor="yellow">TUESDAY</th>

            <th bgcolor="yellow">WEDNESDAY</th>

            <th bgcolor="yellow">THURSDAY</th>

            <th bgcolor="yellow">FRIDAY</th>

        </tr>

        <tr>

            <td bgcolor="yellow">8 - 10</td>

            <td bgcolor="skyblue" colspan="3" style="text-align:center;">FREE SLOT</td>

            <td bgcolor="skyblue">PHY</td>

            <td bgcolor="skyblue">CHE</td>

        </tr>

        <tr>

            <td bgcolor="yellow">10 - 12</td>

            <td bgcolor="skyblue">GER</td>

            <td bgcolor="skyblue">FREE SLOT</td>

            <td bgcolor="skyblue">FWAD</td>

            <td bgcolor="skyblue">FWAD</td>

            <td bgcolor="skyblue">CHY</td>

        </tr>

        <tr>

            <td bgcolor="yellow">12 - 1</td>
            <td bgcolor="skyblue" colspan="6" style="text-align: center;">lunch break</td>
        </tr>
        <tr>

            <td bgcolor="yellow">1 - 3</td>

            <td bgcolor="skyblue" colspan="2" style="text-align: center;">FREE SLOT</td>

            <td bgcolor="skyblue">MAT</td>

            <td bgcolor="skyblue">MAT</td>

            <td bgcolor="skyblue">SS</td>

        </tr>

        <tr>

            <td bgcolor="yellow">3 - 5</td>

            <td bgcolor="skyblue" colspan="2" style="text-align: center;">FREE SLOT</td>

            <td bgcolor="skyblue">GER</td>

            <td bgcolor="skyblue">CHE</td>

            <td bgcolor="skyblue">FWAD</td>

        </tr>
       </table> <br><br>
    
    <table border="1">
      <tr>
        <th>S. No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
      </tr>
      <tr>
        <td>1.</td>
        <td>19A1414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
      </tr>
      <tr>
        <td>2.</td>
        <td>19EN612</td>
        <td>German Basic (GER)</td>
      </tr>
      <tr>
        <td>3.</td>
        <td>19PH206</td>
        <td>Physics for Information Technology (PHY)</td>
      </tr>
      <tr>
        <td>4.</td>
        <td>19CY205</td>
        <td>Principles of Chemistry in Engineering (CHE)</td>
      </tr>
      <tr>
        <td>5.</td>
        <td>19MA201</td>
        <td>Calculus and Matrix Algebra (MAT)</td>
      </tr>
      <tr>
        <td>6.</td>
        <td>19EY701</td>
        <td>Soft Skills (SS)</td>
      </tr>
    </table>
    
</body>

</html>
```

## OUTPUT
![Screenshot 2025-03-12 114307](https://github.com/user-attachments/assets/c361f1c2-686f-43f0-857d-500081528ffc)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
