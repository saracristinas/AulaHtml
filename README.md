# AulaHtml-Css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

#appView {
    background-color: #500076;
    width: 100vw;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-content: center;
}

#header {
    position: fixed;
    background-color: #F47676;
    width: 100vw;
    height: 120px;
    left: 0;
    top: 0;
}

#main {
    width: 100vw;
    right: 100%;
    display: flex;
    justify-content: center;
    align-content: center;
    margin-top: 200px;
    gap: 200px;
}


#text {
    background-color: rgba(100, 100, 100, 0.6);
    padding: 15px;
    padding-left: 30px;
    padding-top: 15px;
    display: flex;
    flex-direction: column;
    gap: 10px;
}

#text p span{
    color: #F47676;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

#text p {
    font-size: 15px;
    display: flex;
    flex-direction: column;
    gap: 10px;
}
#line {
    border-left: 2px solid white;
    height: 500px;
}

#gojozin, #text {
    width: 300px;
    height: 500px;
    border-radius: 15px;
    display: flex;
    border: 2px solid white;
    color: white;
}



HTML

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./css/style.css">
    <title>IHUUU</title>
</head>

<body>
    <div id="appView">
        <header id="header">

        </header>

        <main id="main">

            <div id="text">
                <h1>Sobre isso</h1>

                <p>“O que é importante não é vencer todos os dias, mas lutar sempre.” – Jigoro Kano “Para ser forte,
                    você deve ver a fraqueza de seus adversários.” – Edward Newgate “Se você dono da sua vontade, pode
                    superar seus limites.” – Gon Freecss “Não importa quantas vezes caímos, sempre podemos nos
                    levantar.” – Natsu Dragneel <span>"Seu pai é viado" - mc poze do rodo"</span> “A verdadeira dor é não poder alcançar seus sonhos.” – Yugi Muto
                    “Devemos lutar pelos nossos sonhos até o fim, mesmo que isso signifique sacrificar tudo.” – Naruto
                    Uzumaki “Nunca desista, pois essa é a única maneira de perder.” – Gintoki Sakata “Não importa o quão
                    difícil seja a batalha, nunca desista!” – Monkey D. Luffy “Não há limites para o que um homem pode
                    alcançar, desde que ele nunca desista.” – Saitama “O medo é apenas um obstáculo. Se você quer algo,
                    vá lá e conquiste!” – Tatsuya Shiba
                </p>
                <h2>Gojozin Sabe muito</h2>
            </div>

            <div id="line">


            </div>

            <figure>
                <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ&pp=ygUYbmV2ZXIgZ29ubmEgZ2l2ZSB5b3UgdXAg">
                    <img src="./img/gojo.png" alt="irmãogojo.pgn" id="gojozin">
                </a>
            </figure>
        </main>
    </div>
</body>

</html>
