<template>
  <div class="social-media">
    <a class="social-media" href="https://www.linkedin.com/in/alexander-berndt/">
      <fa :icon="['fab', 'linkedin']" class="fa-lg"/>
    </a>
    <a class="social-media" href="https://github.com/alexberndt">
      <fa :icon="['fab', 'github']" class="fa-lg"/>
    </a>
    <a class="social-media" href="https://www.instagram.com/berndtalexander/">
      <fa :icon="['fab', 'instagram']" class="fa-lg"/>
    </a>
  </div>
</template>

<script>

export default {
  name: 'SocialMedia'
}
</script>

<style lang="scss">
.social-media {
  color: var(--social-regular);
  background-color: transparent;
  text-decoration: none;
  padding: 5px;
}

.social-media:hover {
  color: var(--social-highlight);
  background-color: transparent;
  text-decoration: underline;
}
</style>