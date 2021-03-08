<template lang="pug">
.home
  #bio.container.section
    .container
      h4 Bio
    Bio(
      imagelink="square.jpg",
      text1="Alexander Berndt is a dedicated and passionate doctoral student at KTH Royal Institute of Technology in Stockholm.",
      text2="His research interests include machine learning applied to critical infrastructure, discrete optimization, multi-agent path planning, vehicle routing and scheduling and networked control."
    )

  #publications.container.section
    .container
      h4 Publications
    //- Publication(
    //-   title="A Feedback Scheme to Reorder a Multi-Agent Execution Schedule by Persistently Optimizing a Switchable Action Dependency Graph",
    //-   link="https://arxiv.org/pdf/2010.05254.pdf",
    //-   conference="ICAPS 2020 Nancy, France"
    //- ) 
    //- Publication(
    //-   title="Investigating Different Vehicle Velocity Estimators and an Adaptive Kalman Filter for Anti-Lock Braking Systems for Off-Road Vehicles",
    //-   link="./pages/p/Berndt_Penny_Els_ISTVS2017.pdf",
    //-   conference="ISTVS 2017 Budapest, Hungary",
    //-   imagelink="src/assets/alexander-berndt.jpg"
    //- )

  #projects.container.section
    Project(
      title="ISS Tracker",
      link="https://iss-tracker.tk",
      description="Real-time tracking of the International Space Station",
      imagelink="img/isstracker.jpg"
    ) 
    Project(
      title="Inverse Flying Pendulum Model Predictive Control",
      link="./f/pendulum-quad-mpc.pdf",
      description="A model predictive control design and stability analysis for an inverted pendulum balanced on a quadrotor",
      imagelink="img/quadrotor.jpg"
    ) 
    Project(
      title="Handwritten Digits Classification",
      link="./f/nist-classification.pdf",
      description="Pattern recognition project on the analysis of machine learning algorithms to classify handwritten numbers",
      imagelink="img/nist-ml.png"
    )
    Project(
      title="Smartphone Indoor Localization",
      link="./f/phone-sensing.pdf",
      description="Smartphone-based localization using bayesian classification and the particle filter utilizing WiFi access point signal strength and IMU measurements",
      imagelink="img/sps-project.png"
    )
    Project(
      title="Mechanical Gimbal Design for Action Camera",
      link="./f/mox-design.pdf",
      description="Detailed mechanical gimbal design and dampening validation for an action camera",
      imagelink="img/mox-drawing.png"
    )
    Project(
      title="HiL Simulation for off-road ABS brakes",
      link="./f/thesis-BEng.pdf",
      description="Bachelor thesis on the implementation of a Hardware-in-the-Loop setup for off-road ABS algorithm validation",
      imagelink="img/hil.png"
    )
</template>

<script>
// import Vue from 'vue';
// // import Project from '@/components/Project.vue';
import Publication from "@/components/Publication.vue";
import Project from "@/components/Project.vue";
import Bio from "@/components/Bio.vue";

export default {
  components: {
    Bio,
    Publication,
    Project,
  },
};
</script>

<style>
.section {
  padding-top: 100px;
  padding-bottom: 50px;
}
</style>
