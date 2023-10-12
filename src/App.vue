<script setup>
</script>

<template>
  <header class="bg-black border-b-light-100 border-b h-20 text-white items-center flex p-5 text-2xl">A Wonderful Blog</header>
  <section class="flex">
    <aside class="w-[450px] bg-black ">
      <section class="mt-[40px] text-white p-5">
        <ul class="flex flex-col space-y-5">
          <li>Home</li>
          <li>About</li>
          <li>Contact</li>
          <li>Blog</li>
        </ul>
      </section>
    </aside>
    <main class="w-full min-h-screen p-5">
      <article class="mb-10">
        <h1 class="text-xl mb-2">Hello World Post</h1>
        <p>
          <img src="https://source.unsplash.com/random/300x200?1" alt="">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempore, esse id. Dolorum delectus quas eos dolores amet cupiditate sed fugiat, facere quisquam deserunt suscipit culpa animi neque, modi inventore officiis omnis nam.
        </p>
      </article>
      <article class="mb-10">
        <h1 class="text-xl mb-2">Hello World Post</h1>
        <p>
          <img src="https://source.unsplash.com/random/300x200?2" alt="">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempore, esse id. Dolorum delectus quas eos dolores amet cupiditate sed fugiat, facere quisquam deserunt suscipit culpa animi neque, modi inventore officiis omnis nam.
        </p>
      </article>
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
