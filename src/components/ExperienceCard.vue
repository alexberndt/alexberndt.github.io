<template>
<div class="experience container">
    <div class="row g-0">

        <div class="col-md-3">
             <div id="verticle-line" class="d-flex flex-column justify-content-center align-items-center">
                 <span class="badge bg-secondary">{{ date }}</span>   
             </div>
        </div>

        <div class="col-md card mb-3">
            <div class="row g-0">
                <!-- <a data-toggle="collapse" href="#collapseExample" role="button" aria-expanded="false" aria-controls="collapseExample"> -->
                    <div class="card-body">
                        <h5 class="card-title mb-2">{{ role }}</h5>
                        <div class="text-muted font-italic">
                            <small class="card-subtitle left">{{ company }}</small>
                            <small class="card-subtitle right">{{ location }}</small>
                        </div>
                        <div class="mt-1">
                            <small class="card-text">{{ content }}</small>
                        </div>
                    </div> 
                <!-- </a> -->
            </div>
        </div>

    </div> 
</div>
</template>

<script>

export default {
  name: 'ExperienceCard',
  props: {
    role: String,
    company: String,
    date: String,
    location: String,
    content: String,
    id: String,
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
img {
  object-fit: cover;
  width: 100%;
  height: 100%;
}

.flex-column {
    padding: 5px;
}

.left {
    width: 49%;
    display: inline-block;
}

.right {
    width: 50%;
    text-align: right;
    display: inline-block;
}

#verticle-line {
  margin-right: 20px;
  min-height: 100%;
  vertical-align: middle;
  border-right: thick solid var(--text-regular);
}
</style>
