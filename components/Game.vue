<script setup lang="ts">
defineProps<{
  title: string
  description: string
  link?: string
  image: string
}>()
</script>

<style scoped>
.description {
  color: white;
  background-color: rgb(0, 0, 53);
  border: 1px solid rgb(0, 0, 144);
  border-radius: 8px;

  text-align: center;
  padding: 1rem;
  max-width: 80%;
  margin: 30px auto;
}
.container {
  border-radius: 4px;
  max-width: 50%;
  margin: auto;
}

a {
  color: blueviolet;
  border: 1px solid rgb(120, 38, 197);
  background-color: rgb(54, 16, 89);
  border-radius: 8px;
  text-decoration: none;
  padding: 4px;
}
a:hover {
  color: blue;
}

img {
    border-radius: 8px;
}
</style>

<template>
  <div class="container">
    <NuxtImg :src=image width="250" height="250" />
    <h2>{{title}}</h2>
    <p class="description">
      {{ description }}
    </p>
    <NuxtLink v-if=link :to=link>
      Visit Website
    </NuxtLink>
    <br />
    <br />
  </div>
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
</template>
