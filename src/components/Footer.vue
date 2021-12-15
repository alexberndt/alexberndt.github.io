<template>
  <div class="container-fluid">
    <div class="container">
      <social-media/>
      <p>{{ msg }}</p>
    </div>
  </div>
</template>

<script>
import SocialMedia from '@/components/SocialMedia.vue'

export default {
  name: 'Footer',
  props: {
    msg: String,
  },
  components: {
    "social-media": SocialMedia
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
div {
  color: var(--footer-color-text);
  background-color: var(--footer-color-background);
}

p {
  padding-top: 35px;
  padding-bottom: 15px;
}

.container {
  padding: 25px;
}
</style>

<style lang="scss">
.social-media {
  color: var(--footer-regular);
  background-color: transparent;
  text-decoration: none;
  padding: 5px;
}

.social-media:hover {
  color: var(--footer-highlight);
  background-color: transparent;
  text-decoration: underline;
}
</style>