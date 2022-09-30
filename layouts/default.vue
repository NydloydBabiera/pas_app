<template>
  <div class="bar">
    <div class="container"><Sidebar /></div>
  </div>
</template>

<script>
import Sidebar from '../components/Sidebar.vue'
export default {
  components: {
    Sidebar,
  },
}
</script>

<style>
  .bar {
    background-color: aqua;
    width: 25%;
    height: 100%;
  }
/*  {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  position: relative;
  overflow-x: hidden;
  background-color: #cfd8dc;
  /* font-family: Arial, Helvetica, sans-serif;
  font-size: 1rem;
  line-height: 1.6;
  background: #f4f4f4; 
}

/* a stands for design of the link in main page; this css removes the underline in link */
 /*a {
  color: rgb(255, 13, 13);
  text-decoration: none;
}

ul {
  list-style: none;
}

.container {
  width: 25%;
  position: ;
  /* max-width: 800px;
  margin: 2rem auto;
  overflow: hidden;
  padding: 1rem 2rem; 
  background: rgb(253, 0, 0); 
} */
</style>
