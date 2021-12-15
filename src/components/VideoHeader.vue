<template>
    <video-background 
        :src="require(`@/assets/beach_red.mp4`)"
        :poster="require(`@/assets/static.jpg`)"
        style="max-height: 300px; height: 100vh;"
        overlay="linear-gradient(90deg,#00000050,#00000050)"
        id="video" 
        class="container">
        <h1 id="heading">{{ msg }}</h1>
    </video-background>
</template>

<script>
import VideoBackground from 'vue-responsive-video-background-player'

export default {
  name: 'VideoHeader',
  props: {
    msg: String
  },
  components: {
    "video-background": VideoBackground
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container {
    max-width: 100%;
    padding: 0px;
}

#heading {
    color: rgb(223, 223, 223);
    padding-top: 110px;
}

#profilepicture {
    width: 200px;
    height: 200px;
    top: 30px;
    object-fit:cover;
    border-radius: 50%;
    border: 8px solid rgb(214, 214, 214);
}
</style>
