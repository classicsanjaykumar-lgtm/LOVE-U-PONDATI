# LOVE-U-PONDATI
<!DOCTYPE html>
<html>
<head>
<title>Will You Be My Valentine?</title>
<style>
body {
  text-align: center;
  font-family: Arial, sans-serif;
  background-color: #ffe6f0;
}

h1 {
  margin-top: 100px;
}

button {
  padding: 15px 30px;
  font-size: 18px;
  margin: 20px;
  border: none;
  border-radius: 10px;
  cursor: pointer;
}

#yes {
  background-color: #ff4d6d;
  color: white;
}

#no {
  background-color: #ccc;
}
</style>
</head>

<body>

<h1>Hi YOUR_WIFE_NAME ❤️</h1>
<h2>Will you be my Valentine? 💖</h2>

<button id="yes" onclick="yesClick()">Yes 💕</button>
<button id="no" onmouseover="moveButton()">No 😜</button>

<script>
function yesClick() {
  document.body.innerHTML = "<h1>Yayyyyy! I love you forever 💘</h1>";
}

function moveButton() {
  var button = document.getElementById("no");
  button.style.position = "absolute";
  button.style.left = Math.random() * window.innerWidth + "px";
  button.style.top = Math.random() * window.innerHeight + "px";
}
</script>

</body>
</html>


