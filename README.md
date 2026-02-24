<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>index.html</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: Arial, sans-serif; line-height: 1.6; }
    header {
      background: #111;
      color: #fff;
      padding: 15px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 { font-size: 24px; }
    nav a {
      color: #fff;
      margin-left: 20px;
      text-decoration: none;
      font-size: 16px;
    }
    nav a:hover { color: #f4c10f; }
    .hero {
      background: url('https://images.unsplash.com/photo-1521334884684-d80222895322') no-repeat center/cover;
      height: 80vh;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
    }
    .hero h2 {
      font-size: 40px;
      background: rgba(0,0,0,0.6);
      padding: 15px;
      border-radius: 10px;
    }
    .container { padding: 40px 20px; max-width: 1100px; margin: auto; }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      border: 1px solid #ddd;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: 0.3s;
    }
    .card:hover { transform: scale(1.05); }
    .card img { width: 100%; height: 300px; object-fit: cover; }
    .card-body { padding: 15px; text-align: center; }
    .card-body h3 { margin-bottom: 10px; }
    .card-body p { color: #555; }
    footer {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
    }
    .contact p { margin: 8px 0; }
    .whatsapp-btn {
      display: inline-block;
      margin-top: 15px;
      background: #25D366;
      color: white;
      padding: 12px 20px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }
    .whatsapp-btn:hover { background: #1ebe5d; }
  </style>
</head>
<body>  <header>
    <h1>Sanju Fashion Point</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#products">Products</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>  <section class="hero">
    <h2>Latest Fashion for Everyone</h2>
  </section>  <section class="container" id="products">
    <h2 style="text-align:center; margin-bottom:20px;">Our Collection</h2>
    <div class="products">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1520975916090-3105956dac38" alt="Men Shirt">
        <div class="card-body">
          <h3>Men's Shirt</h3>
          <p>Stylish and comfortable.</p>
        </div>
      </div><div class="card">
    <img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f" alt="Women Dress">
    <div class="card-body">
      <h3>Women's Dress</h3>
      <p>Elegant modern design.</p>
    </div>
  </div>

  <div class="card">
    <img src="https://images.unsplash.com/photo-1523381210434-271e8be1f52b" alt="Kids Wear">
    <div class="card-body">
      <h3>Kids Wear</h3>
      <p>Comfortable & colorful.</p>
    </div>
  </div>
</div>

  </section>  <section class="container contact" id="contact">
    <h2 style="text-align:center; margin-bottom:20px;">Contact Us</h2>
    <p><strong>Shop Name:</strong> Sanju Fashion Point</p>
    <p><strong>Phone:</strong> +91 9012352304</p>
    <p><strong>Address:</strong> Kanalichhina, Pithoragarh</p>
    <a class="whatsapp-btn" href="https://wa.me/919012352304" target="_blank">Order on WhatsApp</a>
  </section>  <footer>
    <p>© 2026 Sanju Fashion Point | All Rights Reserved</p>
  </footer></body>
</html>
