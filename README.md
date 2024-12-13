# Ex03 Time Table
# Date:15-10-2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM

## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

## PROGRAM
~~~
<html>
    <head>
        <title>Table</title>
        <style>
            .hor{writing-mode: horizontal-tb;text-align: center;}
        </style>
    </head>
    <body>
        <center><img src="C:\Users\admin\Documents\saveetha log.png"width="500px">  </img>
    
    <h1>TIME TABLE</h1>
    <table border="10px" style="text-align: center;">
        <tr>
            <th>Day</th>
            <th>8am-10am</th>
            <th>10am-12am</th>
            <th>12pm-01pm</th>
            <th>01pm-3pm</th>
            <th>3pm-5pm</th>
        </tr>
        <tr>
            <th>monday</td>
            <td></td>
            <td>quantum physics</td>
            <td>L</td>
            <td>webdevelopment</td>
            <td></td>
        </tr>
        <tr>
            <th>tuesday</td>
            <td></td>
            <td>Digital electonic</td>
            <td>U</td>
            <td>Communicative english</td>
            <td></td>
        </tr>
        <tr>
            <th>wednesday</td>
            <td></td>
            <td>Career development</td>
            <td>N</td>
            <td>Mentor meet</td>
            <th>Chemistry</th>
        </tr>
        <tr>
            <th>thursday</td>
            <td></td>
            <td>Communicative english</td>
            <td>C</td> 
            <td>physics</td>
            <th></th>
        </tr>
        <tr>
            <th>friday</td>
            <td></td>
            <td>webdevelopment</td>
            <td>H</td>
            <td>Digital electronic</td>
            <td></td>
        </tr>
        <th>saturday</th>
        <td></td>
        <td>webdevelopment</td>
        <td></td>
        <td>Chemistry</td>
        <td></td>

        <tr>
            <th bgcolor="red">sunday</th>
            <th bgcolor="red" colspan="6">H  O  L  I  D  A  Y</th>
        </tr>

    </table>
    </html>
    <br>
</br>
    <table border="10px" style="text-align: center;">
    <tr>
        <th style="color:black";>S.no</th>
        <th style="color:black";>Subject Code</th>
        <th style="color:black";>Subject Expansion</th>
    </tr>
    <tr>
        <td style="color:black";>1</td>
        <td style="color:black";>19EN101</td>
        <td style="color:black";>COMMUNICATIVE ENGLISH</td>
    </tr>
    <tr>
        <td style="color:black";>2</td>
        <td style="color:black";>SH3214</td>
        <td style="color:black";>PHYSICS FOR QUANTAM COMPUTING</td>
    </tr
    <tr>
        <td style="color:black";>3</td>
        <td style="color:black";>19EE404</td>
        <td style="color:black";>DIGITAL ELECTRONIC</td>
    </tr>
    <tr>
        <td style="color:black";>4</td>
        <td style="color:black";>19EY708</td>
        <td style="color:black";>CARRER DEVELOPMENT</td>
    </tr>
    <tr>
        <td style="color:black";>5</td>
        <td style="color:black";>19CY205</td>
        <td style="color:black";>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
    </tr>
   
    <tr>
        <td style="color:black";>7</td>
        <td style="color:black";>19AL414</td>
        <td style="color:black";>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
    </tr>
    
    
</table>
</body>
~~~
# OUTPUT
![Screenshot 2024-11-25 134345](https://github.com/user-attachments/assets/27dcd985-270f-4b5e-b250-3e40efb2f4d2)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
