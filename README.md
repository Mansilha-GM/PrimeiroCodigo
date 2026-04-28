Meu Primeiro Site
Hello World!
Este projeto é uma página simples em HTML com estilização em CSS, criada como meu primeiro código para repositório no GitHub.

Prévia do Projeto
Página centralizada com:

Fundo em degradê
Caixa com sombra e bordas arredondadas
Texto centralizado
Botão interativo com efeito hover
Código do Projeto
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Primeiro Site</title>

    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #4e73df, #1cc88a);
            font-family: Arial, Helvetica, sans-serif;
            color: white;
            text-align: center;
        }

        .container {
            background-color: rgba(0, 0, 0, 0.3);
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
        }

        h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        p {
            font-size: 1.2em;
        }

        button {
            margin-top: 20px;
            padding: 10px 20px;
            border: none;
            border-radius: 8px;
            background-color: white;
            color: #4e73df;
            font-weight: bold;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background-color: #f8f9fc;
            transform: scale(1.05);
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Hello World!</h1>
        <p>Este será o meu primeiro código para repositório no GitHub.</p>
        <button onclick="alert('Bem-vindo ao meu primeiro site!')">
            Clique aqui
        </button>
    </div>

</body>
</html>
Objetivo
Praticar:

Estrutura básica do HTML
Estilização com CSS
Publicação de projeto no GitHub
Tecnologias Utilizadas
HTML5
CSS3
Feito por Guilherme
