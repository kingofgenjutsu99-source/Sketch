<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Shoe Collection</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    header {
      background: #333;
      color: white;
      padding: 20px 0;
    }
    header h1 {
      margin: 0;
      font-size: 28px;
    }
    .shoe-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
      gap: 20px;
    }
    .shoe-card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      width: 220px;
      padding: 10px;
    }
    .shoe-card img {
      width: 100%;
      border-radius: 10px;
    }
    .shoe-card p {
      margin: 10px 0 0 0;
      font-weight: bold;
      color: #333;
    }
  </style>
</head>
<body>

  <header>
    <h1>Shardex Shoes</h1>
  </header>

  <div class="shoe-container">
    <div class="shoe-card">
      <img src="https://via.placeholder.com/200x150?text=Shoe+1" alt="Shoe 1">
      <p>Shoe 1</p>
    </div>
    <div class="shoe-card">
      <img src="https://via.placeholder.com/200x150?text=Shoe+2" alt="Shoe 2">
      <p>Shoe 2</p>
    </div>
    <div class="shoe-card">
      <img src="https://via.placeholder.com/200x150?text=Shoe+3" alt="Shoe 3">
      <p>Shoe 3</p>
    </div>
  </div>

</body>
</html>
