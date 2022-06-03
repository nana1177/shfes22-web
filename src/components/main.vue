<template>
<div class="all">
  <header class="header">
    <h1 class="title">
      Sakae Higashi Fes 2022
    </h1>
  </header>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header{
  position: absolute;
  width: 100%;
  height: min(3vh,3vw);
  color: black;
}
</style>
