<template>
  <div id="app">
    <div class="nav-top" uk-sticky="animation: uk-animation-slide-top; sel-target: .uk-navbar-container; cls-active: uk-navbar-sticky; cls-inactive: uk-navbar-transparent uk-dark; top: 200">
        <vk-navbar class="uk-navbar-transparent">
          <vk-navbar-nav>
              <img class="ks-logo margin-left" alt="Kickstarters Logo" src="../src/assets/images/ks.png">
          </vk-navbar-nav>
          <vk-navbar-nav class="margin-top-bottom margin-right" slot="right">
            <router-link class="nav-item" to="/"><p>Home</p></router-link> 
            <router-link class="nav-item" to="/about"><p>Teams</p></router-link>
            <router-link class="nav-item" to="/about"><p>Locations</p></router-link>
            <router-link class="nav-item" to="/about"><p>Coaches</p></router-link>
            <router-link class="nav-item" to="/about"><p>About Us</p></router-link>
            <router-link class="nav-item" to="/about">
              <vk-button type="primary">Enroll Now</vk-button>
            </router-link>
          </vk-navbar-nav>
        </vk-navbar>
      </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
  @import '../src/assets/css/style.css';

  .nav-top {
    position: absolute;
    z-index: 10;
    width: 100%;
  }

  .uk-navbar-container:not(.uk-navbar-transparent) {
    background: #0e2e50 !important;
  }

  .margin-top-bottom {
    margin-bottom: 25px !important;
    margin-top: 25px !important;
  }

  .margin-left {
    margin-left: 150px !important;
  }

  .margin-right {
    margin-right: 150px !important;
  }
</style>

