<script setup>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="min-h-full">
    <div class="bg-gray800">
      <Navbar></Navbar>

      <!-- <header>
        <div class="mx-auto max-w-7xl py-4 px-4 sm:px-6 lg:px-8">
          <h1 class="text-3xl font-bold tracking-tight leading-6 text-gray-900">
            Dashboard
          </h1>
        </div>
      </header> -->

      <video playsinline loop autoplay muted class="w-full">
        <source src="./assets/movie.mp4" type="video/mp4" />
        Your browser does not support the video tag.
      </video>
    </div>

    <main class="bg-gray-800">
      <div class="mx-auto max-w-7xl py-6 sm:px-6 lg:px-8">
        <!-- Replace with your content -->
        <!-- <div class="px-4 py-4 sm:px-0">
          <video playsinline loop autoplay muted class="w-full rounded-lg">
            <source src="./assets/movie.mp4" type="video/mp4" />
            Your browser does not support the video tag.
          </video>
        </div> -->

        <!-- /End replace -->
      </div>
    </main>
  </div>

  <Footer></Footer>
</template>
