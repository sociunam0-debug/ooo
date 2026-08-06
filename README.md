<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Gửi đến em</title>

<style>
body {
    background: pink;
    text-align: center;
    font-family: Arial;
}

.container {
    margin-top: 100px;
}

button {
    padding: 10px 20px;
    font-size: 18px;
    margin: 10px;
    cursor: pointer;
}

#no {
    position: absolute;
}
</style>

</head>

<body>

<div class="container">
    <h1>Em có thích anh không? 💖</h1>
    <button onclick="yes()">Có</button>
    <button id="no" onmouseover="run()">Không</button>
</div>

<script>
function yes() {
    document.body.innerHTML = "<h1>Anh biết mà 😎❤️</h1>";
}

function run() {
    let btn = document.getElementById("no");
    btn.style.top = Math.random() * window.innerHeight + "px";
    btn.style.left = Math.random() * window.innerWidth + "px";
}
</script>

</body>
</html>
