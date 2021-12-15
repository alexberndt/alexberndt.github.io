<template>
<div class="project container">
    <a :href="link">
        <div class="card mb-3">
            <div class="row g-0">
                <div class="col-3 hidden-xs" v-if="source_image_1">
                    <img :src="require(`@/assets/images/projects/${source_image_1}`)" class="img-fluid rounded p-1" :alt="name">
                </div>
                <div class="col-3 hidden-sm" v-if="source_image_2">
                    <img :src="require(`@/assets/images/projects/${source_image_2}`)" class="img-fluid rounded p-1" :alt="name">
                </div>
                <div class="col">
                    <div class="card-body">
                            <h5 class="card-title mb-2">{{ name }}</h5>
                            <h6 v-if="link" class="card-subtitle mb-2 text-muted">{{ link }}</h6>
                        <p class="card-text">{{ content }}</p>
                    </div>  
                </div>
            </div>
        </div> 
    </a>
</div>
</template>

<script>

export default {
  name: 'ProjectCard',
  props: {
    name: String,
    link: String,
    content: String,
    source_image_1: String,
    source_image_2: String,
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

a {
    text-decoration: none;
    color: var(--text-regular);
}

a:hover {
    color: var(--text-highlight);
}

@media (max-width: 767px) {
  .hidden-sm {
    display: none !important;
  }
}

@media (max-width: 500px) {
  .hidden-xs {
    display: none !important;
  }
}
</style>
