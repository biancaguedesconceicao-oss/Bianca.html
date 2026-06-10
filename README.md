<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Projeto Economia de Água | Colégio Estadual de Campo Machado de Assis</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#f5fbff;
    color:#333;
}

/* MENU */

header{
    position:fixed;
    top:0;
    width:100%;
    background:rgba(0,84,166,0.95);
    backdrop-filter:blur(8px);
    z-index:1000;
    box-shadow:0 3px 10px rgba(0,0,0,.2);
}

nav{
    max-width:1400px;
    margin:auto;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:15px 40px;
}

.logo{
    color:white;
    font-size:1.4rem;
    font-weight:700;
}

nav ul{
    display:flex;
    list-style:none;
}

nav ul li{
    margin-left:25px;
}

nav ul li a{
    color:white;
    text-decoration:none;
    font-weight:500;
    transition:.3s;
}

nav ul li a:hover{
    color:#90caf9;
}

/* HERO */

.hero{
    height:100vh;
    background:
    linear-gradient(rgba(0,40,90,.7),rgba(0,40,90,.7)),
    url('https://images.unsplash.com/photo-1544551763-46a013bb70d5?auto=format&fit=crop&w=1920&q=80');

    background-size:cover;
    background-position:center;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
}

.hero-content{
    max-width:900px;
}

.hero h1{
    font-size:4rem;
    margin-bottom:20px;
}

.hero p{
    font-size:1.3rem;
    margin-bottom:30px;
}

.btn{
    display:inline-block;
    padding:15px 35px;
    background:#00b0ff;
    color:white;
    text-decoration:none;
    border-radius:50px;
    transition:.3s;
}

.btn:hover{
    background:#0288d1;
}

/* GERAL */

section{
    padding:100px 8%;
}

.titulo{
    text-align:center;
    color:#0054a6;
    font-size:2.7rem;
    margin-bottom:50px;
}

/* SOBRE */

.sobre{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:50px;
    align-items:center;
}

.sobre img{
    width:100%;
    border-radius:20px;
    box-shadow:0 5px 20px rgba(0,0,0,.2);
}

.sobre p{
    margin-bottom:20px;
    text-align:justify;
}

/* ESTATÍSTICAS */

.estatisticas{
    background:linear-gradient(135deg,#0054a6,#0088ff);
    color:white;
}

.stats{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:30px;
}

.stat{
    text-align:center;
}

.numero{
    font-size:3rem;
    font-weight:bold;
}

/* OBJETIVOS */

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:30px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,.1);
    transition:.4s;
}

.card:hover{
    transform:translateY(-10px);
}

.card h3{
    color:#0054a6;
    margin-bottom:15px;
}

/* CRONOGRAMA */

table{
    width:100%;
    border-collapse:collapse;
    background:white;
    box-shadow:0 5px 15px rgba(0,0,0,.1);
}

table th{
    background:#0054a6;
    color:white;
    padding:15px;
}

table td{
    padding:15px;
    border:1px solid #ddd;
    text-align:center;
}

/* GALERIA */

.galeria{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
}

.galeria img{
    width:100%;
    height:250px;
    object-fit:cover;
    border-radius:15px;
    transition:.5s;
}

.galeria img:hover{
    transform:scale(1.05);
}

/* DEPOIMENTOS */

.depoimentos{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:25px;
}

.depoimento{
    background:white;
    padding:30px;
    border-left:6px solid #2196f3;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,.1);
}

/* DICAS */

.dicas{
    background:#e3f2fd;
}

