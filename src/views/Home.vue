<template>
  <div class="home">
    <p>
      I am a machine learning engineer at 
        <a href="https://dashmote.com/ai-labs/">Dashmote B.V.</a> 
      where I work on solving a wide variety of data-related problems.
      My main focus is on designing, implementing and orchestrating 
      machine learning pipelines. This not only involves ensuring we 
      use the best ML models, theoretically, but ensuring these pipelines
      are scalable and efficient in production.
    </p>
    <h4>Education</h4>
    <p>
      I obtained my Masters degree in Systems & Control at the 
      <a href="https://www.tudelft.nl/3me/over/afdelingen/delft-center-for-systems-and-control">Delft Center for Systems and Control</a>
       of <a href="https://www.tudelft.nl/en/">TU Delft</a>, 
        the Netherlands.
      My master's thesis was supported by the 
      <a href="https://www.bosch-ai.com/">Robert Bosch Research Campus</a> in Renningen, Germany, 
      involved the development of a 
      <a href="https://repository.tudelft.nl/islandora/object/uuid%3Ad70c13ac-a992-4408-a7db-30033eec987d"> novel real-time optimization scheme</a>
       to re-order autonomous guided vehicles 
       (AGVs) in collaborative warehouses.
    </p>
    <p>I also spent 9 months at the 
      <a href="https://www.kth.se/en">KTH Royal Institute of Technology</a>
      in Stockholm, Sweden, as a PhD student under the supervision of 
      <a href="https://people.kth.se/~hsan/">Henrik Sandberg</a>
      and 
      <a href="https://people.kth.se/~kallej/">Karl Henrik Johansson</a>
      as part of the 
      <a href="https://www.kth.se/is/dcs/">Division of Decisions and Control Systems</a>.
      My research focus was on 
      <a href="https://www.youtube.com/watch?v=oulLR06lj_E">data-driven control policies</a>
      applied to 
      <a href="https://ptolemy.berkeley.edu/projects/cps/">cyber-physical systems</a>,
      after which I ended up pursuing a career in industry.
    </p>
    <h4>Interests</h4>
    <p>I am a generally curious person and interested in a wide variety of topics.
      In my current role as a machine learning engineer, I am particularly interested in
    </p>
    <ul>
      <li>Productization of ML-based pipelines,</li>
      <li>Designing and optimizing data-driven processes,</li>
      <li>Interfacing business value and algorithm optimization functions.</li>
    </ul>
    <p>Other non-work related interests include</p>
    <ul>
      <li>Full-stack web development,</li>
      <li>A casual chess game,</li>
      <li>Playing the piano.</li>
    </ul>
  </div>
</template>

<script>

export default {
  name: 'Home'
}
</script>

<style scoped lang="scss">
.home {
  text-align: left;
}
h1 {
  text-align: center
}
.container {
  max-width: 768px;
  margin: auto;
  overflow: auto;
  padding: 20px 10px;
}
a {
  text-decoration: none;
  color: var(--text-navbar);
}
a.hover {
  color: var(--text-highlight);
}
</style>
