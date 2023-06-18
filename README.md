# netflix-clone
![image](https://github.com/gabimatos81/netflix-clone/assets/99931221/472361e7-9d6d-4cec-badf-8db8630d58c9)
<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="main.css">

  <!-- responsividade -->
  <link rel="stylesheet" href="style/responsive.css" />

  <!-- owl css -->
  <link rel="stylesheet" href="style/owl/owl.carousel.min.css" />
  <link rel="stylesheet" href="style/owl/owl.theme.default.min.css" />

  <title>NETFLIX CLONE</title>
</head>

<body>
  <header>
    <div class="container">
      <h2 class="logo">NETFLIX</h2>
      <nav>
        <a href="#">Inicio</a>
        <a href="#">Séries</a>
        <a href="#">Filmes</a>
        <a href="#">Documentários</a>
      </nav>
    </div>
  </header>

  <main>
    <div class="filme-principal">
      <div class="container">

        <h3 class="titulo">Something the Rain</h3>
        <p class="descricao">Explore o relacionamento de duas pessoas à medida que passam de “apenas conhecidos” para
          “um casal genuíno” – Yoon Jin Ah, uma supervisora ​​de café na casa dos 30 anos, e Seo Joon Hee, designer de
          uma empresa de videogame que acabou de retornar de trabalhar no exterior.</p>

        <div class="botoes">
          <button role="button" class="botao">
            <i class="fas-fa-play"></i>
            ASSISTIR AGORA
          </button>
          <button role="button" class="botao">
            <i class="fas fa-info-circle"></i>
            MAIS INFORMAÇÕES
          </button>
        </div>
      </div>
    </div>
  </main>

  <div class="carousel-filmes">
    <div class="owl-carousel owl-theme">

      <div class="item">
        <img class="box-filme" src="img/Lista Negra.jpg" alt="" srcset="">
      </div>
      <div class="item">
        <img class="box-filme" src="img/Lucifer.jpg" alt="" srcset="">
      </div>
      <div class="item">
        <img class="box-filme" src="img/miraculous.jpg" alt="" srcset="">

      </div>
      <div class="item">
        <img class="box-filme" src="img/O gato de botas.jpg" alt="" srcset="">
      </div>
      <div class="item">
        <img class="box-filme" src="img/O lobo viking.jpg" alt="" srcset="">

      </div>
      <div class="item">
        <img class="box-filme" src="img/Sobrenatural.jpg" alt="" srcset="">
      </div>
      <div class="item">
        <img class="box-filme" src="img/The last of us.jpg" alt="" srcset="">

      </div>
      <div class="item">
        <img class="box-filme" src="img/walking dead.jpg" alt="" srcset="">
      </div>
      <div class="item">
        <img class="box-filme" src="img/wandinha.jpg" alt="" srcset="">
      </div>

    </div>
    <script src="https://kit.fontawesome.com/1d4cb0d7dc.js"></script>
    <script src="js/owl/jquery.min.js"></script>
    <script src="js/owl/owl.carousel.min.js"></script>
    <script src="js/owl/setup.js"></script>
</body>

</html>
