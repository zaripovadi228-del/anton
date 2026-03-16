<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Мастерская уюта — мебель на заказ</title>

<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet">

<style>

html{
scroll-behavior:smooth;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:'Montserrat',sans-serif;
background:#0f0f0f;
color:white;
line-height:1.6;
}

.container{
width:90%;
max-width:1200px;
margin:auto;
}

header{
position:fixed;
width:100%;
top:0;
background:rgba(0,0,0,0.7);
backdrop-filter:blur(10px);
z-index:1000;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 0;
}

.logo{
font-size:24px;
font-weight:600;
}

nav ul{
display:flex;
list-style:none;
gap:30px;
}

nav a{
text-decoration:none;
color:white;
font-size:14px;
}

.hero{
height:100vh;
background:url("https://images.unsplash.com/photo-1615874959474-d609969a20ed") center/cover;
display:flex;
align-items:center;
text-align:center;
}

.hero-content{
max-width: 1500px;
margin:auto;
background:rgba(0, 0, 0, 0.55);
padding: 100px;
border-radius:  30px;
}

.hero h1{
font-size:48px;
margin-bottom:20px;
}

.button{
display:inline-block;
background:#e9cb91;
padding:15px  20px;
border-radius:5px;
text-decoration:none;
color:black;
font-weight:600;
margin-top:20px;
}

section{
padding:100px 0;
}

h2{
text-align:center;
margin-bottom:60px;
font-size:36px;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:350px;
object-fit:cover;
border-radius:10px;
cursor:pointer;
transition:4s;
}

.gallery img:hover{
transform:scale(1.05);
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
}

.card{
background:#1a1a1a;
padding:30px;
border-radius:10px;
transition:0.3s;
}

.card:hover{
transform:translateY(-8px);
background:#222;
}

.steps{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:25px;
text-align:center;
}

.step{
background:#1a1a1a;
padding:30px;
border-radius:10px;
}

form{
max-width:500px;
margin:auto;
display:flex;
flex-direction:column;
gap:15px;
}

input, textarea{
padding:14px;
border:none;
border-radius:6px;
background:#1a1a1a;
color:white;
}

button{
padding:16px;
background:#c9a96a;
border:none;
border-radius:6px;
font-weight:600;
cursor:pointer;
}

footer{
background:black;
text-align:center;
padding:50px 0;
margin-top:50px;
}

/* LIGHTBOX */

.lightbox{
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background:rgba(0,0,0,0.9);
display:none;
align-items:center;
justify-content:center;
z-index:9999;
}

.lightbox img{
max-width:90%;
max-height:90%;
border-radius:10px;
}

.lightbox.active{
display:flex;
}

</style>
</head>

<body>

<header>
<div class="container">

<nav>

<div class="logo">Мастерская уюта</div>

<ul>
<li><a href="#works">Работы</a></li>
<li><a href="#about">Преимущества</a></li>
<li><a href="#steps">Процесс</a></li>
<li><a href="#contact">Контакты</a></li>
</ul>

</nav>

</div>
</header>

<section class="hero">

<div class="hero-content">

<h1>Корпусная мебель премиум качества</h1>

<p>Кухни, шкафы и гардеробные на заказ по индивидуальному проекту</p>

<a class="button" href="#contact">Получить расчет</a>

</div>

</section>

<section id="works">

<div class="container">

<h2>Наши работы</h2>

<div class="gallery">

<img src="images/1.jpg">
<img src="images/2.jpg">
<img src="images/3.jpg">
<img src="images/4.jpg">

</div>

</div>

</section>

<section id="about">

<div class="container">

<h2>Почему выбирают нас</h2>

<div class="grid">

<div class="card">
<h3>Индивидуальный дизайн</h3>
<p>Каждый проект мебели создается под размеры помещения и пожелания клиента.</p>
</div>

<div class="card">
<h3>Качественные материалы</h3>
<p>Используем надежные материалы и современную фурнитуру.</p>
</div>

