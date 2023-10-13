<script setup>

</script>

<template>
  <div class="banner">
    <div class="container uk-container-small">
      <div class="">
        <img src="src/assets/img/mobile_app.png" alt="Cell Phone">
      </div>
      <div class="">
        <h2 class="text uk-width-1-1">
          Get easy access of all features using One Health Application
        </h2>
        <div class="uk-flex images">
          <img src="src/assets/img/google_play.svg" alt="Google Play">
          <img src="src/assets/img/app_store.svg" alt="Apple Store">
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.banner {
  background-color: var(--green);
  background-image: url("src/assets/img/banner-pattern.svg");
 /* background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  width: 100%;
  height: 40vh;*/
}

.container {
  margin: 0 auto;
  display: flex;
  align-items: center;

}

.banner img {
  width: 200px;
  height: 300px;
}

.banner .text {
  margin-top: 5rem;
  color: #fff;
}

.banner .images {
  margin-top: -4rem;
}

@media (max-width: 1120px) {
  .uk-container-large {
    flex-direction: column;
    padding-top: 4rem;
    width: 80%;
    align-content: center;
  }
}
</style>