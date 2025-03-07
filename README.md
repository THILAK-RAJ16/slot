# Ex03 Time Table
## Date:7-March-2025

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
        <title>Time-table</title>
        <style>
            
            table,td{
                border: 2px solid black;
            }
            .heading {
                background-color: orange;
            }
            .nav{
                background-color: aqua;
            }
            .nxt{
                background-color: white;
            }
            .wb{
                background: white;
            }
            .mc{
                background: white;
            }
        </style>
    </head>
    <body>
        <center>
            <img src="logo.png" height="100" width="540">
        </center>
        <br>
        <h1>Time-table for Prime Students(Web Development and Fundamental of AI)</h1>
        <table>
        <tr>
            <th class="heading" colspan="4">WEB DEVELOPMENT AND FUNDAMENTALS OF AI-BATCH </th>
        </tr>
        <tr class="nav">
            <td> </td>
            <td>8-10 </td>
            <td>10-12  </td>
            <td>1-3 </td>
        </tr>
        <tr>
            <td class="nav" >MONDAY </td>
            <td class="wb">WEB DEVELOPMENT</td>
            <td class="nxt">TASK ASSIGNMENT </td>
            <td class="nxt">FUNDAMENTALS OF AI </td>
        </tr>
        <tr>
            <td class="nav">TUESDAY </td>
            <td class="nxt">TASK COMPLETION </td>
            <td class="wb">WEB DEVELOPMENT </td>
            <td class="mc">MODULE COMPLETION </td>
        </tr>
        <tr>
            <td class="nav">WEDNESDAY </td>
            <td class="nxt">ASSESSMENT HOUR </td>
            <td class="nxt">TASK PRESENTATION </td>
            <td class="nxt">MENTORS MEET </td>
        </tr>
        <tr>
            <td class="nav">THURSDAY </td>
            <td class="nxt">TASK PRESENTATION</td>
            <td class="mc">MODULE COMPLETION </td>
            <td class="nxt">FUNDAMENTALS OF AI </td>
        </tr>
        <tr>
            <td class="nav">FRIDAY </td>
            <td class="nxt">TASK COMPLETION </td>
            <td class="wb">WEB DEVELOPMENT </td>
            <td class="nxt">TASK COMPLETION </td>
        </tr>
        <tr>
            <td class="nav">SATURDAY </td>
            <td colspan="3" class="mc" >MODULE ASSESSMENT COMPLETION </td>
            
        </tr>
        </table>
    </body> 
</html>
```


## OUTPUT
![alt text](<Screenshot 2025-03-07 183539.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
