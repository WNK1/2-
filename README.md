<!DOCTYPE html>
<html lang="en-Us"></html>
<meta charset="utf-8" />
<meta name="viewport" content="width=devise-width, initial-scale=1.0">
<!-- предыдущая строчка кода обязательна , используется что бы на всех девайсах было нормальное разрешение и оно автоматически подстраивалось -->
<title> new </title>


<head>
    <link rel="stylesheet" href="new.css">
    <link rel="icon" type="image/png" href="icon.ico">
</head>



<style>
ul {
    list-style-type: none;                                                                         
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #07b2e6;
    }
    
    li {
    float: left;
    }
    
    li a {
    display: block;
    color: whitesmoke;
    text-align: center;
    padding: 20px;
    text-decoration:underline;
    }
    
    li a:hover {
    background-color: #ee710a;
    }

    div {
        background-color: rgb(0, 5, 7);
        color: rgb(125, 12, 160);
    }

    
    .mycontainer{
       display: flex;
    }

    .mycontainer > div {
       width: 50%;
    }

    .semantika{
        display: flex;
        color: aqua;
    }

    .semantika > div {
        width: 20%;
    }



    .secondclass {
        background-color: aquamarine;
        color: whitesmoke;
        border: none;
        text-decoration: underline;
        margin: auto;
        padding: 20px;

    }

    .note {
        font-size: xx-large;
        color: red;
        text-decoration: wavy;
        
    }

    .napominanie {
        font-size: xx-large;
        color: aquamarine;

    }

    #test {
        background-color: black;
        color: teal;
        text-align: center;
        padding: 10px;

    }
    </style>
        <!-- ПРОПИСАНО ЧЕРЕЗ FLEX - ПРИМИНЯЕТСЯ КО ВСЕМ ДИВ ЭЛЕМЕНТАМ 
        .mycontainer{
       display: flex;
    }

    .mycontainer > div {
       width: 50%;
    }
      !!!!!!!!!!!!!!! СПРОСИТЬ ПОЧЕМУ НЕ РАБОТАЕТ ЧЕРЕЗ .GRID-CONTAINER -->
    
    <ul>
      <li><a href="#home">I</a></li>
      <li><a href="#news">New</a></li>
      <li><a href="#contact">TOP</a></li>
      <li><a href="#about">IN THE...</a></li>
      <li><a href="#about"> WORLDS</a></li>
    </ul>
</head>


<body>



<h1>  ITs a test</h1>
<p> second test</p>
<hr>
<!--<ul>
    <li> i</li>
    <li> new</li>
    <li> jenius</li>
    <li> in the world</li>
</ul>
-->
<a href="file:///C:/Users/nikita.kudryavcev/Desktop/first%20project/%D0%BF%D0%B0%D1%81%D1%85%D0%B0%D0%BB%D0%BA%D0%B0.html">
    <img src="https://media1.tenor.com/m/EjowS1wbJjMAAAAC/peaky-blinders.gif" alt="suka" style="width: 320px;height: 180px;"> </a>
    <title>кликни на меня </title>

    <hr>

    <div style="background-color: whitesmoke;color: #ee710a;"></div><h1> new text</h1> 
        <p> London is the capital of britan ...</p>
        <p title="Шутка xd"><span style="background-color: azure;color: black;"> А теперь можешь иди на хуй 0x </span></p>
    </div>

<hr>
<h1 style="color: #ee710a;"> ONE MORE TEST</h1>
<p>ftx ist a <div style="background-color: #ee710a;color: black;">scam</div> its a true </p>


<hr>
<div>
    <h2>on more</h2>
<p>o more</p>
<h3>more </h3>
</div>
<p><span style="color: aqua;"> o more </span> more o more </p>
<p>o more </p>

<hr>

<div class="mycontainer" > 

    <div style="background-color: #ee710a;color: black;">
    <h1>FIRST TEXT</h1>
    <p>wefwfuwfhwiufhwifuhwufhwifhwiufhuwifhwuifhwuifhwiufhwuifhwhfwuihefiwhfuihwiuf</p>  
    <p>weywyyyyyyyuyuyy</p>
    </div>




    <div style="background-color:  rgb(12, 9, 9);color: rgb(47, 196, 255);"> 
    <h1>Second TEXT</h1>
    <p>оч мало текста так то </p>
    <p> ну пусть будет так</p>
    </div>

</div>

<div class="secondclass">
    <div>
        <h1>ЕГОР</h1>
        <p> GONDON</p>
        <P> DA ЭTO ON</P>
    </div>

    <div>
        <h1>Никита</h1>
        <p> Кравсавчик</p> 
        <p id="test">On sasnый malchik</p>
    </div> 
</div>

<hr>
<!--
<div>
    <h1> Who <span class="note"> IMPOSTER <span>  ?</h1>
    <p style="color: #ee710a;font-size:xx-large;"> U <span class="note"> IMPOSTER</span></p>
</div>
<hr>
<div class="napominanie">
    <p>Посхалка и напоминание которое ты не заметил</p>
</div>
<iframe src="file:///C:/Users/nikita.kudryavcev/Desktop/first%20project/%D0%BF%D0%B0%D1%81%D1%85%D0%B0%D0%BB%D0%BA%D0%B0.html" style="width: 1350px;height:420px;border: 1px solid orange;" title="test in site" ></inframe>
-->
<hr>
<h1> TRENING JS SCRIPT'S</h1>
<p>Почему не работает ? я не понимаю </p>
<p id="script" ></p>


<script>
    document.getElementById("script").innerHTML = "а , нет , все таки работает , ошибка в коде сверху , спросить у Еги";
</script>

<hr>

<div class="secondclass">
    <div> 
        <h1>Семантика изучение для верстки </h1>
        <p> Основный теги </p>
    </div>
</div>

<div class="semantika" >
    <div>
    <h1> Элемент HTML section </h1>
    <p> определяет раздел работает по принципу h </p>
    <p>делит текст на 2 разных , схожих по теме </p>
    <p> используется в основном в оглавлениях</p>
    <p>контактных данных и новостных матерьялах</p>
    </div>

    <div>
    <h1> Элемент HTML section </h1>
    <p> определяет раздел работает по принципу h </p>
    <p>делит текст на 2 разных , схожих по теме </p>
    <p> используется в основном в ...</p>
    </div>
</div>




</body>
</html>
