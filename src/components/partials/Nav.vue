<template>
  <nav id="main-nav">
    <div class="container">
      <a id="logo" href=""><i class="fas fa-dumbbell fa-2x"> Gym Buddy</i></a>
      <div class="social">
        <a href="http://facebook.com" target="_blank"><i class="fab fa-facebook fa-2x"></i></a>
        <a href="http://twitter.com" target="_blank"><i class="fab fa-twitter fa-2x"></i></a>
        <a href="http://instagram.com" target="_blank"><i class="fab fa-instagram fa-2x"></i></a>
        <a href="http://youtube.com" target="_blank"><i class="fab fa-youtube fa-2x"></i></a>
      </div>
      <ul>
        <router-link to="/" class="navbar-item">Home</router-link>
        <router-link to="/" class="navbar-item">About</router-link>
      </ul>
        <button>Sign In</button>
    </div>
  </nav>
</template>

<script>
export default {
    name: 'Nav'
}
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  line-height: 1.5;
}

#main-nav #logo {
  display: flex;
  align-items: flex-start;
  margin-left: 1rem;
  text-decoration: none;
  text-shadow: 2px 2px 4px #000000;
  color:whitesmoke;
}

#main-nav ul .navbar-item {
  text-decoration: none;
  padding: 0.75rem;
  text-shadow: 2px 2px 4px #000000;
  color:whitesmoke;
}

#main-nav .container {
  display: grid;
  grid-template-columns: 6fr 3fr 2fr 2fr;
  padding: 1rem;
  align-items: center;
  background-color: #2074c1;
  

}

#main-nav .social {
  justify-self: center;
}

#main-nav .social i {
  color: #777;
  margin-right: .5rem;
  text-shadow: 2px 2px 4px #000000;
}

</style>

