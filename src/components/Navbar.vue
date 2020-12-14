<template>
<!--Navbar -->
<nav class="mb-1 navbar navbar-expand-lg navbar-dark special-color-dark">
  <a class="navbar-brand navLogo" href="#"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent-4"
    aria-controls="navbarSupportedContent-4" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarSupportedContent-4">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a @click="changeView" class="nav-link" href="#"> <i class=""></i> Home</a>
          <span class="sr-only">(current)</span>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" id="navbarDropdownMenuLink-4" data-toggle="dropdown"
          aria-haspopup="true" aria-expanded="false">
          <i class="fas fa-user"></i> Profile </a>
        <div class="dropdown-menu dropdown-menu-right dropdown-info" aria-labelledby="navbarDropdownMenuLink-4">
          <a class="dropdown-item" href="#">My account</a>
          <a class="dropdown-item" href="#">Log out</a>
        </div>
      </li>
    </ul>
  </div>
</nav>
<!--/.Navbar -->
</template>


<script>
export default {
    name: 'Navbar',
    props: [
      'active',
      'Signup'
      ],
      data() {
        return {
        }
      },
      methods: {
        changeView() {
          this.$emit('change-view', )
        }
      }
}
</script>

<style scoped>

.navLogo{
  background-image: url("../assets/excessit_logo_transparant.png");
  display: flex;
  height: 45px;
  width: 200px;
  background-size: 100%;

}
</style>