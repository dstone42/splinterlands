<template>
  <div class="card">
    <CardsComp :cards="cards"/>
  </div>
</template>

<script>
// @ is an alias to /src
import CardsComp from '@/components/CardsComp.vue'

export default {
  name: 'CardsView',
  components: {
    CardsComp
  },
  data() {
    return {
      cards: this.$root.$data.cards
    }
  }
}
</script>