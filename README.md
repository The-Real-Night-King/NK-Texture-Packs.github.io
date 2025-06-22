<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>NK Texture Packs</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #1e1e2f;
      color: #f0f0f0;
    }
    header {
      text-align: center;
      padding: 2rem 1rem;
      background: linear-gradient(to right, #6c2eb9, #452f9e);
    }
    .pack-gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 2rem;
      gap: 2rem;
    }
    .pack {
      background: #2c2c3e;
      border-radius: 12px;
      padding: 1rem;
      width: 220px;
      text-align: center;
      transition: transform 0.2s ease;
    }
    .pack:hover {
      transform: scale(1.05);
    }
    .pack img {
      width: 100%;
      border-radius: 8px;
    }
    .pack a {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.5rem 1rem;
      background: #884dff;
      color: white;
      text-decoration: none;
      border-radius: 6px;
    }
    footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      background: #151521;
    }
  </style>
</head>
<body>
  <header>
    <h1>NK Texture Packs</h1>
    <p>Handcrafted texture packs for Bloxd.io</p>
  </header>
  
  <main>
    <section class="pack-gallery">
      <div class="pack">
        <img src="packs/pack1/thumbnail.png" alt="Pack 1">
        <h3>Frostfire Pack</h3>
        <a href="packs/pack1.zip" download>Download</a>
      </div>
      <div class="pack">
        <img src="packs/pack2/thumbnail.png" alt="Pack 2">
        <h3>Nightstorm Pack</h3>
        <a href="packs/pack2.zip" download>Download</a>
      </div>
      <!-- Add more packs as needed -->
    </section>
  </main>

  <footer>
    <p>Created by The Real Night King – © 2025</p>
  </footer>
</body>
</html>
