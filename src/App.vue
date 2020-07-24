<template>
  <div id="app">
    <Navbar />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';

export default {
  name: 'App',
  components: {
    Navbar,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}
body {
  -webkit-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  background-color: #333;

}
a {
  color: white;
}
hr {
  box-shadow: 0.1em 0.1em #000;
}
.animate {
  -webkit-transition: all 0.2s ease-out;
  -moz-transition: all 0.2s ease-out;
  -ms-transition: all 0.2s ease-out;
  -o-transition: all 0.2s ease-out;
  transition: all 0.2s ease-out;
}
.active {
  color: lime;
  opacity: 1 !important;
}
.text {
  float: left;
  padding: 0em 1em 0em 1em;
  text-align: justify;
  color: white;
  text-shadow: 0.2em 0.2em 0.1em #000;
}
#findPlayer {
  width: 100%;
  float: left;
  color: white;
  text-shadow: 0.2em 0.2em 0.1em #000;
}
#findPlayer span {
  margin-left: 0.5em;
  opacity: 0.5;
  font-weight: bold;
}
#findPlayer input {
  max-width: 10em;
  height: 2em;
  border-radius: 0.2em;
}
#tester {
  position: fixed;
  bottom: 1em;
  right: 1em;
  background: #000;
  color: green;
  font-weight: bold;
  width: 20em;
  height: 6em;
}
</style>
