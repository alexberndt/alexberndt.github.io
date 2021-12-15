<template>
  <div class="profile container">
      <img src="@/assets/square.jpg" alt="Profile Picture" id="profilepicture">
  </div>
</template>

<script>

export default {
  name: 'ProfilePicture',
  props: {
    msg: String
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.profile {
    position: relative;
    top: -100px;
}
#profilepicture {
    width: 200px;
    height: 200px;
    object-fit:cover;
    border-radius: 50%;
    border: 8px solid rgb(255, 255, 255);
    z-index: 1000;
}
</style>
