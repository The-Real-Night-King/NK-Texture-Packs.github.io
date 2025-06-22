<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bloxd.io Texture Packs</title>
    <style>
        :root {
            --dark-cyan: #008b8b;
            --dark-cyan-light: #00a0a0;
            --dark-cyan-dark: #006666;
            --dark-cyan-darker: #004d4d;
            --text-light: #e0f2f2;
            --text-dark: #333;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            width: 100%;
            background-color: #111;
            color: var(--text-light);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        header {
            background-color: var(--dark-cyan-darker);
            padding: 2rem 0;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
        }

        .logo {
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
            text-transform: uppercase;
            letter-spacing: 3px;
            color: var(--text-light);
            text-shadow: 0 0 10px rgba(0, 255, 255, 0.5);
        }

        .subtitle {
            font-size: 1.2rem;
            opacity: 0.8;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
            flex: 1;
        }

        .intro {
            text-align: center;
            margin-bottom: 3rem;
            padding: 1.5rem;
            background-color: rgba(0, 139, 139, 0.1);
            border-radius: 8px;
            border-left: 4px solid var(--dark-cyan);
        }

        .intro h2 {
            margin-bottom: 1rem;
            color: var(--dark-cyan-light);
        }

        .intro p {
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .texture-card {
            background-color: #222;
            border-radius: 8px;
            overflow: hidden;
            transition: all 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            position: relative;
        }

        .texture-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 139, 139, 0.3);
        }

        .texture-card:hover .texture-image {
            filter: brightness(1.1);
        }

        .texture-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
            transition: filter 0.3s ease;
            background: linear-gradient(45deg, var(--dark-cyan-darker), var(--dark-cyan-dark));
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.2rem;
        }

        .texture-info {
            padding: 1.5rem;
        }

        .texture-title {
            font-size: 1.3rem;
            margin-bottom: 0.5rem;
            color: var(--text-light);
        }

        .texture-description {
            color: #aaa;
            margin-bottom: 1rem;
            line-height: 1.5;
        }

        .texture-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-bottom: 1.5rem;
        }

        .tag {
            background-color: var(--dark-cyan-dark);
            color: var(--text-light);
            padding: 0.3rem 0.6rem;
            border-radius: 4px;
            font-size: 0.8rem;
        }

        .download-btn {
            display: inline-block;
            background-color: var(--dark-cyan);
            color: white;
            padding: 0.6rem 1.2rem;
            border-radius: 4px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            width: 100%;
            text-align: center;
        }

        .download-btn:hover {
            background-color: var(--dark-cyan-light);
            transform: translateY(-2px);
        }

        footer {
            background-color: var(--dark-cyan-darker);
            padding: 1.5rem 0;
            text-align: center;
            margin-top: 3rem;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin-bottom: 1rem;
        }

        .social-link {
            color: var(--text-light);
            font-size: 1.5rem;
            transition: color 0.3s ease;
        }

        .social-link:hover {
            color: var(--dark-cyan-light);
        }

        .copyright {
            opacity: 0.7;
            font-size: 0.9rem;
        }

        /* Responsive adjustments */
        @media (max-width: 768px) {
            .gallery {
                grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            }
            
            .logo {
                font-size: 2rem;
            }
        }

        /* Animation for texture cards */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .texture-card {
            animation: fadeIn 0.5s ease forwards;
            opacity: 0;
        }

        .texture-card:nth-child(1) { animation-delay: 0.1s; }
        .texture-card:nth-child(2) { animation-delay: 0.2s; }
        .texture-card:nth-child(3) { animation-delay: 0.3s; }
        .texture-card:nth-child(4) { animation-delay: 0.4s; }
        .texture-card:nth-child(5) { animation-delay: 0.5s; }
        .texture-card:nth-child(6) { animation-delay: 0.6s; }
    </style>
