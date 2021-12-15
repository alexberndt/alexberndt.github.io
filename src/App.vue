<template>
  <VideoHeader msg="Alexander Berndt" id="video-header" />
  <ProfilePicture />
  <SocialMedia class="container social-media"/>
  <Router class="container router"/>
  <router-view class="container content" />
  <Footer msg="© 2021 by Alex Berndt" />
</template>

<script>
import VideoHeader from "@/components/VideoHeader.vue";
import ProfilePicture from "@/components/ProfilePicture.vue";
import SocialMedia from "@/components/SocialMedia.vue";
import Router from "@/components/Router.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "App",
  components: {
    VideoHeader,
    ProfilePicture,
    SocialMedia,
    Router,
    Footer,
  },
  head () {
    return {
      meta: [{
        'og:title': 'alexberndt.com',
        'og:description': 'Bio, experience, projects and other information.'
      }]
    }
  }
};
</script>

<style lang="css">
@import "./assets/styles/variables.css";

#app {
  font-family: 'Roboto Condensed', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  z-index: -1;
}

.content {
  -webkit-overflow-scrolling: touch;
  flex: auto;
  padding-top: 5px;
  padding-bottom: 75px;
}

.container-fluid {
  padding-right: 0;
  padding-left: 0;
  margin-right: auto;
  margin-left: auto;
}
</style>
