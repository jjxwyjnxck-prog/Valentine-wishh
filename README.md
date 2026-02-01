# Valentine-wishh
<!DOCTYPE html>
<html>
<head>
<title>For You ❤️</title>
<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: linear-gradient(135deg, #ff9a9e, #fad0c4);
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
}
.box {
  background: rgba(255,255,255,0.2);
  padding: 30px;
  border-radius: 20px;
}
button {
  padding: 12px 20px;
  border: none;
  border-radius: 25px;
  background: #ff4b5c;
  color: white;
  font-size: 16px;
}
</style>
</head>

<body>
<div class="box" id="box">
  <h1>Hey ❤️</h1>
  <p>You make my days better just by being you.</p>
  <h2>Will you be my Valentine? 💌</h2>
  <button onclick="yes()">YES 💖</button>
</div>

<script>
function yes() {
  document.getElementById("box").innerHTML =
    "<h1>YAY! 💕</h1><p>I knew it 😌<br>Happy Valentine’s Day ❤️</p>";
}
</script>
</body>
</html>
