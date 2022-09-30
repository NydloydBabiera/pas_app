<template>
 <header class="header">
  <h1>TITLE</h1>
    <!-- <div class="links"> -->
       <nuxt-link to="/">Home</nuxt-link>
       <nuxt-link to="/add">ADD</nuxt-link>
       <nuxt-link to="/data">DATA</nuxt-link>
    <!-- </div> -->
 </header>
</template>

<script>
export default {
  name: 'Sidebar',
}
</script>

<style>
.header {
  color: white;
  background-color: #23395d;
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
  /* width: 10%; */
}
body {
  position: relative;
  overflow-x: hidden;
  background-color: #fafbfc;
  /* font-family: Arial, Helvetica, sans-serif;
  font-size: 1rem;
  line-height: 1.6;
  background: #f4f4f4; */
}
/* a stands for design of the link in main page; this css removes the underline in link */
a {
  color: #fafbfc;
  text-decoration: none;
}
/* .header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 1rem;
  padding-bottom: 1rem;
  border-bottom: 1px dotted #ccc;
}

.header .title {
  font-size: 3rem;
  color: #526488;
}

.header ul {
  display: flex;
}

.header a {
  display: inline-block;
  background: #333;
  color: #fff;
  padding: 0.3rem 1rem;
  margin-right: 0.5rem;
} */
</style>    