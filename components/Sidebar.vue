<template>
  <div class="header">
    <h1>TITLE</h1>
    <ul>
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/add">ADD</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/data">DATA</nuxt-link>
      </li>
    </ul>
    <!-- <div class="links"> -->

    <!-- </div> -->
  </div>
</template>

<script>
export default {
  name: 'Sidebar',
}
</script>

<style>
.header{
  color: white;
  background-color: rgb(1, 45, 83);
  float:left;
  position: fixed;
  display: flex;
  flex-direction: column;
  z-index: 1;
  top: 0;
  bottom: 0;
  padding: 0.5em;
}
</style>
