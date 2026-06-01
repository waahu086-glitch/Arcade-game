# Arcade-game
Game website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AI Chatbot Pro</title>
  <link rel="stylesheet" href="style.css"/>
</head>

<body>

<div class="container">

  <header>
    <h2>🤖 AI Chatbot Pro</h2>
    <button id="themeToggle">🌙</button>
  </header>

  <div id="chat" class="chat"></div>

  <div class="input-box">
    <input id="input" type="text" placeholder="Ask something..." />
    <button onclick="sendMessage()">Send</button>
  </div>

</div>

<script src="script.js"></script>
</body>
</html>
