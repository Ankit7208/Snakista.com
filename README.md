<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Purple Café</title>
  <style>
    /* ---------- GLOBAL ---------- */
    :root {
      --fluoro-purple: #da00ff;
      --fluoro-purple-light: #f75aff;
      --bg-light: #f8edff;
      --text-main: #3c096c;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: "Segoe UI", sans-serif;
      background: linear-gradient(to bottom right, #f3e5f5, #e0bbff);
      color: var(--text-main);
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 1rem;
    }

    /* ---------- HEADER & NAV ---------- */
    header {
      background: var(--fluoro-purple);
      color: #fff;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header h1 { font-size: 1.8rem; margin: 0; }
    nav { display: flex; gap: 1.5rem; }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: 600;
      padding: 0.3rem 0.6rem;
      border-radius: 4px;
    }
    nav a:hover { background: var(--fluoro-purple-light); }

    /* ---------- SECTIONS ---------- */
    h2, h3 { text-align: center; margin: 0 0 1rem; }
    section.section-container { margin: 3rem 0; }

    /* ---------- MENU GRID ---------- */
    .menu-section {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 1.5rem;
    }
    .item {
      background: var(--bg-light);
      border-radius: 10px;
      padding: 1rem;
      text-align: center;
      box-shadow: 0 2px 6px rgba(0,0,0,0.08);
    }
    .item img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
    }
    .item h4 { margin: 0.6rem 0; font-size: 1rem; }
    .item button {
      background: var(--fluoro-purple);
      color: #fff;
      border: none;
      padding: 0.5rem;
      width: 100%;
      border-radius: 5px;
      cursor: pointer;
    }
    .item button:hover { background: var(--fluoro-purple-light); }

    /* ---------- ABOUT & CONTACT ---------- */
    .info-box {
      background: #fff;
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.08);
      max-width: 900px;
      margin: 0 auto;
      text-align: center;
      line-height: 1.6;
    }

    /* ---------- FOOTER ---------- */
    footer {
      background: #c700f2;
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 4rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Purple Café</h1>
    <nav>
      <a href="#coffee">Coffee</a>
      <a href="#tea">Tea</a>
      <a href="#desserts">Desserts</a>
      <a href="#snacks">Snacks</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main class="container">
    <h2>Our Menu</h2>

    <!-- 1. COFFEE (8 items) -->
    <section id="coffee" class="section-container">
      <h3>Coffee</h3>
      <div class="menu-section">
        <div class="item"><img src="https://source.unsplash.com/300x200/?cappuccino" alt="Cappuccino"><h4>Cappuccino</h4><a href="https://wa.me/917208731279?text=I%20want%20Cappuccino"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?latte" alt="Latte"><h4>Latte</h4><a href="https://wa.me/917208731279?text=I%20want%20Latte"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?espresso" alt="Espresso"><h4>Espresso</h4><a href="https://wa.me/917208731279?text=I%20want%20Espresso"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?mocha" alt="Mocha"><h4>Mocha</h4><a href="https://wa.me/917208731279?text=I%20want%20Mocha"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?iced-coffee" alt="Iced Coffee"><h4>Iced Coffee</h4><a href="https://wa.me/917208731279?text=I%20want%20Iced%20Coffee"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?cold-brew" alt="Cold Brew"><h4>Cold Brew</h4><a href="https://wa.me/917208731279?text=I%20want%20Cold%20Brew"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?americano" alt="Americano"><h4>Americano</h4><a href="https://wa.me/917208731279?text=I%20want%20Americano"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?macchiato" alt="Macchiato"><h4>Macchiato</h4><a href="https://wa.me/917208731279?text=I%20want%20Macchiato"><button>Order</button></a></div>
      </div>
    </section>

    <!-- 2. TEA (7 items) -->
    <section id="tea" class="section-container">
      <h3>Tea</h3>
      <div class="menu-section">
        <div class="item"><img src="https://source.unsplash.com/300x200/?chai" alt="Masala Chai"><h4>Masala Chai</h4><a href="https://wa.me/917208731279?text=I%20want%20Masala%20Chai"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?green-tea" alt="Green Tea"><h4>Green Tea</h4><a href="https://wa.me/917208731279?text=I%20want%20Green%20Tea"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?black-tea" alt="Black Tea"><h4>Black Tea</h4><a href="https://wa.me/917208731279?text=I%20want%20Black%20Tea"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?lemon-tea" alt="Lemon Tea"><h4>Lemon Tea</h4><a href="https://wa.me/917208731279?text=I%20want%20Lemon%20Tea"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?herbal-tea" alt="Herbal Tea"><h4>Herbal Tea</h4><a href="https://wa.me/917208731279?text=I%20want%20Herbal%20Tea"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?oolong" alt="Oolong Tea"><h4>Oolong Tea</h4><a href="https://wa.me/917208731279?text=I%20want%20Oolong%20Tea"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?iced-tea" alt="Iced Tea"><h4>Iced Tea</h4><a href="https://wa.me/917208731279?text=I%20want%20Iced%20Tea"><button>Order</button></a></div>
      </div>
    </section>

    <!-- 3. DESSERTS (7 items) -->
    <section id="desserts" class="section-container">
      <h3>Desserts</h3>
      <div class="menu-section">
        <div class="item"><img src="https://source.unsplash.com/300x200/?cake" alt="Chocolate Cake"><h4>Chocolate Cake</h4><a href="https://wa.me/917208731279?text=I%20want%20Chocolate%20Cake"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?cheesecake" alt="Cheesecake"><h4>Cheesecake</h4><a href="https://wa.me/917208731279?text=I%20want%20Cheesecake"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?donut" alt="Donut"><h4>Donut</h4><a href="https://wa.me/917208731279?text=I%20want%20Donut"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?muffin" alt="Muffin"><h4>Muffin</h4><a href="https://wa.me/917208731279?text=I%20want%20Muffin"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?ice-cream" alt="Ice Cream"><h4>Ice Cream</h4><a href="https://wa.me/917208731279?text=I%20want%20Ice%20Cream"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?tart" alt="Fruit Tart"><h4>Fruit Tart</h4><a href="https://wa.me/917208731279?text=I%20want%20Fruit%20Tart"><button>Order</button></a></div>
        <div class="item"><img src="https://source.unsplash.com/300x200/?brownie" alt="Brownie"><h4>Brownie</h4><a href="https://wa.me/917208731279?text=I%20want%20Brownie"><button>Order</button></a></div>
      </div>
    </section>

    <!-- 4. SNACKS (8 items) -->
    <section id="snacks" class="section-container">
      <h3>Snacks</
