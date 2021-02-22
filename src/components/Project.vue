<template lang="pug">
.project
  a.card-link(:href='link')
    .card.mb-3( :title="title")
      img.card-img-top(:src='imagelink', :alt='link')
      .card-text
        span {{ description }}
        small(class='card-subtitle m-3 text-muted') {{ link }}
</template>

<script>
export default {
  name: 'Project',
  props: ['title', 'link', 'imagelink', 'description']
}
</script>

<style scoped>
</style>
