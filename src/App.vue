<template>
  <div id="app">
    <header>
      <img class = "logo" src="./assets/logo.png">
    </header>
      <subreddits category ="technology"></subreddits>
      <subreddits category ="space"></subreddits>
      <subreddits category ="art"></subreddits>
      <subreddits category ="sports"></subreddits>
      <subreddits category ="food"></subreddits>
  </div>
</template>

<script>
import Subreddits from './components/Subreddits'

export default {
  name: 'App',
  components: {
    Subreddits
  }
}
</script>

<style>
body {
  font-family:Arial, Helvetica, sans-serif;
  color: #555555;
  background: #f4f4f4;
  margin: 0;
  padding: 0;
}

a {
  text-decoration: none;
}

header {
  background: coral;
  color: #ffffff;
  padding: 10px;
  text-align: center;
}

.logo {
    width: auto;
    height: 3.7rem;
    margin-top: 0.3rem;
}
</style>
