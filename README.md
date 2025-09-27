<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SHASTHA GUPPY FARM</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
    }
    header {
      background: teal;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .container {
      width: 90%;
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }
    .fish-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 10px;
    }
    .price {
      color: green;
      font-weight: bold;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>SHASTHA GUPPY FARM</h1>
    <p>Premium Guppies for Sale</p>
  </header>

  <div class="container">
    <h2>Our Guppies</h2>
    <div class="fish-list">

      <!-- Example Card -->
      <div class="card">
        <img src="images/jet-black.jpg" alt="Jet Black Guppy">
        <h3>Jet Black Pair</h3>
        <p class="price">₹220</p>
      </div>

      <div class="card">
        <img src="images/white-texido.jpg" alt="White Texido Guppy">
        <h3>White Texido Pair</h3>
        <p class="price">₹220</p>
      </div>

      <div class="card">
        <img src="images/chilli-moscow.jpg" alt="Chilli Moscow Guppy">
        <h3>Chilli Moscow Big Ear Pair</h3>
        <p class="price">₹250</p>
      </div>

      <!-- Keep adding cards for all fish from your list -->

    </div>
  </div>
</body>
</html>
