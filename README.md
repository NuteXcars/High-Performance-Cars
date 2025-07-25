high-performance-cars/
│
├── index.html
├── style.css
└── script.js

<!DOCTYPE html> https://yourusername.github.io/high-performance-cars/
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>High Performance Cars</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="logo">🚗 High Performance Cars</div>
    <nav>
      <ul>
        <li><a href="#cars">Cars</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h1>Unleash the Power</h1>
    <p>Elite performance. Unmatched speed. Drive your dream.</p>
    <a href="#cars" class="btn">View Inventory</a>
  </section>

  <section id="cars" class="cars">
    <h2>Featured Cars</h2>
    <div class="car-grid">
      <div class="car-card">
        <img src="https://via.placeholder.com/300x200" alt="Car 1">
        <h3>Lamborghini Huracán</h3>
        <p>V10 · 630 HP · 0-60 in 2.9s</p>
        <button onclick="inquire('Lamborghini Huracán')">Inquire Now</button>
      </div>
      <div class="car-card">
        <img src="https://via.placeholder.com/300x200" alt="Car 2">
        <h3>Ferrari SF90 Stradale</h3>
        <p>V8 Hybrid · 986 HP · 0-60 in 2.5s</p>
        <button onclick="inquire('Ferrari SF90 Stradale')">Inquire Now</button>
      </div>
      <div class="car-card">
        <img src="https://via.placeholder.com/300x200" alt="Car 3">
        <h3>McLaren 765LT</h3>
        <p>V8 · 755 HP · Lightweight Performance</p>
        <button onclick="inquire('McLaren 765LT')">Inquire Now</button>
      </div>
    </div>
  </section>

  <section id="about" class="about">
    <h2>About Us</h2>
    <p>At High Performance Cars, we offer only the finest supercars for drivers who demand excellence. With decades of industry experience, we curate a selection that blends adrenaline with elegance.</p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Email Address" required>
      <textarea placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 High Performance Cars. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', sans-serif;
}

body {
  background-color: #111;
  color: #fff;
  line-height: 1.6;
}

header {
  background: #000;
  padding: 20px 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
  transition: color 0.3s ease;
}

nav a:hover {
  color: #f00;
}

.hero {
  background: url('https://via.placeholder.com/1200x400') center/cover no-repeat;
  text-align: center;
  padding: 100px 20px;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}

.btn {
  padding: 12px 24px;
  background: red;
  color: white;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
}

.cars {
  padding: 60px 20px;
  background: #1a1a1a;
}

.car-grid {
  display: grid;
  gap: 30px;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
}

.car-card {
  background: #222;
  padding: 20px;
  border-radius: 10px;
  text-align: center;
}

.car-card img {
  width: 100%;
  border-radius: 8px;
}

.car-card h3 {
  margin: 15px 0 5px;
}

.car-card p {
  margin-bottom: 10px;
}

.car-card button {
  padding: 10px 20px;
  background: red;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.about, .contact {
  padding: 60px 20px;
}

.contact form {
  display: flex;
  flex-direction: column;
  gap: 15px;
  max-width: 500px;
  margin: auto;
}

.contact input, .contact textarea {
  padding: 12px;
  border: none;
  border-radius: 5px;
  background: #2a2a2a;
  color: white;
}

.contact button {
  background: red;
  padding: 12px;
  border: none;
  border-radius: 5px;
  color: white;
  font-weight: bold;
}

footer {
  background: #000;
  text-align: center;
  padding: 20px;
  margin-top: 40px;
}

function inquire(carName) {
  alert(`Thank you for your interest in the ${carName}!\nPlease contact us using the form below or call us directly.`);
}
# High-Performance-Cars
high-performance-cars/
│
├── index.html
├── style.css
└── script.js

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>High Performance Cars</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="logo">🚗 High Performance Cars</div>
    <nav>
      <ul>
        <li><a href="#cars">Cars</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h1>Unleash the Power</h1>
    <p>Elite performance. Unmatched speed. Drive your dream.</p>
    <a href="#cars" class="btn">View Inventory</a>
  </section>

  <section id="cars" class="cars">
    <h2>Featured Cars</h2>
    <div class="car-grid">
      <div class="car-card">
        <img src="https://via.placeholder.com/300x200" alt="Car 1">
        <h3>Lamborghini Huracán</h3>
        <p>V10 · 630 HP · 0-60 in 2.9s</p>
        <button onclick="inquire('Lamborghini Huracán')">Inquire Now</button>
      </div>
      <div class="car-card">
        <img src="https://via.placeholder.com/300x200" alt="Car 2">
        <h3>Ferrari SF90 Stradale</h3>
        <p>V8 Hybrid · 986 HP · 0-60 in 2.5s</p>
        <button onclick="inquire('Ferrari SF90 Stradale')">Inquire Now</button>
      </div>
      <div class="car-card">
        <img src="https://via.placeholder.com/300x200" alt="Car 3">
        <h3>McLaren 765LT</h3>
        <p>V8 · 755 HP · Lightweight Performance</p>
        <button onclick="inquire('McLaren 765LT')">Inquire Now</button>
      </div>
    </div>
  </section>

  <section id="about" class="about">
    <h2>About Us</h2>
    <p>At High Performance Cars, we offer only the finest supercars for drivers who demand excellence. With decades of industry experience, we curate a selection that blends adrenaline with elegance.</p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Email Address" required>
      <textarea placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 High Performance Cars. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', sans-serif;
}

body {
  background-color: #111;
  color: #fff;
  line-height: 1.6;
}

header {
  background: #000;
  padding: 20px 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
  transition: color 0.3s ease;
}

nav a:hover {
  color: #f00;
}

.hero {
  background: url('https://via.placeholder.com/1200x400') center/cover no-repeat;
  text-align: center;
  padding: 100px 20px;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}

.btn {
  padding: 12px 24px;
  background: red;
  color: white;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
}

.cars {
  padding: 60px 20px;
  background: #1a1a1a;
}

.car-grid {
  display: grid;
  gap: 30px;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
}

.car-card {
  background: #222;
  padding: 20px;
  border-radius: 10px;
  text-align: center;
}

.car-card img {
  width: 100%;
  border-radius: 8px;
}

.car-card h3 {
  margin: 15px 0 5px;
}

.car-card p {
  margin-bottom: 10px;
}

.car-card button {
  padding: 10px 20px;
  background: red;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.about, .contact {
  padding: 60px 20px;
}

.contact form {
  display: flex;
  flex-direction: column;
  gap: 15px;
  max-width: 500px;
  margin: auto;
}

.contact input, .contact textarea {
  padding: 12px;
  border: none;
  border-radius: 5px;
  background: #2a2a2a;
  color: white;
}

.contact button {
  background: red;
  padding: 12px;
  border: none;
  border-radius: 5px;
  color: white;
  font-weight: bold;
}

footer {
  background: #000;
  text-align: center;
  padding: 20px;
  margin-top: 40px;
}

function inquire(carName) {
  alert(`Thank you for your interest in the ${carName}!\nPlease contact us using the form below or call us directly.`);
}
