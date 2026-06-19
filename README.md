# Raju-ff
Developers
levelup-board/
├── index.html
├── style.css
└── script.js
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Level UP Board</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>🔥 LEVEL UP BOARD 🔥</h1>
    <p>अपना लेवल बढ़ाएँ और अपनी प्रगति देखें</p>

    <div class="card">
      <h2>Level: <span id="level">1</span></h2>
      <button onclick="levelUp()">Level Up</button>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
body {
  background: #111;
  color: white;
  text-align: center;
  font-family: Arial, sans-serif;
}

.container {
  margin-top: 100px;
}

.card {
  background: #222;
  padding: 20px;
  border-radius: 15px;
  display: inline-block;
}

button {
  padding: 10px 20px;
  font-size: 18px;
  cursor: pointer;}
  let level = 1;

function levelUp() {
  level++;
  document.getElementById("level").textContent = level;
} develop jaldio
