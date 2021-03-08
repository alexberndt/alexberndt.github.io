<template lang="pug">
.publication
  a.card-link(:href='link')
    div.card.mb-3(img-src='')
      div.card-header
        | Card header
      img.card-img-top(:src="require('@/assets/' + imagelink + '')", :alt='link')
      div.card-body
        .card-title Card title:  {{ title }}
        .card-text
          | card text
          small.card-subtitle.m-3.text-muted {{ conference }}
      div.card-footer
        | Card footer
  //- link.card-link(:href='link')
  //-   card.mb-1(bg-variant="light", text-variant="black", :img-src="imagelink", img-top, style="max-width: 40rem;") 
  //-     card-text.b
  //-       | {{ title }} 
  //-       small.card-subtitle.m-3.text-muted {{ conference }}
      //- b-card-footer          
</template>

<script>
  // import { Component, Prop, Vue } from 'vue-property-decorator';

  // import Vue from 'vue';
  // Vue.component('Publication', {
  //   props: ['title', 'link', 'imagelink', 'conference']
  // })
  export default {
  name: 'Publication',
  props: ['title', 'link', 'imagelink', 'conference']
}

</script>

<style>

</style>
