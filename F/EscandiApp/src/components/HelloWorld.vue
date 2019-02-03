<template>
  <div>
    <nav class="navbar is-primary is-bold" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="https://pornhub.com">
      <img src="https://upload.wikimedia.org/wikipedia/commons/f/f1/Pornhub-logo.svg" alt="Bulma: Free, open source, & modern CSS framework based on Flexbox" width="112" height="28">
    </a>

    <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
    <a class="navbar-item">
           Home
      </a>
      <a class="navbar-item">
           Contanto
      </a>
      <a class="navbar-item">
           Sound
      </a>
  </div>
</nav>

<section class="hero  is-primary">
  <div class="hero-body">
    <div class="container">
      <h1 class="title">
        Alejandro Escandon
      </h1>
      <h2 class="subtitle">
        Master developer
      </h2>
    </div>
  </div>
</section>
  <info/>
</div>

</template>

<script>
import info from './info'
export default {
  name: 'HelloWorld',
  components: {
  info
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
