<template lang="pug">
.bio
  .container 
    .row 
      .col-sm-3
        img.img-thumbnail.rounded-circle.border-0( :src="require('@/assets/' + imagelink + '')", alt='logo')
      .col-sm-9.biotext
        p {{ text1 }}
        p {{ text2 }}
        .container 
          .row 
            a.card-link(href="https://github.com/alexberndt")
              | GitHub
            a.card-link(href="https://linkedin.com/in/alexander-berndt/")
                    | LinkedIn
            a.card-link(href="mailto:alberndt@kth.se")
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
