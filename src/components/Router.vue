<template>
  <div class="router">
    <div id="nav">
      <router-link to="/">Bio</router-link> -
      <!-- <router-link to="/about">About</router-link> - -->
      <router-link to="/experience">Experience</router-link> - 
      <router-link to="/projects">Projects</router-link> -
      <router-link to="/hobbies">Photos</router-link>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Router'
}
</script>

<style scoped lang="scss">
#nav {
  top: -105px;
  position: relative;
  a {
    font-weight: bold;
    color: var(--text-navbar); 
    &.router-link-exact-active {
      color: var(--text-navbar-highlight); 
    }
    text-decoration: none;
  }
}
</style>