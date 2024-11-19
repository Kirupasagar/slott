# Ex03 Time Table
## Date:18-11-2024

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
        <title>Creating slot time table</title>
    </head>
    <body>
        <CENTER>
        <img src="/static/logo.png" width="780" height="100">
        </CENTER>
        <br>
        <table align="center" BORDER="10" width="800" bgcolor="black" cellspacing="7.5" cellpadding="7.5">
            <caption><b>SLOT TIME TABLE - kirupasagar [24006810]</b></caption>
            <TR align="center" bgcolor="white"> 
                <TH>DAY/TIME</TH><TH>MONDAY</TH><TH>TUESDAY</TH><TH>WEDNESDAY</TH><TH>THURSDAY</TH><TH>FRIDAY</TH><TH>SATURDAY</TH>
            </TR>  
            <TR> <TH bgcolor="white">CLASS 1  [8-10]</TH>
                <TH bgcolor="black">-</TH>
                <TH bgcolor="black">WEBAPP</TH>
                <TH bgcolor="#00FA9A">-</TH>
                <TH bgcolor="#ADA96A">PHYSICS</TH>
                <TH bgcolor="black"></TH>
                <TH bgcolor="black">STATISTICS</TH>
            </TR> 
            <TR>
                <TH bgcolor="white">CLASS 2  [10-12]</TH>
                <TH bgcolor="#f22073">CAREEER</TH>
                <TH bgcolor="black">STATISTICS</TH>
                <TH bgcolor="#f22073">C PROGRAMMING</TH>
                <TH bgcolor="coral">ENGLISH</TH>
                <TH bgcolor="#00BFFF">C PROGRAMMING</TH>
                <TH bgcolor="#DDA0DD">PHYSICS</TH>
            </TR>
            <TR>
                <TH bgcolor="white">CLASS 3  [1-3]</TH>
                <TH bgcolor="#DDA0DD">BEEE</TH>
                <TH bgcolor="#00FA9A">ENGLISH</TH>
                <TH bgcolor="#a75a29">MENTOR MEET</TH>
                <TH bgcolor="#00BFFF">BEEE</TH>
                <TH bgcolor="coral">WEBAPP</TH>
                <TH bgcolor="f22073">WEBAPP</TH>
            </TR>
            <table align="center" width="540" cellspacing="2" cellpadding="4" border="5"</table>
            <br>
            <tr align="center"   >
                    <th >S.NO</th>
                    <th>Subject Code</th>
                    <th >Subject Name</th>
              </tr>
            <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of web application</td>
            </tr>
            <tr>
            <td>2</td>
            <td>19EE404</td>
            <td>Digital electronics</td>
            </tr>
            <tr>
            <td>3</td>
            <td>19MA211</td>
            <td>Statistics and numerical methods</td>
            </tr>
            <tr>
            <td>4</td>
            <td>19AI304</td>
            <td>Fundamentals of C programing</td>
            </tr>
            <tr>
            <td>5</td>
            <td>19EN101</td>
            <td>communicative english</td>
            </tr>
            <tr>
            <td>6</td>
            <td>SH3214</td>
            <td>Physics for quantum computing</td>
            </tr>
            <tr>
                <td>7</td>
                <td>ECAM SCOFT</td>
                <td>Mentor meet</td>
            </tr>
            <tr>
                <td>8</td>
                <td>19EY708</td>
                <td>career development skills</td>
            </tr>
        </table>
        </body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2024-11-19 004038-1.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
