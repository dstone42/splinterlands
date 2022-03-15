<template>
  <div class="about">
    <h1>What is Splinterlands?</h1>
    <AboutComp/>
  </div>
</template>

<script>
// @ is an alias to /src
import AboutComp from '@/components/AboutComp.vue'

export default {
  name: 'AboutView',
  components: {
    AboutComp
  }
}
</script>