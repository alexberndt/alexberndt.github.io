<template>
<div class="hobby container">
    <div class="card mb-3">
        <div class="row g-0">

            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3878.jpg" class="img-fluid rounded p-1" alt="name">
            </div>
            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3884.jpg" class="img-fluid rounded p-1" alt="name">
            </div>
            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3888.jpg" class="img-fluid rounded p-1" alt="name">
            </div>


            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3917.jpg" class="img-fluid rounded p-1" alt="name">
            </div>
            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3939.jpg" class="img-fluid rounded p-1" alt="name">
            </div>
            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3966.jpg" class="img-fluid rounded p-1" alt="name">
            </div>

            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3869.jpg" class="img-fluid rounded p-1" alt="name">
            </div>
            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3697.jpg" class="img-fluid rounded p-1" alt="name">
            </div>
            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3747.jpg" class="img-fluid rounded p-1" alt="name">
            </div>

            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3789.jpg" class="img-fluid rounded p-1" alt="name">
            </div>
            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3797.jpg" class="img-fluid rounded p-1" alt="name">
            </div>
            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3687.jpg" class="img-fluid rounded p-1" alt="name">
            </div>

            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3495.jpg" class="img-fluid rounded p-1" alt="name">
            </div>
            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3419.jpg" class="img-fluid rounded p-1" alt="name">
            </div>
            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3438.jpg" class="img-fluid rounded p-1" alt="name">
            </div>

            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3501.jpg" class="img-fluid rounded p-1" alt="name">
            </div>
            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3505.jpg" class="img-fluid rounded p-1" alt="name">
            </div>
            <div class="col-md-4" v-if="srcimg1">
                <img src="@/assets/images/photos/IMG_3549.jpg" class="img-fluid rounded p-1" alt="name">
            </div>


            

        </div>
    </div> 
</div>
</template>

<script>

export default {
  name: 'HobbyCard',
  props: {
    name: String,
    content: String,
    srcimg1: String,
    srcimg2: String,
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
// .card {
//     max-width: 800px;
// }
</style>
