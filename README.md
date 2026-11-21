# Ex04 Time Table
## Date:21-11-2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>project</title>
    </head>
    <body>
        <h2>NANDHAKUMAR(26012045)</h2>
        <img src="logo.png" alt="error on img" height="15%" width="70%" align="center">
        
        <table bgcolor="YELLOW" border="5px" align="center" height="30%" width="70%">
            <caption align="center">MY TIMETABLE _NANDHAKUMAR(2601205)</caption>
            <tr bgcolor="blue">
                <th>Day/Time</th>
                <th>MON</th>
                <th>TUE</th>
                <th>WED</th>
                <th>THU</th>
                <th>FRI</th>
            </tr>
            <tr>
                <th bgcolor="blue">8-9.30</th>
                <td>PY</td>
                <td>CL</td>
                <td>FREE</td>
                <td>CA</td>
                <td>FWAD</td>

            </tr>
            <tr>
                <th bgcolor="blue">9.45-11.15</th>
                <td>FREE</td>
                <td>PY</td>
                <td>FWAD</td>
                <td>CA</td>
                <td>CDS</td>
            </tr>
            <tr>
                <th bgcolor="tblue">12-1</th>
                <td colspan="5">LUNCH</td>
            </tr>
            <tr>
                <th bgcolor="blue">1-2.45</th>
                <td colspan="2">FREE</td>
                <td>BEEE</td>
                <td>MAT</td>
                <td>FWAD</td>

            </tr>
            <tr>
                <th bgcolor="blue">3-4.30</th>
                <td colspan="2">FREE </td>
                <td>MAT</td>
                <td>CA</td>
                <td>CL</td>
            </tr>
        </table>
        <table  border="5px" align="center" height="30%" width="70%">
            <tr>
                <th>S.NO</th>
                <td>Subject Code</td>
                <td>Subject name</td>
            </tr>
             <tr>
                <th>1</th>
                <td>19AI414</td>
                <td>FWAD</td>
            </tr>
            <tr>
                <th>2</th>
                <td>19A301</td>
                <td>PY</td>
            </tr>
              <tr>
                <th>3</th>
                <td>19CS305</td>
                <td>CA</td>
            </tr>
             <tr>
                <th>4</th>
                <td>19CS418</td>
                <td>CL</td>
            </tr>
             <tr>
                <th>5</th>
                <td>19MA201</td>
                <td>MATH</td>
            </tr>


     

        </table>


    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2026-11-21 122041.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
