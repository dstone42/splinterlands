<template>
  <div class="hello">
    <h1>Sample Cards</h1>
    <div class="cards" v-for="card in cards" :key="card.id">
        <h3>{{card.name}}</h3>
        <ul>
          <li>Total Printed: {{card.total_printed}}</li>
          <li>Color: {{card.color}}</li>
          <li>Type: {{card.type}}</li>
        </ul>
    </div>
  </div>
</template>

<script>
    export default {
      name: 'CardsComp',
      props: {
        cards: Array
      }
    }
</script>

<style>
  ul {
    list-style-type: none;
  }
</style>