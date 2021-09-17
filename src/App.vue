<template>
  <div id="app">
    <nav id ="nav" class="navbar">
      
        
      <a class="navbar-brand" href="#">
        <img src="@/assets/logo.webp" 
        height="40"
        class="d-inline-block align-top"
        loadings ="lazy"
        /> 

     
      </a>
        <h1>Coachera</h1>
     
      <router-link to="/signup" style=" color:black" >Get Started</router-link>
      
    </nav>

    <div class="container">
      <router-view/>
    </div>
  
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  background-color: white !important;

  a {
    font-size: 20px;
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
