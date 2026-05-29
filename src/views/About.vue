```vue
<script setup>
import aboutImage from '@/assets/Images/about-rwanda.jpg'
</script>

<template>
  <!-- About Hero Section -->
  <section
    class="relative h-screen bg-cover bg-center flex items-center justify-center text-white"
    :style="{ backgroundImage: `url(${aboutImage})` }"
  >
    <!-- Dark Overlay -->
    <div class="absolute inset-0 bg-black/60"></div>

    <!-- Content -->
    <div class="relative text-center px-6 max-w-3xl">
      <h1 class="text-5xl font-bold mb-4">
        ABOUT THE LAND OF A THOUSAND HILLS
      </h1>

      <p class="text-xl text-green-200">
        Discover Rwanda, the Land of a Thousand Hills,
        rich culture, wildlife, and beautiful landscapes.
      </p>
    </div>
  </section>

  <!-- About Content -->
  <section class="py-14 px-8 bg-green-50 text-center">
    <h2 class="text-4xl font-bold text-green-800 mb-4">
      Why Visit Rwanda?
    </h2>

    <p class="text-gray-700 max-w-3xl mx-auto text-lg leading-8">
      Rwanda is one of Africa’s most beautiful destinations,
      famous for mountain gorillas, clean cities, national parks,
      Lake Kivu, breathtaking hills, and warm hospitality.
      Visitors enjoy nature, adventure, culture, and unforgettable experiences.
    </p>
  </section>

  <!-- Mission & Vision -->
  <section class="py-14 px-8 bg-white">
    <h2 class="text-4xl font-bold text-center text-green-800 mb-10">
      Our Mission & Vision
    </h2>

    <div class="grid md:grid-cols-2 gap-8 max-w-5xl mx-auto">
      
      <!-- Mission -->
      <div class="bg-green-100 p-8 rounded-xl shadow-lg">
        <h3 class="text-2xl font-bold text-green-800 mb-4">
          Our Mission
        </h3>

        <p class="text-gray-700 text-lg">
          To promote Rwanda as a top tourist destination by
          showcasing its natural beauty, wildlife, culture,
          and unique tourism experiences.
        </p>
      </div>

      <!-- Vision -->
      <div class="bg-green-100 p-8 rounded-xl shadow-lg">
        <h3 class="text-2xl font-bold text-green-800 mb-4">
          Our Vision
        </h3>

        <p class="text-gray-700 text-lg">
          To make Rwanda one of the leading tourism destinations
          in Africa where visitors enjoy safe, memorable,
          and inspiring travel experiences.
        </p>
      </div>

    </div>
  </section>
</template>

