
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Guerreiros da Luz</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(180deg, #0f2027, #203a43, #2c5364);
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .app {
      text-align: center;
      background: rgba(0, 0, 0, 0.6);
      padding: 30px;
      border-radius: 20px;
      width: 90%;
      max-width: 400px;
      box-shadow: 0 0 25px rgba(255, 215, 0, 0.4);
    }

    h1 {
      color: gold;
      margin-bottom: 10px;
    }

    p {
      font-size: 18px;
      margin-bottom: 25px;
    }

    button {
      background: gold;
      color: #000;
      border: none;
      padding: 15px 25px;
      font-size: 18px;
      border-radius: 30px;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background: #ffd700;
      transform: scale(1.05);
    }
  </style>
</head>

<body>
  <div class="app">
    <h1>⚔️ Guerreiros da Luz</h1>
    <p>Prepare-se para a missão</p>
    <button onclick="alert('Missão iniciada! Em breve as perguntas 😄')">
      Começar Missão
    </button>
  </div>
</body>
</html>
