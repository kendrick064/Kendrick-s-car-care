# Kendrick-s-car-care
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kendrick's Car Care</title>
<style>
  body { font-family: Arial, sans-serif; margin:0; padding:0; background:#f0f2f5; color:#333; }
  a { text-decoration:none; color:inherit; }
  header { background:#1a73e8; color:white; padding:30px 20px; text-align:center; }
  header h1 { margin:0; font-size:2rem; }
  header p { margin:5px 0 0; font-size:1rem; }
  nav { display:flex; justify-content:center; gap:20px; background:white; padding:10px 0; box-shadow:0 2px 5px rgba(0,0,0,0.1);}
  nav a { color:#1a73e8; font-weight:bold; }
  section { max-width:900px; margin:20px auto; background:white; padding:20px; border-radius:12px; box-shadow:0 2px 10px rgba(0,0,0,0.05); }
  h2 { color:#1a73e8; text-align:center; margin-bottom:20px; }
  .services { display:grid; grid-template-columns:1fr; gap:15px; }
  .service { padding:15px; border:1px solid #ddd; border-radius:10px; }
  .service h3 { margin-top:0; color:#1a73e8; }
  .gallery { display:grid; grid-template-columns:1fr 1fr; gap:10px; }
  .gallery img { width:100%; border-radius:10px; }
  ul { list-style:none; padding:0; text-align:center; }
  li { padding:8px 0; font-weight:bold; font-size:1.1rem; }
  .btn { display:inline-block; background:#1a73e8; color:white; padding:10px 20px; border:none; border-radius:5px; cursor:pointer; margin-top:10px; }
  footer { text-align:center; padding:15px; background:#333; color:white; margin-top:20px; }
</style>
</head>
<body>

<header>
  <h1>Kendrick's Car Care</h1>
  <p>Affordable, Fast, and Professional Detailing for Your Car</p>
</header>

<nav>
  <a href="#services">Services</a>
  <a href="#pricing">Pricing</a>
  <a href="#gallery">Gallery</a>
  <a href="#contact">Contact</a>
</nav>

<section id="services">
  <h2>Our Services</h2>
  <div class="services">
    <div class="service">
      <h3>Basic Exterior & Interior Wash</h3>
      <p>Wash, vacuum, and clean your car inside and out. Perfect for a weekend refresh.</p>
    </div>
    <div class="service">
      <h3>Full Detailing</h3>
      <p>Includes waxing, tire shine, interior deep cleaning, and window polishing.</p>
    </div>
    <div class="service">
      <h3>Custom Packages</h3>
      <p>We can tailor a package to your car’s needs.</p>
    </div>
  </div>
</section>

<section id="pricing">
  <h2>Pricing</h2>
  <ul>
    <li>Basic Wash & Vacuum: $60</li>
    <li>SUV / Truck: $80</li>
    <li>Full Detailing: $120–$150</li>
  </ul>
</section>

<section id="gallery">
  <h2>Before & After</h2>
  <div class="gallery">
    <img src="https://via.placeholder.com/400x300?text=Before+1" alt="Before 1">
    <img src="https://via.placeholder.com/400x300?text=After+1" alt="After 1">
    <img src="https://via.placeholder.com/400x300?text=Before+2" alt="Before 2">
    <img src="https://via.placeholder.com/400x300?text=After+2" alt="After 2">
  </div>
</section>

<section id="contact">
  <h2>Contact Kendrick</h2>
  <p>Email: <a href="mailto:kendrick@cardetailing.com">kendrick@cardetailing.com</a></p>
  <p>WhatsApp / Call: <a href="https://wa.me/15551234567" target="_blank">+1 (555) 123-4567</a></p>
  <p>Instagram / TikTok: <a href="https://www.instagram.com/kendrickcarcare" target="_blank">@KendrickCarCare</a></p>
  <a href="https://wa.me/15551234567" class="btn">Book Now on WhatsApp</a>
  <br>
  <a href="mailto:kendrick@cardetailing.com" class="btn">Book Now via Email</a>
</section>

<footer>
  <p>© 2026 Kendrick's Car Care. All Rights Reserved.</p>
</footer>

</body>
</html>