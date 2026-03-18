<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sofi Builders</title>

<style>
body { margin:0; font-family:Arial; scroll-behavior:smooth; }

header {
  background:#111;
  color:white;
  padding:15px 30px;
  display:flex;
  justify-content:space-between;
  align-items:center;
}

.logo {
  color:gold;
  font-size:22px;
  font-weight:bold;
}

nav a {
  color:white;
  margin:0 10px;
  text-decoration:none;
}

.hero {
  background:url('https://images.unsplash.com/photo-1503387762-592deb58ef4e') no-repeat center/cover;
  height:90vh;
  display:flex;
  justify-content:center;
  align-items:center;
  text-align:center;
  color:white;
}

.section { padding:50px; text-align:center; }

.services, .gallery {
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
}

.card {
  width:250px;
  margin:15px;
  padding:20px;
  box-shadow:0 0 10px gray;
  border-radius:10px;
}

.gallery img {
  width:300px;
  margin:10px;
  border-radius:10px;
}

input, textarea {
  width:80%;
  padding:10px;
  margin:10px;
}

button {
  padding:10px 20px;
  background:gold;
  border:none;
  cursor:pointer;
}

footer {
  background:#111;
  color:white;
  padding:20px;
}

.whatsapp {
  position:fixed;
  bottom:20px;
  right:20px;
  background:#25D366;
  color:white;
  padding:15px;
  border-radius:50%;
  text-decoration:none;
}
</style>
</head>

<body>

<header>
  <div class="logo">🏗️ Sofi Builders</div>
  <nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="home" class="hero">
  <div>
    <h2>We Build Your Dream</h2>
    <button onclick="document.getElementById('contact').scrollIntoView()">Contact Us</button>
  </div>
</section>

<section id="services" class="section">
  <h2>Our Services</h2>
  <div class="services">
    <div class="card">Home Construction</div>
    <div class="card">Interior Design</div>
    <div class="card">Renovation</div>
  </div>
</section>

<section id="projects" class="section">
  <h2>Our Projects</h2>
  <div class="gallery">
    <img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e">
    <img src="https://images.unsplash.com/photo-1507089947367-19c1da9775ae">
    <img src="https://images.unsplash.com/photo-1494526585095-c41746248156">
  </div>
</section>

<section id="contact" class="section">
  <h2>Contact Us</h2>

  <!-- Contact Form -->
  <form>
    <input type="text" placeholder="Your Name" required><br>
    <input type="email" placeholder="Your Email" required><br>
    <textarea placeholder="Your Message" required></textarea><br>
    <button type="submit">Send</button>
  </form>

  <!-- Google Map -->
  <iframe 
    src="https://maps.google.com/maps?q=Hyderabad&t=&z=13&ie=UTF8&iwloc=&output=embed"
    width="100%" height="300" style="border:0;">
  </iframe>

</section>

<footer>
  <p>© 2026 Sofi Builders</p>
</footer>

<!-- WhatsApp -->
<a class="whatsapp" href="https://wa.me/917780263982" target="_blank">💬</a>

</body>
</html>
