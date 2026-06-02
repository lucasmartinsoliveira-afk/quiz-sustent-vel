<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiz Sustentável - Agrinho</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <!-- Tela inicial -->
        <div id="start-screen" class="screen">
            <h1>🌱 Quiz Sustentável</h1>
            <p>Teste seus conhecimentos sobre meio ambiente!</p>
            <button onclick="startQuiz()" class="btn-start">Começar Quiz</button>
        </div>

        <!-- Tela do Quiz -->
        <div id="quiz-screen" class="screen hidden">
            <div class="progress">
                <span id="question-number">1</span>/10
            </div>
            <h2 id="question-text"></h2>
            <div id="options" class="options"></div>
            <button onclick="nextQuestion()" id="next-btn" class="btn-next hidden">Próxima pergunta</button>
        </div>

        <!-- Tela de Resultado -->
        <div id="result-screen" class="screen hidden">
            <h1>🎉 Fim do Quiz!</h1>
            <div class="score">
                <h2>Sua pontuação:</h2>
                <h1 id="score-text">0/10</h1>
            </div>
            <p id="message"></p>
            <button onclick="restartQuiz()" class="btn-restart">Jogar novamente</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
