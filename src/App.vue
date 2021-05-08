<template>
  <div id="app">
    <Header />
    <div class="flex items-center justify-center my-5 ml-auto mr-auto Line justify-items-center"></div>
    <SubHeader />
    <Content1 />
    <Jobshowcase />
    <Content2 />
    <Step />
    <Content3 />
    <Showcase />
    <Mapshow />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import SubHeader from './components/SubHeader.vue'
import Content1 from './components/Content1.vue'
import Content2 from './components/Content2.vue'
import Content3 from './components/Content3.vue'
import Footer from './components/Footer.vue'
import Jobshowcase from './components/Jobshowcase.vue'
import Step from './components/Step.vue'
import Showcase from './components/Showcase.vue'
import Mapshow from './components/Mapshow.vue'
export default {
  name: 'App',
  components: {
    Header,
    SubHeader,
    Content1,
    Content2,
    Content3,
    Footer,
    Jobshowcase,
    Step,
    Showcase,
    Mapshow
  }
}
</script>

<style>
.bg-form {
  background-color: #151922;
}

.step1 {
  background-image: url("./assets/bgstep1.png");
  background-repeat: no-repeat;
  background-size: 100%;
}

.step2 {
    background-image: url("./assets/bgstep2.png");
  background-repeat: no-repeat;
  background-size: 100%;
}

.step3 {
    background-image: url("./assets/bgstep3.png");
  background-repeat: no-repeat;
  background-size: 100%;
}

.job1 {
  background-image: url("./assets/job1.png");
  background-repeat: no-repeat;
  background-size: 100%;
}

.job2 {
  background-image: url("./assets/job2.png");
  background-repeat: no-repeat;
  background-size: 100%;
}

.job3 {
  background-image: url("./assets/job3.png");
  background-repeat: no-repeat;
  background-size: 100%;
}

.job4 {
  background-image: url("./assets/job4.png");
  background-repeat: no-repeat;
  background-size: 100%;
}

.job5 {
  background-image: url("./assets/job5.png");
  background-repeat: no-repeat;
  background-size: 100%;
}

footer {
  background-color: #05050f;
}

input[type="text"]
{
    background: transparent;
}

* {
    outline: none !important;
    box-shadow: none !important;
}

.cont2 {
  background-image: url("./assets/bgcont2.png");
  background-repeat: no-repeat;
  background-size: 100%;
}

.cont1 {
  background-image: url("./assets/bgcont1.png");
  background-repeat: no-repeat;
  background-size: 100%;
}
body {
  background-image: url("./assets/bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}
.Line {
  width: 1800px;
  height: 2px;
  background: gray;
}
#app {
  
}
</style>
