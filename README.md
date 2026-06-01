# Arcade-game
Game website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AI Chatbot</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>

<div class="app">

  <header>
    <h1>AI Chatbot</h1>
    <button id="themeBtn">🌙</button>
  </header>

  <div id="chatBox" class="chat-box"></div>

  <div class="input-area">
    <input id="userInput" type="text" placeholder="Type a message..." />
    <button onclick="sendMessage()">Send</button>
  </div>

</div>

<script src="script.js"></script>
</body>
</html>
