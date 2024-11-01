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
