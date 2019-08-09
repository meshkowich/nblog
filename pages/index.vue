<template>
  <div class="container">
    <!-- <div> 
      <logo />
      <h1 class="title">
        nblog
      </h1>
      
      <h2 class="subtitle">
        front of nblog
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey"
        >
          GitHub
        </a>
      </div>
    </div>-->
    <parallax/>
    <!-- <trash/> -->
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Parallax from '~/components/parallax.vue'
// import Trash from '~/components/trash.vue'

export default {
  components: {
    Logo,
    Parallax
    // Trash
  }  
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
}
</style>
