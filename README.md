<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bloxd.io Texture Packs</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;

            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        

        body {
            background-color: #f0f8ff;
            color: #155e75;

        }
        .container-lg {
        max-width: 100%;
        margin-right: auto;
        margin-left: auto;
        }
        /* Header */
        header {
            background: linear-gradient(135deg, #06b6d4, #0e7490);
            color: white;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            font-weight: bold;
            font-size: 1.2rem;
        }

        .header-icons a {
            color: white;
            font-size: 1.3rem;
            transition: color 0.2s;
        }

        .header-icons a:hover {
            color: #cffafe;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #06b6d4, #0e7490);
            color: white;
            padding: 7rem 1rem 4rem;
            text-align: center;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .hero p {
            max-width: 600px;
            margin: 0 auto;
            font-size: 1.1rem;
        }

        /* Texture Packs Grid */
        .texture-packs {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 1rem;
        }

        .section-title {
            text-align: center;
            margin-bottom: 2rem;
            font-size: 2rem;
        }

        .grid-2x2 {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2rem;
        }

        /* Texture Card */
        .texture-card {
            background: white;
            border-radius: 0.5rem;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            transition: all 0.3s ease;
        }

        .texture-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(6, 182, 212, 0.3);
        }

        .card-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .card-content {
            padding: 1.5rem;
        }

        .card-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 0.8rem;
        }

        .pack-name {
            font-weight: bold;
            font-size: 1.2rem;
        }

        .pack-author {
            color: #0891b2;
            font-size: 0.9rem;
        }

        .pack-rating {
            display: flex;
            align-items: center;
            color: #fcd34d;
        }

        .pack-rating span {
            color: #164e63;
            margin-left: 0.3rem;
        }

        .pack-description {
            margin: 1rem 0;
            color: #475569;
            font-size: 0.95rem;
        }

        .card-footer {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .file-info {
            color: #64748b;
            font-size: 0.85rem;
        }

        .download-btn {
            background: #0891b2;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 0.3rem;
            font-weight: 500;
            cursor: pointer;
            transition: background 0.2s;
        }

        .download-btn:hover {
            background: #0e7490;
        }

        /* Footer */
        footer {
            background: #164e63;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 3rem;
        }

        .footer-content {
            max-width: 600px;
            margin: 0 auto;
        }

        .social-icon {
            color: white;
            font-size: 1.3rem;
            margin: 0 0.5rem;
        }

        .copyright {
            margin-top: 1rem;
            font-size: 0.9rem;
            color: #a5f3fc;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .grid-2x2 {
                grid-template-columns: 1fr;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .hero {
                padding: 6rem 1rem 3rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">
            <i class="fas fa-cubes"></i>
            <span>Bloxd.io Textures</span>
        </div>
        <div class="header-icons">
            <a href="#" class="youtube-icon">
                <i class="fab fa-youtube"></i>
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Bloxd.io Texture Packs</h1>
        <p>Discover and download the best texture packs for your Bloxd.io world</p>
    </section>

    <!-- Texture Packs -->
    <section class="texture-packs">
        <h2 class="section-title">Featured Texture Packs</h2>
        
        <div class="grid-2x2">
            <!-- Pack 1 -->
            <div class="texture-card">
                <img src="https://images.unsplash.com/photo-1518562180175-0ed4a6f6a541?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" 
                     alt="Aqua Pack" class="card-image">
                <div class="card-content">
                    <div class="card-header">
                        <div>
                            <h3 class="pack-name">Aqua Fantasy</h3>
                            <p class="pack-author">By OceanBuilder</p>
                        </div>
                        <div class="pack-rating">
                            <i class="fas fa-star"></i>
                            <span>4.8</span>
                        </div>
                    </div>
                    <p class="pack-description">
                        Beautiful water textures with realistic waves and reflections for aquatic builds.
                    </p>
                    <div class="card-footer">
                        <span class="file-info">1.4MB • v2.1</span>
                        <button class="download-btn">Download</button>
                    </div>
                </div>
            </div>

            <!-- Pack 2 -->
            <div class="texture-card">
                <img src="https://images.unsplash.com/photo-1512273222628-4daea6e55abb?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" 
                     alt="Ice Pack" class="card-image">
                <div class="card-content">
                    <div class="card-header">
                        <div>
                            <h3 class="pack-name">Frozen Kingdom</h3>
                            <p class="pack-author">By FrostDesign</p>
                        </div>
                        <div class="pack-rating">
                            <i class="fas fa-star"></i>
                            <span>4.9</span>
                        </div>
                    </div>
                    <p class="pack-description">
                        Crystal clear ice textures with frost patterns for winter landscapes.
                    </p>
                    <div class="card-footer">
                        <span class="file-info">1.2MB • v1.5</span>
                        <button class="download-btn">Download</button>
                    </div>
                </div>
            </div>

            <!-- Pack 3 -->
            <div class="texture-card">
                <img src="https://images.unsplash.com/photo-1533134242443-95e46fe0bfce?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" 
                     alt="Neon Pack" class="card-image">
                <div class="card-content">
                    <div class="card-header">
                        <div>
                            <h3 class="pack-name">Neon City</h3>
                            <p class="pack-author">By GlowMaster</p>
                        </div>
                        <div class="pack-rating">
                            <i class="fas fa-star"></i>
                            <span>4.7</span>
                        </div>
                    </div>
                    <p class="pack-description">
                        Vibrant neon textures that glow in the dark for futuristic cities.
                    </p>
                    <div class="card-footer">
                        <span class="file-info">1.7MB • v3.0</span>
                        <button class="download-btn">Download</button>
                    </div>
                </div>
            </div>

            <!-- Pack 4 -->
            <div class="texture-card">
                <img src="https://images.unsplash.com/photo-1579547621309-5e57ab3246c1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" 
                     alt="Steampunk Pack" class="card-image">
                <div class="card-content">
                    <div class="card-header">
                        <div>
                            <h3 class="pack-name">Steampunk</h3>
                            <p class="pack-author">By GearMaster</p>
                        </div>
                        <div class="pack-rating">
                            <i class="fas fa-star"></i>
                            <span>4.6</span>
                        </div>
                    </div>
                    <p class="pack-description">
                        Brass, gears, and mechanical textures for industrial builds.
                    </p>
                    <div class="card-footer">
                        <span class="file-info">1.5MB • v2.3</span>
                        <button class="download-btn">Download</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <a href="#" class="social-icon">
                <i class="fab fa-youtube"></i>
            </a>
            <p class="copyright">
                © 2023 Bloxd.io Texture Packs. Not affiliated with Bloxd.io.
            </p>
        </div>
    </footer>
</body>
</html>
