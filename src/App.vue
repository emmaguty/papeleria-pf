<template>
  <div id="app">
    <div id="navbar-container">
      <div id="navbar-content">
        <router-link to="/">
          <i class='bx bx-home-alt-2 bx-sm'></i>
        </router-link>
        <router-link to="/carrito">
          <i class='bx bxs-store bx-sm'></i>
        </router-link>
        <router-link to="/favoritos">
          <i class='bx bxs-heart-circle bx-sm'></i>
        </router-link>
        <router-link to="/historial">
          <i class='bx bx-history bx-sm' ></i>
        </router-link>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Tillana&display=swap');

*{
  margin: 0px;
  padding: 0px;
}

#navbar-container{
  width: 100%;
  position: fixed;
  bottom: 0;

}

#navbar-content{
 display:flex;
 justify-content: space-between; 
 padding: 20px;
}

#navbar-content a{
  color: #f3a8c2;
}

#navbar-content a.router-link-exact-active{
  color: #fa34df;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #f3a8c2;
}
</style>
