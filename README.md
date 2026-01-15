<html lang="en">
<head>
<meta charset="UTF-8">
<title>𝓼𝓴𝓮𝓽𝓬𝓱 𝓼𝓽𝔂𝓵𝓮</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI', sans-serif;
}

body{
    background:#000;
    color:#fff;
}

header{
    text-align:center;
    padding:30px 0;
    font-size:44px;
    font-weight:800;
    letter-spacing:4px;
}

.container{
    display:flex;
    justify-content:center;
    gap:30px;
    padding:40px;
    flex-wrap:wrap;
}

.card{
    background:#2a2a2a;
    width:260px;
    border-radius:16px;
    padding:18px;
    text-align:center;
    transition:0.3s ease;
}

.card:hover{
    transform:translateY(-10px);
}

.card img{
    width:100%;
    border-radius:12px;
}

.price{
    margin-top:15px;
    font-size:22px;
    font-weight:bold;
}

.stock{
    color:#aaa;
    font-size:14px;
    margin-top:4px;
}
</style>
</head>

<body>

<header>Sketch Styles</header>

<div class="container">

<div class="card">
<img src="https://cdn.discordapp.com/attachments/1452543776173326381/1461422522376524002/17bb4008f8f31fd4462a3809d4e2c6fe.jpg">
<div class="price">$50</div>
<div class="stock">In Stock</div>
</div>

<div class="card">
<img src="https://cdn.discordapp.com/attachments/1452543776173326381/1461422527933845638/aabeb5e202185509200a543e9168c88d.jpg">
<div class="price">$50</div>
<div class="stock">In Stock</div>
</div>

<div class="card">
<img src="https://cdn.discordapp.com/attachments/1452543776173326381/1461422538331652253/5e1a822c3f481252495549d9b3c10cc3.jpg">
<div class="price">$50</div>
<div class="stock">In Stock</div>
</div>

<div class="card">
<img src="https://cdn.discordapp.com/attachments/1452543776173326381/1461422542643527793/2068d08f82960e8b524a3056720156f6.jpg">
<div class="price">$50</div>
<div class="stock">In Stock</div>
</div>

<div class="card">
<img src="https://cdn.discordapp.com/attachments/1452543776173326381/1461422549480243404/fb76262529fa6c161767b77b1ad2814b.jpg">
<div class="price">$50</div>
<div class="stock">In Stock</div>
</div>

</div>

</body>
</html>
