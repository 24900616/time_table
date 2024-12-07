# Ex03 Time Table
# Date:18\10\2024
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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> SAVEETHA ENGINEERING COLLEGE SLOT TIMETABLE</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f4f4f4;
        }

        .container {
            width: 80%;
            margin: 0 auto;
        }

        h1 {
            text-align: center;
            color: #333;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }

        th, td {
            border: 1px solid #ccc;
            padding: 10px;
            text-align: center;
        }

        th {
            background-color: #f4b400;
            color: #fff;
        }

        td {
            background-color: #e0f7fa;
        }

        .subject-table th {
            background-color: #00796b;
            color: white;
        }

        .subject-table td {
            background-color: #fff;
        }
    </style>
</head>
<body>

<div class="container">
    <img src="saveetha engin.logo.png" alt="saveetha Engineering College"
    width="1200" height="200">
    <h1> SWETHA.K (24900616)</h1>

    <!-- Slot Time Table -->
    <table>
        <thead>
        <tr>
            <th>Day/Time</th>
            <th>8-10</th>
            <th>10-12</th>
            <th>12-1</th>
            <th>1-3</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>Monday</td>
            <td>Digital Electronics</td>
            <td>Career development skills</td>
            <td ROWSPAN="6" <big>Lunch</big></td>
            <td>Fundamental of web Application</td>
        </tr>
        <tr>
            <td>Tuesday</td>
            <td ROWSPAN ="3"<big>Free Slot</big></td>
            <td>Physics for quantum computing</td>
            <td>Probability and Queueing Models</td>
        </tr>
        <tr>
            <td>Wednesday</td>
            <td>Communicative english</td>
            <td>Mentor meeting</td>
        </tr>
        <tr>
            <td>Thursday</td>
            <td>probability and Queueing Models</td>
            <td>Digital Electronics</td>
        </tr>
        <tr>
            <td>Friday</td>
            <td>Physics for quantum computing</td>
            <td>fundamentals of web Application Development</td>
            <td>Fundamentals of C Programming </td>
        </tr>
        <tr>
            <td>Saturday</td>
            <td>Communicative English</td>
            <td>Fundamentals of C Programming</td>
            <td>Probability and Queueing Models</td>
        </tr>
        </tbody>
    </table>

    <!-- Subject Table -->
    <h2>Subject Details</h2>
    <table class="subject-table">
        <thead>
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>1</td>
            <td>19A1410</td>
            <td>Fundamentals of Web Application Development</td>
        </tr>
        <tr>
            <td>2</td>
            <td>SH3214</td>
            <td>Physics for quantum Computing</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19EN101</td>
            <td>Communicative english</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19EY708</td>
            <td>Career development skills</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19EE404</td>
            <td>Digital electronics</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19MA222</td>
            <td>Probability and Queueing Models</td>
        </tr>
        <tr>
            <td>7</td>
            <td>19AI304</td>
            <td>Fundamnetals of C Programming</td>
        </tr>
        </tbody>
    </table>
</div>

</body>
</html>
```
# OUTPUT
![image](https://github.com/user-attachments/assets/190d154c-ea19-494d-9735-cb1ed8346304)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