<div class="card">
<h3>Собственное производство</h3>
<p>Контролируем весь процесс изготовления мебели.</p>
</div>

<div class="card">
<h3>Профессиональная


установка</h3>
<p>Аккуратно устанавливаем мебель и проверяем каждую деталь.</p>
</div>

<div class="card">
<h3>Гарантия качества</h3>
<p>Предоставляем гарантию на все изделия.</p>
</div>

<div class="card">
<h3>Работаем по Красноярску</h3>
<p>Выезжаем на замер и помогаем подобрать лучшее решение.</p>
</div>

</div>

</div>

</section>

<section id="steps">

<div class="container">

<h2>Как мы работаем</h2>

<div class="steps">

<div class="step">1. Заявка</div>
<div class="step">2. Консультация</div>
<div class="step">3. Замер</div>
<div class="step">4. Производство</div>
<div class="step">5. Установка</div>

</div>

</div>

</section>

<section id="contact">

<div class="container">

<h2>Получить расчет мебели</h2>

<form id="telegramForm">

<input type="text" placeholder="Ваше имя">

<input 
type="tel" 
id="phone"
placeholder="+7XXXXXXXXXX"
pattern="^\+7\d{10}$"
maxlength="12"
required
>

<textarea placeholder="Какая мебель вам нужна"></textarea>

<button type="submit">Отправить заявку</button>

</form>

</div>

<section id="map">

<h2>Наш офис</h2>

<p style="text-align:center;margin-bottom:30px;">
г. Красноярск, ул. Калинина 76ас1
<a href="https://yandex.ru/maps/?text=Красноярск%20Калинина%2076ас1" 
target="_blank"
class="button">
Проложить маршрут
</a>
</p>

<div style="width:100%;height:700px;border-radius:10px;overflow:hidden;">

<iframe 
src="https://yandex.ru/map-widget/v1/?text=Красноярск%20Калинина%2076ас1&z=16"
width="100%" 
height="700" 
frameborder="0">
</iframe>

</div>

</div>

</section>

<footer>

<p>Мастерская уюта</p>
<p>Корпусная мебель на заказ</p>

</footer>

<div id="lightbox" class="lightbox">
<img id="lightbox-img">
</div>

<script>

const images = document.querySelectorAll('.gallery img');
const lightbox = document.getElementById('lightbox');
const lightboxImg = document.getElementById('lightbox-img');

images.forEach(img=>{
img.addEventListener('click',()=>{
lightbox.classList.add('active');
lightboxImg.src=img.src;
});
});

lightbox.addEventListener('click',()=>{
lightbox.classList.remove('active');
});

</script>
<script>

const TOKEN = "8540261447:AAHFaJBxySnxIcpsuR3dcL2XZVF-IxuBs0U";
const CHAT_ID = "625782547";

document.getElementById("telegramForm").addEventListener("submit", function(e){

e.preventDefault();

let name = document.querySelector('input[type="text"]').value;
let phone = document.querySelector('input[type="tel"]').value;
let text = document.querySelector('textarea').value;

let message = 
"Новая заявка с сайта\n\n" +
"Имя: " + name + "\n" +
"Телефон: " + phone + "\n" +
"Комментарий: " + text;

fetch(`https://api.telegram.org/bot${TOKEN}/sendMessage`,{
method:"POST",
headers:{
"Content-Type":"application/json"
},
body:JSON.stringify({
chat_id:CHAT_ID,
text:message
})
})
.then(()=>alert("Заявка отправлена!"))
.catch(()=>alert("Ошибка отправки"));

});

</script>
<script>

const phoneInput = document.getElementById('phone');

phoneInput.addEventListener('input', function() {

let value = phoneInput.value.replace(/\D/g,'');

if(value.startsWith('7')){
value = value.substring(1);
}

phoneInput.value = '+7' + value.substring(0,10);

});

</script>
</body>
</html>
