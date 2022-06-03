<template>
<div class="all">
  <header class="header">
    <h1 class="title">
      Sakae Higashi Fes 2022
    </h1>
  </header>
  <div class="body">
    <div class="main-img">
    </div>
  </div>
</div>
</template>

<script>
</script>

<style>
.all{
  background-color: #E6E5DC;
}
.header{
  position: absolute;
  width: 100%;
  height: min(11vh,11vw);
  background-color: #E6E5DC;
  color: white;
  z-index: 1000;
}
.main-img{
  background: url(~@/assets/school-building.jpg) top center;
  position: fixed;
  width: 100%;
  height: 100vh;
  background-size: cover;
  overflow-y: scroll;
}
</style>
