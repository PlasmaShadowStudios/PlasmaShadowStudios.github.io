<style scoped>
.main {
  @import url("https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@400&display=swap");

  color: white;
  background-color: rgb(0, 0, 37);
  text-align: center;
  font-family: "Josefin Sans", sans-serif;
  font-size: 18px;

}
</style>

<template>
  <div class="main">
    <AppHeader />
    <slot />
    <AppFooter />
  </div>
</template>
