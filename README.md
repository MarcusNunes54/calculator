<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <link rel="stylesheet" href="./css/style.css">
</head>
<body>
    <div>
    <input  class="display">
    <button class="gray-button"onclick="limparTela()">AC</button>
    <button class="gray-button" onclick="inverter()">+/-</button>
    <button class="blue-button"  onclick="addCaracter('/')">/</button>
    <button class="blue-button"  onclick="addCaracter('*')">*</button>
    <button class="black-button" onclick="addCaracter('7')">7</button>
    <button class="black-button" onclick="addCaracter('8')">8</button>
    <button class="black-button" onclick="addCaracter('9')">9</button>
    <button class="blue-button" onclick="addCaracter('-')">-</button>
    <button class="black-button" onclick="addCaracter('4')">4</button>
    <button class="black-button" onclick="addCaracter('5')">5</button>
    <button class="black-button"onclick="addCaracter('6')">6</button>
    <button class="blue-button" onclick="addCaracter('+')">+</button>
    <button class="black-button" onclick="addCaracter('1')">1</button>
    <button class="black-button" onclick="addCaracter('2')">2</button>
    <button class="black-button" onclick="addCaracter('3')">3</button>
    <button class="blue-button equal" onclick="calcular()">=</button>
    <button class="black-button zero" onclick="addCaracter('0')">0</button>
    <button class="black-button" onclick="addCaracter('.')">.</button>
</div>
    <script src="./js/script.js"></script>
</body>
</html>
