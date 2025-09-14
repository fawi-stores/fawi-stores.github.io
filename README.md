# storefront-showcase
A responsive small business website for showcasing and advertising products, built with HTML and Tailwind CSS, and hosted on GitHub Pages.
<!DOCTYPE html>
<html lang="en">
<head><!DOCTYPE html>
<html lang="en">
<head><meta name="google-site-verification" content="MPsdWTM4oPVVg5mrnc2FsFYGYAGHx8ryi9yf0hWIx_M" />
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Business Store</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Business Store</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-900">
  <!-- Navbar -->
  <header class="bg-white shadow">
    <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-blue-600">MyStore</h1>
      <nav class="space-x-6">
        <a href="#products" class="hover:text-blue-600">Products</a>
        <a href="#about" class="hover:text-blue-600">About</a>
        <a href="#contact" class="hover:text-blue-600">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="text-center py-20 bg-gradient-to-r from-blue-500 to-indigo-600 text-white">
    <h2 class="text-4xl font-bold mb-4">Welcome to My Business</h2>
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
        <img src="https://via.placeholder.com/300" alt="Product 1" class="w-full h-48 object-cover rounded-md">
        <h4 class="text-xl font-bold mt-4">Product 1</h4>
        <p class="text-gray-600">₦5,000</p>
        <p class="text-sm mt-2">Short description of the product goes here.</p>
        <button class="mt-4 w-full bg-blue-600 text-white py-2 rounded-lg hover:bg-blue-700">Contact to Buy</button>
      </div>

      <div class="bg-white rounded-lg shadow p-4">
        <img src="https://via.placeholder.com/300" alt="Product 2" class="w-full h-48 object-cover rounded-md">
        <h4 class="text-xl font-bold mt-4">Product 2</h4>
        <p class="text-gray-600">₦10,000</p>
        <p class="text-sm mt-2">Another description for product 2.</p>
        <button class="mt-4 w-full bg-blue-600 text-white py-2 rounded-lg hover:bg-blue-700">Contact to Buy</button>
      </div>

      <div class="bg-white rounded-lg shadow p-4">
        <img src=https://tse2.mm.bing.net/th/id/OIP.vG8ZdaJtNoDVA28Gsa-J2QAAAA?r=0&rs=1&pid=ImgDetMain&o=7&rm=3
        <h4 class="text-xl font-bold mt-4">Product 3</h4>
        <p class="text-gray-600">₦15,000</p>
        <p class="text-sm mt-2">Description for product 3 goes here.</p>
        <button class="mt-4 w-full bg-blue-600 text-white py-2 rounded-lg hover:bg-blue-700">Contact to Buy</button>
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
      <form class="space-y-4 max-w-md mx-auto">
        <input type="text" placeholder="Your Name" class="w-full p-3 border rounded-lg" required>
        <input type="email" placeholder="Your Email" class="w-full p-3 border rounded-lg" required>
        <textarea placeholder="Your Message" rows="5" class="w-full p-3 border rounded-lg" required></textarea>
        <button type="submit" class="w-full bg-blue-600 text-white py-3 rounded-lg hover:bg-blue-700">Send</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white text-center py-6 mt-10">
    <p>&copy; 2025 MyStore. Built with ❤️.</p>
  </footer>
</body>
</html>
