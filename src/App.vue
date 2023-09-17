<script setup>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="min-h-full">
    <div class="bg-gray-800 pb-32">
      <Navbar></Navbar>

      <header class="py-10">
        <!-- <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
          <h1 class="text-3xl font-bold tracking-tight text-white">Dashboard</h1>
        </div> -->
      </header>
    </div>

    <main class="-mt-32">
      <div class="mx-auto max-w-7xl px-4 pb-12 sm:px-6 lg:px-8">
        <!-- Replace with your content -->
        <div class="rounded-lg bg-white px-5 py-6 shadow sm:px-6">
          <div class="rounded-lg border-4 border-dashed border-gray-200">
            <video loop autoplay muted class="h-fit rounded-lg">
              <source src="./assets/movie.mp4" type="video/mp4" />
              Your browser does not support the video tag.
            </video>
          </div>
        </div>
        <!-- /End replace -->
      </div>
    </main>
  </div>

  <Footer></Footer>
</template>
