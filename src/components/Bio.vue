<template lang="pug">
.bio
  .container 
    .row 
      .col-md-3
        img.img-thumbnail.rounded-circle.border-1( :src="require('@/assets/' + imagelink + '')", alt='logo')
      .col-md-9.biotext
        p {{ text1 }}
        p {{ text2 }}
        .container 
          .row 
            a.col-md-3.card-link(href="https://github.com/alexberndt")
              | GitHub
            a.col-md-3.card-link(href="https://linkedin.com/in/alexander-berndt/")
                    | LinkedIn
            a.col-md-3.card-link(href="mailto:alberndt@kth.se")
                    | E-mail
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
.biotext {
  text-align: left;
}
</style>
