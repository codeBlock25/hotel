<template>
  <section>
    <Navigation />
    <Home />
  </section>
</template>

<script>
import './index.css'
import Home from "./view/home"
import Navigation from "./components/nav-bar"

export default {
  name: 'App',
  components: {
    Home,
    Navigation,
  }
}
</script>

<style>
</style>
