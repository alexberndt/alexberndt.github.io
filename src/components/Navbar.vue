<template lang="pug">
nav#nav.navbar.navbar-expand-lg.navbar-light.bg-light
  a.navbar-brand(href='#') Alexander Berndt
  button.navbar-toggler(type='button' data-toggle='collapse' data-target='#navbarNav' aria-controls='navbarNav' aria-expanded='false' aria-label='Toggle navigation')
    span.navbar-toggler-icon
  #navbarNav.collapse.navbar-collapse
    ul.navbar-nav
      li.nav-item.active
        a.nav-link(href='#')
          | Home 
          span.sr-only (current)
      li.nav-item
        a.nav-link(href='#bio') Bio
      li.nav-item
        a.nav-link(href='#publications') Publications
      li.nav-item
        a.nav-link(href='#projects') Projects
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #nav{
    margin: 0px
  }
</style>
