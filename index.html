<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LoFi e Relax</title>
    <style>
        /* Resetando margens e padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Estilos do corpo da página */
        body {
            font-family: 'Arial', sans-serif;
            color: #fff;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start;
            min-height: 100vh;
            margin: 0;
            overflow: hidden;
            position: relative;
            padding-top: 20px;
            background-color: #1e3a5f;
            background-image: url('https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExbjBsOXp3aGFmajRudHJnMTh3dmluNnpkZjhheXJ5cmVoNGRkZHo2ZiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/qGWVA1zoivT7a/giphy.gif');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            transition: background-color 0.5s ease, color 0.5s ease;
        }

        /* Título de boas-vindas */
        h1 {
            font-size: 24px;
            text-align: center;
            margin-bottom: 10px;
            color: #fff;
        }

        /* Mensagem relaxante */
        .message {
            font-size: 18px;
            font-weight: bold;
            text-align: center;
            animation: colorChange 4s infinite;
        }

        @keyframes colorChange {
            0% { color: #ff6347; }
            25% { color: #32cd32; }
            50% { color: #1e90ff; }
            75% { color: #ffff00; }
            100% { color: #ff6347; }
        }

        /* Player de música LoFi */
        .music-player {
            position: fixed;
            top: 10px;
            left: 10px;
            width: 300px;
            height: 169px;
            border-radius: 10px;
            border: none;
            z-index: 2;
            background-color: rgba(0, 0, 0, 0.7); /* Fundo transparente */
        }

        /* Controle de tema */
        .theme-toggle {
            position: absolute;
            top: 10px;
            right: 10px;
            font-size: 30px;
            cursor: pointer;
            color: #fff;
            z-index: 3;
            transition: color 0.3s ease;
        }

        .theme-toggle:hover {
            color: #00bcd4;
        }

        /* Feedback do Usuário no canto inferior */
        .feedback-form {
            position: fixed;
            bottom: 10px;
            left: 10px;
            text-align: center;
            width: 300px;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 10px;
            border-radius: 5px;
        }

        .feedback-form textarea {
            width: 100%;
            max-width: 300px;
            height: 60px;
            margin-top: 10px;
            padding: 10px;
            background-color: #fff;
            color: #333;
            border: none;
            border-radius: 5px;
        }

        .feedback-form button {
            margin-top: 10px;
            padding: 10px;
            background-color: #32cd32;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .feedback-form button:hover {
            background-color: #28a745;
        }

        /* Menu de sentimentos */
        select.mood-select {
            position: fixed;
            top: 200px; /* Ajustado para ficar abaixo do player */
            left: 10px;
            background-color: rgba(0, 0, 0, 0.06); /* Fundo transparente */
            color: #fff;
            border-radius: 5px;
            padding: 10px;
            font-size: 16px;
            border: none;
            cursor: pointer;
            z-index: 9999;
        }

        select.mood-select option {
            background-color: #1e3a5f;
            color: #fff;
        }
    </style>
</head>
<body>

    <!-- Player de música LoFi com autoplay -->
    <iframe id="musicPlayer" class="music-player" src="https://www.youtube.com/embed/jfKfPfyJRdk?autoplay=1&loop=1&playlist=jfKfPfyJRdk" allow="autoplay; encrypted-media" allowfullscreen></iframe>

    <!-- Texto de boas-vindas -->
    <h1>Bem-vindo ao Seu Espaço Tranquilo</h1>

    <!-- Mensagem relaxante -->
    <div class="message">
        Relaxe e seja somente um cara Tranquilo
    </div>

    <!-- Controle de tema -->
    <div class="theme-toggle" onclick="toggleTheme()">🌙</div>

    <!-- Menu para selecionar o sentimento -->
    <select id="moodSelector" class="mood-select" onchange="changeMood()">
        <option value="relaxed">Tranquilo</option>
        <option value="tired">Cansado</option>
        <option value="happy">Feliz</option>
        <option value="focused">Focado</option>
    </select>

    <!-- Feedback do Usuário no canto inferior -->
    <div class="feedback-form">
        <label for="feedback">Seu Feedback:</label><br>
        <textarea id="feedback" name="feedback" placeholder="Deixe seu comentário aqui..."></textarea><br>
        <button onclick="submitFeedback()">Enviar Feedback</button>
    </div>

    <script>
        // Links para os GIFs e vídeos com autoplay configurado
        const backgrounds = {
            "relaxed": {
                gif: "https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExbjBsOXp3aGFmajRudHJnMTh3dmluNnpkZjhheXJ5cmVoNGRkZHo2ZiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/qGWVA1zoivT7a/giphy.gif",
                video: "https://www.youtube.com/embed/jfKfPfyJRdk?autoplay=1" // Link do vídeo para "Tranquilo"
            },
            "tired": {
                gif: "https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExeW1kcXdzb290aXRldTFka3ljeXk3cHFwdngwZWJqeDY5ODNheGtwMSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/1yld7nW3oQ2IyRubUm/giphy.gif",
                video: "https://www.youtube.com/embed/7OKd5cty0vw?autoplay=1" // Link do vídeo para "Cansado"
            },
            "happy": {
                gif: "https://i.giphy.com/media/abc98765/giphy.gif",  // Coloque aqui o link do GIF para Feliz
                video: "https://www.youtube.com/embed/abc98765?autoplay=1" // Link do vídeo para "Feliz"
            },
            "focused": {
                gif: "https://i.giphy.com/media/xyz12345/giphy.gif",  // Coloque aqui o link do GIF para Focado
                video: "https://www.youtube.com/embed/pqr56789?autoplay=1" // Link do vídeo para "Focado"
            }
        };

        // Função para alterar o fundo e o vídeo com base no sentimento selecionado
        function changeMood() {
            const mood = document.getElementById("moodSelector").value;
            const selectedBackground = backgrounds[mood];

            // Alterando o fundo da página
            document.body.style.backgroundImage = `url('${selectedBackground.gif}')`;

            // Alterando o vídeo do player
            const musicPlayer = document.getElementById("musicPlayer");
            musicPlayer.src = selectedBackground.video; // Autoplay configurado
        }

        // Função para alternar entre o tema escuro e claro
        function toggleTheme() {
            const currentTheme = document.body.style.backgroundColor;
            if (currentTheme === 'rgb(30, 58, 95)') {
                document.body.style.backgroundColor = '#f0f0f0';
                document.body.style.color = '#333';
                document.querySelector('h1').style.color = '#333';
                document.querySelector('.message').style.color = '#333';
                document.querySelector('.theme-toggle').textContent = '🌙';
            } else {
                document.body.style.backgroundColor = '#1e3a5f';
                document.body.style.color = '#fff';
                document.querySelector('h1').style.color = '#fff';
                document.querySelector('.message').style.color = '#fff';
                document.querySelector('.theme-toggle').textContent = '☀️';
            }
        }

        // Função para enviar feedback
        function submitFeedback() {
            const feedback = document.getElementById("feedback").value;
            if (feedback) {
                alert("Obrigado pelo seu feedback!");
            } else {
                alert("Por favor, escreva algo antes de enviar.");
            }
        }
    </script>

</body>
</html>
