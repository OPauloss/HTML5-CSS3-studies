<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="projeto/imagens/favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="style.css">
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap');

      @font-face {
          font-family: 'idroid';
          src: url(projeto/fontes/idroid.otf) format('opentype');
          }

          :root{
              --cor0: #c5ebd6;
              --cor1: #83e1ad;
              --cor2: #3ddc84;
              --cor3: #2fa866;
              --cor4: #1a5c37;
              --cor5: #063d1e;
          }
          * {
              box-sizing : border-box;
          }
          body{
              background-color: var(--cor1);
              margin: 0px;
          }
          header{
              background-image: linear-gradient(to bottom, var(--cor2), var(--cor3), var(--cor4), var(--cor5));
              border-bottom: 20px;
              margin: auto;
              padding-bottom: 10px;
              box-shadow: 0px 7px 9px rgba(0, 0, 0, 0.37);
          }
          header > h1{
              color: #ffffff;
              font: 500 2.5em 'Oswald', sans-serif;
              margin-top: 0px;
              margin-bottom: 0px;
              padding: 35px 35px 10px 35px;
              text-align: center;
              text-shadow: 2px 2px 0px rgba(0, 0, 0, 0.281);
          }
          header > h2{
              text-align: center;
              color: #ffffff;
              font-family: Arial, Helvetica, sans-serif;
              font-weight: 200;
              font-size: 1.3em;
              margin-top: 30px;
              margin-bottom: 50px;
              text-shadow: 2px 2px 0px rgba(0, 0, 0, 0.281);
          }
          nav > a{
              font-family: Arial, Helvetica, sans-serif;
              font-weight: bold;
              color: #ffffff;
              text-decoration: none;
              padding: 10px;
              margin-left: 10px;
          }
          nav > a:hover{
              background-color: var(--cor3);
              border-radius: 5px;
              color: var(--cor5);
              transition-duration: 0.5s;
          }
          main{
              text-align: justify;
              margin: auto;
              max-width: 1000px;
              min-width: 300px;
              background-color: white;
              font-family: Verdana, Geneva, Tahoma, sans-serif;
              padding: 20px;
          }
          main > h1 {
              font-family: 'idroid';
              color: var(--cor5);
          }
          main > h2 {
              font-family: 'idroid';
              color: var(--cor5);
              background-image: linear-gradient(to right, var(--cor1), transparent);
              padding-left: 10px;
          }
          main > p{
              text-indent: 20px;
          }
          main img{
              width: 100%;
          }
          #Bugdroid{
              display: block;
              margin: auto;
              max-width: 350px;
          }
          span{
              color: var(--cor4);
              font-weight: bold;
          }
          span > a{
              color: #156D3A;
              font: bold;
              text-decoration: none;
          }
          span > a:hover{
              background-color: #3df191;
          }
          span > a::after{
              content: '🔗';
              font-weight: normal;
              color: darkgray;
          }
          #video{
              background-color: var(--cor5);
              text-align: center;
              margin: 0px -20px 0px -20px;
              padding: 4px;
              padding-bottom: 58.5%;
              position: relative;
          }
          #video > iframe{
              position: absolute;
              width: 90%;
              height: 90%;
              top: 5%;
              left: 5%;
          }
          h3{
              margin: 0px;
              background-color: #156D3A;
              border-radius: 10px 10px 0px 0px;
              color: white;
              padding: 10px
          }
          article{
              background-color: var(--cor1);
              margin-left: 20px;
              margin-right: 20px;
              border-radius: 10px;
              text-align: justify;
              text-indent: 20px;
          }
          article > p{
              padding: 10px;
          }
          aside{
              background-color: white;
              text-align: justify;
              margin: auto;
              max-width: 1000px;
              min-width: 300px;
              border-bottom-left-radius: 10px;
              border-bottom-right-radius: 10px;
          }
          aside > p{
              font-family: Verdana, Geneva, Tahoma, sans-serif;
              text-indent: 10px;
              padding: 10px;
          }
          aside ul{
              list-style-position: inside;
              list-style-type: '\2714\00a0';
              columns: 2;
              padding: 10px;
          }
          aside li{
              text-indent: 0px;
          }
          footer{
              text-align: center;
              background-color: #023B1A;
              color: white;
              font-weight: bold;
              padding: 2px;
          }
  </style>
    <title>Primeiro site</title>
