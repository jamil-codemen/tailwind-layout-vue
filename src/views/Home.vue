<template>
  <div class="home">
    <Hero />
  </div>
</template>

<script>
// @ is an alias to /src
import Hero from '@/components/Home/Hero.vue'

export default {
  name: 'Home',
  components: {
    Hero
  }
}
</script>
