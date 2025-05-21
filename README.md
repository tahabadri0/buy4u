<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BUY4U - Premium Amazon Affiliate Store</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
    
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #f8fafc;
    }
    
    .product-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1);
    }
    
    .category-title {
      position: relative;
      display: inline-block;
    }
    
    .category-title:after {
      content: '';
      position: absolute;
      width: 100%;
      height: 4px;
      bottom: -8px;
      left: 0;
      background: linear-gradient(90deg, #3b82f6, #8b5cf6);
      border-radius: 2px;
    }
    
    .search-bar:focus {
      outline: none;
      box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.2);
    }
    
    .deal-badge {
      animation: pulse 2s infinite;
    }
    
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.05); }
      100% { transform: scale(1); }
    }
    
    .scroll-to-top {
      transition: all 0.3s ease;
    }
    
    .scroll-to-top:hover {
      transform: scale(1.1);
    }
  </style>
</head>
<body class="bg-gray-50">
  <!-- Header with Search -->
  <header class="bg-gradient-to-r from-blue-600 to-indigo-700 shadow-lg">
    <div class="container mx-auto px-4 py-6">
      <div class="flex flex-col md:flex-row justify-between items-center">
        <div class="flex items-center mb-4 md:mb-0">
          <i class="fas fa-shopping-bag text-white text-3xl mr-3"></i>
          <h1 class="text-3xl font-bold text-white">BUY4U</h1>
        </div>
        <div class="w-full md:w-1/2 relative">
          <input 
            type="text" 
            placeholder="Search for products..." 
            class="w-full py-3 px-4 rounded-full shadow-md focus:outline-none search-bar"
          >
          <button class="absolute right-3 top-3 text-gray-500 hover:text-blue-600">
            <i class="fas fa-search"></i>
          </button>
        </div>
      </div>
      <p class="text-blue-100 text-center mt-2">Your curated Amazon affiliate store with exclusive deals</p>
    </div>
  </header>

  <!-- Navigation -->
  <nav class="bg-white shadow-md sticky top-0 z-10">
    <div class="container mx-auto px-4">
      <div class="flex overflow-x-auto py-3 hide-scrollbar">
        <a href="#home-kitchen" class="flex items-center whitespace-nowrap px-4 py-2 text-gray-700 hover:text-blue-600 hover:bg-blue-50 rounded-lg mx-1 transition-colors">
          <i class="fas fa-blender text-lg mr-2"></i> Home & Kitchen
        </a>
        <a href="#toys-games" class="flex items-center whitespace-nowrap px-4 py-2 text-gray-700 hover:text-blue-600 hover:bg-blue-50 rounded-lg mx-1 transition-colors">
          <i class="fas fa-gamepad text-lg mr-2"></i> Toys & Games
        </a>
        <a href="#makeup-selfcare" class="flex items-center whitespace-nowrap px-4 py-2 text-gray-700 hover:text-blue-600 hover:bg-blue-50 rounded-lg mx-1 transition-colors">
          <i class="fas fa-spa text-lg mr-2"></i> Beauty & Selfcare
        </a>
        <a href="#clothing-shoes" class="flex items-center whitespace-nowrap px-4 py-2 text-gray-700 hover:text-blue-600 hover:bg-blue-50 rounded-lg mx-1 transition-colors">
          <i class="fas fa-tshirt text-lg mr-2"></i> Clothing & Shoes
        </a>
        <a href="#electronics" class="flex items-center whitespace-nowrap px-4 py-2 text-gray-700 hover:text-blue-600 hover:bg-blue-50 rounded-lg mx-1 transition-colors">
          <i class="fas fa-laptop text-lg mr-2"></i> Electronics
        </a>
        <a href="#deals" class="flex items-center whitespace-nowrap px-4 py-2 text-red-600 font-medium hover:bg-red-50 rounded-lg mx-1 transition-colors">
          <i class="fas fa-bolt text-lg mr-2"></i> Today's Deals
        </a>
      </div>
    </div>
  </nav>

  <!-- Hero Banner -->
  <section class="bg-gradient-to-r from-blue-500 to-indigo-600 text-white py-12">
    <div class="container mx-auto px-4 text-center">
      <h2 class="text-4xl font-bold mb-4">Exclusive Amazon Deals</h2>
      <p class="text-xl mb-6">Handpicked products with the best discounts and quality</p>
      <a href="#deals" class="bg-white text-blue-600 font-bold py-3 px-8 rounded-full inline-block hover:bg-gray-100 transition-colors shadow-lg">
        Shop Deals <i class="fas fa-arrow-right ml-2"></i>
      </a>
    </div>
  </section>

  <!-- Main Content -->
  <main class="container mx-auto px-4 py-8">
    <!-- Deals Section -->
    <section id="deals" class="mb-16">
      <div class="flex items-center mb-6">
        <h2 class="text-2xl font-bold text-gray-800 category-title">Today's Hot Deals</h2>
        <span class="ml-4 bg-red-600 text-white text-xs font-bold px-2 py-1 rounded-full deal-badge">LIMITED TIME</span>
      </div>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
        <!-- Deal Product 1 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <div class="relative">
            <img src="https://m.media-amazon.com/images/I/71Y1S1m-QAL._AC_UL320_.jpg" alt="Instant Pot" class="w-full h-48 object-contain">
            <span class="absolute top-2 left-2 bg-red-600 text-white text-xs font-bold px-2 py-1 rounded">30% OFF</span>
          </div>
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Instant Pot Duo 7-in-1 Electric Pressure Cooker</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(12,543)</span>
            </div>
            <div class="flex items-center">
              <span class="text-lg font-bold text-gray-900">$79.00</span>
              <span class="text-sm text-gray-500 line-through ml-2">$99.95</span>
            </div>
            <a href="https://www.amazon.com/dp/B00FLYWNYQ" target="_blank" rel="noopener noreferrer" class="mt-3 inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Deal Product 2 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <div class="relative">
            <img src="https://m.media-amazon.com/images/I/71Swqqe7XAL._AC_UL320_.jpg" alt="Echo Dot" class="w-full h-48 object-contain">
            <span class="absolute top-2 left-2 bg-red-600 text-white text-xs font-bold px-2 py-1 rounded">50% OFF</span>
          </div>
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Echo Dot (4th Gen) | Smart speaker with Alexa</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(89,432)</span>
            </div>
            <div class="flex items-center">
              <span class="text-lg font-bold text-gray-900">$24.99</span>
              <span class="text-sm text-gray-500 line-through ml-2">$49.99</span>
            </div>
            <a href="https://www.amazon.com/dp/B07XJ8C8F5" target="_blank" rel="noopener noreferrer" class="mt-3 inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Deal Product 3 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <div class="relative">
            <img src="https://m.media-amazon.com/images/I/61L5QgPvgxL._AC_UL320_.jpg" alt="Wireless Earbuds" class="w-full h-48 object-contain">
            <span class="absolute top-2 left-2 bg-red-600 text-white text-xs font-bold px-2 py-1 rounded">45% OFF</span>
          </div>
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">TOZO T6 True Wireless Earbuds Bluetooth Headphones</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(43,210)</span>
            </div>
            <div class="flex items-center">
              <span class="text-lg font-bold text-gray-900">$27.99</span>
              <span class="text-sm text-gray-500 line-through ml-2">$50.99</span>
            </div>
            <a href="https://www.amazon.com/dp/B07RGZ5NKM" target="_blank" rel="noopener noreferrer" class="mt-3 inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Deal Product 4 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <div class="relative">
            <img src="https://m.media-amazon.com/images/I/71WwzAz1DkL._AC_UL320_.jpg" alt="Fitness Tracker" class="w-full h-48 object-contain">
            <span class="absolute top-2 left-2 bg-red-600 text-white text-xs font-bold px-2 py-1 rounded">60% OFF</span>
          </div>
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Fitbit Charge 5 Advanced Fitness & Health Tracker</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(32,765)</span>
            </div>
            <div class="flex items-center">
              <span class="text-lg font-bold text-gray-900">$99.95</span>
              <span class="text-sm text-gray-500 line-through ml-2">$149.95</span>
            </div>
            <a href="https://www.amazon.com/dp/B09B9W5KHY" target="_blank" rel="noopener noreferrer" class="mt-3 inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- Home & Kitchen Section -->
    <section id="home-kitchen" class="mb-16">
      <h2 class="text-2xl font-bold text-gray-800 mb-6 category-title">
        <i class="fas fa-blender text-blue-500 mr-2"></i> Home & Kitchen Essentials
      </h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
        <!-- Product 1 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71Vj5yqJtmL._AC_UL320_.jpg" alt="Air Fryer" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Ninja AF101 Air Fryer</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(24,876)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$99.95</div>
            <a href="https://www.amazon.com/dp/B07FDJMC2Q" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 2 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71qod6GjYIL._AC_UL320_.jpg" alt="Coffee Maker" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Keurig K-Classic Coffee Maker</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(56,321)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$89.99</div>
            <a href="https://www.amazon.com/dp/B01F5K9NJG" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 3 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71YHjVXyJ0L._AC_UL320_.jpg" alt="Blender" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">NutriBullet Pro 900W Blender</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(18,543)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$69.99</div>
            <a href="https://www.amazon.com/dp/B00I5HUDOY" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 4 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71vZypjNk2L._AC_UL320_.jpg" alt="Food Storage" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Rubbermaid Brilliance Food Storage Containers</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(32,109)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$29.99</div>
            <a href="https://www.amazon.com/dp/B00HZEW37W" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- Toys & Games Section -->
    <section id="toys-games" class="mb-16">
      <h2 class="text-2xl font-bold text-gray-800 mb-6 category-title">
        <i class="fas fa-gamepad text-blue-500 mr-2"></i> Toys & Games
      </h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
        <!-- Product 1 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/81qYyfUILxL._AC_UL320_.jpg" alt="LEGO Set" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">LEGO Star Wars Mandalorian Helmet</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(2,543)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$59.99</div>
            <a href="https://www.amazon.com/dp/B08G4MNJ5X" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 2 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71sVXWfUvKL._AC_UL320_.jpg" alt="Board Game" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Catan Board Game (Base Game)</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(15,321)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$44.99</div>
            <a href="https://www.amazon.com/dp/B00U26V4VQ" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 3 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71gqyZQx0TL._AC_UL320_.jpg" alt="Nerf Gun" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Nerf N-Strike Elite Disruptor</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(8,543)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$19.99</div>
            <a href="https://www.amazon.com/dp/B01B7XAA9E" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 4 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/81zGgX+9+1L._AC_UL320_.jpg" alt="Puzzle" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Ravensburger Disney Villainous Strategy Board Game</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(12,109)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$29.99</div>
            <a href="https://www.amazon.com/dp/B07MZWFWGL" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- Beauty & Selfcare Section -->
    <section id="makeup-selfcare" class="mb-16">
      <h2 class="text-2xl font-bold text-gray-800 mb-6 category-title">
        <i class="fas fa-spa text-blue-500 mr-2"></i> Beauty & Selfcare
      </h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
        <!-- Product 1 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71YHjVXyJ0L._AC_UL320_.jpg" alt="Hair Dryer" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Revlon One-Step Hair Dryer And Volumizer</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(124,876)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$39.99</div>
            <a href="https://www.amazon.com/dp/B01LSUQSB0" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 2 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71YHjVXyJ0L._AC_UL320_.jpg" alt="Skincare Set" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">CeraVe AM Facial Moisturizing Lotion SPF 30</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(56,321)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$14.99</div>
            <a href="https://www.amazon.com/dp/B00F3K1S3Q" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 3 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71YHjVXyJ0L._AC_UL320_.jpg" alt="Makeup Palette" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Maybelline New York City Mini Eyeshadow Palette</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(18,543)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$9.99</div>
            <a href="https://www.amazon.com/dp/B07RGZ5NKM" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 4 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71YHjVXyJ0L._AC_UL320_.jpg" alt="Perfume" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Dolce & Gabbana Light Blue Eau de Toilette</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(32,109)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$79.99</div>
            <a href="https://www.amazon.com/dp/B000C1Z6H2" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- Clothing & Shoes Section -->
    <section id="clothing-shoes" class="mb-16">
      <h2 class="text-2xl font-bold text-gray-800 mb-6 category-title">
        <i class="fas fa-tshirt text-blue-500 mr-2"></i> Clothing & Shoes
      </h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
        <!-- Product 1 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71YHjVXyJ0L._AC_UL320_.jpg" alt="T-Shirt" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Amazon Essentials Men's Classic-Fit T-Shirt</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(24,876)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$12.90</div>
            <a href="https://www.amazon.com/dp/B07KGL3X4N" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 2 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71YHjVXyJ0L._AC_UL320_.jpg" alt="Jeans" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Levi's Men's 505 Regular Fit Jeans</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(56,321)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$49.99</div>
            <a href="https://www.amazon.com/dp/B001ANQBNE" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 3 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71YHjVXyJ0L._AC_UL320_.jpg" alt="Running Shoes" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Nike Men's Revolution 5 Running Shoes</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(18,543)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$59.99</div>
            <a href="https://www.amazon.com/dp/B07P619D5S" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 4 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71YHjVXyJ0L._AC_UL320_.jpg" alt="Dress" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Lulus Women's Wrap Dress</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(32,109)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$49.99</div>
            <a href="https://www.amazon.com/dp/B07RGZ5NKM" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- Electronics Section -->
    <section id="electronics" class="mb-16">
      <h2 class="text-2xl font-bold text-gray-800 mb-6 category-title">
        <i class="fas fa-laptop text-blue-500 mr-2"></i> Electronics
      </h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
        <!-- Product 1 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71YHjVXyJ0L._AC_UL320_.jpg" alt="Laptop" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Acer Aspire 5 Slim Laptop</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(24,876)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$499.99</div>
            <a href="https://www.amazon.com/dp/B07RF1XD36" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 2 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71YHjVXyJ0L._AC_UL320_.jpg" alt="Tablet" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Samsung Galaxy Tab A7 Lite</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(56,321)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$159.99</div>
            <a href="https://www.amazon.com/dp/B08GF5GQBG" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 3 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71YHjVXyJ0L._AC_UL320_.jpg" alt="Smartwatch" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Apple Watch Series 7 (GPS, 45mm)</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(18,543)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$429.00</div>
            <a href="https://www.amazon.com/dp/B09HFXGQ4N" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
        
        <!-- Product 4 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden product-card transition-transform duration-300">
          <img src="https://m.media-amazon.com/images/I/71YHjVXyJ0L._AC_UL320_.jpg" alt="Headphones" class="w-full h-48 object-contain">
          <div class="p-4">
            <h3 class="font-semibold text-gray-800 mb-1">Sony WH-1000XM4 Wireless Noise Canceling Headphones</h3>
            <div class="flex items-center mb-2">
              <div class="flex text-yellow-400">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
              </div>
              <span class="text-gray-600 text-sm ml-1">(32,109)</span>
            </div>
            <div class="text-lg font-bold text-gray-900 mb-3">$348.00</div>
            <a href="https://www.amazon.com/dp/B0863TXGM3" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-4 rounded-lg transition-colors">
              <i class="fas fa-shopping-cart mr-2"></i> Buy Now
            </a>
          </div>
        </div>
      </div>
    </section>
  </main>

  <!-- Newsletter -->
  <section class="bg-gray-100 py-12">
    <div class="container mx-auto px-4 text-center">
      <h2 class="text-2xl font-bold text-gray-800 mb-4">Get Exclusive Deals</h2>
      <p class="text-gray-600 mb-6 max-w-2xl mx-auto">Subscribe to our newsletter and be the first to know about special offers, new products, and more!</p>
      <div class="flex flex-col sm:flex-row justify-center max-w-md mx-auto">
        <input 
          type="email" 
          placeholder="Your email address" 
          class="flex-grow px-4 py-3 rounded-l-full sm:rounded-r-none rounded-r-full mb-2 sm:mb-0 focus:outline-none"
        >
        <button class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-r-full sm:rounded-l-none rounded-l-full transition-colors">
          Subscribe <i class="fas fa-paper-plane ml-2"></i>
        </button>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-white py-8">
    <div class="container mx-auto px-4">
      <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
        <div>
          <h3 class="text-xl font-bold mb-4">BUY4U</h3>
          <p class="text-gray-400">Your trusted Amazon affiliate store with handpicked products and exclusive deals.</p>
          <div class="flex mt-4 space-x-4">
            <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-facebook-f"></i></a>
            <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-twitter"></i></a>
            <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-instagram"></i></a>
            <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-pinterest"></i></a>
          </div>
        </div>
        <div>
          <h4 class="font-bold mb-4">Shop</h4>
          <ul class="space-y-2">
            <li><a href="#" class="text-gray-400 hover:text-white">Home & Kitchen</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Toys & Games</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Beauty & Selfcare</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Clothing & Shoes</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Electronics</a></li>
          </ul>
        </div>
        <div>
          <h4 class="font-bold mb-4">Help</h4>
          <ul class="space-y-2">
            <li><a href="#" class="text-gray-400 hover:text-white">FAQs</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Shipping Info</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Returns & Exchanges</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Contact Us</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Privacy Policy</a></li>
          </ul>
        </div>
        <div>
          <h4 class="font-bold mb-4">Contact</h4>
          <ul class="space-y-2 text-gray-400">
            <li class="flex items-center"><i class="fas fa-map-marker-alt mr-2"></i> 123 Main St, New York, NY 10001</li>
            <li class="flex items-center"><i class="fas fa-phone-alt mr-2"></i> (123) 456-7890</li>
            <li class="flex items-center"><i class="fas fa-envelope mr-2"></i> info@buy4u.com</li>
          </ul>
        </div>
      </div>
      <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400">
        <p>© 2023 BUY4U. All rights reserved.</p>
        <p class="mt-2 text-sm">BUY4U is a participant in the Amazon Services LLC Associates Program, an affiliate advertising program designed to provide a means for sites to earn advertising fees by advertising and linking to Amazon.com.</p>
      </div>
    </div>
  </footer>

  <!-- Scroll to Top Button -->
  <button id="scrollToTop" class="fixed bottom-6 right-6 bg-blue-600 text-white w-12 h-12 rounded-full flex items-center justify-center shadow-lg scroll-to-top hover:bg-blue-700">
    <i class="fas fa-arrow-up"></i>
  </button>

  <script>
    // Scroll to top button functionality
    const scrollToTopBtn = document.getElementById('scrollToTop');
    
    window.addEventListener('scroll', () => {
      if (window.pageYOffset > 300) {
        scrollToTopBtn.classList.add('opacity-100');
        scrollToTopBtn.classList.remove('opacity-0', 'pointer-events-none');
      } else {
        scrollToTopBtn.classList.add('opacity-0', 'pointer-events-none');
        scrollToTopBtn.classList.remove('opacity-100');
      }
    });
    
    scrollToTopBtn.addEventListener('click', () => {
      window.scrollTo({
        top: 0,
        behavior: 'smooth'
      });
    });
    
    // Smooth scrolling for navigation links
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        
        const targetId = this.getAttribute('href');
        const targetElement = document.querySelector(targetId);
        
        if (targetElement) {
          window.scrollTo({
            top: targetElement.offsetTop - 20,
            behavior: 'smooth'
          });
        }
      });
    });
    
    // Simple search functionality (just logs to console in this example)
    const searchInput = document.querySelector('.search-bar');
    const searchButton = document.querySelector('.search-bar + button');
    
    searchButton.addEventListener('click', () => {
      if (searchInput.value.trim() !== '') {
        console.log('Searching for:', searchInput.value);
        // In a real implementation, you would filter products or make an API call
      }
    });
    
    searchInput.addEventListener('keypress', (e) => {
      if (e.key === 'Enter' && searchInput.value.trim() !== '') {
        console.log('Searching for:', searchInput.value);
        // In a real implementation, you would filter products or make an API call
      }
    });
  </script>
</body>
</html>
