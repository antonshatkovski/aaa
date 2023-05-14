<html>
    <head>
        <title>BitMarket</title>
        <link rel="stylesheet" href="style.css">
    </head>
  body {
    font-family: sans-serif;
    background-color: gray;
}
.skidk :hover {
    background-color: orange;
}
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px;
    margin-bottom: 20px;
}
.hit{ 
    width: 500px;
}
 
.promo  { 
    background-color: #ECDB9E;
    padding: 6px;
    font-size: 20px;
    position: fixed;
    bottom: 0px;
    width: 7%;
    right: 6px;
    border-radius: 35px;
}
.kata a:hover {
    color: darkorange;
    background-color: lightblue;
} 
.opt a:hover {
    color: darkorange;
    background-color: lightblue;
}
.doct a:hover {
    color: darkorange;
    background-color: lightblue;
}
.vozv a:hover {
    color: darkorange;
    background-color: lightblue;
}
.button  {
    text-decoration: none;
    color: white; 
    background-color: #312c22;
    color: white;
    text-decoration: none;
    padding: 15px;
    font-size: 24px;
    border-radius: 10px;
    display: block;
    
}

nav {
    background-color: black;
    border-top: 5px solid white;
    border-bottom: 5px solid white;
    padding: 25px 100px 25px 95px;
    display: flex;
    justify-content: space-between;
}

.nav-link {
    font-size: 24px;
    color: white;
    text-decoration: none;
    display: block;
}

h1 {
    text-align: center;
    color: white;
    font-size: 36px;
    margin-top: 45px;
    margin-bottom: 40px;
}
.h1::after{
content: url("");
width: 30px;
weight: 30px;
display: block;
}    
.post-text {
    font-size: 24px;
    
}

.info {
    display: flex;
    flex-wrap: wrap;
    max-width: 1100px;
    margin: 0 auto;
}

.post {
     background-color: rgb(236, 197, 112);
    padding: 15px 45px 30px 45px;
    width: 400px;
    margin: 20px;
    position: relative;
    border-radius: 35px
}
.post:hover{
    background-color: rgb(158, 158, 158);
    color: white;
}
.post a:hover {
    color: white;
    background-color: rgb(0, 140, 255);
}
.article-but {
   text-decoration: none;
    background-color: #133aac;
    color: white;
    font-size: 24px;
    text-align: center;
    padding: 10px 75px 10px 75px;
    display: block;
    border: 5px double rgb(3, 212, 219);
    border-radius: 20px
    
    
}


.full-image {
    margin: 100px 0px 100px 0px;
}

.social {
    display: block;
    width: 30px;
}

footer {
    background-color: white;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    padding: 30px 30px 20px 45px;
}

.footer-text {
    font-size: 24px;
    margin-right: 30px;
}

.footer-text span {
    color: #850AE5;
    font-weight: bolder;
}
    <body>
        <header>
            <img class="logo" src="https://backoffice.algoritmika.org/uploads/2021/03/logo1_0_1615899136.svg">
            <div class="skidk">
            <a class="button" href="">Скидки</a>
            </div>
        </header>
        <nav>
            <div class="kata">
            <a class="nav-link" href="">Каталог</a>
            </div>
            <div class="opt">
            <a class="nav-link" href="">Оптом</a>
            </div>
            <div class="doct">
            <a class="nav-link" href="">Доставка</a>
            </div>
            <div class="vozv">
            <a class="nav-link" href="">Возврат товара</a>
            </div>
        </nav>
       
        <div class="promo">
            <p><b>Напиши — получи промокод!</b></p>
            <a class="social" href=""><img src="https://backoffice.algoritmika.org/uploads/2021/02/icon-set-1142000_1280%201_0_1613586391.png"></a>
            <a class="social" href=""><img src="https://backoffice.algoritmika.org/uploads/2021/02/Group%201_0_1613586391.png"></a>
            <a class="social" href=""><img src="https://backoffice.algoritmika.org/uploads/2021/02/instagram-3288419_1280%201_0_1613586391.png"></a>
            </div>
        <main>
            <h1>Профессионалы советуют</h1>
            <section class="info">
                <article class="post">
                    
                    <h2>Лэптоп для отдыха</h2>
                    <img class="post-img" src="https://backoffice.algoritmika.org/uploads/2021/02/notebook-405755_1920_0_1613586011.jpg" width="400px" height="300px"/>
                    <p class="post-text">Samsung V145-S</p>
                    <a class="article-but" href="">Подробнее</a>
                </article>
                <article class="post">
                    <h2>Как выбрать наушники</h2>
                    <img class="post-img" src="https://backoffice.algoritmika.org/uploads/2021/02/music-1813100_1280_0_1613586010.png" width="330px" height="300px"/>
                    <p class="post-text">Поговорим о новинках</p>
                    <a class="article-but" href="">Подробнее</a>
                </article>
                <article class="post">
                    <h2>Телефон мечты</h2>
                    <img class="post-img" src="https://backoffice.algoritmika.org/uploads/2021/02/mobile-phone-1875813_1920_0_1613586011.jpg" width="400px" height="300px"/>
                    <p class="post-text">Apple iphone 13</p>
                    <a class="article-but" href="">Подробнее</a>
                </article>
                <article class="post">
                    <h2>Техника для всего</h2>
                    <img class="post-img" src="https://backoffice.algoritmika.org/uploads/2021/02/laptop-1483974_1920_0_1613586010.jpg" width="400px" height="300px"/>
                    <p class="post-text">И целого мира мало...</p>
                    <a class="article-but" href="">Подробнее</a>
                     </article>
                     </section>
        </main>
        <footer>
            <div class="contacts">
                <p class="footer-text"><span class="address">Адрес:</span> город Технологический,<br/> пр-д Современный, 29/2</p>
                <p class="footer-text"><span class="tel">Телефон:</span> 4138-564</p>
            </div>
            <div class="footer-logo">
                <img src="https://backoffice.algoritmika.org/uploads/2021/03/logo2_0_1615898903.svg"/>
            </div>
        </footer>
    </body>
</html>
