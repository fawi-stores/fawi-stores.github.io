# storefront-showcase
A responsive small business website for showcasing and advertising products, built with HTML and Tailwind CSS, and hosted on GitHub Pages.
<!DOCTYPE html>
<html lang="en">
<head><!DOCTYPE html>
<html lang="en">
<head><meta name="google-site-verification" content="MPsdWTM4oPVVg5mrnc2FsFYGYAGHx8ryi9yf0hWIx_M" />
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Fawi Stores</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Fawi Stores</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-900">
  <!-- Navbar -->
  <header class="bg-white shadow">
    <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-blue-600">Fawi Stores</h1>
      <nav class="space-x-6">
        <a href="#products" class="hover:text-blue-600">Products</a>
        <a href="#about" class="hover:text-blue-600">About</a>
        <a href="#contact" class="hover:text-blue-600">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="text-center py-20 bg-gradient-to-r from-blue-500 to-indigo-600 text-white">
    <h2 class="text-4xl font-bold mb-4">Welcome to Fawi Stores </h2>
    <p class="mb-6">Discover our latest products at affordable prices 🚀</p>
    <a href="#products" class="bg-white text-blue-600 font-semibold px-6 py-3 rounded-lg shadow hover:bg-gray-100">
      Shop Now
    </a>
  </section>

  <!-- Products -->
  <section id="products" class="max-w-6xl mx-auto py-16 px-4">
    <h3 class="text-3xl font-bold mb-8 text-center">Our Products</h3>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8">
      
      <!-- Product Card -->
      <div class="bg-white rounded-lg shadow p-4">
        <img src=https://ng.jumia.is/unsafe/fit-in/680x680/filters:fill(white)/product/41/6269404/1.jpg?5647
        <h4 class="text-xl font-bold mt-4">Product 1</h4>
        <p class="text-gray-600">₦5,000</p>
        <p class="text-sm mt-2">Short description of the product goes here.</p>
        <a href="tel:+2348133224424" class="mt-4 w-full block text-center bg-blue-600 text-white py-2 rounded-lg hover:bg-blue-700">
  Contact to Buy
</a>
      </div>

      <div class="bg-white rounded-lg shadow p-4">
        <img src="https://via.placeholder.com/300" alt="Product 2" class="w-full h-48 object-cover rounded-md">
        <h4 class="text-xl font-bold mt-4">Product 2</h4>
        <p class="text-gray-600">₦10,000</p>
        <p class="text-sm mt-2">Another description for product 2.</p>
      <a href="tel:+2348133224424" class="mt-4 w-full block text-center bg-blue-600 text-white py-2 rounded-lg hover:bg-blue-700">
  Contact to Buy
</a>

      </div>

     <!-- Product Card with Lightbox -->
<!-- Product Card with Lightbox -->
<!-- Product Card with Lightbox -->
<div class="bg-white rounded-lg shadow p-4">
  <!-- Product Image -->
  <img src="https://raw.githubusercontent.com/fawi-stores/fawi-stores.github.io/refs/heads/main/Shop%20by%20category%20(1).png" 
       alt="TiLECC A9 Pro" 
       class="w-full object-contain rounded-md cursor-pointer" 
       onclick="openLightbox(this.src)">

  <!-- Product Name -->
  <h4 class="text-xl font-bold mt-4">TiLECC A9 Pro</h4>

  <!-- Price -->
  <p class="text-gray-600">₦15,000</p>

  <!-- Product Description -->
  <p class="text-sm mt-2">
    TiLECC A9 Pro Wireless Bluetooth Headsets LED Touchscreen Earphones Noise Cancelling Earplugs.
  </p>

  <!-- WhatsApp Button -->
  <a href="https://wa.me/2348133224424" target="_blank" 
     class="mt-4 w-full block text-center bg-green-600 text-white py-2 rounded-lg hover:bg-green-700">
    Contact on WhatsApp
  </a>
</div>

<!-- Lightbox (opens when image is clicked) -->
<div id="lightbox" class="fixed inset-0 bg-black bg-opacity-80 flex items-center justify-center hidden">
  <span class="absolute top-5 right-8 text-white text-3xl cursor-pointer" onclick="closeLightbox()">&times;</span>
  <img id="lightbox-img" class="max-w-screen max-h-screen rounded-lg shadow-lg">
</div>

<script>
  function openLightbox(src) {
    document.getElementById("lightbox-img").src = src;
    document.getElementById("lightbox").classList.remove("hidden");
  }
  function closeLightbox() {
    document.getElementById("lightbox").classList.add("hidden");
  }
</script>




      </div>

    </div>
  </section>

  <!-- About -->
  <section id="about" class="max-w-4xl mx-auto py-16 px-4 text-center">
    <h3 class="text-3xl font-bold mb-6">About Us</h3>
    <p class="text-lg text-gray-700 leading-relaxed">
      We are a small business dedicated to providing quality products at affordable prices. 
      Customer satisfaction is our top priority.
    </p>
  </section>

  <!-- Contact -->
  <section id="contact" class="bg-white py-16 shadow-inner">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <h3 class="text-3xl font-bold mb-6">Contact Us</h3>
      <p class="mb-6">Reach us via phone: <strong>+234 8133224424</strong> or email: <strong>fawiboyoo@email.com</strong></p>
     <iframe src="https://docs.google.com/forms/d/e/1FAIpQLScnH2lQK-ivOoh1gFVvm-A0koa2xOwNVW6Ys0pKwp-b9uuDnA/viewform?embedded=true" width="640" height="863" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white text-center py-6 mt-10">
    <p>&copy; 2025 MyStore. Built with ❤️.</p>
  </footer>
</body>
</html>
