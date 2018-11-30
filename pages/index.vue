<template>
  <section class="container">
    <div>
      <app-logo/>
      <h1 class="title">
        Cyber Cangaço
      </h1>
      <h2 class="subtitle">
        Cyber Cangaço, Digital security research and development group made by cabras da peste
      </h2>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  head () {
    return {
      title: 'Seja invocado! - Cyber Cangaço',
      meta: [
        { hid: 'description', name: 'description', content: 'About our company Nuxt.js ' }
      ]
    }
  },
  components: {
    AppLogo
  }
}

</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

