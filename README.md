# Ex03 Time Table
## Date: 18.03.2024

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
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Timetable</title>
</head>
<body bgcolor="white">
    <img src="./logo.png" height="200" width="1080">
    <table border="3" cellspacing="4" cellpadding bgcolor="skyblue" height="300" width="1000" align="center">
    <caption ><b>MY TIMETABLE - SURESH S (212223040215)</b></caption>
        <tr align="center" bgcolor="silver">
        <th>Day/Time</th>
        <th>8 - 10</th>
        <th>10 - 12</th>
        <th>1 - 3</th>
        <th>3 - 5</th>
        </tr>

        <tr align="center">
            <th align="center" bgcolor="silver">Mon</th>
            <th>-</th>
            <th>EBD</th>
            <th>FWAD</th>
            <th>C Programming</th>
        </tr>

        <tr>
            <th align="center" bgcolor="silver">Tue</th>
            <th>-</th>
            <th>FWAD</th>
            <th>Chemistry</th>
            <th>-</th>
        </tr>

        <tr>
            <th align="center" bgcolor="silver">Wed</th>
            <th>FWAD</th>
            <th>-</th>
            <th>PIoT</th>
            <th>CN</th>
        </tr>

        <tr>
            <th align="center" bgcolor="silver">Thu</th>
            <th>-</th>
            <th>Probablity</th>
            <th>-</th>
            <th>EBD</th>
        </tr>

        <tr>
            <th align="center" bgcolor="silver">Fri</th>
            <th>Chemistry</th>
            <th>C Programming</th>
            <th>CN</th>
            <th>-</th>
        </tr>

        <tr>
            <th align="center" bgcolor="silver">Sat</th>
            <th>Probality</th>
            <th>-</th>
            <th>PIot</th>
            <th>-</th>
        </tr>
        
    </table>
    <br>

    <table border="3" cellspacing="4" cellpadding  height="300" width="1000" align="center" bgcolor="beige">
        <tr align="center">
            <th>S.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
            </tr>

        <tr align="center">
            <th>1</th>
            <th>19AI304</th>
            <th>Fundamentals of C Programming</th>
            </tr>

        <tr align="center">
            <th>2</th>
            <th>19AI414</th>
            <th>Fundamentals of Web Application Development (FWAD)</th>
            </tr>
            <tr align="center">
                <th>3</th>
                <th>19CS406</th>
                <th>Computer Networks (CN)</th>
                </tr>
                <tr align="center">
                    <th>4</th>
                    <th>19CS420</th>
                    <th>Prototyping to Iot Systems(PIot)</th>
                    </tr>
                    <tr align="center">
                        <th>5</th>
                        <th>19CS542</th>
                        <th>Embedded Board Desig(EBD)</th>
                        </tr>
                        <tr align="center">
                            <th>6</th>
                            <th>19CY205</th>
                            <th>Principles of Chemistry in Engineering</th>
                            </tr>
                            <tr align="center">
                                <th>6</th>
                                <th>19MA222</th>
                                <th>Probablity and Queueing Models</th>
                                </tr>
    </table>
</body>
</html>
```

## OUTPUT
![output](<Screenshot 2024-03-18 140842.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
