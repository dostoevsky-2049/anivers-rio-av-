<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Memórias do Vovô</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      text-align: center;
      padding: 20px;
    }
    h1 {
      color: #333;
    }
    .galeria {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }
    .foto {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      overflow: hidden;
      max-width: 300px;
    }
    .foto img {
      width: 100%;
      height: auto;
      display: block;
    }
    .foto p {
      padding: 10px;
      color: #555;
    }
  </style>
</head>
<body>
  <h1>Memórias do Vovô</h1>
  <p>Uma homenagem cheia de carinho e recordações.</p>

  <div class="galeria">
    <div class="foto">
      <img src="https://i.imgur.com/EXEMPLO1.jpg" alt="Foto 1 do Vovô">
      <p>Momentos de alegria</p>
    </div>
    <div class="foto">
      <img src="https://i.imgur.com/EXEMPLO2.jpg" alt="Foto 2 do Vovô">
      <p>Família reunida</p>
    </div>
    <div class="foto">
      <img src="https://i.imgur.com/EXEMPLO3.jpg" alt="Foto 3 do Vovô">
      <p>Recordações inesquecíveis</p>
    </div>
  </div>
</body>
</html>
