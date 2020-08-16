<template>
  <div>
    <b-navbar id="navbar-example2" toggleable="lg">
      <!-- Show this only on mobile & medium screens -->
      <b-navbar-brand href="#index" class="d-lg-none">
        <img src="@/assets/images/locos-white.png" class="my-logo">
      </b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav class="justify-content-center">
        <b-navbar-nav>
          <b-nav-item href="#index">Home</b-nav-item>
          <b-nav-item href="#games">Games</b-nav-item>
        </b-navbar-nav>
        <!-- Show this only on lg screens & bigger -->
        <b-navbar-brand href="#index" class="d-none d-lg-block my-logo-container">
          <img src="@/assets/images/locos-white.png" class="my-logo">
        </b-navbar-brand>

        <b-navbar-nav>
          <b-nav-item href="#about">About Us</b-nav-item>
          <b-nav-item href="#">Policy</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'Header',
  methods: {
  }
}
</script>

<style lang="scss">
.navbar {
  background: #160c28;
  padding: 15px 60px !important;

  @media screen and (max-width: 600px) {
    padding: 0.5rem 1rem !important;
  }

  .nav-item {
    margin: 0px 5px;
  }

  .nav-item > a {
    color: #efcb68 !important;
    font-weight: 500;
  }
  .nav-item > a:hover {
    color: #fbf2da !important;
  }

  .navbar-toggler {
    border-color: rgb(239,203,104) !important;
  } 
  .navbar-toggler-icon {
    background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 32 32' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(239,203,104, 0.5)' stroke-width='3' stroke-linecap='round' stroke-miterlimit='10' d='M4 8h24M4 16h24M4 24h24'/%3E%3C/svg%3E") !important;
  }
}
.my-logo-container {
  margin: 0px 20px;
}
.my-logo {
  // vertical-align: middle;
  width: 150px;
  height: 50px;
}
</style>