<template lang="pug">
.project
  a.card-link(:href='link')
    .container.mb-3 
      .card 
        .card-body
          .row 
            .col-sm-3( :title='title')
                img.card-img( :src="require('@/assets/' + imagelink + '')", :alt='link')
            .col-sm-9
              .card-title {{ title }}
              .card-text
                span {{ description }} 
</template>

<script>
export default {
  name: 'Project',
  props: ['title', 'link', 'imagelink', 'description']
}
</script>

<style scoped>
.project{
  text-decoration: none;
}
.card-title{
  text-align: left;
  text-decoration-color: black;
  color: black;
  text-decoration: none !important;
}
.card-text{
  text-align: left;
}
</style>
