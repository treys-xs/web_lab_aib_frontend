### как выглядит страница компьютерной версии
![комп верс](https://github.com/treys-xs/web_lab_aib_frontend/blob/main/labs/Lab_05_HTML_CSS/solution/comp_lab5.png)
### как выглядит страница мобильной версии
![мобил верс](https://github.com/treys-xs/web_lab_aib_frontend/blob/main/labs/Lab_05_HTML_CSS/solution/mobil_lab5.png)
### файл html
```
<!DOCTYPE html>
<html lang="ru">
<html>
<head>
    <title>TOP GAMES</title>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <link rel="stylesheet" href="style_lab5.css"/>
    <script src="JavaScript.js"></script>
</head>
<body>

<header>
    <nav>
        <li><a href="#main">Содержимое</a></li>
        <article id="main"></srticle>
            <li><a href="https://www.metrothegame.com/en-us/" target="_blank">Это стоит посетить</a></li>
    </nav>
    <p class="logocenter">
        <img src="Online-Exclusive.jpg" width="170" alt="Логотип сайта">
    </p>
</header>
<main>
    <h1>Каталог игр</h1>
    <h2>Новые игры</h2>
    <div class="main-catalog">
        <div class="item">
            <img src="photo/1682840635_fonzon-club-p-igri-oblozhka-7.jpg" alt="Dead Rising 4">
            <p><br>Dead Rising 4</p>
        </div>
        <div class="item">
            <img src="photo/1682840657_fonzon-club-p-igri-oblozhka-13.jpg" alt="MURDERED">
            <p><br>MURDERED</p>
        </div>
        <div class="item">
            <img src="photo/1682840668_fonzon-club-p-igri-oblozhka-28.jpg" alt="Star Wars: Battlefront">
            <p><br>Star Wars: Battlefront</p>
        </div>
        <div class="item">
            <img src="photo/1682840676_fonzon-club-p-igri-oblozhka-75.jpg" alt="Tom Clancy’s The Division">
            <p><br>Tom Clancy’s The Division</p>
        </div>
        <div class="item">
            <img src="photo/1682840699_fonzon-club-p-igri-oblozhka-40.jpg" alt="Resident Evil 2">
            <p><br>Resident Evil 2</p>
        </div>
        <div class="item">
            <img src="photo/1682840717_fonzon-club-p-igri-oblozhka-29.jpg" alt="Watch Dogs">
            <p><br>Watch Dogs</p>
        </div>
    </div>
    <h2>Популярные игры</h2>
    <div class="promo-catalog">
        <div class="item2">
            <img src="photo/1682840720_fonzon-club-p-igri-oblozhka-51.jpg" alt="InFamous 2">
            <p><br>InFamous 2</p>
        </div>
        <div class="item2">
            <img src="photo/1682840731_fonzon-club-p-igri-oblozhka-42.jpg" alt="Dead Rising 3">
            <p><br>Dead Rising 3</p>
        </div>
        <div class="item2">
            <img src="photo/1682840740_fonzon-club-p-igri-oblozhka-88.jpg" alt="Battlefield 3">
            <p><br>Battlefield 3</p>
        </div>
        <div class="item2">
            <img src="photo/1682840766_fonzon-club-p-igri-oblozhka-81.jpg" alt="Call of Duty: Infinite Warfare">
            <p><br>Call of Duty: Infinite Warfare</p>
        </div>
        <div class="item2">
            <img src="photo/1682840703_fonzon-club-p-igri-oblozhka-85.jpg" alt="DMC">
            <p><br>DMC</p>
        </div>
        <div class="item2">
            <img src="photo/1682840732_fonzon-club-p-igri-oblozhka-69.jpg" alt="Assassin’s Creed II">
            <p><br>Assassin’s Creed II</p>
        </div>
        <div class="item2">
            <img src="photo/1682840705_fonzon-club-p-igri-oblozhka-21.jpg" alt="Mafia 3">
            <p><br>Mafia 3</p>
        </div>
        <div class="item2">
            <img src="photo/1682840707_fonzon-club-p-igri-oblozhka-90.jpg" alt="Gears 5">
            <p><br>Gears 5</p>
        </div>
        <div class="item2">
            <img src="photo/1682840716_fonzon-club-p-igri-oblozhka-37.jpg" alt="Mass Effect">
            <p><br>Mass Effect</p>
        </div>
        <div class="item2">
            <img src="photo/1682840712_fonzon-club-p-igri-oblozhka-76.jpg" alt="Damnation">
            <p><br>Damnation</p>
        </div>
        <div class="item2">
            <img src="photo/1682840708_fonzon-club-p-igri-oblozhka-38.jpg" alt="Tomb Raider">
            <p><br>Tomb Raider</p>
        </div>
        <div class="item2">
            <img src="photo/1682840664_fonzon-club-p-igri-oblozhka-36.jpg" alt="Mortal Kombat 11">
            <p><br>Mortal Kombat 11</p>
        </div>
</main>
<footer>
    <p>лабораторная №5. сделал Щербань Владислав АСБ-3-037</p>
</footer>
</body>
</html>
```
### файл стилей style_lab5.css
```
header {
width:100%;
background: Snow;
height: 110px;
position: fixed;
margin-bottom: 0px;
}
main {
padding-top: 100px;
}
.logocenter {
    text-align: center;
}
h1, h2, p {
font-family: franklin gothic medium;
}
nav {
float: right;
margin-right: 50px;
line-height: 30px;
}
a, p{
color: Navy;
}
.item {
background: Snow;
width: 440px;
height: 300px;
margin-bottom: 10px;
margin-left: 25px;
}
.item2 {
background: Snow;
width: 40%;
height: 300px;
margin-bottom: 10px;
margin-left:5%;
}
img {
width: 200px;
}
.main-catalog {
text-align: center;
align-item: center;
display: flex;
flex-wrap: wrap;
padding-left: 12px;
padding-right: 12px;
margin-top: 20px;
margin-bottom: 20px;
}
.promo-catalog {
text-align: center;
align-item: center;
display: flex;
flex-wrap: wrap;
padding-left: 12px;
padding-right: 12px;
margin-top: 20px;
margin-bottom: 20px;
}
@media (min-width: 1280px) {
.item2{
width:20%;
margin-bottom: 30px;
margin-left:4%;
}
}
```
файл JavaScript.js ничего не содержит