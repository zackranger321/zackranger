<html>
<head>
<title>style css</title>
</head>
<style>
{
  box-sizing: border-box;
}

body {
  margin: 0;
}

.header {
  background-color: #F1F1F1;
  text-align: center;
  padding: 20px;
}

.column {
  float: left;
  padding: 10px;
}

.column.left, .column.right {
  width: 25%;
}

.column.middle {
  width: 60%;
}

.row::after {
  content: "";
  display: table;
  clear: both;
}

@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}

.footer {
  background-color: #F1F1F1;
  text-align: center;
  padding: 20px;
}
</style>

<html>
<head>
<title> Praktikum Web 1 Teknik informatika 2023511001 </title>
</head>
<body>
<div class="header">
<h1> Data Mahasiswa Teknik Informatika </h1>
</div>

 <div class="row">
<div class="column left">
<ul> <h2 text-align="center"> 
<li><a href="menu.html">Menu utama</a></li>
<li><a href="Prodi.html">prodi</a></li>
<li><a href="aboutus.html">about us</a></li>
</h2> </ul>
</div>
<div class="column middle">
<table border="1" align="center" cellpadding="4" cellspacing="4">
         <tr>
             <th>Nama</th>
             <th>Npm</th>
             <th>Prodi</th>
         </tr>
         <tr>
            <td>Muhammad Zaki Nur Wahid</td>
            <td>2023511001</td>
            <td>Teknik Informatika</td>
         </tr>
         <tr>
            <td>Ardian Shaleh</td>
            <td>2023511002</td>
            <td>Teknik Informatika</td>
         </tr>
         <tr>
            <td>Fikar</td>
            <td>2023511003</td>
            <td>Teknik Informatika</td>
         </tr>
</table>
</div>
<div class="column right">
<img src="ikon teknik.jpg" height="150">
</div>
 </div>

<div class="footer">
   <h2> WELCOME </h2>
</div>
 </body>
   </html>
