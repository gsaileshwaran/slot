# Ex03 Time Table
## Date: 18-04-2025

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
<title>Time Table</title>
<style>
img.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100%;
}
marquee {
  font-size: larger;
  color: red;
}
table, tr, th, td {
  border: 1px solid black;
  text-align: center;
}
table.center {
  margin-left: auto;
  margin-right: auto;
}
h1, h2 {
  text-align: center;
}
</style>
</head>
<body>

<img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-10-13 100810.png" class="center" />

<h1><b>TIME TABLE</b></h1>
<h2><b> Saileshwaran Ganesan 212224230237</b></h2>


<table class="center" width="50%">
<tr>
  <th bgcolor="yellow">Time/Day</th>
  <th bgcolor="yellow">Monday</th>
  <th bgcolor="yellow">Tuesday</th>
  <th bgcolor="yellow">Wednesday</th>
  <th bgcolor="yellow">Thursday</th>
  <th bgcolor="yellow">Friday</th>
  <th bgcolor="yellow">Saturday</th>
</tr>
<tr>
  <th bgcolor="yellow">8-10</th>
  <td bgcolor="aqua">Free</td>
  <td bgcolor="aqua">Free</td>
  <td bgcolor="aqua">19EE305</td>
  <td bgcolor="aqua">Free</td>
  <td bgcolor="aqua">Free</td>
  <td bgcolor="aqua">Free</td>
</tr>
<tr>
  <th bgcolor="yellow">10-12</th>
  <td bgcolor="aqua">19EN101</td>
  <td bgcolor="aqua">Free</td>
  <td bgcolor="aqua">19AI304</td>
  <td bgcolor="aqua">19MA211</td>
  <td bgcolor="aqua">19AI303</td>
  <td bgcolor="aqua">19AI303</td>
</tr>
<tr>
  <th bgcolor="yellow">12-1</th>
  <td colspan="6" bgcolor="aqua">Lunch</td>
</tr>
<tr>
  <th bgcolor="yellow">1-3</th>
  <td bgcolor="aqua">19AI303</td>
  <td bgcolor="aqua">19EN101</td>
  <td bgcolor="aqua">Free</td>
  <td bgcolor="aqua">SH3214</td>
  <td bgcolor="aqua">19EE305</td>
  <td bgcolor="aqua">19AI304</td>
</tr>
<tr>
  <th bgcolor="yellow">3-5</th>
  <td bgcolor="aqua">Free</td>
  <td bgcolor="aqua">Free</td>
  <td bgcolor="aqua">Free</td>
  <td bgcolor="aqua">Free</td>
  <td bgcolor="aqua">Free</td>
  <td bgcolor="aqua">Free</td>
</tr>
</table>

<h2>Subjects Code</h2>
<table class="center">
<tr>
  <th>S.No</th>
  <th>Subject Code</th>
  <th>Subject Name</th>
</tr>
<tr>
  <th>1.</th>
  <td>19AI304</td>
  <td>FUNDAMENTALS OF C PROGRAMMING</td>
</tr>
<tr>
  <th>2.</th>
  <td>19AI303</td>
  <td>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
</tr>
<tr>
  <th>3.</th>
  <td>SH3214</td>
  <td>PHYSICS FOR QUANTUM COMPUTING</td>
</tr>
<tr>
  <th>4.</th>
  <td>19EN101</td>
  <td>COMMUNICATIVE ENGLISH</td>
</tr>
<tr>
  <th>5.</th>
  <td>19MA211</td>
  <td>STATISTICS AND NUMERICAL METHODS</td>
</tr>
<tr>
  <th>6.</th>
  <td>19EE305</td>
  <td>BASIC ELECTRICAL ELECTRONICS AND MEASUREMENT ENGINEEIRNG</td>
</tr>
</table>

</body>
</html>

```

## OUTPUT
![Screenshot 2025-04-18 190933](https://github.com/user-attachments/assets/a5f21888-3e8f-48c9-abbd-615635780671)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
