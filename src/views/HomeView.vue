<script setup>
import TopbarComponent from "@/components/TopbarComponent.vue";
import SliderComponent from "@/components/SliderComponent.vue";
import LatestNewsComponent from "@/components/LatestNewsComponent.vue";
import AppoinmentComponent from "../components/AppoinmentComponent.vue";
</script>

<template>
  <div>
    <TopbarComponent/>

    <div class="hero-section">

      <div class="uk-height-large uk-flex uk-flex-center uk-flex-middle uk-background-cover uk-light"
           data-src="./src/assets/img/bg_image_1.jpg" uk-img>
      </div>

      <div class="container">
        <div class="subhead">
          LET'S MAKE YOUR LIFE HAPPIER
        </div>
        <h1>Healthy Living</h1>
        <button class="uk-button-default login-button uk-border-rounded">Login/Register</button>
      </div>

      <div class="card-container uk-container" uk-flex>

        <div class="uk-card uk-card-default uk-card-body uk-border-rounded">
          <div class="content">
            <div class="circle-shape" style="background-color: var(--blue);">
              <span uk-icon="icon: check"></span>
            </div>
            <p class="uk-margin-small-left">Chat with a doctors</p></div>
        </div>

        <div class="uk-card uk-card-default uk-card-body uk-border-rounded">
          <div class="content">
            <div class="circle-shape" style="background-color: var(--green);">
              <span uk-icon="icon: check"></span>
            </div>
            <p class="uk-margin-small-left">One-Health Protection</p></div>
        </div>

        <div class="uk-card uk-card-default uk-card-body uk-border-rounded">
          <div class="content">
            <div class="circle-shape" style="background-color: var(--pink);">
              <span uk-icon="icon: check"></span>
            </div>
            <p class="uk-margin-small-left">One-Health Pharmacy</p></div>
        </div>
      </div>

      <div class="page-section">
        <div class="container uk-container">
          <div class="uk-width-1-2 welcome">
            <h2>Welcome to Your Health Center</h2>
            <p>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore
              et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
              Accusantium aperiam earum ipsa eius, inventore nemo labore eaque porro consequatur ex aspernatur.
              Explicabo, excepturi accusantium! Placeat voluptates esse ut optio facilis!</p>
            <button class="uk-button-default login-button uk-border-rounded">Learn More</button>
          </div>
          <div class="uk-width-1-2 img">
            <img src="src/assets/img/bg-doctor.png" alt="" style=" max-width: 25rem;">
            <div class="background"></div>
          </div>
        </div>
      </div>
    </div>

    <SliderComponent />

    <LatestNewsComponent />

    <AppoinmentComponent />
  </div>



</template>

<style scoped>
.uk-background-cover {
  filter: brightness(50%);
}

.hero-section h1 {
  filter: brightness(100%) !important;
}

.hero-section .container {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: #fff;
  text-align: center;
}

.hero-section .container h1 {
  color: #fff;
}

.container button {
  background-color: var(--green);
  color: #fff;
  position: relative;
  padding: 0.8rem 1.5rem;
  font-size: 14px;
  border: 1px solid var(--green);
}

.card-container {
  position: absolute;
  margin: -3rem;
  display: flex;
  left: 50%;
  transform: translateX(-50%);
  width: 80%;
  justify-content: space-between;
}

.circle-shape {
  width: 2.5rem;
  height: 2.5rem;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  text-align: center;
}

.content {
  display: flex;
  align-items: center;
}

.uk-card-default .circle-shape {
  color: #fff;
}

.card-container p {
  font-weight: bolder;
}

.page-section {
  position: absolute;
  background-color: var(--light);
  width: 100vw;
  height: 100vh;
  z-index: -1;
}

.page-section .container {
  position: relative;
  margin-top: 6rem;
  display: flex;
  align-items: center;
}

.page-section .welcome {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.page-section .container p {
  color: var(--grey);
  text-align: left;
}

@media (max-width: 1120px) {
  .card-container {
    flex-direction: column;
    align-items: center;
  }

  .uk-card {
    margin-bottom: 2rem;
    width: 70%;
  }

  .page-section .container {
    margin-top: 14rem;
    flex-direction: column;
  }

  .page-section .container .uk-width-1-2.img {
    width: 100%;
    max-width: 400px;
  }

  .page-section .container .uk-width-1-2 img {
    position: absolute;
    transform: translateX(-50%);
    left: 50%;
  }

  .page-section .container .uk-width-1-2.img .background {
    position: absolute;
    top: 16rem;
    bottom: 6rem;
    left: 0;
    width: 100%;
    height: 72vh;
    background: var(--light);
    z-index: -1;
  }

  .page-section .welcome {
    width: 80%;
  }

  .page-section .container img {
    width: 20rem;
  }

}
</style>