</head>
<body>
    <header>
        <h1>CURIOSIDADES DE TECNOLOGIA</h1>
        <h2>Tudo aquilo que você sempre quis saber sobre o mundo <br> Tech, em um único lugar.</h2>
        <nav>
            <a href="#">Home</a>
            <a href="#">Notícias</a>
            <a href="#">Curiosidades</a>
            <a href="#">Fale Conosco</a>
        </nav>
    </header>
    <main>
        <h1>HISTÓRIA DO MASCOTE DO ANDROID</h1>
            <p>Provavelmente você sabe que o sistema operacional <span>Android</span>, mantido pelo <span>Google</span> é um dos mais utilizados para dispositivos móveis em todo o mundo. Mas tavez você não saiba que o seu simpático mascote tem um nome e uma história muito curiosa? Pois acompanhe esse artigo para aprender muita coisa sobre esse robozinho.</p>
        <h2>A PRIMEIRA VERSÃO</h2>
        <p>A primeira tentativa de criar um mascote surgiu em 2007 e veio de um desenvolvedor chamado <span><a href="https://androidcommunity.com/dan-morrill-shows-us-the-android-mascot-that-almost-was-20130103/" target="_blank">Dan Morrill</a></span>. Ele conta que abriu o <span><a href="https://inkscape.org/pt-br/" target="_blank">Inkscape</a></span> (software livre para vetorização de imagens) e criou sua própria versão de robô. O objetivo era apenas personificar o sistema apenas para a a sua equipe, não existia nenhuma solicitação da empresa para a criação de um mascote.</p>
        <picture>
            <source media="(max-width: 670px)" srcset="projeto/imagens/dan-droids-pq.png" type="image/png">
            <img src="projeto/imagens/dan-droids.png" alt="Dandroids">
        </picture>
        <p>Essa primeira versão bizarra até foi batizada em homenagem ao seu criador: seriam os <span>Dandroids</span>.</p>
        <h2>SURGE UM MASCOTE</h2>
        <p>A ideia de ter um mascote foi amadurecendo e a missão foi passada para uma profissional da área. A ilustradora Russa <span><a href="https://www.irinablok.com/android" target="_blank">Irina Blok</a></span>, também funcionária do Google, ficou com a missão de representar o pequeno robô de uma maneira mais agradável.</p>
        <picture>
            <source media="(max-width: 670px)" srcset="projeto/imagens/irina-blok-pq.jpg" type="image/jpeg">
            <img src="projeto/imagens/irina-blok.jpg" alt="Irina Blok">
        </picture>
        <p>A ideia principal da Irina era representar tudo graficamente com poucos traços e de forma mais chapada. O desenho também deveria gerar identificação rápida com quem o olha. Surgiu então o <span>Bugdroid</span>, o novo mascote do Android.</p>
        <img src="projeto/imagens/bugdroid.png" alt="Bugdroid" id="Bugdroid">
        <p>A principal inspiração para os traços do novo Bugdroid veio daqueles bonequinhos que ilustram portas de banheiro para indicar o gênero de cada porta. Conta a lenda que a artista estava criando em sua mesa no escritório do Google e olhou para o lado dos banheiros e a identificação foi imediata: simples, limpo, objetivo.</p>
        <div id="video">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/l2UDgpLz20M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </main>
    <aside>
        <article>
            <h3>Quer aprender mais?</h3>
            <p>Outro assunto curioso em relação ao Android é que cada versão sempre foi nomeada em homenagem a um doce, em ordem alfabética a partir da versão 1.5 até a 9.0.</p>
            <ul>
                <li>1.5 - <abbr title="Bolo de copo">Cupcake</abbr></li>
                <li>1.6 - <abbr title="Rosquinha">Donut</abbr></li>
                <li>3.0 - <abbr title="Bomba">Eclair</abbr></li>
                <li>2.2 - <abbr title="Iogurte congelado">Froyo</abbr></li>
                <li>2.3 - <abbr title="Biscoito de gengibre">Gingerbread</abbr></li>
                <li>3.0 - <abbr title="Favo de mel">Honeycomb</abbr></li>
                <li>4.0 - <abbr title="Sanduíche de sorvete">Ice Cream Sandwich</abbr></li>
                <li>4.1 - <abbr title="Jujuba">Jelly Bean</abbr></li>
                <li>4.4 - <abbr title="KitKat">KitKat</abbr></li>
                <li>5.0 - <abbr title="Pirulito">Lolipop</abbr></li>
                <li>6.0 - <abbr title="Marshmallow">Marshmallow</abbr></li>
                <li>7.0 - <abbr title="Torrone">Nougat</abbr></li>
                <li>8.0 - <abbr title="Oreo">Oreo</abbr></li>
                <li>9.0 - <abbr title="Torta">Pie</abbr></li>
            </ul>
            <p>Infelizmente, o <span>Android Q</span> não existiu, pois o Google resolveu pôr fim a essa divertida prática e começou a usar numerações, o que deu origem ao <span>Android 10</span>.</p>
            <p>Acesse aqui o site <span><a href="https://www.android.com/intl/en_uk/">Android History</a></span> para conhecer a sequência das versões "adocicadas" e o que cada uma trouxe para o sistema Android.</p>
        </article>
        <p>Então é isso! Espero que você tenha gostado do nosso artigo com essa curiosidade sobre sistema Android e seu simpático mascote.</p>
    </aside>
    <footer>Site criado por <span><a href="https://github.com/OPauloss" target="_blank">Paulo Henrique Santos</a></span> para o CursoemVídeo</footer>
</body>
</html>
