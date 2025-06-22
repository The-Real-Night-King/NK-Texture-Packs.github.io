<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bloxd.io Texture Packs | Cyan Theme</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        cyan: {
                            50: '#ecfeff',
                            100: '#cffafe',
                            200: '#a5f3fc',
                            300: '#67e8f9',
                            400: '#22d3ee',
                            500: '#06b6d4',
                            600: '#0891b2',
                            700: '#0e7490',
                            800: '#155e75',
                            900: '#164e63',
                        }
                    }
                }
            }
        }
    </script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #06b6d4 0%, #0e7490 100%);
        }
        .gradient-card {
            background: linear-gradient(135deg, #ecfeff 0%, #cffafe 100%);
            transition: all 0.3s ease;
        }
        .gradient-button {
            background: linear-gradient(135deg, #06b6d4 0%, #0891b2 100%);
        }
        .texture-card {
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .texture-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(6, 182, 212, 0.5);
        }
    </style>
</head>
<body class="bg-cyan-50 font-sans">
    <!-- Navigation -->
    <nav class="gradient-bg text-white shadow-lg">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i class="fas fa-cubes text-2xl text-cyan-200"></i>
                <span class="text-xl font-bold">Bloxd.io Textures</span>
            </div>
            <a href="https://youtube.com" class="hover:text-cyan-200 transition" target="_blank">
                <i class="fab fa-youtube text-xl"></i>
            </a>
        </div>
    </nav>

    <!-- Hero Section with Wave -->
    <section class="gradient-bg text-white pt-16 pb-32 relative">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-4xl md:text-5xl font-bold mb-6">Bloxd.io Texture Packs</h1>
            <p class="text-xl mb-8 max-w-2xl mx-auto">Cool cyan-themed textures for your Bloxd.io world</p>
        </div>
        <div class="wave-shape">
            <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
                <path d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V0H0V27.35A600.21,600.21,0,0,0,321.39,56.44Z" class="shape-fill"></path>
            </svg>
        </div>
    </section>

    <!-- Texture Packs -->
    <section id="textures" class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-8 text-center text-cyan-800">Featured Texture Packs</h2>
            
            <!-- First Row -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mb-8">
                <!-- Aqua Pack -->
                <div class="texture-card gradient-card rounded-xl overflow-hidden transition border border-cyan-200">
                    <div class="h-48 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1518562180175-0ed4a6f6a541?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" 
                             alt="Aqua Pack" class="w-full h-full object-cover">
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-bold text-lg text-cyan-800">Aqua Fantasy</h3>
                                <p class="text-cyan-600">By OceanBuilder</p>
                            </div>
                            <div class="flex items-center text-amber-300">
                                <i class="fas fa-star"></i>
                                <span class="ml-1 text-cyan-700">4.9</span>
                            </div>
                        </div>
                        <p class="mt-2 text-cyan-700">Cool water-themed textures with aquatic elements.</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-sm text-cyan-600">1.4MB • v2.0</span>
                            <a href="#" class="gradient-button text-white px-4 py-2 rounded-lg hover:opacity-90 transition">Download</a>
                        </div>
                    </div>
                </div>

                <!-- Ice Pack -->
                <div class="texture-card gradient-card rounded-xl overflow-hidden transition border border-cyan-200">
                    <div class="h-48 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1512273222628-4daea6e55abb?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" 
                             alt="Ice Pack" class="w-full h-full object-cover">
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-bold text-lg text-cyan-800">Frozen Kingdom</h3>
                                <p class="text-cyan-600">By FrostArtist</p>
                            </div>
                            <div class="flex items-center text-amber-300">
                                <i class="fas fa-star"></i>
                                <span class="ml-1 text-cyan-700">4.7</span>
                            </div>
                        </div>
                        <p class="mt-2 text-cyan-700">Icy textures with snow and crystal effects.</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-sm text-cyan-600">1.1MB • v1.5</span>
                            <a href="#" class="gradient-button text-white px-4 py-2 rounded-lg hover:opacity-90 transition">Download</a>
                        </div>
                    </div>
                </div>

                <!-- Neon Cyan -->
                <div class="texture-card gradient-card rounded-xl overflow-hidden transition border border-cyan-200">
                    <div class="h-48 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1579547621309-5e57ab3246c1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" 
                             alt="Neon Cyan" class="w-full h-full object-cover">
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-bold text-lg text-cyan-800">Neon Cyan</h3>
                                <p class="text-cyan-600">By GlowMaster</p>
                            </div>
                            <div class="flex items-center text-amber-300">
                                <i class="fas fa-star"></i>
                                <span class="ml-1 text-cyan-700">4.8</span>
                            </div>
                        </div>
                        <p class="mt-2 text-cyan-700">Vibrant neon cyan textures for futuristic builds.</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-sm text-cyan-600">1.7MB • v3.2</span>
                            <a href="#" class="gradient-button text-white px-4 py-2 rounded-lg hover:opacity-90 transition">Download</a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Second Row -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Crystal Pack -->
                <div class="texture-card gradient-card rounded-xl overflow-hidden transition border border-cyan-200">
                    <div class="h-48 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1535554979431-517f69f5a44f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" 
                             alt="Crystal Pack" class="w-full h-full object-cover">
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-bold text-lg text-cyan-800">Crystal Clear</h3>
                                <p class="text-cyan-600">By GemDesigner</p>
                            </div>
                            <div class="flex items-center text-amber-300">
                                <i class="fas fa-star"></i>
                                <span class="ml-1 text-cyan-700">4.6</span>
                            </div>
                        </div>
                        <p class="mt-2 text-cyan-700">Transparent crystal textures with refraction effects.</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-sm text-cyan-600">1.3MB • v1.8</span>
                            <a href="#" class="gradient-button text-white px-4 py-2 rounded-lg hover:opacity-90 transition">Download</a>
                        </div>
                    </div>
                </div>

                <!-- Ocean Depths -->
                <div class="texture-card gradient-card rounded-xl overflow-hidden transition border border-cyan-200">
                    <div class="h-48 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1505118380757-91f5f5632de0?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" 
                             alt="Ocean Depths" class="w-full h-full object-cover">
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-bold text-lg text-cyan-800">Ocean Depths</h3>
                                <p class="text-cyan-600">By DeepSea</p>
                            </div>
                            <div class="flex items-center text-amber-300">
                                <i class="fas fa-star"></i>
                                <span class="ml-1 text-cyan-700">4.9</span>
                            </div>
                        </div>
                        <p class="mt-2 text-cyan-700">Deep ocean textures with realistic water effects.</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-sm text-cyan-600">1.5MB • v2.1</span>
                            <a href="#" class="gradient-button text-white px-4 py-2 rounded-lg hover:opacity-90 transition">Download</a>
                        </div>
                    </div>
                </div>

                <!-- Cyber Waves -->
                <div class="texture-card gradient-card rounded-xl overflow-hidden transition border border-cyan-200">
                    <div class="h-48 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1533134242443-95e46fe0bfce?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" 
                             alt="Cyber Waves" class="w-full h-full object-cover">
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-bold text-lg text-cyan-800">Cyber Waves</h3>
                                <p class="text-cyan-600">By NeonTech</p>
                            </div>
                            <div class="flex items-center text-amber-300">
                                <i class="fas fa-star"></i>
                                <span class="ml-1 text-cyan-700">4.8</span>
                            </div>
                        </div>
                        <p class="mt-2 text-cyan-700">Digital wave patterns with glowing cyan highlights.</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-sm text-cyan-600">1.6MB • v3.0</span>
                            <a href="#" class="gradient-button text-white px-4 py-2 rounded-lg hover:opacity-90 transition">Download</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Tutorial Section -->
    <section id="tutorial" class="py-12 bg-cyan-50">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="text-3xl font-bold mb-8 text-center text-cyan-800">Installation Guide</h2>
            <div class="gradient-card rounded-xl shadow-lg overflow-hidden border border-cyan-200">
                <div class="p-6 md:p-8">
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="flex-shrink-0 gradient-button text-white rounded-full w-10 h-10 flex items-center justify-center font-bold mr-4">1</div>
                            <div>
                                <h3 class="text-xl font-semibold mb-2 text-cyan-800">Download a Pack</h3>
                                <p class="text-cyan-700">Click the download button to get the texture pack .zip file.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="flex-shrink-0 gradient-button text-white rounded-full w-10 h-10 flex items-center justify-center font-bold mr-4">2</div>
                            <div>
                                <h3 class="text-xl font-semibold mb-2 text-cyan-800">Extract the Files</h3>
                                <p class="text-cyan-700">Unzip the downloaded file to access the texture files.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="flex-shrink-0 gradient-button text-white rounded-full w-10 h-10 flex items-center justify-center font-bold mr-4">3</div>
                            <div>
                                <h3 class="text-xl font-semibold mb-2 text-cyan-800">Add to Bloxd.io</h3>
                                <p class="text-cyan-700">Place the texture files in your Bloxd.io textures folder.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="gradient-bg text-white py-8">
        <div class="container mx-auto px-4 text-center">
            <p>&copy; 2023 Bloxd.io Texture Packs. All textures belong to their creators.</p>
            <p class="mt-2 text-cyan-200">This is an unofficial fan site not affiliated with
