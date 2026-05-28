<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <nav class="bg-green-800 text-white sticky top-0 z-50 shadow-md">

    <!-- Navbar Container -->
    <div class="flex items-center justify-between px-8 py-4">

      <!-- Logo + Title -->
      <div class="flex items-center gap-3">
        <img
          src="/src/assets/Images/logo.png"
          alt="Logo"
          class="w-12 h-12 object-cover"
        />

        <h1 class="text-xl font-bold text-yellow-300">
          TEMBERA U RWANDA
        </h1>
      </div>

      <!-- Menu -->
      <ul class="flex gap-8 text-sm font-medium items-center">

        <!-- Home -->
        <li>
          <RouterLink
            to="/"
            class="hover:text-yellow-300 transition"
            active-class="text-yellow-300"
          >
            Home
          </RouterLink>
        </li>

        <!-- About -->
        <li>
          <RouterLink
            to="/about"
            class="hover:text-yellow-300 transition"
            active-class="text-yellow-300"
          >
            About
          </RouterLink>
        </li>

        <!-- Services -->
        <li>
          <RouterLink
            to="/services"
            class="hover:text-yellow-300 transition"
            active-class="text-yellow-300"
          >
            Services
          </RouterLink>
        </li>

        <!-- Gallery Dropdown -->
        <li class="relative group">

          <button
            class="hover:text-yellow-300 transition"
          >
            Gallery ▼
          </button>

          <ul
            class="absolute hidden group-hover:block bg-white text-black rounded-md shadow-lg mt-2 min-w-[180px]"
          >
            <li>
              <RouterLink
                to="/gallery/photos"
                class="block px-4 py-2 hover:bg-green-100"
              >
                Photos
              </RouterLink>
            </li>

            <li>
              <RouterLink
                to="/gallery/videos"
                class="block px-4 py-2 hover:bg-green-100"
              >
                Videos
              </RouterLink>
            </li>
          </ul>

        </li>

        <!-- Destinations Dropdown -->
        <li class="relative group">

          <button
            class="hover:text-yellow-300 transition"
          >
            Destinations ▼
          </button>

          <ul
            class="absolute hidden group-hover:block bg-white text-black rounded-md shadow-lg mt-2 min-w-[200px]"
          >

            <li>
              <RouterLink
                to="/eastern"
                class="block px-4 py-2 hover:bg-green-100"
              >
                Eastern Province
              </RouterLink>
            </li>

            <li>
              <RouterLink
                to="/western"
                class="block px-4 py-2 hover:bg-green-100"
              >
                Western Province
              </RouterLink>
            </li>

            <li>
              <RouterLink
                to="/northern"
                class="block px-4 py-2 hover:bg-green-100"
              >
                Northern Province
              </RouterLink>
            </li>

            <li>
              <RouterLink
                to="/southern"
                class="block px-4 py-2 hover:bg-green-100"
              >
                Southern Province
              </RouterLink>
            </li>

            <li>
              <RouterLink
                to="/kigali"
                class="block px-4 py-2 hover:bg-green-100"
              >
                Kigali City
              </RouterLink>
            </li>

          </ul>

        </li>

        <!-- Contacts -->
        <li>
          <RouterLink
            to="/contacts"
            class="hover:text-yellow-300 transition"
            active-class="text-yellow-300"
          >
            Contacts
          </RouterLink>
        </li>

      </ul>

    </div>

  </nav>
</template>
 