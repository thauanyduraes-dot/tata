<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Blog Tech</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1a3a6c; /* Tom de azul do fundo */
            color: white;
            margin: 0;
            padding: 20px;
            text-align: center;
        }

        header {
            margin-bottom: 40px;
        }

        .container {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .card {
            background-color: #2c5282; /* Azul um pouco mais claro para os cards */
            padding: 20px;
            border-radius: 8px;
            width: 300px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.2);
        }

        .card img {
            width: 50px;
            height: 50px;
            margin-bottom: 15px;
        }

        .card h2 {
            font-size: 1.2rem;
            margin-bottom: 10px;
        }

        .card p {
            font-size: 0.9rem;
            line-height: 1.5;
            color: #cbd5e0;
        }

        .author {
            font-weight: bold;
            display: block;
            margin-bottom: 10px;
            font-size: 0.8rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Meu Blog Tech</h1>
        <p>Novidades sobre o mundo da tecnologia e programação</p>
    </header>

    <main class="container">
        <!-- Post 1 -->
        <article class="card">
            <div class="icon">💻</div>
            <h2>Meu primeiro post</h2>
            <span class="author">Por: Alisson Chagas</span>
            <p>Este é o começo da minha jornada no desenvolvimento web. Compartilharei meus aprendizados aqui.</p>
        </article>

        <!-- Post 2 -->
        <article class="card">
            <div class="icon">🍃</div>
            <h2>A popularidade do Node.js é real?</h2>
            <span class="author">Por: Rodrigo Teixeira</span>
            <p>Explorando os motivos que tornaram o Node.js uma das tecnologias mais usadas no backend.</p>
        </article>

        <!-- Post 3 -->
        <article class="card">
            <div class="icon">📦</div>
            <h2>O primeiro passo com CI/CD</h2>
            <span class="author">Por: Guilherme Souza</span>
            <p>Entenda como automatizar seus deploys e melhorar a qualidade do seu fluxo de entrega.</p>
        </article>
    </main>

</body>
