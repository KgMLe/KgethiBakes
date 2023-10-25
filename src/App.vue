<template>
 <NavBar/>
  <main>
    <router-view/>
  </main>
 <FooTer/>

</template>

<script>
import NavBar from '@/components/NavBar.vue';
import FooTer from './components/FooTer.vue';
export default{
components: {
  NavBar, FooTer
}
}
</script>

<style>
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: auto minmax(100vh, 1fr) auto;
}

#app > *{
    grid-column: 1/-1;
}

/* nav {
  padding: 30px;
} */

</style>
