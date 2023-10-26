<script setup>

</script>

<template>
  <div class="banner">
    <div class="container  uk-flex">
      <img class="img" src="src/assets/img/mobile_app.png" alt="Cell Phone">

      <div class="uk-margin-medium-left">
        <div class="text">
          Get easy access of all features using One Health Application
        </div>
        <div class="uk-flex images">
          <img class="img" src="src/assets/img/google_play.svg" alt="Google Play">
          <img class="img" src="src/assets/img/app_store.svg" alt="Apple Store">
        </div>
      </div>

    </div>
  </div>
</template>

<style scoped>
.banner {
  background-color: var(--green);
  background-image: url("src/assets/img/banner-pattern.svg");
}

.container {
  margin: 0 auto;
  display: flex;
  align-items: center;
  width: 70%;
}

.banner img {
  width: 200px;
  height: 300px;
  align-self: end;
}

.text {
  margin-top: 5rem;
  color: #fff;
  font-size: 2.5rem;
}

.banner .images {
  margin-top: -6rem;
  padding: 0;
}

img.img:hover {
   cursor: pointer;
}

@media (max-width: 1120px) {
  .container {
    flex-direction: column;
    padding-top: 4rem;
    width: 80%;
    align-content: center;
  }

  .img {
    display: none;
  }
}
</style>