</head>
<body>
    <header>
        <div class="logo">Bloxd.io Textures</div>
        <div class="subtitle">Premium Texture Packs for Enhanced Gameplay</div>
    </header>

    <div class="container">
        <div class="intro">
            <h2>Welcome to My Texture Collection</h2>
            <p>Discover high-quality texture packs designed to transform your Bloxd.io experience. Each pack is carefully crafted to enhance visuals while maintaining performance. Click on any pack to learn more and download.</p>
        </div>

        <div class="gallery">
            <!-- Texture Pack 1 -->
            <div class="texture-card">
                <div class="texture-image">Preview Image</div>
                <div class="texture-info">
                    <h3 class="texture-title">Cyber Neon</h3>
                    <p class="texture-description">A futuristic neon-themed pack with glowing elements and vibrant colors that make your world pop.</p>
                    <div class="texture-tags">
                        <span class="tag">Modern</span>
                        <span class="tag">Glow</span>
                        <span class="tag">Vibrant</span>
                    </div>
                    <a href="#" class="download-btn">Download</a>
                </div>
            </div>

            <!-- Texture Pack 2 -->
            <div class="texture-card">
                <div class="texture-image">Preview Image</div>
                <div class="texture-info">
                    <h3 class="texture-title">Ancient Ruins</h3>
                    <p class="texture-description">Weathered stone textures with intricate carvings perfect for adventure maps and historical builds.</p>
                    <div class="texture-tags">
                        <span class="tag">RPG</span>
                        <span class="tag">Detailed</span>
                        <span class="tag">Historical</span>
                    </div>
                    <a href="#" class="download-btn">Download</a>
                </div>
            </div>

            <!-- Texture Pack 3 -->
            <div class="texture-card">
                <div class="texture-image">Preview Image</div>
                <div class="texture-info">
                    <h3 class="texture-title">Pixel Perfect</h3>
                    <p class="texture-description">Clean, crisp pixel art textures with perfect alignment for those who love the classic look.</p>
                    <div class="texture-tags">
                        <span class="tag">Retro</span>
                        <span class="tag">Clean</span>
                        <span class="tag">Pixel Art</span>
                    </div>
                    <a href="#" class="download-btn">Download</a>
                </div>
            </div>

            <!-- Texture Pack 4 -->
            <div class="texture-card">
                <div class="texture-image">Preview Image</div>
                <div class="texture-info">
                    <h3 class="texture-title">Nature's Palette</h3>
                    <p class="texture-description">Organic textures with realistic wood grains, leaf patterns, and natural stone variations.</p>
                    <div class="texture-tags">
                        <span class="tag">Realistic</span>
                        <span class="tag">Nature</span>
                        <span class="tag">Organic</span>
                    </div>
                    <a href="#" class="download-btn">Download</a>
                </div>
            </div>

            <!-- Texture Pack 5 -->
            <div class="texture-card">
                <div class="texture-image">Preview Image</div>
                <div class="texture-info">
                    <h3 class="texture-title">Dark Fantasy</h3>
                    <p class="texture-description">Mystical textures with dark tones and magical elements perfect for horror or fantasy builds.</p>
                    <div class="texture-tags">
                        <span class="tag">Fantasy</span>
                        <span class="tag">Dark</span>
                        <span class="tag">Magical</span>
                    </div>
                    <a href="#" class="download-btn">Download</a>
                </div>
            </div>

            <!-- Texture Pack 6 -->
            <div class="texture-card">
                <div class="texture-image">Preview Image</div>
                <div class="texture-info">
                    <h3 class="texture-title">Industrial</h3>
                    <p class="texture-description">Metal and concrete textures with realistic wear and tear for modern industrial builds.</p>
                    <div class="texture-tags">
                        <span class="tag">Modern</span>
                        <span class="tag">Industrial</span>
                        <span class="tag">Urban</span>
                    </div>
                    <a href="#" class="download-btn">Download</a>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <div class="social-links">
            <a href="#" class="social-link">GitHub</a>
            <a href="#" class="social-link">Twitter</a>
            <a href="#" class="social-link">Discord</a>
        </div>
        <div class="copyright">© 2023 Bloxd.io Texture Packs. All rights reserved.</div>
    </footer>

    <script>
        // Add interactivity
        document.addEventListener('DOMContentLoaded', function() {
            // Add click event to texture cards
            const cards = document.querySelectorAll('.texture-card');
            cards.forEach(card => {
                card.addEventListener('click', function() {
                    // In a real implementation, this would open a modal or navigate to a detail page
                    console.log('Selected texture pack:', this.querySelector('.texture-title').textContent);
                });
            });

            // Animate elements when they come into view
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('animate');
                    }
                });
            }, { threshold: 0.1 });

            document.querySelectorAll('.texture-card, .intro').forEach(el => {
                observer.observe(el);
            });
        });
    </script>
</body>
</html>
