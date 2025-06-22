<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bloxd.io Texture Packs | GitHub Hosted</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .texture-card:hover .preview-overlay {
            opacity: 1;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
    </style>
</head>
<body class="bg-gray-100 font-sans">
    <!-- Navigation -->
    <nav class="gradient-bg text-white shadow-lg">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i class="fas fa-cubes text-2xl"></i>
                <span class="text-xl font-bold">Bloxd.io Textures</span>
            </div>
            <a href="https://github.com/yourusername/bloxd-textures" class="hover:text-gray-200 transition" target="_blank">
                <i class="fab fa-github text-xl"></i>
            </a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="gradient-bg text-white py-16">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-4xl md:text-5xl font-bold mb-6">Bloxd.io Texture Packs</h1>
            <p class="text-xl mb-8 max-w-2xl mx-auto">Hand-picked texture packs to enhance your Bloxd.io experience</p>
            <a href="#textures" class="bg-white text-indigo-700 font-semibold px-6 py-3 rounded-lg hover:bg-gray-100 transition">Browse Textures</a>
        </div>
    </section>

    <!-- Texture Packs -->
    <section id="textures" class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-8 text-center">Available Texture Packs</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Texture Card 1 -->
                <div class="texture-card bg-gray-50 rounded-xl overflow-hidden shadow-lg hover:shadow-xl transition">
                    <div class="relative h-48 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1627855437693-dcc7b0e1d7f8?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" 
                             alt="Realistic Pack" class="w-full h-full object-cover">
                        <div class="preview-overlay absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 transition">
                            <button class="bg-white text-indigo-700 px-4 py-2 rounded-full font-semibold">Quick Preview</button>
                        </div>
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-bold text-lg">Realistic Pack</h3>
                                <p class="text-gray-600">By BlockMaster</p>
                            </div>
                            <div class="flex items-center text-yellow-400">
                                <i class="fas fa-star"></i>
                                <span class="ml-1 text-gray-700">4.8</span>
                            </div>
                        </div>
                        <p class="mt-2 text-gray-700">High-resolution realistic textures for a modern look.</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-sm text-gray-500">1.2MB • v1.3</span>
                            <a href="#" class="bg-indigo-600 text-white px-4 py-2 rounded-lg hover:bg-indigo-700 transition">Download</a>
                        </div>
                    </div>
                </div>

                <!-- Texture Card 2 -->
                <div class="texture-card bg-gray-50 rounded-xl overflow-hidden shadow-lg hover:shadow-xl transition">
                    <div class="relative h-48 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1635070041078-e363dbe005cb?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" 
                             alt="Cartoon Pack" class="w-full h-full object-cover">
                        <div class="preview-overlay absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 transition">
                            <button class="bg-white text-indigo-700 px-4 py-2 rounded-full font-semibold">Quick Preview</button>
                        </div>
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-bold text-lg">Cartoon Fantasy</h3>
                                <p class="text-gray-600">By PixelArtist</p>
                            </div>
                            <div class="flex items-center text-yellow-400">
                                <i class="fas fa-star"></i>
                                <span class="ml-1 text-gray-700">4.9</span>
                            </div>
                        </div>
                        <p class="mt-2 text-gray-700">Bright, colorful textures with a cartoon aesthetic.</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-sm text-gray-500">0.8MB • v2.1</span>
                            <a href="#" class="bg-indigo-600 text-white px-4 py-2 rounded-lg hover:bg-indigo-700 transition">Download</a>
                        </div>
                    </div>
                </div>

                <!-- Texture Card 3 -->
                <div class="texture-card bg-gray-50 rounded-xl overflow-hidden shadow-lg hover:shadow-xl transition">
                    <div class="relative h-48 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1639762681057-408e52192e55?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" 
                             alt="Steampunk Pack" class="w-full h-full object-cover">
                        <div class="preview-overlay absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 transition">
                            <button class="bg-white text-indigo-700 px-4 py-2 rounded-full font-semibold">Quick Preview</button>
                        </div>
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-bold text-lg">Steampunk</h3>
                                <p class="text-gray-600">By GearMaster</p>
                            </div>
                            <div class="flex items-center text-yellow-400">
                                <i class="fas fa-star"></i>
                                <span class="ml-1 text-gray-700">4.7</span>
                            </div>
                        </div>
                        <p class="mt-2 text-gray-700">Brass, gears, and Victorian industrial textures.</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-sm text-gray-500">1.5MB • v1.0</span>
                            <a href="#" class="bg-indigo-600 text-white px-4 py-2 rounded-lg hover:bg-indigo-700 transition">Download</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Tutorial Section -->
    <section id="tutorial" class="py-12 bg-gray-50">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="text-3xl font-bold mb-8 text-center">How to Install</h2>
            <div class="bg-white rounded-xl shadow-lg overflow-hidden">
                <div class="p-6 md:p-8">
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="flex-shrink-0 bg-indigo-100 text-indigo-700 rounded-full w-10 h-10 flex items-center justify-center font-bold mr-4">1</div>
                            <div>
                                <h3 class="text-xl font-semibold mb-2">Download a Pack</h3>
                                <p class="text-gray-700">Click the download button on any texture pack to get the .zip file.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="flex-shrink-0 bg-indigo-100 text-indigo-700 rounded-full w-10 h-10 flex items-center justify-center font-bold mr-4">2</div>
                            <div>
                                <h3 class="text-xl font-semibold mb-2">Extract the Files</h3>
                                <p class="text-gray-700">Right-click the .zip file and select "Extract All" to unzip the contents.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="flex-shrink-0 bg-indigo-100 text-indigo-700 rounded-full w-10 h-10 flex items-center justify-center font-bold mr-4">3</div>
                            <div>
                                <h3 class="text-xl font-semibold mb-2">Add to Bloxd.io</h3>
                                <p class="text-gray-700">Place the extracted files in your Bloxd.io textures folder.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4 text-center">
            <p>&copy; 2023 Bloxd.io Texture Packs. All textures belong to their respective creators.</p>
            <p class="mt-2 text-gray-400">This is an unofficial fan site not affiliated with Bloxd.io.</p>
            <div class="mt-4 flex justify-center space-x-4">
                <a href="https://github.com/yourusername/bloxd-textures" class="hover:text-indigo-400 transition" target="_blank">
                    <i class="fab fa-github text-xl"></i>
                </a>
            </div>
        </div>
    </footer>

    <script>
        // Simple GitHub link handling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            ]);
        });
    </script>
</body>
</html>
