# Ex03 Time Table
## Date:21/04/2025

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
```<html>
    <head>
        
    </head>
    <body>
        
        <center>
            
            
            <img src="/static/logo.png" height="100" width="550">
            
            <h1>SLOT TIMETABLE </h1>
            <br><h2>S.yaazhini        (reg no:212224230308)</h2>
            <hr color="black">
        </center>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="lightblue">
            <tr align="center">
                <th bgcolor="yellow">DAY/TIME</th>
                <th bgcolor="yellow">8:00-10:00</th>
                <th bgcolor="yellow">10:00-12:00</th>
                <th bgcolor="yellow">12:00-1:00</th>
                <th bgcolor="yellow">1:00-3:00</th>
                <th bgcolor="yellow">3:00-5:00</th>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">MONDAY</th>
                <td>FREE SLOT</td>
                <td>WEB</td>
                <td>LUNCH</td>
                <td>STATISTICS</td>
                <td>FREE SLOT</td>
                
            </tr>
            <tr align="center">
                <th bgcolor="yellow">TUESDAY</th>
                <td>FREE SLOT</td>
                <td>DE</td>
                <td>LUNCH </td>
                <td>PHYSICS</td>
                <td>C PROGRAMMING</td>
                
                
            </tr>
            <tr align="center">
                <th bgcolor="yellow">WEDNESDAY</th>
                <td>DE</td>
                <td>WEB</td>
                <td>LUNCH</td>
                <td>MENTOR MEET</td>
                <td>CHEMISTRY</td>
            </tr>
            <tr align="center">
                <TH bgcolor="yellow">THURSDAY</TH>
                <TD>PHYSICS</TD>
                <TD>STATISTICS</TD>
                <TD>LUNCH</TD>
                <TD>FREE SLOT</TD>
                <TD>REASONING ABILITY</TD>
            </tr>
            <TR align="center">
                <TH bgcolor="yellow">FRIDAY</TH>
                <TD>FREE SLOT</TD>
                <TD>CHEMISTRY</TD>
                <TD>LUNCH</TD>
                <TD>C PROGRAMMING</TD>
                <td>EVS</td>

            </TR>
            <TR align="center">
                <TH bgcolor="yellow">SATURDAY</TH>
                <TD>FREE SLOT</TD>
                <TD>FREE SLOT</TD>
                <TD>LUNCH</TD>
                <TD>FREE SLOT</TD>
                <TD>FREE SLOT</TD>

            </TR>
        </table>
        <BR>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.NO : </th>
                <TH>SUBJECT CODE :</TH>
                <TH>SUBJECT NAME :</TH>
            </tr>
            <TR align="center">
                <td>1.</td>
                <td>19AI414</td>
                <TD>FUNDAMENTALS OF WEB APPLICATION</TD>
            </TR>
            <TR align="center">
                <TD>2.</TD>
                <TD>19AI304</TD>
                <TD>FUNDAMENTALS OF C PROGRAMMING</TD>
            </TR>
            <TR align="center">
                <TD>3.</TD>
                <TD>19CY801</TD>
                <TD>ENVIRONMENTAL SCIENCE AND SUSTAINABILITY</TD>
            </TR>
            <TR align="center">
                <TD>4.</TD>
                <TD>19MA211</TD>
                <TD>STATISTICS AND NUMERICAL METHODS</TD>
            </TR>
            <TR align="center">
                <TD>5.</TD>
                <TD>19CY205</TD>
                <TD>PRINCIPLES OF CHEMISTRY IN ENGINEERING</TD>
            </TR>
            <TR align="center">
                <TD>6.</TD>
                <TD>19EY709</TD>
                <TD>REASONING ABILITY</TD>
            </TR>
            <TR align="center">
                <TD>7.</TD>
                <TD>19PH814</TD>
                <TD>PHYSICS FOR QUANTUM COMPUTING</TD>
            </TR>
            <TR align="center">
                <TD>8.</TD>
                <TD>19EE404</TD>
                <TD>DIGITAL ELECTRONICS</TD>
            </TR>
        </table>
        
    </body>
</html>
```

## OUTPUT
![output img](<Screenshot (64)-1.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
