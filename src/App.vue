<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: black;
}

nav a.router-link-exact-active {
  color: rgb(236, 132, 205);
}
body {
  background: rgb(211, 19, 211);
}
/* responsive query start */
@media (max-width: 1104px) {
  .home .max-width {
    margin-left: 0px;
  }
}

@media (max-width: 991px) {
  .max-width {
    padding: 0 50px;
  }
}

@media (max-width: 947px) {
  .container {
    display: block;
    z-index: 999;
  }

  .navbar .menu {
    position: fixed;
    height: 100vh;
    width: 100%;
    left: -100%;
    top: 0;
    background: rgb(252, 48, 252);

    text-align: center;
    padding-top: 80px;
    transition: all 0.3s ease;
  }

  .navbar .menu li a:hover {
    color: #000;
  }

  .navbar .menu.active {
    left: 0;
  }

  .navbar .menu li {
    display: block;
  }

  .navbar .menu li a {
    display: inline-block;
    margin: 20px 0;
    font-size: 25px;
  }

  .home .home-content .text-2 {
    font-size: 70px;
  }

  .home .home-content .text-3 {
    font-size: 35px;
  }

  .home .home-content a {
    font-size: 23px;
    padding: 10px 30px;
  }
}

@media (max-width: 690px) {
  .max-width {
    padding: 0 23px;
  }

  .home .home-content .text-2 {
    font-size: 60px;
  }

  .home .home-content .text-3 {
    font-size: 32px;
  }

  .home .home-content a {
    font-size: 20px;
    padding: 9px 25px;
  }
}

@media (max-width: 500px) {
  .home .home-content .text-2 {
    font-size: 50px;
  }

  .home .home-content .text-3 {
    font-size: 27px;
  }
}
</style>
