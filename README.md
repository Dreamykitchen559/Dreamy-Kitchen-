# Dreamy-Kitchen-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dreamy Kitchen</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <img src="logo.jpeg" alt="Dreamy Kitchen Logo" class="logo" />
    <nav>
      <a href="#about">About</a>
      <a href="#menu">Menu</a>
      <a href="#order">Order</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Dreamy Kitchen</h1>
    <p>Handcrafted sweets & kits with love. Pickup & delivery available!</p>
  </section>

  <section id="about" class="content">
    <h2>About Dreamy Kitchen</h2>
    <p>We specialize in custom-made candy, pastries, and food kits. Everything is crafted in our cozy kitchen using high-quality, locally-sourced ingredients. Whether you're celebrating a special moment or just craving something sweet, we’re here to make your treat dreams come true.</p>
  </section>

  <section id="menu" class="content">
    <h2>Our Treats</h2>
    <ul>
      <li>🍭 Custom Candy Boxes – Starting at $10</li>
      <li>🧁 Signature Pastries – Seasonal & custom options</li>
      <li>🥣 DIY Food Kits – Fun for families and gifting</li>
    </ul>
    <p>We also take special orders for events and holidays!</p>
  </section>

  <section id="order" class="content">
    <h2>Place an Order</h2>
    <p>Ready to order? Use our <a href="https://forms.gle/YOURFORM">online form</a> to request your custom treats and choose a pickup or delivery time.</p>
    <p><strong>Pickup & Delivery:</strong> Available within [Your Area Name]. Minimum 24–48 hours notice required for all orders.</p>
  </section>

  <footer>
    <p>&copy; 2025 Dreamy Kitchen | Follow us on Instagram @dreamykitchenbakes</p>
  </footer>
</body>
</html>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: #fff8f0;
  color: #2e1a12;
}

.logo {
  width: 120px;
  margin: 15px auto;
  display: block;
  border-radius: 50%;
}

header {
  background: #f5d5c4;
  padding: 10px 0;
  text-align: center;
}

nav a {
  margin: 0 12px;
  color: #432818;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  background: #fdecd0;
  padding: 40px 20px;
  text-align: center;
}

.content {
  padding: 30px 20px;
  max-width: 800px;
  margin: auto;
}

ul {
  list-style: none;
  padding: 0;
}

ul li {
  font-size: 18px;
  padding: 8px 0;
}

footer {
  background: #f5d5c4;
  padding: 15px;
  text-align: center;
  font-size: 14px;
}
