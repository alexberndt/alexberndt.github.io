<template lang="pug">
.footer
  .container.text-center
    span Copyright © {{ new Date().getFullYear() }}
</template>

<script>
export default {
  name: 'Footer',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  .footer {
    font-size: small;
    background-color: #fff;
    color: #aaa;
    padding: 15px;
  }
</style>
