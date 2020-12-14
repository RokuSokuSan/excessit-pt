<template>
  <div>
    <navbar :active="active"/>
    <splash />
    <app-footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Splash from './components/Splash'
import appFooter from './components/Footer'


export default {
  name: 'App',
  components: {
    Navbar,
    Splash,
    appFooter,

  },
  data() {
    return {
    active: true
    }
  }
}
</script>

<style>

</style>
