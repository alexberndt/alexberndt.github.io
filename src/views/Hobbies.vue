<template>
  <div class="hibby">
    <h1>Photos</h1>
    <hobby-card 
      name="Cycling"
      content="Photos from some cycling trips."
      srcimg1="IMG_3869.jpg"
      srcimg2="IMG_3797.jpg"
    />
  </div>
</template>

<script>
import HobbyCard from '@/components/HobbyCard.vue'

export default {
  name: 'Hobbies',
  components: {
    "hobby-card": HobbyCard
  }
}
</script>

<style scoped lang="scss">
h1 {
  text-align: center;
  padding: 20px;
}

.hobby {
  text-align: left;
}
</style>