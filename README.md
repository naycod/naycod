<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aplikasi Penghitung Klik</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="script.js" defer></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }
        #count {
            margin-top: 20px;
            font-size: 24px;
        }
    </style>
</head>
<body>
    <h1>Aplikasi Penghitung Klik</h1>
    <button id="clickButton">Klik Saya!</button>
    <div id="count">Jumlah Klik: 0</div>
</body>
</html>
