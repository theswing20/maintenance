<template>
  <div class="home">
    <h1 class="title">Sorry, the site is <br> undergoing maintenance.</h1>
  </div>
</template>

<script>

export default {
  name: 'Home'

}
</script>

<style>
  .home {
    height: 100%;

    display: flex;
    justify-content: center;
    align-items: center;
  }

  .title {
    font-size: 96px;
    line-height: 112px;
    text-align: center;
    color: #F0F0F0;

    opacity: .8;
  }
</style>
