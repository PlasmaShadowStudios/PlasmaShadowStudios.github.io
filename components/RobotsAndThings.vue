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
    <NuxtImg src="/img/500x500_Thumbnail.png" width="250" height="250" />
    <h1>Robots & Things</h1>
    <p class="description">
      Robots & Things is a 3D collectathon platformer that combines classic
      concepts with new twists like score attack based progression or a meter
      for chaining moves!
    </p>
    <NuxtLink to="https://plasmashadowstudios.github.io/Robots-And-Things">
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