.lista-dicas{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.dica{
    background:white;
    padding:25px;
    border-radius:15px;
    text-align:center;
}

/* RODAPÉ */

footer{
    background:#003b73;
    color:white;
    padding:50px;
    text-align:center;
}

footer p{
    margin:10px;
}

/* RESPONSIVO */

@media(max-width:900px){

.sobre{
    grid-template-columns:1fr;
}

.stats{
    grid-template-columns:repeat(2,1fr);
}

.hero h1{
    font-size:2.5rem;
}

nav{
    flex-direction:column;
}

nav ul{
    flex-wrap:wrap;
    justify-content:center;
}

}

</style>
</head>

<body>

<header>

<nav>

<div class="logo">💧 Projeto Economia de Água</div>

<ul>
<li><a href="#inicio">Início</a></li>
<li><a href="#sobre">Projeto</a></li>
<li><a href="#objetivos">Objetivos</a></li>
<li><a href="#cronograma">Cronograma</a></li>
<li><a href="#galeria">Galeria</a></li>
<li><a href="#depoimentos">Depoimentos</a></li>
</ul>

</nav>

</header>

<!-- HERO -->

<section class="hero" id="inicio">

<div class="hero-content">

<h1>Projeto Economia de Água</h1>

<p>
Colégio Estadual de Campo Machado de Assis<br>
Distrito de Marabá – Tuneiras do Oeste/PR
</p>

<a href="#sobre" class="btn">Conheça o Projeto</a>

</div>

</section>

<!-- SOBRE -->

<section id="sobre">

<h2 class="titulo">Sobre o Projeto</h2>

<div class="sobre">

<img src="https://images.unsplash.com/photo-1527066236128-2ff79f7b9705?auto=format&fit=crop&w=1200&q=80">

<div>

<p>
O Projeto Economia de Água surgiu da necessidade de conscientizar estudantes e comunidade escolar sobre a importância da preservação dos recursos hídricos.
</p>

<p>
Por meio de atividades práticas, campanhas educativas, monitoramento do consumo e ações sustentáveis, os alunos desenvolvem atitudes responsáveis relacionadas ao uso da água.
</p>

<p>
O projeto integra educação ambiental, cidadania e sustentabilidade, formando multiplicadores de boas práticas dentro e fora da escola.
</p>

</div>

</div>

</section>

<!-- ESTATÍSTICAS -->

<section class="estatisticas">

<h2 class="titulo" style="color:white;">Resultados Esperados</h2>

<div class="stats">

<div class="stat">
<div class="numero">30%</div>
<p>Redução do Desperdício</p>
</div>

<div class="stat">
<div class="numero">250+</div>
<p>Alunos Envolvidos</p>
</div>

<div class="stat">
<div class="numero">12</div>
<p>Campanhas Educativas</p>
</div>

<div class="stat">
<div class="numero">100%</div>
<p>Participação Escolar</p>
</div>

</div>

</section>

<!-- OBJETIVOS -->

<section id="objetivos">

<h2 class="titulo">Objetivos do Projeto</h2>

<div class="cards">

<div class="card">
<h3>Conscientização</h3>
<p>Promover a educação ambiental e o consumo consciente da água.</p>
</div>

<div class="card">
<h3>Monitoramento</h3>
<p>Identificar desperdícios e acompanhar o consumo mensal.</p>
</div>

<div class="card">
<h3>Sustentabilidade</h3>
<p>Estimular práticas sustentáveis dentro e fora da escola.</p>
</div>

<div class="card">
<h3>Comunidade</h3>
<p>Envolver famílias e moradores em ações de preservação.</p>
</div>

</div>

</section>

<!-- CRONOGRAMA -->

<section id="cronograma">

<h2 class="titulo">Cronograma de Ações</h2>

<table>

<tr>
<th>Etapa</th>
<th>Período</th>
</tr>

<tr>
<td>Planejamento</td>
<td>Março</td>
</tr>

<tr>
<td>Diagnóstico do Consumo</td>
<td>Abril</td>
</tr>

<tr>
<td>Campanhas Educativas</td>
<td>Maio e Junho</td>
</tr>

<tr>
<td>Monitoramento</td>
<td>Julho a Outubro</td>
</tr>

<tr>
<td>Apresentação dos Resultados</td>
<td>Novembro</td>
</tr>

</table>

</section>

<!-- DICAS -->

<section class="dicas">

<h2 class="titulo">Dicas para Economizar Água</h2>

<div class="lista-dicas">

<div class="dica">
💧 Feche a torneira ao escovar os dentes.
</div>

<div class="dica">
🚿 Tome banhos mais rápidos.
</div>

<div class="dica">
🔧 Conserte vazamentos imediatamente.
</div>

<div class="dica">
🌱 Reutilize água para irrigação de jardins.
</div>

</div>

</section>

<!-- GALERIA -->

<section id="galeria">

<h2 class="titulo">Galeria de Imagens</h2>

<div class="galeria">

<img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb">
<img src="https://images.unsplash.com/photo-1473448912268-2022ce9509d8">
<img src="https://images.unsplash.com/photo-1437482078695-73f5ca6c96e2">
<img src="https://images.unsplash.com/photo-1464037866556-6812c9d1c72e">
<img src="https://images.unsplash.com/photo-1500375592092-40eb2168fd21">
<img src="https://images.unsplash.com/photo-1497436072909-60f360e1d4b1">

</div>

</section>

<!-- DEPOIMENTOS -->

<section id="depoimentos">

<h2 class="titulo">Depoimentos</h2>

<div class="depoimentos">

<div class="depoimento">
<p>
"O projeto nos ajudou a compreender que cada gota de água é importante para o futuro do planeta."
</p>
<br>
<strong>Aluno do 9º Ano</strong>
</div>

<div class="depoimento">
<p>
"Percebemos uma mudança significativa nos hábitos dos estudantes após as campanhas educativas."
</p>
<br>
<strong>Professora de Ciências</strong>
</div>

<div class="depoimento">
<p>
"A escola está formando cidadãos mais conscientes e comprometidos com o meio ambiente."
</p>
<br>
<strong>Representante da Comunidade</strong>
</div>

</div>

</section>

<!-- RODAPÉ -->

<footer>

<h2>💧 Projeto Economia de Água</h2>

<p>Colégio Estadual de Campo Machado de Assis</p>

<p>Distrito de Marabá – Tuneiras do Oeste/PR</p>

<p>Educação Ambiental • Sustentabilidade • Cidadania</p>

<p>© 2026 - Todos os direitos reservados</p>

</footer>

</body>
</html>
