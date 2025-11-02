<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Future Road Company</title>
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
<style>
/* Reset */
* { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Arial', sans-serif; }

/* Body */
body { background-color: #f5f7fa; color: #333; line-height: 1.6; }

/* Header */
header { background: linear-gradient(to right, #1f4e79, #3b6a99); color: #fff; padding: 50px 20px; text-align: center; }
header h1 { font-size: 3rem; margin-bottom: 10px; }
header p { font-size: 1.2rem; }

/* Navigation */
nav { display: flex; justify-content: center; background-color: #3b6a99; flex-wrap: wrap; }
nav a { color: #fff; text-decoration: none; padding: 15px 25px; transition: 0.3s; }
nav a:hover { background-color: #294c6b; }

/* Sections */
section { padding: 60px 20px; max-width: 1100px; margin: auto; }
section h2 { color: #1f4e79; margin-bottom: 40px; text-align: center; font-size: 2.2rem; }

/* About */
#about p { text-align: center; font-size: 1.1rem; max-width: 800px; margin: auto; }

/* Services */
.services { display: flex; flex-wrap: wrap; gap: 30px; justify-content: center; }
.service-card { background: #fff; border-radius: 12px; padding: 25px; flex: 1 1 250px; box-shadow: 0 6px 15px rgba(0,0,0,0.1); text-align: center; transition: transform 0.3s; }
.service-card:hover { transform: translateY(-7px); }
.service-card i { font-size: 3rem; color: #1f4e79; margin-bottom: 15px; }
.service-card h3 { margin-bottom: 15px; color: #1f4e79; }
.service-card p { font-size: 1rem; }

/* Contact */
#contact p { text-align: center; margin-bottom: 10px; font-size: 1.1rem; }
.contact-btn { display: inline-block; background: #1f4e79; color: #fff; padding: 12px 25px; border-radius: 8px; text-decoration: none; margin-top: 15px; transition: 0.3s; }
.contact-btn:hover { background: #294c6b; }

/* Footer */
footer { background-color: #1f4e79; color: #fff; text-align: center; padding: 20px 0; margin-top: 50px; }

/* Responsive */
@media(max-width: 768px){ .services { flex-direction: column; align-items: center; } nav { flex-direction: column; } }
</style>
</head>
<body>

<header>
<h1>The Future Road Company</h1>
<p>Experts in Building Repair & Maintenance</p>
</header>

<nav>
<a href="#about">About Us</a>
<a href="#services">Services</a>
<a href="#contact">Contact</a>
</nav>

<section id="about">
<h2>About Us</h2>
<p>At The Future Road Company, we specialize in building repair and maintenance, ensuring that your structures are safe, durable, and visually appealing. Our skilled team uses the latest techniques to deliver high-quality results every time.</p>
</section>

<section id="services">
<h2>Our Services</h2>
<div class="services">
<div class="service-card">
<i class="fas fa-tools"></i>
<h3>Structural Repair</h3>
<p>We fix structural issues in buildings, ensuring safety and stability for all occupants.</p>
</div>
<div class="service-card">
<i class="fas fa-paint-roller"></i>
<h3>Facade Restoration</h3>
<p>Restore the exterior of your building to look new and visually appealing.</p>
</div>
<div class="service-card">
<i class="fas fa-home"></i>
<h3>Interior Renovation</h3>
<p>Upgrade interiors for comfort, style, and modern functionality.</p>
</div>
</div>
</section>

<section id="contact">
<h2>Contact Us</h2>
<p>Email: info@thefutureroad.com</p>
<p>Phone: +123 456 7890</p>
<p>Address: 123 Future Road, Your City</p>
<a href="mailto:info@thefutureroad.com" class="contact-btn"><i class="fas fa-envelope"></i> Send Email</a>
</section>

<footer>
&copy; 2025 The Future Road Company. All rights reserved.
</footer>

</body>
</html>
