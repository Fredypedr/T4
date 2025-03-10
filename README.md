<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flores Encanto - Loja de Flores</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff8f0;
            color: #5a3e36;
        }
        header {
            background-color: #ff6f61;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 24px;
        }
        nav {
            background-color: #ff8a75;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        main {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .produto {
            background-color: white;
            border-radius: 10px;
            padding: 15px;
            margin: 15px;
            text-align: center;
            width: 250px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .produto img {
            width: 100%;
            border-radius: 10px;
        }
        .botao-comprar {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background-color: #ff6f61;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        footer {
            background-color: #5a3e36;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        .redes-sociais {
            text-align: center;
            margin-top: 20px;
        }
        .redes-sociais a {
            display: inline-block;
            margin: 5px;
            color: #ff6f61;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>Flores Encanto - Beleza Natural para Você</header>
    <nav>
        <a href="#rosas">Rosas</a>
        <a href="#orquideas">Orquídeas</a>
        <a href="#buques">Buquês</a>
        <a href="#contato">Contato</a>
    </nav>
    <main>
        <div class="produto" id="rosas">
            <h2>Rosas Vermelhas</h2>
            <img src="rosas.jpg" alt="Rosas Vermelhas">
            <p>Encante com rosas vermelhas apaixonantes.</p>
            <a href="#" class="botao-comprar">Comprar</a>
        </div>
        <div class="produto" id="orquideas">
            <h2>Orquídeas Brancas</h2>
            <img src="orquideas.jpg" alt="Orquídeas Brancas">
            <p>Orquídeas elegantes para presentear.</p>
            <a href="#" class="botao-comprar">Comprar</a>
        </div>
        <div class="produto" id="buques">
            <h2>Buquês Especiais</h2>
            <img src="buque.jpg" alt="Buquê de Flores">
            <p>Perfeito para ocasiões especiais.</p>
            <a href="#" class="botao-comprar">Comprar</a>
        </div>
    </main>
    <div class="redes-sociais">
        <h3>Siga-nos nas redes sociais</h3>
        <p>
            <a href="https://www.instagram.com/fredy_pedroo" target="_blank">Instagram</a> |
            <a href="https://www.facebook.com/Fredy Pedro" target="_blank">Facebook</a> |
            <a href="https://wa.me/929724711" target="_blank">WhatsApp</a> |
            <a href="mailto:mucoco111@gmail.com">E-mail</a>
        </p>
    </div>
    <footer>
        <p>&copy; 2025 - Flores Encanto. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
