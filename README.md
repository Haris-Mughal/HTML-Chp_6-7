# HTML-Chp_6-7

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <header>
<nav>
    <a href="index.html">Tables</a> |
    <a href="form.html">Forms</a>
</nav>                                  
    </header>
    <main>
<h1 style="text-align:center;">Tables</h1>
<h2>Student Data</h2>
<table border="1">
    <caption>Class Students</caption>
    <tr>
        <th>Name</th>
        <th>Roll No.</th>
        <th>City</th>
        <th>Address</th>
    </tr>
    <tr>
        <td>Haris</td>
        <td>55911</td>
        <td>Faisalsbad</td>
        <td rowspan="2">Mehmoodabad, Faisalsbad, Pakistan</td>
    </tr>
    <tr>
        <td>Aqib</td>
        <td>55908</td>
        <td>Faisalsbad</td>
    </tr>    
</table>
<br />
<br />
<br />
<table border="2">
    <tr>
        <td rowspan="2">Row 1 Class 1</td>
        <td>Row 1 Class 2</td>
    </tr>
    <tr>
        <td>Row 1 Class 3</td>
    </tr>
    <tr>
        <td colspan="3" style="text-align:center;">Row 2 Class 1</td>
    </tr>
</table>
<br />
<br />
<br />
<br />
    </main>

  <footer style="text-align:center;">
<p>&copy;2022. All Rights Reserved.</p>
    </footer>
</body>
</html>
