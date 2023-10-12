<script setup>

</script>
 
<template>
    <section class="mt-[40px] text-white p-5">
        <ul class="flex flex-col space-y-5">
            <li>
                <!-- <router-link to="/">Home</router-link> -->
                <router-link :to="{name:'home'}">Home</router-link>
            </li>
            <li>
                <!-- <RouterLink to="/about">About</RouterLink> -->
                <!-- <router-link to="/about">About</router-link> -->
                <router-link :to="{name:'about'}">About</router-link>
            </li>
            <li>
                <!-- <router-link to="/contact">Contact</router-link> -->
                <router-link :to="{name:'contact'}">Contact</router-link>
            </li>
            <li>
                <!-- <router-link to="/blog">Blog</router-link> -->
                <router-link :to="{name:'blog'}">Blog</router-link>
            </li>
        </ul>
    </section>
</template>
 
<style scoped></style>