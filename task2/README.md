CSS WEBPAGE:


<html>
<head>
<title>webpage</title>
</head>
<style>
body {
background-color: powderblue;
}
p {
color: blue;
text-align: center;
}
h1 {
color:Red;
font-family:verdana;
text-align:center; 

text-decoration: underline;
text-shadow: 3px 2px red;
}
marquee {
color:yellow;
border-width: 5px;
border-style:solid;
}
h3.one {
text-align: center;
font-family: arial;
color: green;
text-decoration: underline;
}
h3.two {

font-family: arial;
color: navyblue;
text-decoration: underline;
}
a {
color: white;
display: inline-block;
text-align: center;
background-color: darkblue;
}
ul {
list-style: square
}
table, th, td {
border: 2px solid black;
width: 100%; 
text-align: center;
cellpadding: 5px;
font-size: 100%
}
</style>
<h1 id="start">GYM MEMBERSHIP</h1>

<marquee>JOIN NOW! JOIN NOW! JOIN NOW!</marquee>
<br>


<p><img src="C:\Users\Vanessa Lobo\Documents\web dev\gym.jpg" alt="gym" width="600" height="350" title="picture only for representational purposes"></p>
<br>
<br>

<h3 class="one">
GYM MEMBERSHIP DETAILS</h3>
<br>

<h3 class="two">LOCATIONS</h3>
<ul>
<li>Bandra</li>
<li>Santacruz</li>
<li>Andheri</li>
</ul>

<br>

<h3 class="one">
Gym membership fee details</h3><br>
</p>
<table>
<tr>
<th>Duration</th>
<th>Fee</th>
</tr>
<tr>
<td>1 month</td>
<td>Rs.2500</td>
</tr>
<tr>
<td>3 months</td>
<td>Rs.6000</td>
</tr>
<tr>
<td>1 year</td>
<td>Rs.20,000</td>
</tr>
</table>
<br>
<a href="C:\Users\Vanessa Lobo\Documents\web dev\logincss.htm" target="_blank" title="Go to login page">To login click here</a>
<br>
<br>
<u>Head Office:</u><br>
<address>

Fitness centre<br>
ABC building<br>
xyz road<br>
Bandra-400000<br>
</address>
<br>

<a href="#start">Go to the top</a>
</body>
</html>



LOGIN PAGE:


<html>
<head>
<title>
login
</title>
</head>
<style>

body {
background-color: pink;
}
h1 {
color: blue;
font family: verdana;
text-decoration: underline;
text-align: center;
}
input[type=text] {
width: 100%;
border: 2px solid black;
border radius: 4px;
margin: 4px, 0;
padding: 8px 10px;

}
input[type=password] {
width: 100%;
border: 2px solid black;
border radius: 4px;
margin: 4px, 0;
padding: 8px 10px;

}
input[type=submit] {
color: blue;
cursor:pointer;
border: 2px solid black;
padding: 4px 6px;
}
</style>

<body>

<h1>Sign In</h1>

<form action="https://www.google.com/">
USERNAME:<br>
<input type="text" name="username"><br>
PASSWORD:<br>
<input type="password" name="password"><br>
<br>
<input type="submit" value="login">
</form>
</body>
</html>


