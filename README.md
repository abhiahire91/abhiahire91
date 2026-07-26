<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abhishek Ahire</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Poppins,sans-serif}
body{
background:#0a0a0a;
color:#fff;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
}
.card{
width:360px;
background:#111;
padding:30px;
border-radius:20px;
text-align:center;
box-shadow:0 0 30px #00e5ff55;
transition:.4s;
}
.card:hover{
transform:translateY(-10px) scale(1.03);
box-shadow:0 0 40px cyan;
}
img{
width:150px;
height:150px;
border-radius:50%;
border:4px solid cyan;
box-shadow:0 0 25px cyan;
}
h1{
margin:20px 0 5px;
font-size:32px;
background:linear-gradient(90deg,cyan,#00ff88);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}
h3{color:#bbb;margin-bottom:15px}
p{color:#ddd;font-size:15px;line-height:1.6}
.btn{
display:inline-block;
margin-top:20px;
padding:12px 30px;
background:cyan;
color:#000;
font-weight:bold;
border-radius:30px;
text-decoration:none;
transition:.3s;
}
.btn:hover{
background:#00ff88;
}
</style>
</head>

<body>

<div class="card">

<img src="profile.jpg">

<h1>Abhishek Ahire</h1>

<h3>Data Analyst</h3>

<p>
SQL • Python • Power BI • Excel • Machine Learning
</p>

<p style="margin-top:15px;">
Turning Data Into Business Insights.
</p>

<a class="btn" href="https://github.com/abhiahire91">GitHub</a>

</div>

</body>
</html>
