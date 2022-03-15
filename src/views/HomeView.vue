<template>
  <div class="home">
    <img alt="Splinterlands logo" src="../assets/splinterlands_logo.png">
    <HelloWorld msg="Splinterlands Information"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
