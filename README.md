# Ex03 Time Table
## Date: 15.11.2024

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
        <IMG src = "logo.png" height = "12%">
            <BR><BR>
        <TABLE border = "1" cellpadding = "5" bgcolor = "cyan">
            <CAPTION><H2>SLOT TIME TABLE - S Rajath (24900186)</H2></CAPTION>
            <TR bgcolor = "yellow">
                <TH>DAY/TIME</TH>
                <TH>8 - 10</TH>
                <TH>10 - 12</TH>
                <TH rowspan = "7">Lunch</TH>
                <TH>1 - 3</TH>
                <TH>3 - 5</TH>
            </TR>
            <TR>
                <TH bgcolor = "yellow">Monday</TH>
                <TD colspan = "2">Free Slot</TD>
                <TD>BEEE</TD>
                <TD rowspan = "6">Free Slot</TD>
            </TR>
            <TR>
                <TH bgcolor = "yellow">Tuesday</TH>
                <TD>Web Dev</TD>
                <TD>Physics</TD>
                <TD>Python</TD>
            </TR>
            <TR>
                <TH bgcolor = "yellow">Wednesday</TH>
                <TD>Python</TD>
                <TD>Digital Electronics</TD>
                <TD>Mentor Meet</TD>
            </TR>
            <TR>
                <TH bgcolor = "yellow">Thursday</TH>
                <TD>Free Slot</TD>
                <TD>Python</TD>
                <TD>BEEE</TD>
            </TR>
            <TR>
                <TH bgcolor = "yellow">Friday</TH>
                <TD>Physics</TD>
                <TD>Career Dev</TD>
                <TD>Web Dev</TD>
            </TR>
            <TR>
                <TH bgcolor = "yellow">Saturday</TH>
                <TD>Digital Electronics</TD>
                <TD>Python</TD>
                <TD>Web Dev</TD>
            </TR>
        </TABLE>
        <BR>
        <TABLE border = "1" cellpadding = "5">
            <CAPTION>Courses</CAPTION>
            <TR>
                <TH>S.No</TH>
                <TH>Course Code</TH>
                <TH>Course Name</TH>
            </TR>
                <TD>1.</TD>
                <TD>SH3214</TD>
                <TD>Physics for Quantum Computing</TD>
            </TR>
            <TR>
                <TD>2.</TD>
                <TD>19EY708</TD>
                <TD>Career Development Skills</TD>
            </TR>
            <TR>
                <TD>3.</TD>
                <TD>19EE404</TD>
                <TD>Digital Electronics</TD>
            </TR>
            <TR>
                <TD>4.</TD>
                <TD>19EE305</TD>
                <TD>BEEE</TD>
            </TR>
            <TR>
                <TD>5.</TD>
                <TD>19AI414</TD>
                <TD>Fundamentals Of Web Application</TD>
            </TR>
            <TR>
                <TD>6.</TD>
                <TD>19AI301</TD>
                <TD>Python and Linear Algebra</TD>
            </TR>
        </TABLE>
    </BODY>
</HTML>
```

## OUTPUT
![alt text](<Screenshot 2024-11-15 204622.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
