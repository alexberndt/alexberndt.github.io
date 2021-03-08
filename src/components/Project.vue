<template lang="pug">
.project
  a.card-link(:href='link')
    .container 
      .row 
        .col-sm-3( :title='title')
            img.card-img( :src="require('@/assets/' + imagelink + '')", :alt='link')
        .col-sm-9
          .card-text
            span {{ description }} 
            span {{ imagelink }} 

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
