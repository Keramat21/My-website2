<!DOCTYPE html>
<html lang="ps">
<head>
<meta charset="UTF-8">
<title>Simple Calculator</title>

<style>
body{
    font-family: Arial;
    background: linear-gradient(135deg,#4facfe,#00f2fe);
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.calculator{
    background:white;
    padding:20px;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,0.2);
    width:260px;
}

#display{
    width:100%;
    height:50px;
    font-size:22px;
    text-align:right;
    margin-bottom:10px;
    padding:5px;
}

.buttons{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:10px;
}

button{
    padding:15px;
    font-size:18px;
    border:none;
    border-radius:10px;
    cursor:pointer;
    background:#f0f0f0;
    transition:0.2s;
}

button:hover{
    background:#ddd;
}

.operator{
    background:#ff9f43;
    color:white;
}

.equal{
    background:#2ecc71;
    color:white;
}

.clear{
    background:#e74c3c;
    color:white;
}
</style>

</head>
<body>

<div class="calculator">
<input type="text" id="display" disabled>

<div class="buttons">
<button onclick="append('7')">7</button>
<button onclick="append('8')">8</button>
<button onclick="append('9')">9</button>
<button class="operator" onclick="append('/')">÷</button>

<button onclick="append('4')">4</button>
<button onclick="append('5')">5</button>
<button onclick="append('6')">6</button>
<button class="operator" onclick="append('*')">×</button>

<button onclick="append('1')">1</button>
<button onclick="append('2')">2</button>
<button onclick="append('3')">3</button>
<button class="operator" onclick="append('-')">−</button>

<button onclick="append('0')">0</button>
<button onclick="append('.')">.</button>
<button class="equal" onclick="calculate()">=</button>
<button class="operator" onclick="append('+')">+</button>

<button class="clear" onclick="clearDisplay()" style="grid-column: span 4;">C</button>
</div>
</div>

<script>
function append(value){
    document.getElementById("display").value += value;
}

function calculate(){
    let display = document.getElementById("display");
    try{
        display.value = eval(display.value);
    }catch{
        display.value = "Error";
    }
}

function clearDisplay(){
    document.getElementById("display").value = "";
}
</script>

</body>
</html><!DOCTYPE html>
<html lang="ps">
<head>
<meta charset="UTF-8">
<title>Simple Calculator</title>

<style>
body{
    font-family: Arial;
    background: linear-gradient(135deg,#4facfe,#00f2fe);
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.calculator{
    background:white;
    padding:20px;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,0.2);
    width:260px;
}

#display{
    width:100%;
    height:50px;
    font-size:22px;
    text-align:right;
    margin-bottom:10px;
    padding:5px;
}

.buttons{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:10px;
}

button{
    padding:15px;
    font-size:18px;
    border:none;
    border-radius:10px;
    cursor:pointer;
    background:#f0f0f0;
    transition:0.2s;
}

button:hover{
    background:#ddd;
}

.operator{
    background:#ff9f43;
    color:white;
}

.equal{
    background:#2ecc71;
    color:white;
}

.clear{
    background:#e74c3c;
    color:white;
}
</style>

</head>
<body>

<div class="calculator">
<input type="text" id="display" disabled>

<div class="buttons">
<button onclick="append('7')">7</button>
<button onclick="append('8')">8</button>
<button onclick="append('9')">9</button>
<button class="operator" onclick="append('/')">÷</button>

<button onclick="append('4')">4</button>
<button onclick="append('5')">5</button>
<button onclick="append('6')">6</button>
<button class="operator" onclick="append('*')">×</button>

<button onclick="append('1')">1</button>
<button onclick="append('2')">2</button>
<button onclick="append('3')">3</button>
<button class="operator" onclick="append('-')">−</button>

<button onclick="append('0')">0</button>
<button onclick="append('.')">.</button>
<button class="equal" onclick="calculate()">=</button>
<button class="operator" onclick="append('+')">+</button>

<button class="clear" onclick="clearDisplay()" style="grid-column: span 4;">C</button>
</div>
</div>

<script>
function append(value){
    document.getElementById("display").value += value;
}

function calculate(){
    let display = document.getElementById("display");
    try{
        display.value = eval(display.value);
    }catch{
        display.value = "Error";
    }
}

function clearDisplay(){
    document.getElementById("display").value = "";
}
</script>

</body>
</html><!DOCTYPE html>
<html lang="ps">
<head>
<meta charset="UTF-8">
<title>Simple Calculator</title>

<style>
body{
    font-family: Arial;
    background: linear-gradient(135deg,#4facfe,#00f2fe);
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.calculator{
    background:white;
    padding:20px;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,0.2);
    width:260px;
}

#display{
    width:100%;
    height:50px;
    font-size:22px;
    text-align:right;
    margin-bottom:10px;
    padding:5px;
}

.buttons{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:10px;
}

button{
    padding:15px;
    font-size:18px;
    border:none;
    border-radius:10px;
    cursor:pointer;
    background:#f0f0f0;
    transition:0.2s;
}

button:hover{
    background:#ddd;
}

.operator{
    background:#ff9f43;
    color:white;
}

.equal{
    background:#2ecc71;
    color:white;
}

.clear{
    background:#e74c3c;
    color:white;
}
</style>

</head>
<body>

<div class="calculator">
<input type="text" id="display" disabled>

<div class="buttons">
<button onclick="append('7')">7</button>
<button onclick="append('8')">8</button>
<button onclick="append('9')">9</button>
<button class="operator" onclick="append('/')">÷</button>

<button onclick="append('4')">4</button>
<button onclick="append('5')">5</button>
<button onclick="append('6')">6</button>
<button class="operator" onclick="append('*')">×</button>

<button onclick="append('1')">1</button>
<button onclick="append('2')">2</button>
<button onclick="append('3')">3</button>
<button class="operator" onclick="append('-')">−</button>

<button onclick="append('0')">0</button>
<button onclick="append('.')">.</button>
<button class="equal" onclick="calculate()">=</button>
<button class="operator" onclick="append('+')">+</button>

<button class="clear" onclick="clearDisplay()" style="grid-column: span 4;">C</button>
</div>
</div>

<script>
function append(value){
    document.getElementById("display").value += value;
}

function calculate(){
    let display = document.getElementById("display");
    try{
        display.value = eval(display.value);
    }catch{
        display.value = "Error";
    }
}

function clearDisplay(){
    document.getElementById("display").value = "";
}
</script>

</body>
</html>
