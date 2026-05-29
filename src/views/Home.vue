```vue
<script setup>
import heroImage from '@/assets/Images/tembera.jpeg'
import gorilla from '@/assets/Images/gorilla.jpg'
import lake from '@/assets/Images/lakekivu.jpg'
import convention from '@/assets/Images/convention.jpg'
</script>

<template>
  <!-- Hero Section -->
  <section
    class="relative h-screen bg-cover bg-center flex items-center justify-center text-white"
    :style="{ backgroundImage: `url(${heroImage})` }"
  >
    <!-- Overlay -->
    <div class="absolute inset-0 bg-black/60"></div>

    <!-- Content -->
    <div class="relative text-center px-6 max-w-4xl">
      <h1 class="text-6xl font-extrabold mb-5">
        Explore Beautiful Rwanda
      </h1>

      <p class="text-xl text-green-200 mb-6 leading-8">
        Welcome to the Land of a Thousand Hills.
        Discover breathtaking landscapes, wildlife,
        culture, and unforgettable tourism experiences.
      </p>

      <button
        class="bg-green-700 hover:bg-green-800 px-8 py-3 rounded-lg text-lg font-semibold transition"
      >
        Visit Rwanda
      </button>
    </div>
  </section>

  <!-- Welcome Section -->
  <section class="py-14 px-8 bg-green-50 text-center">
    <h2 class="text-4xl font-bold text-green-800 mb-4">
      Discover Rwanda
    </h2>

    <p class="max-w-3xl mx-auto text-lg text-gray-700 leading-8">
      Rwanda offers unique experiences including gorilla trekking,
      beautiful lakes, modern infrastructure, rich culture,
      and warm hospitality for every visitor.
    </p>
  </section>

  <!-- Tourist Attractions -->
  <section class="py-14 px-8 bg-white">
    <h2 class="text-4xl font-bold text-center text-green-800 mb-10">
      Top Attractions
    </h2>

    <div class="grid md:grid-cols-3 gap-8">

      <!-- Gorilla -->
      <div class="bg-white rounded-xl shadow-lg overflow-hidden hover:scale-105 transition duration-300">
        <img
          :src="gorilla"
          alt="Gorilla"
          class="w-full h-56 object-cover"
        />

        <div class="p-5 text-center">
          <h3 class="text-2xl font-bold text-green-700 mb-2">
            Gorilla Trekking
          </h3>

          <p class="text-gray-600">
            Visit Volcanoes National Park and experience
            Rwanda’s mountain gorillas.
          </p>
        </div>
      </div>

      <!-- Lake Kivu -->
      <div class="bg-white rounded-xl shadow-lg overflow-hidden hover:scale-105 transition duration-300">
        <img
          :src="lake"
          alt="Lake Kivu"
          class="w-full h-56 object-cover"
        />

        <div class="p-5 text-center">
          <h3 class="text-2xl font-bold text-green-700 mb-2">
            Lake Kivu
          </h3>

          <p class="text-gray-600">
            Enjoy relaxing beaches, fresh air,
            and amazing lakeside views.
          </p>
        </div>
      </div>

      <!-- Kigali Convention Center -->
      <div class="bg-white rounded-xl shadow-lg overflow-hidden hover:scale-105 transition duration-300">
        <img
          :src="convention"
          alt="Kigali Convention Centre"
          class="w-full h-56 object-cover"
        />

        <div class="p-5 text-center">
          <h3 class="text-2xl font-bold text-green-700 mb-2">
            Kigali Convention Centre
          </h3>

          <p class="text-gray-600">
            Explore Rwanda’s modern landmark
            and beautiful Kigali city views.
          </p>
        </div>
      </div>

    </div>
  </section>
</template>

