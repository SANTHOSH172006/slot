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
<html>
<head>
    <title>Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
    
    <br>
    <table align="center" width="540" cellspacing="2" cellpadding="2" border="5" bgcolor="cyan">
        <caption><b>SLOT TIME TABLE - SANTHOSH D (23011482)</b></caption>
        <tr align="center">
            <th bgcolor="orange">Day/Time</th>
            <th bgcolor="orange">Monday</th>
            <th bgcolor="orange">Tuesday</th>
            <th bgcolor="orange">Wednesday</th>
            <th bgcolor="orange">Thursday</th>
            <th bgcolor="orange">Friday</th>
        </tr>
        <tr align="center">
            <th bgcolor="orange">8-10</th>
            <td bgcolor="yellow">FREE SLOT</td>
            <td bgcolor="yellow">SOFT SKILL</td>
            <td bgcolor="yellow">FWAD</td>
            <td bgcolor="yellow">FREE SLOT</td>
            <td bgcolor="yellow">FREE SLOT</td>
        </tr>
        <tr align="center">
            <th bgcolor="orange">10-12</th>
            <td bgcolor="yellow">SOFT SKILL</td>
            <td bgcolor="yellow">FWAD</td>
            <td bgcolor="yellow">FREE SLOT</td>
            <td bgcolor="yellow">CA</td>
            <td bgcolor="yellow">FCP</td>
        
        </tr>
        <tr align="center">
            <th bgcolor="orange">12-1</th>
            <td colspan="5" align="center" bgcolor="yellow">L U N C H</td>
            
        </tr>
        <tr align="center">
            <th bgcolor="orange">1-3</th>
            <td bgcolor="yellow">FCP</td>
            <td bgcolor="yellow">PYH</td>
            <td bgcolor="yellow">PYH</td>
            <td bgcolor="yellow">SOFT SKILL</td>
            <td bgcolor="yellow">CA</td>
        
        </tr>
        <tr align="center">
            <th bgcolor="orange">3-5</th>
            <td bgcolor="yellow">FCP</td>
            <td bgcolor="yellow">FREE SLOT</td>
            <td bgcolor="yellow">FREE SLOT</td>
            <td bgcolor="yellow">CN</td>
            <td bgcolor="yellow">CN</td>
        
        </tr>
        </table>
        
    
    
<br>
    <table align="center" border="2" cellspacing="2" cellpadding="4" bgcolor="white" height="100" width="540">
        <tr>
            <th>S.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td align="center">1.</td>
            <td align="center">19PH214</td>
            <td align="center">Physics for Quantum Computing(PHY)</td>
        </tr>
        <tr>
            <td align="center">2.</td>
            <td align="center">19CS406</td>
            <td align="center">Computer Network(CN)</td>
        </tr>
        <tr>
            <td align="center">3.</td>
            <td align="center">19AI305</td>
            <td align="center">Fundamental of C Programming(FCP)</td>
        </tr>
        <tr>
            <td align="center">4.</td>
            <td align="center">19AI414</td>
            <td align="center">Fundamentals of Web Application Development(FWAD)</td>
        </tr>
        <tr>
            <td align="center">5.</td>
            <td align="center">19CS305</td>
            <td align="center">Computer Architecture(CA)</td>
        </tr>
        <tr>
            <td align="center">6.</td>
            <td align="center">19EY701</td>
            <td align="center">Soft Skills</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2024-04-02 114533.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
