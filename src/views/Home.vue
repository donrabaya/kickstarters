<template>
  <div class="home">
    <!-- Header Block -->
    <div class="parallax filter-gradient blue" uk-parallax="bgy: -200" data-color="blue">
      <div class="">
        <img class="main-bg" src="../assets/images/ks-main-bg.png">
        <div class="uk-overlay uk-overlay-light uk-position-center">
            <h2 class="header">Join Kickstarters PH <i class="far fa-heart" style="color: #ff7675"></i></h2>
            <h5 class="description">Kickstarters is committed to providing year-round values centered sports training for children 2 to 8 years old.</h5>
            <router-link class="nav-item" to="/about">
              <vk-button type="primary">Enroll Now</vk-button>
            </router-link>
        </div>
      </div>
    </div>
    <!-- Choose Team Block -->
    <div>
     <h1>heloo</h1>
     <h1>heloo</h1>
     <h1>heloo</h1>
     <h1>heloo</h1>
     <h1>heloo</h1>
     <h1>heloo</h1>
     <h1>heloo</h1>
     <h1>heloo</h1>
     <h1>heloo</h1>
     <h1>heloo</h1>
     <h1>heloo</h1>
     <h1>heloo</h1>
     <h1>heloo</h1>
     <h1>heloßo</h1>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'home',
  components: {
    HelloWorld,
  },
};
</script>

<style>
  .uk-overlay {
    width: 30vw;
  }
  .uk-position-center {
    z-index: 2;
    left: 69% !important;
    top: 43% !important;
  }
  .header, .description {
    color: white;
    font-weight: bold;
  }
  
  .description {
    margin-top: 0;
  }
</style>

