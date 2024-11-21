# Ex03 Time Table
## Date:21-11-2024

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
<HTML>
    <HEAD>
        <TITLE>Time Table</TITLE>
    </HEAD>
    <BODY>
        <img src="logo.png" width="500" height="100" >
        <TABLE border = "1"  cellpadding = "5" bgcolor = "white">
            <CAPTION>SLOT TIME TABLE - JAWAHAR (24004142)</CAPTION>
            <TR bgcolor = "blue">
                <TH>DAY/TIME</TH>
                <TH>8 - 10</TH>
                <TH>10 - 12</TH>
                <TH rowspan = "7">Lunch</TH>
                <TH>1 - 3</TH>
                <TH>3 - 5</TH>
            </TR>
            <TR>
                <TH bgcolor = "blue">Monday</TH>
                <TD>Free Slot</TD>
                <TD>C programming</TD>
                <TD>WEB</TD>
                <TD>Free Slot</TD>
            </TR>
            <TR>
                <TH bgcolor = "blue">Tuesday</TH>
                <TD>Chemistry</TD>
                <TD>Digital Electronics</TD>
                <TD>WEB</TD>
                <TD>Free Slot</TD>
            </TR>
            <TR>
                <TH bgcolor = "blue">Wednesday</TH>
                <TD>Math</TD>
                <TD>English</TD>
                <TD>Mentor Meet</TD>
                <TD>Free Slot</TD>
            </TR>
            <TR>
                <TH bgcolor = "blue">Thursday</TH>
                <TD>Free Slot</TD>
                <TD>Math</TD>
                <TD>Chemistry</TD>
                <TD>Free Slot</TD>
            </TR>
            <TR>
                <TH bgcolor = "blue">Friday</TH>
                <TD>WEB</TD>
                <TD>C Programming</TD>
                <TD>Digital Electronics</TD>
                <TD>Free Slot</TD>
            </TR>
            <TR>
                <TH bgcolor = "blue">Saturday</TH>
                <TD>English</TD>
                <TD>Career Development</TD>
                <TD colspan="2">Free Slot</TD>
            </TR>
        </TABLE>
        <BR>
        <TABLE border = "1"  cellpadding = "5">
            <CAPTION>Courses</CAPTION>
            <TR>
                <TH bgcolor = "blue">S.No</TH>
                <TH bgcolor = "blue">Course Code</TH>
                <TH bgcolor = "blue">Course Name</TH>
            </TR>
                <TD>1.</TD>
                <TD>19AI414</TD>
                <TD>Fundamentals of Web Application Development</TD>
            </TR>
            <TR>
                <TD>2.</TD>
                <TD>19AI304</TD>
                <TD>Fundamentals of C Programming</TD>
            </TR>
            <TR>
                <TD>3.</TD>
                <TD>19CY205</TD>
                <TD>Principles of Chemistry Engineering</TD>
            </TR>
            <TR>
                <TD>4.</TD>
                <TD>19EN101 </TD>
                <TD>Communicative English</TD>
            </TR>
            <TR>
                <TD>5.</TD>
                <TD>19EE404</TD>
                <TD>Digital Electronics</TD>
            </TR>
            <TR>
                <TD>6.</TD>
                <TD>19MA201</TD>
                <TD>Calculus and Matrix Algebra</TD>
            </TR>
            <TR>
                <TD>7.</TD>
                <TD>19EY708</TD>
                <TD>Career Development Skills</TD>
        </TABLE>
    </BODY>
</HTML>

```

## OUTPUT

![WhatsApp Image 2024-11-21 at 22 48 11_1514d5fd](https://github.com/user-attachments/assets/1820267b-cb95-4955-be5a-ae311e385b9a)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
