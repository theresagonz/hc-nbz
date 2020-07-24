<template>
  <!-- Links (sit on top) -->
  <div class="w3-top">
    <div class="navbar w3-row w3-large w3-dark-grey">
      <div class="nav-item w3-col w3-third">
        <a href="#" class="w3-button w3-block animate">Home</a>
      </div>
      <div class="nav-item w3-col w3-third">
        <a href="#plans" class="w3-button w3-block animate">Plans</a>
      </div>
      <div class="nav-item w3-col w3-third">
        <a href="#aboutus" class="w3-button w3-block animate">About Us</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  props: {
    msg: String,
  },
};
</script>
