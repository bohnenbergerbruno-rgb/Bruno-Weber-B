<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Agro Forte - Futuro Sustentável</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#f5f5f5;
    color:#333;
}

header{
    background:linear-gradient(135deg,#2e7d32,#66bb6a);
    color:white;
    padding:20px;
    position:sticky;
    top:0;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

nav ul{
    list-style:none;
    display:flex;
    gap:20px;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:bold;
}

.hero{
    height:90vh;
    background:url("https://images.unsplash.com/photo-1500382017468-9049fed747ef?auto=format&fit=crop&w=1600&q=80") center/cover;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
}

.hero .conteudo{
    background:rgba(0,0,0,0.55);
    padding:40px;
    border-radius:15px;
}

.hero h1{
    font-size:55px;
}

.hero p{
    margin:20px 0;
    font-size:20px;
}

.botao{
    display:inline-block;
    background:#43a047;
    color:white;
    padding:15px 30px;
    border-radius:8px;
    text-decoration:none;
    font-weight:bold;
    transition:.3s;
}

.botao:hover{
    background:#2e7d32;
}

section{
    padding:70px 10%;
}

.titulo{
    text-align:center;
    color:#2e7d32;
    margin-bottom:40px;
    font-size:38px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,.1);
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card h3{
    color:#2e7d32;
    margin-bottom:10px;
}

.numeros{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:25px;
    text-align:center;
}

.numero{
    background:#2e7d32;
    color:white;
    padding:30px;
    border-radius:15px;
}

.numero h2{
    font-size:45px;
}

footer{
    background:#1b5e20;
    color:white;
    text-align:center;
    padding:30px;
}

@media(max-width:700px){
.hero h1{
font-size:38px;
}

.hero p{
font-size:18px;
}

nav{
flex-direction:column;
gap:15px;
}
}
</style>

</head>
<body>

<header>
<nav>
<h2>🌱 Agro Forte</h2>

<ul>
<li><a href="#sobre">Sobre</a></li>
<li><a href="#tecnologia">Tecnologia</a></li>
<li><a href="#impacto">Impacto</a></li>
<li><a href="#contato">Contato</a></li>
</ul>

</nav>
</header>

<section class="hero">

<div class="conteudo">
<h1>Agro Forte, Futuro Sustentável</h1>

<p>
Produzir mais, preservar a natureza e alimentar o futuro com inovação.
</p>

<a href="#sobre" class="botao">Conheça Mais</a>

</div>

</section>

<section id="sobre">

<h2 class="titulo">O Agro Move o Mundo</h2>

<div class="cards">

<div class="card">
<h3>🌾 Produção</h3>
<p>
O agronegócio fornece alimentos, fibras e energia para milhões de pessoas,
impulsionando a economia e garantindo segurança alimentar.
</p>
</div>

<div class="card">
<h3>🌎 Sustentabilidade</h3>
<p>
Tecnologias modernas ajudam a reduzir impactos ambientais,
economizando água, solo e recursos naturais.
</p>
</div>

<div class="card">
<h3>🚜 Inovação</h3>
<p>
Drones, sensores, inteligência artificial e agricultura de precisão tornam
o campo mais eficiente e produtivo.
</p>
</div>

</div>

</section>

<section id="tecnologia">

<h2 class="titulo">Tecnologias do Campo</h2>

<div class="cards">

<div class="card">
<h3>🚁 Drones</h3>
<p>Monitoramento das lavouras com rapidez e precisão.</p>
</div>

<div class="card">
<h3>📡 Sensores</h3>
<p>Controle da umidade, temperatura e qualidade do solo.</p>
</div>

<div class="card">
<h3>🤖 Inteligência Artificial</h3>
<p>Auxílio na tomada de decisões e aumento da produtividade.</p>
</div>

<div class="card">
<h3>☀ Energia Limpa</h3>
<p>Painéis solares e fontes renováveis tornam as propriedades mais sustentáveis.</p>
</div>

</div>

</section>

<section id="impacto">

<h2 class="titulo">Impacto Positivo</h2>

<div class="numeros">

<div class="numero">
<h2>90%</h2>
<p>Uso eficiente de recursos naturais.</p>
</div>

<div class="numero">
<h2>100%</h2>
<p>Compromisso com o futuro sustentável.</p>
</div>

<div class="numero">
<h2>+50%</h2>
<p>Maior produtividade com tecnologia.</p>
</div>

</div>

</section>

<section id="contato">

<h2 class="titulo">Juntos pelo Futuro</h2>

<div class="card">
<p style="text-align:center;font-size:20px;">
🌱 O futuro começa no campo. Valorizar o agronegócio é investir em inovação,
desenvolvimento e sustentabilidade para as próximas gerações.
</p>
</div>

</section>

<footer>

<h3>Agro Forte • Futuro Sustentável</h3>

<p>© 2026 - Desenvolvido para fins educacionais.</p>

</footer>

</body>
</html>
