<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>猜數字遊戲</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin-top: 50px; }
        input { padding: 10px; width: 50px; }
        button { padding: 10px; }
        .message { margin-top: 20px; }
    </style>
</head>
<body>
    <h1>猜數字遊戲</h1>
    <p>請猜一個介於 1 到 100 之間的數字：</p>
    <input type="number" id="guess" min="1" max="100" />
    <button onclick="checkGuess()">猜測</button>
    <div class="message" id="message"></div>

    <script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Energy Glow</title>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #1a1a2e;
  }

  .energy-button {
    position: relative;
    padding: 15px 30px;
    font-size: 20px;
    color: #fff;
    background-color: #6a0dad;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    overflow: hidden;
    outline: none;
    box-shadow: 0 0 10px rgba(138, 43, 226, 0.8), 0 0 20px rgba(138, 43, 226, 0.6), 0 0 30px rgba(138, 43, 226, 0.4);
    animation: glow 2s infinite alternate;
  }

  @keyframes glow {
    0% {
      box-shadow: 0 0 10px rgba(138, 43, 226, 0.8), 0 0 20px rgba(138, 43, 226, 0.6), 0 0 30px rgba(138, 43, 226, 0.4);
    }
    100% {
      box-shadow: 0 0 20px rgba(138, 43, 226, 1), 0 0 30px rgba(138, 43, 226, 0.9), 0 0 40px rgba(138, 43, 226, 0.8);
    }
  }
</style>
</head>
<body>

<button class="energy-button">Magic Pulse</button>

</body>
</html>
