<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Add Bot</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }body {
  height: 100vh;
  background: #000;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
}

.container {
  text-align: center;
}

.add-bot-btn {
  width: 96px; /* approx 1 inch */
  height: 96px; /* approx 1 inch */
  border-radius: 50%;
  background: red;
  display: flex;
  justify-content: center;
  align-items: center;
  text-decoration: none;
  color: #fff;
  font-size: 14px;
  font-weight: bold;
  box-shadow: 0 0 20px rgba(255, 0, 0, 0.7);
  transition: 0.3s ease;
}

.add-bot-btn:hover {
  transform: scale(1.08);
  box-shadow: 0 0 40px rgba(255, 0, 0, 1);
}

.commands {
  margin-top: 30px;
  font-size: 16px;
  line-height: 1.8;
  color: #ccc;
}

.commands span {
  color: #fff;
  font-weight: bold;
}

  </style>
</head>
<body>  <div class="container">
    <a 
      class="add-bot-btn" 
      href="https://discord.com/oauth2/authorize?client_id=1459198126333231105&permissions=8&integration_type=0&scope=bot"
      target="_blank"
    >
      Add Bot
    </a><div class="commands">
  <span>commands:</span><br>
  !banall<br>
  !kickall<br>
  !nuke<br>
  !raid
</div>

  </div></body>
</html>
