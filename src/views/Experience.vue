<template>
  <div class="experience">


        <experience-card 
          company="Dashmote B.V." 
          role="Machine Learning Engineer" 
          location="Amsterdam, The Netherlands"
          date="May 2021 - present"
          content="Designing and implementing various ML-pipeline 
                    components. This includes python-based 
                    algorithm design using scikit-learn, PyTorch and DVC; 
                    productization using Docker, Amazon Web Services and Jenkins;
                    and improving the dataset creation process 
                    using FastAPI, Vue.js and Terraform."
          id="1"
        />
        <experience-card 
          company="KTH Royal Institute of Technology" 
          role="Thesis Supervisor on Reinforcement Learning" 
          location="Stockholm, Sweden"
          date="Nov 2020 - Apr 2021"
          content="Supervised the final-year thesis of Joel Kärn
                    on the topic of reinforcement learning and data-driven
                    control of an inverse pendulum in Python using PyTorch,
                    Open AI Gym."
          id="2"
        />
        <experience-card 
          company="TOPdesk Nederland B.V." 
          role="Software Developer" 
          location="Delft, The Netherlands"
          date="Jun 2018 - Sep 2018"
          content="Undertook full-stack web development projects
                    including the design, development and continuous 
                    integration and deployment of a citizen incident alert 
                    app using Docker, Jenkins for CI/CD, Javascript, Vue.js."
          id="3"
        />
        <experience-card 
          company="Vehicle Dynamics Group" 
          role="Algorithms Software Engineer" 
          location="Pretoria, South Africa"
          date="Jan 2016 - Aug 2017"
          content="Designed, developed and validated software to perform
                    collision avoidance for heavy-duty mining vehicles with support
                    from the Mine Health and Safety Council of South Africa.
                    Specifically focused on implementing a Differential GPS-based 
                    collision avoidance scheme using C++, Simulink and dSPACE."
          id="4"
        />
        <experience-card 
          role="Mechatronics and Software Engineer" 
          company="Agile Drones Lab @ MIT" 
          location="Cambridge, USA"
          date="May 2015 - Dec 2015"
          content="Designed and built systems using embedded C, 
                    Python, the Robot Operating System (ROS) and Linux
                    to validate novel algorithms for quadrotors 
                    performing aggressive, agile maneuvers using 
                    only stereo vision, i.e., without motion-capture 
                    based state knowledge."
          id="5"
        />
        

  </div>
</template>

<script>
import ExperienceCard from '@/components/ExperienceCard.vue'

export default {
  name: 'Experience',
  components: {
    "experience-card": ExperienceCard
  }
}
</script>

<style scoped lang="scss">
h4 {
  text-align: center;
  padding: 20px;
}

.experience {
  text-align: left;
}

.container {
  max-width: 768px;
  margin: auto;
  overflow: auto;
}
</style>
