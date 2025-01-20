<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> I LOVE YOU tooo Animation</title>
    <style>
        body {
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient();
            overflow: hidden;
            font-family: Arial, sans-serif;
        }

        .love-text {
            font-size: 5rem;
            font-weight: bold;
            color: red;
            text-shadow: 4px 2px 10px rgba(0, 0, 0, 0.3);
            position: absolute;
            animation: move 6s linear infinite;
        }

        @keyframes move {
            0% {
                transform: translateX(-100vw);
            }
            50% {
                transform: translateX(0) scale(1.2);
            }
            100% {
                transform: translateX(100vw);
            }
        }
    </style>
</head>
<body>
    <div class="love-text"> I LOVE YOU to</div>
</body>
</html>
