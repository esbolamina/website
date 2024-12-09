# website
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Button Redirect</title>
    <style>
        body {
            background-color: pink;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
        }
        .redirect-button {
            padding: 15px 30px;
            font-size: 18px;
            color: white;
            background-color: #ff69b4;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .redirect-button:hover {
            background-color: #ff1493;
        }
    </style>
</head>
<body>
    <button class="redirect-button" onclick="window.location.href='https://esbolamina.wixsite.com/my-site-6'">
        Сайтқа қош келдіңіз
    </button>
</body>
