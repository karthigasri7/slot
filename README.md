# Ex03 Time Table
## Date:6/10/2925

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
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - karthiga sri</title>
</head>
<body>
    <IMG SRC="/static/logo.png"HEIGHT="150"WIDTH="500"BORDER=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - YOUR-NAME</h3>

    <table border="1">
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td></td>
            <td></td>
            <td></td>
            <td>c</td>
            <td>AIML</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td>WEB</td>
            <td></td>
            <td>WEB</td>
            <td></td>
            <td>WEB</td>
        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=5 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td></td>
            <td>AIML</td>
            <td></td>
            <td>C</td>
            <td>AIML</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td>C</td>
            <td>C</td>
            <td>WEB</td>
            <td>AIML</td>
            <td>C</td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19EN612</td>
            <td>INTRODUCTION OF MACHINI LEARNING</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19PH206</td>
            <td>C PROGRAMMING</td>
        </tr>
        
    </table>
</body>
</html>

## OUTPUT
![alt text](<Screenshot 2025-10-06 141430.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
