<template>
  <div class="bar">
    <Sidebar />
    <nuxt/>
  </div>
  
</template>

<script>
import Sidebar from '../components/Sidebar.vue'
import addForm from '../pages/add.vue'
export default {
  components: {
    addForm,
  },
}
</script>

<style>
  * {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 1rem;
  line-height: 1.6;
  background: #ffffff;
}
a {
  color: rgb(255, 255, 255);
  text-decoration: none;
}


 /*.bar {
  color: white;
  background-color: aqua;
  float: left;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  bottom: 0;
  padding: 0.5em;
  transition: 0.3s ease;
  display: flex;
  flex-direction: column;
  width: 10%;
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
