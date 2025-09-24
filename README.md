# Ex03 Time Table
# Date:24/09/2025
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

# PROGRAM
<html>
<head>

</head>
<body>
    <style>
        th{
            background-color:yellow;
        }
        td{
            background-color:aquamarine;
        }

        img{
            margin-left:30%;
        }
        caption{
            align-items: center;
        }
        #sta {
            width:60%;
            height:40%;
        }
        #abc
        {
           width:50%;
           height:30%;
        }
        body{
             background-image: WHITE (120deg, #3e47fc, #e04bae);

        }
    </style>
    <br>
    <br>

     
<center>
<table border="2" id="sta">
    <caption>SLOT TIME TABLE-VISHAL(25016264)</caption>
   
        <tr>
            <th>Day/Time</th>
            <th>8-10</th>
            <th>10-12</th>
            <th>12-1</th>
            <th>1-3</th>
            <th>3-5</th>
            </tr>
        <tr>
            <th>Monday</th>
            <td>FWAD</td>
            <td>FREE SLOT</td>
            <td>LUNCH</td>
            <td>FCP</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <th>Tuesday</th>
            <td colspan="2">CE</td>
            <td>LUNCH</td>
            <td colspan="2">FREE SLOT</td>
        </tr>
        <tr>
            <th>Wednesday</th>
            <td colspan="2">FWAD</td>
            <td>LUNCH</td>
            <td>MENTOR MEET</td>
            <td>FCP</td>
        </tr>
        <tr>
            <th>Thursday</th>
            <td>CE</td>
            <td>FCP</td>
            <td>LUNCH</td>
            <td>CE</td>
            <td>FCP</td>
            
        </tr>
        <tr>
            <th>Friday</th>
            <td>CE</td>
            <td>CE</td>
            <td>LUNCH</td>
            <td colspan="2">FREE SLOT</td>

        </tr>
        <tr>
            <th>Saturday</th>
            <td>CE</td>
            <td>FWAD</td>
        <td>LUNCH</td>
        <td>CE</td>
        <td>FREE SLOT</td>
         </tr>
</table>
<br>
<br>
<br>
<table border="3" id="abc">
    <tr>
        <th>S.No</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>
    <tr>
        <td>1.</td>
    <td>19AI414</td>  
<td >Fundamental of Web Application Development(FWAD)</td>  </tr>
<tr>
    <td>2.</td>
    <td>19AI304</td>
    <td>Fundamental of C Programming(FCP)</td>
</tr>
<tr>
    <td>3.</td>
    <td>19EN101</td>
    <td>Communicative English(CE)</td>
</tr>
</table>
</center>


</body>
</html>

# OUTPUT
![Uploading Screenshot 2025-09-24 134820.png…]()

![Uploading Screenshot 2025-09-24 131735.png…]()


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
