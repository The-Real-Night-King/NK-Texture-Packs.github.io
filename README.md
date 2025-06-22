<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bloxd.io Texture Hub | Share & Download Packs</title>
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
                <span class="text-xl font-bold">Bloxd.io Texture Hub</span>
            </div>
            <div class="hidden md:flex space-x-6">
                <a href="#featured" class="hover:text-gray-200 transition">Featured</a>
                <a href="#categories" class="hover:text-gray-200 transition">Categories</a>
                <a href="#upload" class="hover:text-gray-200 transition">Upload</a>
                <a href="#tutorial" class="hover:text-gray-200 transition">Tutorial</a>
            </div>
            <button class="md:hidden text-xl">
                <i class="fas fa-bars"></i>
            </button>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="gradient-bg text-white py-16">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-4xl md:text-5xl font-bold mb-6">Share Your Bloxd.io Textures</h1>
            <p class="text-xl mb-8 max-w-2xl mx-auto">Discover and share the best texture packs for Bloxd.io. Enhance your building experience!</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#upload" class="bg-white text-indigo-700 font-semibold px-6 py-3 rounded-lg hover:bg-gray-100 transition">Upload Your Pack</a>
                <a href="#featured" class="bg-transparent border-2 border-white text-white font-semibold px-6 py-3 rounded-lg hover:bg-white hover:text-indigo-700 transition">Browse Textures</a>
            </div>
        </div>
    </section>

    <!-- Featured Texture Packs -->
    <section id="featured" class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-8 text-center">Featured Texture Packs</h2>
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
                            <button class="bg-indigo-600 text-white px-4 py-2 rounded-lg hover:bg-indigo-700 transition">Download</button>
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
                            <button class="bg-indigo-600 text-white px-4 py-2 rounded-lg hover:bg-indigo-700 transition">Download</button>
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
                            <button class="bg-indigo-600 text-white px-4 py-2 rounded-lg hover:bg-indigo-700 transition">Download</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Categories Section -->
    <section id="categories" class="py-12 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-8 text-center">Texture Categories</h2>
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-4">
                <a href="#" class="category-card bg-white rounded-lg p-4 text-center shadow hover:shadow-md transition">
                    <div class="w-16 h-16 mx-auto mb-2 bg-indigo-100 rounded-full flex items-center justify-center text-indigo-600">
                        <i class="fas fa-mountain text-2xl"></i>
                    </div>
                    <span class="font-medium">Nature</span>
                </a>
                <a href="#" class="category-card bg-white rounded-lg p-4 text-center shadow hover:shadow-md transition">
                    <div class="w-16 h-16 mx-auto mb-2 bg-red-100 rounded-full flex items-center justify-center text-red-600">
                        <i class="fas fa-building text-2xl"></i>
                    </div>
                    <span class="font-medium">Modern</span>
                </a>
                <a href="#" class="category-card bg-white rounded-lg p-4 text-center shadow hover:shadow-md transition">
                    <div class="w-16 h-16 mx-auto mb-2 bg-yellow-100 rounded-full flex items-center justify-center text-yellow-600">
                        <i class="fas fa-chess-rook text-2xl"></i>
                    </div>
                    <span class="font-medium">Medieval</span>
                </a>
                <a href="#" class="category-card bg-white rounded-lg p-4 text-center shadow hover:shadow-md transition">
                    <div class="w-16 h-16 mx-auto mb-2 bg-green-100 rounded-full flex items-center justify-center text-green-600">
                        <i class="fas fa-robot text-2xl"></i>
                    </div>
                    <span class="font-medium">Sci-Fi</span>
                </a>
                <a href="#" class="category-card bg-white rounded-lg p-4 text-center shadow hover:shadow-md transition">
                    <div class="w-16 h-16 mx-auto mb-2 bg-purple-100 rounded-full flex items-center justify-center text-purple-600">
                        <i class="fas fa-palette text-2xl"></i>
                    </div>
                    <span class="font-medium">Abstract</span>
                </a>
                <a href="#" class="category-card bg-white rounded-lg p-4 text-center shadow hover:shadow-md transition">
                    <div class="w-16 h-16 mx-auto mb-2 bg-blue-100 rounded-full flex items-center justify-center text-blue-600">
                        <i class="fas fa-hammer text-2xl"></i>
                    </div>
                    <span class="font-medium">Tools</span>
                </a>
            </div>
        </div>
    </section>

    <!-- Upload Section -->
    <section id="upload" class="py-12 bg-white">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="text-3xl font-bold mb-6 text-center">Share Your Texture Pack</h2>
            <div class="bg-gray-50 rounded-xl p-6 md:p-8 shadow-lg">
                <form>
                    <div class="mb-6">
                        <label class="block text-gray-700 font-medium mb-2" for="pack-name">Pack Name</label>
                        <input type="text" id="pack-name" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-500">
                    </div>
                    
                    <div class="mb-6">
                        <label class="block text-gray-700 font-medium mb-2">Pack Images (At least 3)</label>
                        <div class="border-2 border-dashed border-gray-300 rounded-lg p-8 text-center">
                            <i class="fas fa-cloud-upload-alt text-4xl text-indigo-600 mb-3"></i>
                            <p class="text-gray-600 mb-2">Drag & drop your images here or click to browse</p>
                            <button type="button" class="bg-indigo-100 text-indigo-700 px-4 py-2 rounded-lg hover:bg-indigo-200 transition">Select Files</button>
                        </div>
                    </div>
                    
                    <div class="mb-6">
                        <label class="block text-gray-700 font-medium mb-2" for="description">Description</label>
                        <textarea id="description" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-500"></textarea>
                    </div>
                    
                    <div class="mb-6">
                        <label class="block text-gray-700 font-medium mb-2">Category</label>
                        <select class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-500">
                            <option>Nature</option>
                            <option>Modern</option>
                            <option>Medieval</option>
                            <option>Sci-Fi</option>
                            <option>Abstract</option>
                            <option>Tools</option>
                        </select>
                    </div>
                    
                    <div class="mb-6">
                        <label class="block text-gray-700 font-medium mb-2" for="zip-file">Zip File</label>
                        <div class="flex items-center">
                            <input type="file" id="zip-file" class="hidden">
                            <div class="flex-1 bg-gray-200 px-4 py-2 rounded-l-lg truncate" id="file-name">No file selected</div>
                            <button type="button" onclick="document.getElementById('zip-file').click()" class="bg-indigo-600 text-white px-4 py-2 rounded-r-lg hover:bg-indigo-700 transition">Browse</button>
                        </div>
                    </div>
                    
                    <button type="submit" class="w-full gradient-bg text-white font-semibold py-3 rounded-lg hover:opacity-90 transition">Upload Texture Pack</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Tutorial Section -->
    <section id="tutorial" class="py-12 bg-gray-50">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="text-3xl font-bold mb-8 text-center">How to Install Texture Packs</h2>
            <div class="bg-white rounded-xl shadow-lg overflow-hidden">
                <div class="p-6 md:p-8">
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="flex-shrink-0 bg-indigo-100 text-indigo-700 rounded-full w-10 h-10 flex items-center justify-center font-bold mr-4">1</div>
                            <div>
                                <h3 class="text-xl font-semibold mb-2">Download a Texture Pack</h3>
                                <p class="text-gray-700">Find a texture pack you like and click the download button to get the .zip file.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="flex-shrink-0 bg-indigo-100 text-indigo-700 rounded-full w-10 h-10 flex items-center justify-center font-bold mr-4">2</div>
                            <div>
                                <h3 class="text-xl font-semibold mb-2">Extract the Files</h3>
                                <p class="text-gray-700">Right-click the .zip file and select "Extract All" to unzip the contents to a folder.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="flex-shrink-0 bg-indigo-100 text-indigo-700 rounded-full w-10 h-10 flex items-center justify-center font-bold mr-4">3</div>
                            <div>
                                <h3 class="text-xl font-semibold mb-2">Locate Bloxd.io Files</h3>
                                <p class="text-gray-700">Find where Bloxd.io stores its texture files (usually in the game's installation directory).</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="flex-shrink-0 bg-indigo-100 text-indigo-700 rounded-full w-10 h-10 flex items-center justify-center font-bold mr-4
