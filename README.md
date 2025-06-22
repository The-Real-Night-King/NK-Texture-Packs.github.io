<style>
  body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: #0e1a1f;
    color: #e0f7fa;
  }
  header {
    text-align: center;
    padding: 2rem 1rem;
    background: linear-gradient(to right, #00bcd4, #006064);
  }
  .pack-gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 2rem;
    gap: 2rem;
  }
  .pack {
    background: #10292f;
    border-radius: 12px;
    padding: 1rem;
    width: 220px;
    text-align: center;
    transition: transform 0.2s ease, box-shadow 0.3s ease;
  }
  .pack:hover {
    transform: scale(1.05);
    box-shadow: 0 0 20px #00e5ff;
  }
  .pack img {
    width: 100%;
    border-radius: 8px;
  }
  .pack a {
    display: inline-block;
    margin-top: 1rem;
    padding: 0.5rem 1rem;
    background: #00bcd4;
    color: #012b35;
    font-weight: bold;
    text-decoration: none;
    border-radius: 6px;
  }
  footer {
    text-align: center;
    padding: 1rem;
    font-size: 0.9rem;
    background: #061a20;
  }
</style>
