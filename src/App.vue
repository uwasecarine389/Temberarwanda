<script setup>
import logo from './assets/logo.png'
</script>

<template>
  <div class="bg-blue-50 min-h-screen flex flex-col items-center justify-center p-6">

    <!-- Logo -->
    <img
      :src="logo"
      alt="School Logo"
      class="w-24 h-24 rounded-full mb-4"
    />

    <!-- Description -->
    <h1 class="text-3xl font-bold text-blue-600 text-center mb-3">
      SOS Technical High School
    </h1>

    <p class="text-gray-700 text-center max-w-2xl">
      SOS Technical High School is a well-established Technical and 
      Vocational Education and Training (TVET) and Ordinary-Level (O'Level)
      boarding school located in the Kagugu suburb of Kigali, Rwanda. 
      The school is committed to helping students achieve academic excellence, 
      discipline, creativity, and personal growth.
    </p>

  </div>
</template>