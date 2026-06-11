<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Eil ♡</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Georgia, serif;
}

body{
background:linear-gradient(135deg,#ffd9e8,#fff4f7,#e7dcff);
overflow-x:hidden;
color:#444;
}

section{
min-height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
padding:40px;
text-align:center;
}

.hero h1{
font-size:4rem;
color:#ff7eb6;
}

.hero p{
margin-top:15px;
font-size:1.2rem;
max-width:600px;
}

button{
margin-top:25px;
padding:15px 30px;
border:none;
border-radius:30px;
background:#ff9cc6;
color:white;
font-size:1rem;
cursor:pointer;
transition:.3s;
}

button:hover{
transform:scale(1.05);
}

.letter{
background:white;
padding:35px;
border-radius:20px;
max-width:700px;
box-shadow:0 10px 30px rgba(0,0,0,.1);
line-height:1.8;
}

.gallery{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:30px;
}

.polaroid{
background:white;
padding:10px 10px 40px;
width:230px;
box-shadow:0 5px 15px rgba(0,0,0,.15);
transform:rotate(-3deg);
transition:.4s;
}

.polaroid:nth-child(even){
transform:rotate(3deg);
}

.polaroid:hover{
transform:scale(1.08);
}

.polaroid img{
width:100%;
height:260px;
object-fit:cover;
}

.polaroid p{
margin-top:10px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
width:90%;
max-width:900px;
}

.card{
background:white;
padding:25px;
border-radius:20px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
}

.final{
font-size:2rem;
max-width:800px;
}

.music{
position:fixed;
top:20px;
right:20px;
z-index:999;
}
</style>

</head>
<body>

<audio id="song" loop>
<source src="Strawberries & Cigarettes.mp3" type="audio/mpeg">
</audio>

<button class="music" onclick="toggleMusic()">
Strawberries & Cigarettes
</button>

<section class="hero">
<h1>For Eil ♡</h1>

<p>
A little collection of memories,
laughter and all the moments
that made our friendship special.
</p>

<button onclick="document.getElementById('letter').scrollIntoView({behavior:'smooth'})">
Open My Gift
</button>
</section>

<section id="letter">
<div class="letter">

<h2>Dear Eil,</h2>

<br>

<p>
Thank you for being part of my life.
This little website is filled with memories,
smiles and moments that I never want to forget.
I hope it reminds you how much you mean to me.
</p>

<br>

<p>
Love,
<br>
Rin ♡
</p>

</div>
</section>

<section>

<h2 style="margin-bottom:40px;">
when i think of you, i think of ...
</h2>

<div class="gallery">

<div class="polaroid">
<img src="Photo1.jpg">
<p>but you're</p>
</div>

<div class="polaroid">
<img src="Photo2.jpg">
<p>the life</p>
</div>

<div class="polaroid">
<img src="Photo3.jpg">
<p>i needed</p>
</div>

<div class="polaroid">
<img src="Photo4.jpg">
<p>all along</p>
</div>

<div class="polaroid">
<img src="Photo5.jpg">
<p>♡</p>
</div>

</div>

</section>

<section>

<h2 style="margin-bottom:30px;">
Things I Love About You
</h2>

<div class="cards">

<div class="card">
your personality
</div>

<div class="card">
Always makes me smile
</div>

<div class="card">
when you're yapping 
</div>

<div class="card">
your kind heart and pure soul
</div>

<div class="card">
Always makes me feel special
</div>

<div class="card">
Simply being Eil
</div>

</div>

</section>

<section>

<div class="final">

Thank you for every laugh,
every memory,
and every moment.

<br><br>

♡

</div>

</section>

<script>
function toggleMusic(){
const music=document.getElementById("Strawberries & Cigarettes.mp3");

if(music.paused){
music.play();
}
else{
music.pause();
}
}
</script>

</body>
</html>
