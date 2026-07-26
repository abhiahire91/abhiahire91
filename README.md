<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abhishek Ahire Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,sans-serif;
}

body{
background:#050505;
color:white;
}

.container{
width:90%;
max-width:1100px;
margin:auto;
padding:40px 0;
}

.hero{
text-align:center;
padding:70px 20px;
}

.hero img{
width:180px;
height:180px;
border-radius:50%;
border:4px solid #00e5ff;
box-shadow:0 0 40px cyan;
transition:.5s;
}

.hero img:hover{
transform:scale(1.08) rotate(5deg);
}

h1{
font-size:55px;
margin-top:20px;
background:linear-gradient(90deg,#00e5ff,#00ff99);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

h2{
margin:60px 0 20px;
font-size:35px;
color:#00e5ff;
}

p{
font-size:18px;
color:#ccc;
line-height:1.8;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:rgba(255,255,255,.08);
backdrop-filter:blur(10px);
padding:25px;
border-radius:20px;
transition:.4s;
border:1px solid rgba(255,255,255,.1);
}

.card:hover{
transform:translateY(-10px);
box-shadow:0 0 30px cyan;
}

.footer{
text-align:center;
padding:50px;
color:#aaa;
}

a{
color:#00e5ff;
text-decoration:none;
}

</style>
</head>

<body>

<div class="container">

<div class="hero">

<img src="your-photo.jpg">

<h1>Abhishek Ahire</h1>

<p>Data Analyst • Business Intelligence • Power BI • SQL • Python</p>

</div>

<h2>About Me</h2>

<div class="card">
<p>
I'm a Data Analyst passionate about transforming raw data into business insights using SQL, Python, Excel, Power BI and Machine Learning.
</p>
</div>

<h2>Skills</h2>

<div class="cards">

<div class="card">
<h3>SQL</h3>
<p>Advanced Queries<br>Joins<br>Window Functions</p>
</div>

<div class="card">
<h3>Python</h3>
<p>Pandas<br>NumPy<br>Machine Learning</p>
</div>

<div class="card">
<h3>Power BI</h3>
<p>Dashboards<br>DAX<br>KPI Reports</p>
</div>

<div class="card">
<h3>Excel</h3>
<p>Pivot Table<br>Power Query<br>Charts</p>
</div>

</div>

<h2>Projects</h2>

<div class="cards">

<div class="card">
<h3>Customer Churn Prediction</h3>
<p>Random Forest Model<br>83% Accuracy</p>
</div>

<div class="card">
<h3>Retail Sales Dashboard</h3>
<p>Interactive Power BI Dashboard</p>
</div>

<div class="card">
<h3>AI Resume Screening</h3>
<p>NLP Based Resume Ranking</p>
</div>

</div>

<h2>Contact</h2>

<div class="card">

<p>📧 abhiahire9191@gmail.com</p>

<p>💻 github.com/abhiahire91</p>

<p>🔗 linkedin.com/in/abhishek-ahire-49bb6a318</p>

</div>

<div class="footer">
© 2026 Abhishek Ahire | Data Analyst Portfolio
</div>

</div>

</body>
</html>
