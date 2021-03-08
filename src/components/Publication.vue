<template lang="pug">
.publication
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
                span {{ authors }} 
              .conferences
                small {{ conference }}          
</template>

<script>
  export default {
  name: 'Publication',
  props: ['title', 'link', 'imagelink', 'conference', 'authors']
}

</script>

<style>
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
  /* color: rgb(77, 77, 77); */
}
.conferences{
  text-align: left;
  color: grey;
}
</style>
