<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Stone Grill Restaurant</title>
  <style>
    body {
      font-family: 'Georgia', serif;
      margin: 0;
      background: #fff4ea;
      color: #5a2a27;
    }
    header {
      background: linear-gradient(to right, #f7b733, #fc4a1a);
      padding: 20px;
      text-align: center;
    }
    header img {
      max-height: 60px;
    }
    nav {
      background: #d93404;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 30px;
    }
    .hero {
      text-align: center;
      background: #fff6e6;
      padding: 50px 20px;
    }
    .hero h1 {
      font-size: 48px;
    }
    .featured {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .dish {
      margin: 15px;
      border: 2px solid #e67e22;
      padding: 15px;
      background: #fffaf0;
      border-radius: 10px;
      max-width: 250px;
    }
    .reviews, .updates {
      background: #fff;
      border-top: 4px solid #fc4a1a;
      padding: 20px;
    }
    footer {
      background: #5a2a27;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .btn {
      background: #d93404;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      display: inline-block;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.png" alt="Stone Grill Logo">
    <h1>Stone Grill Restaurant</h1>
    <p><em>Enjoyable and Relaxing</em></p>
  </header>

  <nav>
    <a href="#menu">Menu</a>
    <a href="#updates">Updates</a>
    <a href="#reviews">Reviews</a>
    <a href="tel:0535680539">Call Us</a>
    <a href="https://www.facebook.com/stonecitygrill" target="_blank">Facebook</a>
  </nav>

  <section class="hero">
    <h1>Deliciously Crafted Moments</h1>
    <p>Indulge in our favorites: Calamari, Crispy Pata, Pancit Canton, and more!</p>
    <a class="btn" href="https://m.me/stonecitygrill" target="_blank">Message Us</a>
  </section>

  <section id="menu">
    <h2>Featured Dishes</h2>
    <div class="featured">
      <div class="dish"><strong>Calamari</strong><br>Golden-fried and perfectly seasoned</div>
      <div class="dish"><strong>Crispy Pata</strong><br>Crunchy, juicy pork knuckle delight</div>
      <div class="dish"><strong>Pancit Canton</strong><br>Savory stir-fried noodles</div>
      <div class="dish"><strong>Seafood Platter</strong><br>Fresh ocean flavors on one plate</div>
    </div>
  </section>

  <section id="updates" class="updates">
    <h2>Latest Updates</h2>
    <p>[Post pictures, videos, events and promos here...]</p>
  </section>

  <section id="reviews" class="reviews">
    <h2>Customer Reviews</h2>
    <p>[Add space or script for live reviews, testimonials, or ratings]</p>
  </section>

  <footer>
    <p>Contact us at <a href="mailto:stonegrill2014@gmail.com">stonegrill2014@gmail.com</a> or call 053 568 0539</p>
    <p>&copy; 2025 Stone Grill Restaurant</p>
  </footer>

</body>
</html>