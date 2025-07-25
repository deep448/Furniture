
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nilkamal Furniture - Living Storage Solutions</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            color: #333;
        }
        
        .header-nav {
            border-bottom: 1px solid #e5e7eb;
        }
        
        .product-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: 1px solid #e5e7eb;
        }
        
        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1);
        }
        
        .category-filter {
            scrollbar-width: thin;
            scrollbar-color: #e5e7eb transparent;
        }
        
        .category-filter::-webkit-scrollbar {
            height: 4px;
        }
        
        .category-filter::-webkit-scrollbar-thumb {
            background-color: #e5e7eb;
            border-radius: 2px;
        }
        
        .sale-badge {
            background-color: #ef4444;
            color: white;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header Section -->
    <header class="bg-white sticky top-0 z-10">
        <div class="container mx-auto px-4 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-8">
                    <a href="#" class="text-2xl font-bold text-gray-800">NILKAMAL</a>
                    <nav class="hidden md:flex space-x-6">
                        <a href="#" class="text-gray-700 hover:text-gray-900">Products</a>
                        <a href="#" class="text-gray-700 hover:text-gray-900">Collections</a>
                        <a href="#" class="text-gray-700 hover:text-gray-900">Inspiration</a>
                        <a href="#" class="text-gray-700 hover:text-gray-900">Offers</a>
                    </nav>
                </div>
                <div class="flex items-center space-x-6">
                    <button class="text-gray-700 hover:text-gray-900">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                        </svg>
                    </button>
                    <button class="text-gray-700 hover:text-gray-900">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z" />
                        </svg>
                    </button>
                    <button class="bg-blue-600 text-white px-4 py-2 rounded-md hover:bg-blue-700 transition-colors">
                        Login
                    </button>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero/Breadcrumb Section -->
    <section class="bg-gray-100 py-6">
        <div class="container mx-auto px-4">
            <div class="flex items-center space-x-2 text-sm text-gray-600">
                <a href="#" class="hover:text-gray-900">Home</a>
                <span>/</span>
                <a href="#" class="hover:text-gray-900">Furniture</a>
                <span>/</span>
                <a href="#" class="hover:text-gray-900 font-medium">Living Storage Solutions</a>
            </div>
            <h1 class="text-3xl font-bold mt-4 text-gray-800">Living Storage Solutions</h1>
        </div>
    </section>

    <!-- Main Content -->
    <main class="container mx-auto px-4 py-8">
        <!-- Filters Section -->
        <div class="mb-8">
            <div class="flex flex-col md:flex-row justify-between items-start md:items-center space-y-4 md:space-y-0">
                <!-- Category Filters -->
                <div class="category-filter w-full md:w-auto overflow-x-auto whitespace-nowrap pb-2">
                    <div class="flex space-x-4">
                        <button class="px 4 py-2 bg-gray-200 rounded-full text-sm font-medium">All</button>
                        <button class="px-4 py-2 hover:bg-gray-100 rounded-full text-sm">Bookcases</button>
                        <button class="px-4 py-2 hover:bg-gray-100 rounded-full text-sm">Shelving Units</button>
                        <button class="px-4 py-2 hover:bg-gray-100 rounded-full text-sm">Cabinets</button>
                        <button class="px-4 py-2 hover:bg-gray-100 rounded-full text-sm">TV Units</button>
                        <button class="px-4 py-2 hover:bg-gray-100 rounded-full text-sm">Display Units</button>
                    </div>
                </div>
                
                <!-- Sort Options -->
                <div class="flex items-center space-x-2">
                    <span class="text-sm text-gray-600">Sort by:</span>
                    <select class="border border-gray-300 rounded-md px-3 py-2 text-sm bg-white">
                        <option>Popularity</option>
                        <option>Price: Low to High</option>
                        <option>Price: High to Low</option>
                        <option>Newest First</option>
                    </select>
                </div>
            </div>
        </div>

        <!-- Product Grid -->
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
            <!-- Product Card 1 -->
            <div class="product-card bg-white rounded-lg overflow-hidden">
                <div class="relative">
                    <img src="https://vibecrafts.com/cdn/shop/files/brain-shape-backlit-wood-wall-shelf-book-shelf-night-light_-light-oak-finish-WWSVC_62504_01.webp?v=1724958893" alt="Modern wooden bookshelf with five shelves in light oak finish, empty and ready for decoration" class="w-full h-64 object-cover">
                    <span class="sale-badge absolute top-2 right-2 text-xs px-2 py-1 rounded">SALE</span>
                </div>
                <div class="p-4">
                    <h3 class="font-medium text-gray-800">Monte Carlo 5-Shelf Bookcase</h3>
                    <div class="flex items-center mt-1">
                        <span class="text-gray-600 line-through mr-2 text-sm">₹7,999</span>
                        <span class="text-red-600 font-medium">₹6,399</span>
                    </div>
                    <button class="w-full mt-4 bg-blue-600 text-white py-2 rounded-md hover:bg-blue-700 transition-colors">
                        Add to Cart
                    </button>
                </div>
            </div>

            <!-- Product Card 2 -->
            <div class="product-card bg-white rounded-lg overflow-hidden">
                <div class="relative">
                    <img src="https://damroimages.blob.core.windows.net/damroimages/2451.jpg" alt="Contemporary TV stand unit with two drawers and open shelving in walnut finish" class="w-full h-64 object-cover">
                </div>
                <div class="p-4">
                    <h3 class="font-medium text-gray-800">Alpha TV Unit with Storage</h3>
                    <div class="flex items-center mt-1">
                        <span class="text-gray-800 font-medium">₹12,999</span>
                    </div>
                    <button class="w-full mt-4 bg-blue-600 text-white py-2 rounded-md hover:bg-blue-700 transition-colors">
                        Add to Cart
                    </button>
                </div>
            </div>

            <!-- Product Card 3 -->
            <div class="product-card bg-white rounded-lg overflow-hidden">
                <div class="relative">
                    <img src="https://m.media-amazon.com/images/I/51q7TWprPmL._UF1000,1000_QL80_.jpg" alt="Minimalist wall-mounted floating shelves set of three in white finish with invisible brackets" class="w-full h-64 object-cover">
                </div>
                <div class="p-4">
                    <h3 class="font-medium text-gray-800">Floating Shelf Set (3 Pieces)</h3>
                    <div class="flex items-center mt-1">
                        <span class="text-gray-800 font-medium">₹4,499</span>
                    </div>
                    <button class="w-full mt-4 bg-blue-600 text-white py-2 rounded-md hover:bg-blue-700 transition-colors">
                        Add to Cart
                    </button>
                </div>
            </div>

            <!-- Product Card 4 -->
            <div class="product-card bg-white rounded-lg overflow-hidden">
                <div class="relative">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSG9bifgkubDM9CgQDDa5sulWrMNoOaenk_QA&s" alt="Industrial-style metal and wood storage cabinet with glass doors and adjustable shelves" class="w-full h-64 object-cover">
                </div>
                <div class="p-4">
                    <h3 class="font-medium text-gray-800">Industrial Storage Cabinet</h3>
                    <div class="flex items-center mt-1">
                        <span class="text-gray-600 line-through mr-2 text-sm">₹18,999</span>
                        <span class="text-red-600 font-medium">₹15,199</span>
                    </div>
                    <button class="w-full mt-4 bg-blue-600 text-white py-2 rounded-md hover:bg-blue-700 transition-colors">
                        Add to Cart
                    </button>
                </div>
            </div>

            <!-- Product Card 5 -->
            <div class="product-card bg-white rounded-lg overflow-hidden">
                <div class="relative">
                    <img src="https://m.media-amazon.com/images/I/71JNUUCEG3L.jpg" alt="Modern cube storage organizer with six square compartments in dark grey finish" class="w-full h-64 object-cover">
                </div>
                <div class="p-4">
                    <h3 class="font-medium text-gray-800">Cube Storage Organizer</h3>
                    <div class="flex items-center mt-1">
                        <span class="text-gray-800 font-medium">₹8,499</span>
                    </div>
                    <button class="w-full mt-4 bg-blue-600 text-white py-2 rounded-md hover:bg-blue-700 transition-colors">
                        Add to Cart
                    </button>
                </div>
            </div>

            <!-- Product Card 6 -->
            <div class="product-card bg-white rounded-lg overflow-hidden">
                <div class="relative">
                    <img src="https://m.media-amazon.com/images/I/51TNTHYjapL.jpg" alt="Rustic wooden ladder shelf with five tiers for displaying books and decor items" class="w-full h-64 object-cover">
                    <span class="sale-badge absolute top-2 right-2 text-xs px-2 py-1 rounded">SALE</span>
                </div>
                <div class="p-4">
                    <h3 class="font-medium text-gray-800">Farmhouse Ladder Shelf</h3>
                    <div class="flex items-center mt-1">
                        <span class="text-gray-600 line-through mr-2 text-sm">₹11,499</span>
                        <span class="text-red-600 font-medium">₹9,199</span>
                    </div>
                    <button class="w-full mt-4 bg-blue-600 text-white py-2 rounded-md hover:bg-blue-700 transition-colors">
                        Add to Cart
                    </button>
                </div>
            </div>
        </div>

        <!-- Pagination -->
        <div class="flex justify-center mt-12">
            <nav class="flex items-center space-x-2">
                <button class="px-3 py-1 border border-gray-300 rounded-md text-gray-600 hover:bg-gray-100">Previous</button>
                <button class="px-3 py-1 bg-blue-600 text-white rounded-md">1</button>
                <button class="px-3 py-1 border border-gray-300 rounded-md text-gray-600 hover:bg-gray-100">2</button>
                <button class="px-3 py-1 border border-gray-300 rounded-md text-gray-600 hover:bg-gray-100">3</button>
                <span class="px-2 text-gray-600">...</span>
                <button class="px-3 py-1 border border-gray-300 rounded-md text-gray-600 hover:bg-gray-100">8</button>
                <button class="px-3 py-1 border border-gray-300 rounded-md text-gray-600 hover:bg-gray-100">Next</button>
            </nav>
        </div>
    </main>

    <!-- Newsletter Section -->
    <section class="bg-gray-100 py-12">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-2xl font-bold mb-4">Stay Updated With Our Latest Collections</h2>
            <p class="text-gray-600 max-w-2xl mx-auto mb-6">Subscribe to our newsletter for exclusive offers, new arrivals, and design inspiration.</p>
            <div class="flex max-w-md mx-auto">
                <input type="email" placeholder="Enter your email" class="flex-grow px-4 py-2 border border-r-0 rounded-l-md focus:outline-none focus:ring-2 focus:ring-blue-500">
                <button class="bg-blue-600 text-white px-6 py-2 rounded-r-md hover:bg-blue-700 transition-colors">
                    Subscribe
                </button>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-lg font-medium mb-4">Shop</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Living Room</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Bedroom</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Dining</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Storage</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-lg font-medium mb-4">Customer Service</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Contact Us</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">FAQs</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Shipping & Returns</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Warranty</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-lg font-medium mb-4">About Nilkamal</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Our Story</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Sustainability</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Careers</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Blog</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-lg font-medium mb-4">Connect With Us</h3>
                    <div class="flex space-x-4 mb-4">
                        <a href="#" class="text-gray-400 hover:text-white">
                            <s
