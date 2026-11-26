<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hotplate Vurghata Restaurant | Good Food • Good Mood</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: Arial, sans-serif;
  background: #111;
  color: white;
}

header {
  background: #171717;
  padding: 20px 8%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: sticky;
  top: 0;
  z-index: 10;
}

.logo {
  color: #e7b85b;
  font-size: 23px;
  font-weight: bold;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 18px;
}

nav a:hover {
  color: #e7b85b;
}

.hero {
  min-height: 520px;
  display: flex;
  align-items: center;
  padding: 60px 8%;
  background: linear-gradient(#0008,#0009),
  url('images/8645.jpg') center/cover;
}

.hero h1 {
  font-size: 48px;
  max-width: 650px;
  margin-bottom: 20px;
}

.hero span {
  color: #e7b85b;
}

.hero p {
  font-size: 18px;
  line-height: 1.7;
}

section {
  padding: 65px 8%;
}

.heading {
  text-align: center;
  color: #e7b85b;
  font-size: 32px;
  margin-bottom: 35px;
}

.menu {
  display: grid;
  grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
  gap: 25px;
}

.food {
  background: #202020;
  border-radius: 12px;
  overflow: hidden;
}

.food img {
  width: 100%;
  height: 190px;
  object-fit: cover;
}

.food div {
  padding: 18px;
}

.food h3 {
  margin-bottom: 8px;
}

.item-desc {
  color: #ccc;
  font-size: 14px;
  margin-bottom: 10px;
}

.price {
  color: #e7b85b;
  font-weight: bold;
  font-size: 19px;
}

.more-menu-note {
  text-align: center;
  margin-top: 30px;
  color: #ddd;
  line-height: 1.7;
  font-size: 15px;
}

.about {
  background: #1c1c1c;
  text-align: center;
  line-height: 1.8;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit,minmax(200px,1fr));
  gap: 15px;
}

.gallery img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  border-radius: 10px;
}

.contact {
  text-align: center;
  line-height: 2;
}

footer {
  background: #080808;
  text-align: center;
  padding: 25px;
  color: #aaa;
}

@media(max-width:600px) {
  header {
    flex-direction: column;
    gap: 15px;
  }

  nav a {
    margin: 0 6px;
    font-size: 13px;
  }

  .hero h1 {
    font-size: 34px;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">Hotplate Vurghata</div>
  <nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#about">About</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<div class="hero" id="home">
  <div>
    <h1>Welcome to <span>Hotplate Vurghata Restaurant</span></h1>
    <p>BBQ Fine Dining &amp; Chinese Restaurant — Good Food • Good Mood.<br>
    Get the best taste in an unbeatable price at Kalkini Vurghata.</p>
  </div>
</div>

<section id="menu">
  <h2 class="heading">Featured Menu</h2>

  <div class="menu">

    <div class="food">
      <img src="images/8643.jpg" alt="Special Handi Biryani">
      <div>
        <h3>Special Handi Biryani</h3>
        <p class="item-desc">Handi Chicken Biryani: ৳250 | Beef: ৳320</p>
        <p class="price">৳250</p>
      </div>
    </div>

    <div class="food">
      <img src="images/8644.jpg" alt="Chicken Mushroom & Chinese">
      <div>
        <h3>Chicken &amp; Mushroom Stir</h3>
        <p class="item-desc">Fresh Chinese &amp; sizzling specialties</p>
        <p class="price">৳280</p>
      </div>
    </div>

    <div class="food">
      <img src="images/8641.jpg" alt="Hotplate Special Platter">
      <div>
        <h3>Hotplate Special Platter</h3>
        <p class="item-desc">Combo Plater: ৳350 | Chef Special: ৳349</p>
        <p class="price">৳349</p>
      </div>
    </div>

    <div class="food">
      <img src="images/8640.jpg" alt="Traditional Rice Platter">
      <div>
        <h3>Traditional Platter &amp; Rice</h3>
        <p class="item-desc">Kacchi, Biryani, Fried Rice &amp; Set Menus</p>
        <p class="price">৳300</p>
      </div>
    </div>

    <div class="food">
      <img src="images/8639.jpg" alt="Handi Biryani Bowls">
      <div>
        <h3>Handi Biryani Bowls</h3>
        <p class="item-desc">Aromatic Handi Biryani &amp; Kacchi</p>
        <p class="price">৳250</p>
      </div>
    </div>

    <div class="food">
      <img src="images/8636.jpg" alt="Hotplate Special Pizza">
      <div>
        <h3>Hotplate Special Pizza</h3>
        <p class="item-desc">Freshly baked pizza • Home delivery available</p>
        <p class="price">৳350</p>
      </div>
    </div>

    <div class="food">
      <img src="images/8642.jpg" alt="Hot Soup Bowl">
      <div>
        <h3>Thai &amp; Chicken Corn Soup</h3>
        <p class="item-desc">Thai Soup (1:2): ৳300 | Corn Soup (1:1): ৳150</p>
        <p class="price">৳150</p>
      </div>
    </div>

  </div>

  <p class="more-menu-note">
    <strong>Full Menu Available:</strong> Starters (৳120–৳250), Burgers (৳130–৳320), Steaks &amp; Wings (৳280–৳320), Pasta (৳300–৳350), Sandwiches (৳200–৳250), Fried Chicken (৳100–৳380), Chowmein (৳180–৳880), Salads (৳230–৳400), Meatbox (৳150–৳220), Shawarma (৳150–৳200), Momo (৳160–৳250), Hot Drinks (৳80–৳150), Lacchi &amp; Floats (৳100–৳150), Faluda (৳250–৳280), Shakes (৳150–৳200), Kacchi (৳300–৳350), Grill &amp; Chaap (৳130–৳500), Naan (৳40–৳70), Rice &amp; Set Platters (৳249–৳450).
  </p>
</section>

<section class="about" id="about">
  <h2 class="heading">About Us</h2>
  <p>
    Welcome to <strong>Hotplate Vurghata Restaurant</strong> — a BBQ fine dining and Chinese restaurant in Kalkini Vurghata, Madaripur.<br>
    We serve quality food with care and love so you can enjoy great taste at an unbeatable price.<br>
    Services available: <strong>Outdoor Seating</strong> &amp; <strong>Dine-in</strong>.
  </p>
</section>

<section id="gallery">
  <h2 class="heading">Our Gallery</h2>

  <div class="gallery">
    <img src="images/8645.jpg" alt="Outdoor Seating Evening View">
    <img src="images/8647.jpg" alt="Restaurant Seating Area">
    <img src="images/8646.jpg" alt="Warm String Lights Ambience">
    <img src="images/8643.jpg" alt="Special Handi Biryani">
    <img src="images/8641.jpg" alt="Platter & Drinks">
    <img src="images/8636.jpg" alt="Best Pizza in Town">
  </div>
</section>

<section class="contact" id="contact">
  <h2 class="heading">Contact Us</h2>
  <p>Restaurant: Hotplate Vurghata Restaurant</p>
  <p>Phone: 01974-602180</p>
  <p>WhatsApp: +880 1714-602177</p>
  <p>Address: Kalkini Vurghata, Madaripur, 7902, Dhaka Division, Bangladesh</p>
  <p>Dining Options: Outdoor seating • Dine-in</p>
</section>

<footer>
  <p>© 2026 Hotplate Vurghata Restaurant. All Rights Reserved.</p>
</footer>

</body>
</html>
