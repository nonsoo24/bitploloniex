<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view/>
  </div>
</template>

<style>
@font-face {
    font-family: "helvetica-neue-cyr-black";
    src: url("/assets/fonts/HelveticaNeueCyr-Black.otf") format("woff"),
        url("/assets/fonts/HelveticaNeueCyr-Black.otf") format("opentype"),
        url("/assets/fonts/HelveticaNeueCyr-Black.otf") format("truetype");
}

@font-face {
    font-family: "helvetica-neue-cyr-bold";
    src: url("/assets/fonts/HelveticaNeueCyr-Bold.otf") format("woff"),
        url("/assets/fonts/HelveticaNeueCyr-Bold.otf") format("opentype"),
        url("/assets/fonts/HelveticaNeueCyr-Bold.otf") format("truetype");
}
#app {
  font-family: 'helvetica-neue-cyr-bold', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
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
  color: #42b983;
}

html, body {
    max-width: 100%;
    overflow-x: hidden;
}
</style>
