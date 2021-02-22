<template lang="pug">
.bio
  img.img-thumbnail.rounded-circle.border-1(:src='imagelink', alt='logo')
  p {{ text1 }}
  p {{ text2 }}
</template>

<script>
export default {
  name: 'Project',
  props: ['imagelink', 'text1', 'text2']
}
</script>

<style scoped>

.img-thumbnail {
  max-height: 150px;
  margin: 0px;
}
</style>
