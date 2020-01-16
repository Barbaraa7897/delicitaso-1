<template>
  <div id="app">
   
      <!--ovdje idu poveznice koje smo napravili u router folderu -> index.js fileu -->
      <router-link to="/"></router-link> 
      <router-link to="/about"></router-link> 
      <router-link to="/login"></router-link>
 
    <router-view/>
  </div>
</template>
<script>
  
</script>

<style lang="scss">
/*ovdje se pise CSS kod, unutar <style lang="scss"> taga
  *nothing*(ime taga) { css kod }
  .(naziv klase taga) { css kod }
  #(id taga) { css kod }
*/
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
