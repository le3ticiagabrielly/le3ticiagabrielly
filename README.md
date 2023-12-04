<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site de Paisagens</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
        }

        nav {
            background-color: #444;
            color: #fff;
            padding: 1em;
            text-align: center;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            padding: 0.5em 1em;
            margin: 0 1em;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #555;
        }

        main {
            padding: 2em;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>
    <header>
        <h1>Meu Site de Paisagens</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#galeria">Galeria</a>
        <a href="#sobre">Sobre</a>
        <a href="#contato">Contato</a>
    </nav>

    <main>
        <section id="home">
            <h2>Bem-vindo ao Nosso Mundo de Paisagens!</h2>
            <p>Explore a beleza natural ao redor do globo.</p>
        </section>

        <section id="galeria">
            <h2>Galeria de Paisagens</h2>
            <!-- Adicione suas imagens aqui -->
            <img src="paisagem1.jpg" alt="Paisagem 1">
            <img src="paisagem2.jpg" alt="Paisagem 2">
            <img src="paisagem3.jpg" alt="Paisagem 3">
        </section>

        <section id="sobre">
            <h2>Sobre Nós</h2>
            <p>Descubra mais sobre a equipe por trás deste site.</p>
        </section>

        <section id="contato">
            <h2>Entre em Contato</h2>
            <p>Envie-nos uma mensagem para compartilhar suas próprias paisagens incríveis!</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Meu Site de Paisagens. Todos os direitos reservados.</p>
    </footer>
</body>

</html>

