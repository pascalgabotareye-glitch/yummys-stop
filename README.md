# yummys-stop
Food stop
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Yummys Stop | Cafe & Restaurant</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f7f7f7;
      color: #333;
    }
    header {
      background-color: #ff6347;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }
    section {
      padding: 30px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #ff6347;
      margin-bottom: 15px;
    }
    .menu {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 15px;
    }
    .menu-item {
      background: white;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .highlight {
      background: #fff3cd;
      padding: 15px;
      border-left: 5px solid #ff6347;
      margin-bottom: 20px;
    }
    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>Yummys Stop</h1>
  <p>Cafe & Restaurant</p>
  <p><strong>Open 24 Hours</strong></p>
</header>

<section>
  <div class="highlight">
    <strong>We do deliveries!</strong> Enjoy your favorite meals anytime, anywhere.
  </div>

  <h2>Best Dishes</h2>
  <div class="menu">
    <div class="menu-item">
      <h3>Jollof Rice with Chicken</h3>
      <p>₵35.00</p>
    </div>
    <div class="menu-item">
      <h3>Fried Rice with Beef</h3>
      <p>₵38.00</p>
    </div>
    <div class="menu-item">
      <h3>Banku with Tilapia</h3>
      <p>₵45.00</p>
    </div>
    <div class="menu-item">
      <h3>Waakye Special</h3>
      <p>₵40.00</p>
    </div>
    <div class="menu-item">
      <h3>Assorted Noodles</h3>
      <p>₵30.00</p>
    </div>
    <div class="menu-item">
      <h3>Chicken Burger & Fries</h3>
      <p>₵32.00</p>
    </div>
  </div>
</section>

<section>
  <h2>Contact Us</h2>
  <p><strong>Phone:</strong> 0550001816</p>
  <p><strong>Email:</strong> pasysbite@gmail.com</p>
</section>

<footer>
  <p>&copy; 2025 Yummys Stop</p>
  <p>Created by <strong>Pascal</strong> | Class: <strong>1S11</strong></p>
</footer>

</body>
</html>
