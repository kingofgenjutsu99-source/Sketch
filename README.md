<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sketch Shoes</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      text-align: center;
      padding: 20px;
    }
    h1 {
      color: #333;
    }
    .shoe-card {
      display: inline-block;
      background: white;
      border-radius: 10px;
      padding: 10px;
      margin: 15px;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
    }
    .shoe-card img {
      width: 200px;
      border-radius: 10px;
    }
    .colors {
      margin-top: 10px;
    }
    .color {
      display: inline-block;
      width: 25px;
      height: 25px;
      border-radius: 50%;
      margin: 0 5px;
      border: 2px solid #ccc;
      cursor: pointer;
    }
    .orange { background: orange; }
    .black { background: black; }
    .white { background: white; border: 2px solid #333; }
  </style>
</head>
<body>

  <h1>Shardex Shoes</h1>

  <div class="shoe-card">
    <img src="https://via.placeholder.com/200x150?text=Shoe" alt="Shoe">
    <div class="colors">
      <div class="color orange"></div>
      <div class="color black"></div>
      <div class="color white"></div>
    </div>
  </div>

</body>
</html>
