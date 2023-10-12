<script setup>
import Home from './components/Home.vue';
import Sidebar from './components/Sidebar.vue';
</script>

<template>
  <header class="bg-black border-b-light-100 border-b h-20 text-white items-center flex p-5 text-2xl">A Wonderful Blog</header>
  <section class="flex">
    <aside class="w-[450px] bg-black ">
      <Sidebar/>
    </aside>
    <main class="w-full min-h-screen p-5">
      <Home/>
    </main>
  </section>
  <footer></footer>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
