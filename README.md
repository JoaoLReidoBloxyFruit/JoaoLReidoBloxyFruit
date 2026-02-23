<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Meu Perfil Dev</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .card {
            background: #ffffff;
            width: 350px;
            padding: 30px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 15px 35px rgba(0,0,0,0.3);
            transition: 0.4s;
        }

        .card:hover {
            transform: translateY(-10px);
        }

        .foto {
            width: 140px;
            height: 140px;
            border-radius: 50%;
            border: 4px solid #2c5364;
            margin-bottom: 15px;
        }

        h1 {
            font-size: 22px;
            margin-bottom: 5px;
        }

        h3 {
            color: #555;
            margin-bottom: 15px;
            font-weight: normal;
        }

        p {
            font-size: 14px;
            margin-bottom: 20px;
            color: #333;
        }

        .skills {
            margin-bottom: 20px;
        }

        .skills h2 {
            font-size: 16px;
            margin-bottom: 10px;
        }

        .skill {
            display: inline-block;
            background: #2c5364;
            color: white;
            padding: 6px 10px;
            border-radius: 8px;
            margin: 4px;
            font-size: 12px;
        }

        .botoes {
            display: flex;
            justify-content: space-between;
        }

        .btn {
            text-decoration: none;
            background: #0f2027;
            color: white;
            padding: 8px 15px;
            border-radius: 10px;
            transition: 0.3s;
            font-size: 14px;
        }

        .btn:hover {
            background: #2c5364;
        }

        @media (max-width: 400px) {
            .card {
                width: 90%;
            }
        }
    </style>
</head>

<body>

    <div class="card">
        <img src="https://via.placeholder.com/140" alt="Foto de Perfil" class="foto">

        <h1>Seu Nome 👨‍💻</h1>
        <h3>Desenvolvedor em Formação</h3>

        <p>
            🎓 Estudante da ETEC - Centro Paula Souza <br>
            💻 2º ano de Desenvolvimento de Sistemas <br>
            🚀 Focado em Front-End e Back-End
        </p>

        <div class="skills">
            <h2>🚀 Tecnologias</h2>
            <span class="skill">HTML5</span>
            <span class="skill">CSS3</span>
            <span class="skill">JavaScript</span>
            <span class="skill">Python</span>
            <span class="skill">MySQL</span>
        </div>

        <div class="botoes">
            <a href="#" class="btn">GitHub</a>
            <a href="#" class="btn">LinkedIn</a>
        </div>
    </div>

</body>
</html>
