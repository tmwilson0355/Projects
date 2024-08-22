<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header>
    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/products">Products</RouterLink>
      <RouterLink to="">Contact Us</RouterLink>
    </nav>
  </header>
  <main>
    <!-- Vue router gives us a couple of HTMl elements/tags that make routing easier -->
     <!-- one of these if the router-view tag -> this tag tells vue-router where to render the content for the new page. -->
      <router-view></router-view>
  </main>
  <footer>

  </footer>

</template>

<style scoped>

header, footer {
  height: 100px;
  background-color: lightpink;
}

main {
  height: 750px;
}

a {
  margin: 16px;
}

</style>
