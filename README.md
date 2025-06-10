<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Snakista - Taste the Love, Spice the Life</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    *{margin:0;padding:0;box-sizing:border-box}
    body{font-family:'Poppins',sans-serif;background:#fdf6f9;color:#333}
    header{background:#6a1b9a;color:#fff;padding:1.5em 1em;text-align:center}
    nav{background:#4a148c;display:flex;justify-content:center;gap:2em;padding:.8em 0}
    nav a{color:#fff;text-decoration:none;font-weight:600}
    .hero{padding:3em 1em;text-align:center;background:url('https://images.unsplash.com/photo-1606851092094-d68ef3e5d90d') center/cover no-repeat;color:#fff}
    .hero h1{font-size:2.8em;margin-bottom:.3em}
    .section{padding:3em 1em;text-align:center}
    .section h2{margin-bottom:1em}
    .products{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:1.5em}
    .card{background:#fff;border-radius:10px;box-shadow:0 4px 10px rgba(0,0,0,.1);padding:1em;display:flex;flex-direction:column;align-items:center}
    .card img{width:100%;height:160px;object-fit:cover;border-radius:8px}
    .card h3{margin:.8em 0 .3em;font-size:1.1em}
    .btn{margin-top:auto;background:#6a1b9a;color:#fff;padding:.55em 1.2em;border-radius:5px;text-decoration:none;font-weight:600}
    footer{background:#4a148c;color:#fff;padding:1.5em;text-align:center;margin-top:3em}
  </style>
</head>
<body>
  <header>
    <h1>Snakista</h1>
    <p>Taste the Love, Spice the Life</p>
  </header>

  <nav>
    <a href="#bhel">Bhel & Mixes</a>
    <a href="#namkeen">Bhujia & Namkeen</a>
    <a href="#beverages">Beverages</a>
    <a href="#combos">Combos</a>
  </nav>

  <section class="hero">
    <h1>Crunch • Sip • Repeat</h1>
    <p>Your destination for irresistible dry & fresh snacks!</p>
  </section>

  <!-- BHEL & MIXES -->
  <section id="bhel" class="section">
    <h2>Bhel & Mixes</h2>
    <div class="products">
      <div class="card"><img src="https://images.unsplash.com/photo-1601050690590-be1bfa311a12" alt="Shuka Bhel"><h3>Shuka Bhel</h3><p>₹25</p><a class="btn" href="https://wa.me/917208731279?text=I%20want%20Shuka%20Bhel%20(₹25)" target="_blank">Order Now</a></div>
      <div class="card"><img src="https://images.unsplash.com/photo-1612874742287-8526b5b6a39c" alt="Spicy Bhel"><h3>Spicy Bhel</h3><p>₹30</p><a class="btn" href="https://wa.me/917208731279?text=I%20want%20Spicy%20Bhel%20(₹30)" target="_blank">Order Now</a></div>
      <div class="card"><img src="https://images.unsplash.com/photo-1551782450-a2132b4ba21d" alt="Mumbai Bhel"><h3>Mumbai Bhel</h3><p>₹35</p><a class="btn" href="https://wa.me/917208731279?text=I%20want%20Mumbai%20Bhel%20(₹35)" target="_blank">Order Now</a></div>
      <div class="card"><img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c" alt="Corn Chaat"><h3>Corn Chaat</h3><p>₹40</p><a class="btn" href="https://wa.me/917208731279?text=I%20want%20Corn%20Chaat%20(₹40)" target="_blank">Order Now</a></div>
      <div class="card"><img src="https://images.unsplash.com/photo-1563371351-db4f5a4f0878" alt="Soya Chivda"><h3>Soya Chivda</h3><p>₹30</p><a class="btn" href="https://wa.me/917208731279?text=I%20want%20Soya%20Chivda%20(₹30)" target="_blank">Order Now</a></div>
      <div class="card"><img src="https://images.unsplash.com/photo-1525755662778-989d0524087e" alt="Masala Murmura"><h3>Masala Murmura</h3><p>₹25</p><a class="btn" href="https://wa.me/917208731279?text=I%20want%20Masala%20Murmura%20(₹25)" target="_blank">Order Now</a></div>
    </div>
  </section>

  <!-- BHUJIA & NAMKEEN -->
  <section id="namkeen" class="section">
    <h2>Bhujia & Namkeen</h2>
    <div class="products">
      <div class="card"><img src="https://images.unsplash.com/photo-1627308595229-7830a5c91f9f" alt="Aloo Bhujia"><h3>Aloo Bhujia</h3><p>₹30</p><a class="btn" href="https://wa.me/917208731279?text=I%20want%20Aloo%20Bhujia%20(₹30)" target="_blank">Order Now</a></div>
      <div class="card"><img src="https://images.unsplash.com/photo-1611042553365-490bf6f3228d" alt="Moong Dal"><h3>Moong Dal</h3><p>₹40</p><a class="btn" href="https://wa.me/917208731279?text=I%20want%20Moong%20Dal%20(₹40)" target="_blank">Order Now</a></div>
      <div class="card"><img src="https://images.unsplash.com/photo-1586190848861-99aa4a171e90" alt="Sev Mix"><h3>Sev Mix</h3><p>₹35</p><a class="btn" href="https://wa.me/917208731279?text=I%20want%20Sev%20Mix%20(₹35)" target="_blank">Order Now</a></div>
      <div class="card"><img src="https://images.unsplash.com/photo-1604079623834-490b75c0cec2" alt="Punjabi Tadka Mix"><h3>Punjabi Tadka Mix</h3><p>₹45</p><a class="btn" href="https://wa.me/917208731279?text=I%20want%20Punjabi%20Tadka%20Mix%20(₹45)" target="_blank">Order Now</a></div>
      <div class="card"><img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9" alt="Masala Peanuts"><h3>Masala Peanuts</h3><p>₹35</p><a class="btn" href="https://wa.me/917208731279?text=I%20want%20Masala%20Peanuts%20(₹35)" target="_blank">Order Now</a></div>
      <div class="card"><img src="https://images.unsplash.com/photo-1506086679525-eca07ce68773" alt="Khatta Meetha Mix"><h3>Khatta Meetha Mix</h3><p>₹30</p><a class="btn" href="https://wa.me/917208731279?text=I%20want%20Khatta%20Meetha%20Mix%20(₹30)" target="_blank">Order Now</a></div>
    </div>
  </section>

  <!-- BEVERAGES -->
  <section id="beverages" class="section">
    <h2>Beverages</h2>
    <div class="products">
      <div class="card"><img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93" alt="Masala Chai"><h3>Masala Chai</h3><p>₹20</p><a class="btn" href="https://wa.me/917208731279?text=I%20want%20Mas
