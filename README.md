<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cartoon Cat</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
        }
        .cat {
            font-size: 2em;
            margin-bottom: 20px;
        }
        .options {
            display: flex;
            gap: 20px;
        }
        .option {
            padding: 10px 20px;
            font-size: 1.2em;
            cursor: pointer;
            border: 2px solid #000;
            border-radius: 10px;
            transition: all 0.3s ease;
        }
        .option.yes {
            background-color: #4CAF50;
            color: white;
        }
        .option.no {
            background-color: #f44336;
            color: white;
        }
        .message {
            margin-top: 20px;
            font-size: 1.5em;
            color: #333;
        }
    </style>
</head>
<body>
    <div class="cat">🐱</div>
    <div class="message">Are we still good friends?</div>
    <div class="options">
        <div class="option yes" onclick="chooseYes()">Yes</div>
        <div class="option no" onclick="chooseNo()">No</div>
    </div>
    <div class="message" id="response"></div>

    <script>
        function chooseYes() {
            document.getElementById('response').innerText = 'I love u';
            document.querySelector('.yes').style.transform = 'scale(1.2)';
            document.querySelector('.no').style.transform = 'scale(1)';
        }

        function chooseNo() {
            document.getElementById('response').innerText = '';
            document.querySelector('.no').style.transform = 'scale(1.5)';
            document.querySelector('.yes').style.transform = 'scale(1)';
        }
    </script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cartoon Cat</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
        }
        .cat {
            font-size: 2em;
            margin-bottom: 20px;
        }
        .options {
            display: flex;
            gap: 20px;
        }
        .option {
            padding: 10px 20px;
            font-size: 1.2em;
            cursor: pointer;
            border: 2px solid #000;
            border-radius: 10px;
            transition: all 0.3s ease;
        }
        .option.yes {
            background-color: #4CAF50;
            color: white;
        }
        .option.no {
            background-color: #f44336;
            color: white;
        }
        .message {
            margin-top: 20px;
            font-size: 1.5em;
            color: #333;
        }
    </style>
</head>
<body>
    <div class="cat">🐱</div>
    <div class="message">Are we still good friends?</div>
    <div class="options">
        <div class="option yes" onclick="chooseYes()">Yes</div>
        <div class="option no" onclick="chooseNo()">No</div>
    </div>
    <div class="message" id="response"></div>

    <script>
        function chooseYes() {
            document.getElementById('response').innerText = 'I love u';
            document.querySelector('.yes').style.transform = 'scale(1.2)';
            document.querySelector('.no').style.transform = 'scale(1)';
        }

        function chooseNo() {
            document.getElementById('response').innerText = '';
            document.querySelector('.no').style.transform = 'scale(1.5)';
            document.querySelector('.yes').style.transform = 'scale(1)';
        }
    </script>
</body>
</html>
