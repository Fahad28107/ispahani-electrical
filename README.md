<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Ispahani Electrical & Electronics in Jamalpur Sadar. Trusted electronics & electrical shop since 2007. Wiring, repair, LED, cables, CCTV." />
  <meta name="keywords" content="Electrical shop Jamalpur, Electronics repair Jamalpur, LED light shop, wiring service Jamalpur" />
  <meta name="author" content="Ispahani Electrical & Electronics" />
  <title>Ispahani Electrical & Electronics | Jamalpur</title>
  <style>
    body { margin:0; font-family: Arial, Helvetica, sans-serif; background: #f5f7fa; color: #222; }
    header { background: #0b3c5d; color: #fff; padding: 20px; text-align: center; }
    header h1 { margin: 0; }
    nav { background: #062f4f; display: flex; justify-content: center; gap: 20px; padding: 10px 0; }
    nav a, nav button { color: #fff; text-decoration: none; font-weight: bold; cursor: pointer; background:none; border:none; font-size:16px; }
    nav a:hover, nav button:hover { text-decoration: underline; }
    .hero { padding: 60px 20px; text-align: center; background: #e9eef3; }
    .section { padding: 40px 20px; max-width: 1100px; margin: auto; }
    .services { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 20px; }
    .card { background: #fff; padding: 20px; border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); text-align:center; }
    .card h3 { margin-top: 10px; }
    .card img { width: 100%; border-radius:8px; }
    footer { background: #062f4f; color: #fff; text-align: center; padding: 15px; margin-top: 40px; }
    .contact p { margin: 8px 0; }
    .whatsapp-btn { position: fixed; right: 20px; bottom: 20px; background: #25D366; color: #fff; padding: 12px 18px; border-radius: 50px; text-decoration: none; font-weight: bold; box-shadow: 0 4px 8px rgba(0,0,0,0.2); }
    .whatsapp-btn:hover { opacity: 0.9; }
    [contenteditable="true"] { outline: 2px dashed #0b3c5d; outline-offset: 4px; }
  </style>
</head>
<body>
  <header contenteditable="true">
    <h1>Ispahani Electrical & Electronics</h1>
    <p>Trusted Electronics & Electrical Solutions</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
    <button onclick="toggleLang()">বাংলা / English</button>
  </nav>

  <section id="home" class="hero" contenteditable="true">
    <h2 class="en">Reliable Electronics & Electrical Shop</h2>
    <h2 class="bn" style="display:none;">বিশ্বস্ত ইলেকট্রিক্যাল ও ইলেকট্রনিক্স দোকান</h2>
    <p class="en">Quality products • Fair price • Trusted service</p>
    <p class="bn" style="display:none;">মানসম্মত পণ্য • ন্যায্য দাম • বিশ্বস্ত সার্ভিস</p>
    <p><strong>Established:</strong> 28.10.2007</p>
  </section>

  <section id="services" class="section" contenteditable="true">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">
        <h3>Electrical Wiring</h3>
        <p>Home & shop wiring, repair and maintenance.</p>
      </div>
      <div class="card">
        <h3>Electronics Repair</h3>
        <p>TV, amplifier, power supply, fan, and more.</p>
      </div>
      <div class="card">
        <h3>Installation</h3>
        <p>Light, fan, inverter, CCTV installation.</p>
      </div>
      <div class="card">
        <h3>Custom Projects</h3>
        <p>Electronics projects & circuit solutions.</p>
      </div>
    </div>
  </section>

  <section id="products" class="section">
    <h2 class="en">Our Products</h2>
    <h2 class="bn" style="display:none;">আমাদের পণ্যসমূহ</h2>
    <div class="services">
      <div class="card"><img src="https://via.placeholder.com/200" alt="LED"><h3>LED Light</h3></div>
      <div class="card"><img src="https://via.placeholder.com/200" alt="Wire"><h3>Wire & Cable</h3></div>
      <div class="card"><img src="https://via.placeholder.com/200" alt="Fan"><h3>Fan</h3></div>
      <div class="card"><img src="https://via.placeholder.com/200" alt="Speaker"><h3>Speaker</h3></div>
    </div>
  </section>

  <section id="contact" class="section contact" contenteditable="true">
    <h2>Contact Us / যোগাযোগ</h2>
    <p><strong>Address:</strong> Jamalpur Sadar, Jamalpur</p>
    <p><strong>Phone:</strong> 01977510581, 01713510581</p>
    <p><strong>WhatsApp:</strong> 01977510581</p>
    <p><strong>Opening Time:</strong> 9:00 AM – 9:00 PM</p>
    <p><strong>Google Map:</strong></p>
    <iframe src="https://www.google.com/maps?q=Jamalpur%20Sadar%20Jamalpur&output=embed" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
  </section>

  <footer>
    <p>© 2026 Ispahani Electrical & Electronics. All rights reserved.</p>
    <p>Serving Jamalpur since 2007 | Electronics • Electrical • Repair</p>
  </footer>

  <a class="whatsapp-btn" href="https://wa.me/8801977510581" target="_blank">WhatsApp</a>

  <script>
    function toggleLang(){
      document.querySelectorAll('.en').forEach(e=>e.style.display = e.style.display==='none'?'':'none');
      document.querySelectorAll('.bn').forEach(e=>e.style.display = e.style.display==='none'?'':'none');
    }
    let unlocked = true;
    function lockEdit(){
      const pass = prompt('Enter password');
      if(pass==='1234'){
        unlocked = !unlocked;
        document.querySelectorAll('[contenteditable]').forEach(e=>e.contentEditable = unlocked);
        alert(unlocked?'Edit unlocked':'Edit locked');
      } else alert('Wrong password');
    }
  </script>
  <button onclick="lockEdit()" style="position:fixed;left:20px;bottom:20px;">Lock/Unlock Edit</button>
</body>
</html>
