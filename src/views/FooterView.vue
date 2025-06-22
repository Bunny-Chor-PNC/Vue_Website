<template>
    
     <footer class="bg-gray-900 text-white py-6">
  <!-- Promotional Banner -->
  <div class="bg-yellow-500 text-gray-800 p-4 text-center relative overflow-hidden">
    <div class="absolute top-0 left-0 w-full h-2 bg-yellow-600 transform -skew-y-2"></div>
    <div class="absolute bottom-0 right-0 w-20 h-20 bg-yellow-600 rounded-full opacity-50"></div>
    <p class="text-lg font-semibold z-10 relative">Get Free 20% Discount for All Products on Your First Order!</p>
    <div class="mt-2 flex justify-center items-center space-x-2 z-10 relative">
      <input type="email" placeholder="Enter your email" class="p-2 rounded-lg text-black w-1/3">
      <button class="bg-green-500 text-white p-2 rounded-lg hover:bg-green-600 transition-colors duration-300">Submit</button>
    </div>
  </div>

  <!-- Footer Content -->
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-4 gap-8 mt-6">
    <!-- Company Details -->
    <div>
      <h3 class="text-xl font-semibold mb-4 flex items-center">
        <span class="mr-2">🐝</span> Beeberry
      </h3>
      <p class="text-gray-400">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      <div class="flex space-x-2 mt-4">
        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-facebook-f"></i></a>
        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-twitter"></i></a>
        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-instagram"></i></a>
      </div>
    </div>

  
    <div>
      <h3 class="text-xl font-semibold mb-4">Useful Links</h3>
      <ul class="space-y-2">
        <li><a href="#" class="text-gray-400 hover:text-white">Home</a></li>
        <li><a href="#" class="text-gray-400 hover:text-white">Terms & Conditions</a></li>
        <li><a href="#" class="text-gray-400 hover:text-white">Privacy Policy</a></li>
        <li><a href="#" class="text-gray-400 hover:text-white">Contact</a></li>
      </ul>
    </div>

    <!-- Contact Info -->
    <div>
      <h3 class="text-xl font-semibold mb-4">Contact Us</h3>
      <p class="text-gray-400">1234 Washington Ave, Manchester</p>
      <p class="text-gray-400">+1 234-567-890</p>
      <p class="text-gray-400">support@beeberry.com</p>
    </div>

    <!-- Instagram Feed -->
    <div>
      <h3 class="text-xl font-semibold mb-4">Instagram</h3>
      <div class="grid grid-cols-2 gap-2">
        <img src="./assets/insta1.jpg" alt="Instagram 1" class="w-full h-16 object-cover rounded">
        <img src="./assets/insta2.jpg" alt="Instagram 2" class="w-full h-16 object-cover rounded">
        <img src="./assets/insta3.jpg" alt="Instagram 3" class="w-full h-16 object-cover rounded">
        <img src="./assets/insta4.jpg" alt="Instagram 4" class="w-full h-16 object-cover rounded">
      </div>
    </div>
  </div>
</footer>
</template>