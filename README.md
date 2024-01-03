# Portifolio
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portifólio</title>
    
    <!-- CSS -->
    
    <link rel="stylesheet" href="./CSS/reset.css">
    <link rel="stylesheet" href="./CSS/header.css">
    <link rel="stylesheet" href="./CSS/footer.css">
    <link rel="stylesheet" href="./CSS/main.css">

    <!-- FONTS -->
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2Wfamily=Montserrat:wght@200&display=swap" rel="stylesheet">
    
    <!-- ICONS -->
    
    <script scr="https://kit.fontawesome.com/65cff51947.js" crossorigin="anonymous" defer></script>
    </head>
    <body>
    <header>
        <h1>Dev.KONNOR</h1>
    
        <nav>
            <a class="git" href="https://github.com/konnorw">GITHUB</a>
            <i class="fa-brands fa-github"></i>
        </a>

            <a class="insta" href="https://www.instagram.com/konnorx___/">INSTAGRAM</a>
                <i class="fa-brands fa-instagram"></i>
        </nav>
    </header>

    <main>
          <section class="main-content">
            <article class="text">
            <h2>🙋‍♀️ Sobre mim</h2>
            <p>
                Olá, me chamo Nikelly (ou Konnor 😜), tenho 21 anos e sou de São Paulo, Brasil.
                Estudante do curso profissionalizante Desenvolvimento de Website e Design Gráfico.
                Apaixonada por desenvolvimento de software, estudo programação desde os 18 anos, com ênfase em desenvolvimento front end.
            </p>
            </article>

            <aside class="techs">
                <h2>👩‍💻 Tecnologias</h2>

                <div class="cards-container">
                    <div class="card">
                        <img src="./img/html-logo.png/html-logotipo.png" alt="Logo do HTML5">
                    </div>

                    <div class="cards-container">
                        <div class="card">
                            <img src="./img/css-logo.png/css-logo.jpg" alt="Logo do CSS">
                </div>

                <div class="cards-container">
                    <div class="card">
                        <img src="./img/js-logo.png/JavaScript-logo.png" alt="Logo do JavaScript">
                    </div>

            </div>
            </aside>

          </section>
          
          <figure class=".konnor">
            <img src="./img/konnor (eu)/img.jpeg" alt="Imagem de Nikelly Ferreira">
            <figcaption>Konnor</figcaption>
          </figure>
        </section>
    </main>

    <footer class="footer">
        <span>
            &copy; Nikelly Ferreira, 2021 - Todos os direitos reservados.
        </span>
    </footer>
</body>

main{
    padding: 5%;

    display: flex;
    align-items: center;
    justify-content: space-between;
}

/*MAIN CONTENT ============== */
main.main-content {
    display: flex;
    flex-direction: column;
}

main .main-content h2 {
    margin-bottom: 2%;
    font-size: 2.2em;
}

main .main-content text p {
    width: 76%;
    font-size: 1.2em;
    font-weight: 300;
}

/* CARDS =============== */
main .techs cards-container {
    display: flex;
    text-align: center;
}

main .techs {
    margin-right: 200%;
    text-align: left;
    margin-top: 10%;
    align-items: justify;
}

.card {
    width: 125px;
    height: 125px;
    padding: 10px;
    background-color: #eee;
    border-radius: 8px;
    cursor: pointer;
    
    transition: box-shadow 0.25 ease-in-out;
}

.card img {
    width: 100px;
    align-items: justify;
    vertical-align: 100%;
    justify-content: justify;
}

.card:hover {
    box-shadow: 8px 8px 19px #00e0ff;
}

.card {
    display: block;
    margin: 0 auto;
}

/* FIGURE ################### */
main figure {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

main figure img {
    width: 385px;
    height: 400px;
    border-radius: 700px;

    margin-bottom: 14%;
    border: 1 px #00e0ff solid;
    transition: 0.2s ease-in-out;
}

main figure img:hover {
    box-shadow: 10px 10px 30px #00e0ff;
}

main .konnor {
    width: 38px;
}

header {
    background-color: #222
}

header {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

header h1 {
    font-size: 2.8em;
    font-weight: 200;
    cursor: pointer;
}

header nav {
    display: flex;
}

header nav a {
    margin-right: 1.3em;
    font-size: 1.5em;
}

header h1, a {
    color: #00e0ff
}

header h1:hover, a:hover {
    color: #ffff
}

.git {
    display: inline-block;
    padding: 10px 20px;
    background-color: #222;
    color: #00e0ff;
    border: none;
    text-align: center;
    text-decoration: none;
    font-size: 17px;
    margin: 15px 2px;
    margin-top: 0%;
    margin-left: 0 auto;
    cursor: pointer;
    align-items: center;
    justify-content: space-between;
  }
  
.insta {
 display: inline-block;
    padding: 10px 20px;
    background-color: #222;
    color: #00e0ff;
    border: none;
    text-align: center;
    text-decoration: none;
    font-size: 17px;
    margin: 15px 2px;
    margin-top: 0%;
    margin-left: 0 auto;
    margin-right: 19%;
    cursor: pointer;
    align-items: center;
    justify-content: space-between;   
}

</html>

