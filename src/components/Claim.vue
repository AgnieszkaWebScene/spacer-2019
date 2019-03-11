<template>
  <div class="claimWrapper">
    <h1 class="claim">SPACER</h1>
    <p class="subclaim">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugit, et. Quo officiis molestias, quasi nulla odit vel accusantium debitis culpa.</p>
    <p class="subclaim">Lorem ipsum dolor sit amet.</p>
  </div>
</template>

<script>
  export default {
    name: 'Claim',
  }
</script>

<style lang="scss" scoped>
  .claimWrapper {
    text-align: center;
    display: -webkit-flex;
    display: -ms-flex;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    .claim {
      font-size: 50px;
    }
    .subclaim {
      font-size: 15px;
      margin: 20px 0 0 0;
    }
  }
</style>
