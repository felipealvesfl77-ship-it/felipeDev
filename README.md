<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Felipe Alves | Software Developer</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Inter',sans-serif;
}

body{
background:#0b0f19;
color:#e2e8f0;
overflow-x:hidden;
}

.container{
width:90%;
max-width:1200px;
margin:auto;
}

header{
min-height:100vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
background:radial-gradient(circle at 20% 20%, #1e293b 0%, #0b0f19 50%);
}

h1{
font-size:4rem;
font-weight:800;
background:linear-gradient(90deg,#6366f1,#22d3ee);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

.subtitle{
margin-top:20px;
font-size:1.2rem;
color:#94a3b8;
max-width:600px;
margin-left:auto;
margin-right:auto;
}

.btn{
display:inline-block;
margin-top:40px;
padding:14px 36px;
background:linear-gradient(90deg,#6366f1,#22d3ee);
border:none;
border-radius:999px;
color:#fff;
text-decoration:none;
font-weight:600;
transition:0.3s;
}

.btn:hover{
transform:scale(1.05);
opacity:0.9;
}

section{
padding:120px 0;
}

h2{
font-size:2.5rem;
margin-bottom:50px;
text-align:center;
font-weight:700;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:40px;
}

.card{
background:rgba(30,41,59,0.5);
backdrop-filter:blur(10px);
padding:40px;
border-radius:20px;
border:1px solid rgba(255,255,255,0.05);
transition:0.4s;
}

.card:hover{
transform:translateY(-10px);
border:1px solid rgba(99,102,241,0.5);
}

.card h3{
margin-bottom:15px;
color:#22d3ee;
}

.about{
max-width:800px;
margin:auto;
text-align:center;
color:#94a3b8;
font-size:1.1rem;
line-height:1.6;
}

footer{
text-align:center;
padding:60px 0;
color:#64748b;
font-size:0.9rem;
}
</style>
</head>

<body>

<header>
<div class="container">
<h1>Felipe Alves</h1>
<p class="subtitle">
Construindo soluções digitais modernas com foco em performance, clareza e experiência do usuário.
</p>
<a href="#contato" class="btn">Vamos Conversar</a>
</div>
</header>

<section>
<div class="container">
<h2>Sobre</h2>
<p class="about">
Desenvolvedor focado em criação de aplicações web organizadas e eficientes.
Trabalho com HTML, Python, Java e WordPress.
Buscando oportunidade como Desenvolvedor Júnior remoto.
</p>
</div>
</section>

<section>
<div class="container">
<h2>Stack</h2>
<div class="grid">
<div class="card">
<h3>Frontend</h3>
<p>HTML moderno, estrutura semântica, responsividade.</p>
</div>

<div class="card">
<h3>Backend</h3>
<p>Python para lógica e automações.<br>Java para aplicações estruturadas.</p>
</div>

<div class="card">
<h3>Web & CMS</h3>
<p>WordPress profissional, landing pages e sites institucionais.</p>
</div>
</div>
</div>
</section>

<section>
<div class="container">
<h2>Projetos</h2>
<div class="grid">
<div class="card">
<h3>Site Institucional</h3>
<p>Design moderno com foco em conversão e apresentação profissional.</p>
</div>

<div class="card">
<h3>Landing Page</h3>
<p>Estrutura otimizada para captação de leads.</p>
</div>

<div class="card">
<h3>Aplicação em Python</h3>
<p>Solução simples utilizando lógica estruturada.</p>
</div>
</div>
</div>
</section>

<section id="contato">
<div class="container">
<h2>Contato</h2>
<p class="about">
📩 felipealvesfl77@gmail.com <br>
📍 Curitiba – PR | Disponível para Home Office
</p>
</div>
</section>

<footer>
© 2026 Felipe Alves — Software Developer
</footer>

</body>
</html>
