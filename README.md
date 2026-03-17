<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <title>NetherForge Server</title>
  <style>
    body {
      margin: 0;
      font-family: Arial;
      background: linear-gradient(black, darkred);
      color: white;
      text-align: center;
    }
    header {
      padding: 50px;
      background: #1a0000;
    }
    h1 {
      font-size: 50px;
      color: orange;
    }
    .box {
      margin: 30px;
      padding: 20px;
      background: #330000;
      border-radius: 10px;
    }
    .ip {
      font-size: 25px;
      color: lime;
    }
    button {
      padding: 15px;
      font-size: 18px;
      background: orange;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
  </style>
</head>
<body>

<header>
  <h1>🔥 NetherForge 🔥</h1>
  <p>Nejlepší Minecraft server z Netheru</p>
</header>

<div class="box">
  <h2>🌍 O serveru</h2>
  <p>Survival | Economy | PvP | Events</p>
</div>

<div class="box">
  <h2>📡 IP adresa</h2>
  <p class="ip">play.netherforge.cz</p>
  <button onclick="copyIP()">Kopírovat IP</button>
</div>

<div class="box">
  <h2>⚔️ Připoj se hned!</h2>
  <p>Zapni Minecraft a přijď 🔥</p>
</div>

<script>
function copyIP() {
  navigator.clipboard.writeText("play.netherforge.cz");
  alert("IP zkopírována!");
}
</script>

</body>
</html>
