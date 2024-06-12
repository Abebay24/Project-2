# Project-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Trivia Quiz</title>
</head>
<body>
    <div class="quiz-container">
        <h1>Trivia Quiz</h1>
        <p>Is the Earth round?</p>
        <button onclick="checkAnswer(true)">True</button>
        <button onclick="checkAnswer(false)">False</button>
        <p>Score: <span id="score">0</span></p>
    </div>
    <script src="script.js"></script>
</body>
</html>

/* Basic styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    text-align: center;
}

.quiz-container {
    max-width: 400px;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

button {
    margin: 10px;
    padding: 8px 16px;
    background-color: #3170ff;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}
