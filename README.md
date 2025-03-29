# Ex03 Time Table
## Date:29/03/2025

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
    <body>
        <img src="/static/logo.png" width="700" height="100">
<table border="2" cellspacing="15" cellpadding="5">
    <caption>SLOT TIME TABLE - NANDHITHA S(24900454)</caption>
    <tr bgcolor="pink">
        <th>Day/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
        </tr>
        <tr>
        <th>8-10</th>
        <th>FREE</th>
        <th>UI/UX</th>
        <th>FREE</th>
        <th>UI/UX</th>
        <th>FREE</th>
        <th>FREE</th>
        </tr>
        <tr>
        <th>10-12</th>
        <th>MATH</th>
        <th>CA</th>
        <th>PHY</th>
        <th>FUN OF C</th>
        <th>PHY</th>
        <th> FREE</th>
        </tr>
        <tr>
        <th>12-1</th>
        <th colspan="6">LUNCH</th>
        </tr>
        <tr>
        <th>1-3</th>
        <th>FUN OF C</th>
        <th>FWAD</th>
        <th>MENTOR MEET</th>
        <th>MATH</th>
        <th>FWAD</th>
        <th>FREE</th></tr>
        </tr>
        <tr>
        <th>3-5</th>
        <th>FREE</th>
        <th>FREE</th>
        <th>CA</th>
        <th>RA</th>
        <th>EVS</th>
        <th> FREE</th>


    </tr>
    </table>
    <br>
    <table border="2" cellspacing="15" cellspadding="5">
    <tr bgcolor="sky blue">
        <th>S.NO.</th>
        <th>Course code</th>
        <th>Course Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19MA201</td>
            <td>CALCULUS AND MATRIX ALGEBRA(MATH) </td>
        </tr>
        <tr>
            <td>2</td>
            <td>19EY709</td>
            <td>REASONING ABILITY(RA)</td>
            </tr>
        <tr>
            <td>3</td>
            <td>19PH814</td>
            <td>PHYSICS FOR QUANTUM COMPUTING(PHY)</td>
            </tr>
        <tr>
            <td>4</td>
            <td>19CS305</td>
            <td>COMPUTER ARCHITECTURE(CA)</td>
            </tr>
        <tr>
            <td>4</td>
            <td>19CS549</td>
            <td>UI AND UX DESIGN(UI/UX)</td>
            </tr>
        <tr>
            <td>5</td>
            <td>ECA-M</td>
            <td>SCOFT MENTOR MEET(MENTOR MEET)</td>
            </tr>
        <tr>
            <td>6</td>
            <td>19AI304</td>
            <td>FUNDAMENTAL OF C PROGRAMMING(FUN OF C)</td>
            </tr>
        <tr>
            <td>7</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(FWAD)</td>
            </tr>
        <tr>
            <td>8</td>
            <td>19CY801</td>
            <td>ENVIRONMENTAL SCIENCES AND SUSTAINABILITY(EVS)</td>
            </tr>
    </table>
    </body>
    </html>
```

## OUTPUT

![alt text](<Screenshot 2025-03-29 211355.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
