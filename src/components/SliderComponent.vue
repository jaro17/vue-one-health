<script setup>

</script>

<template>

  <div class="uk-slider-container-offset slider" uk-slider>

    <h2>Our Doctors</h2>

    <div class="uk-position-relative uk-visible-toggle uk-light" tabindex="-1">

      <ul class="uk-slider-items uk-grid" style="width: 300px">
        <li>
          <div class="uk-card uk-card-default">
            <div class="uk-card-media-top">
              <img src="src/assets/img/doctors/doctor_1.jpg" width="300" height="260" alt="">
            </div>
            <div class="uk-card-body">
              <h3 class="uk-card-title">Dr. Stein Albert</h3>
              <p>Cardiology</p>
            </div>
          </div>
        </li>
        <li>
          <div class="uk-card uk-card-default">
            <div class="uk-card-media-top">
              <img src="src/assets/img/doctors/doctor_2.jpg" width="300" height="260" alt="">
            </div>
            <div class="uk-card-body">
              <h3 class="uk-card-title">Dr. Alexa Melvin</h3>
              <p>Dental</p>
            </div>
          </div>
        </li>
        <li>
          <div class="uk-card uk-card-default">
            <div class="uk-card-media-top">
              <img src="src/assets/img/doctors/doctor_3.jpg" width="300" height="260" alt="">
            </div>
            <div class="uk-card-body">
              <h3 class="uk-card-title">Dr. Rebecca Steffany</h3>
              <p>General Health</p>
            </div>
          </div>
        </li>
        <li>
          <div class="uk-card uk-card-default">
            <div class="uk-card-media-top">
              <img src="src/assets/img/doctors/doctor_3.jpg" width="300" height="260" alt="">
            </div>
            <div class="uk-card-body">
              <h3 class="uk-card-title">Dr. Rebecca Steffany</h3>
              <p>General Health</p>
            </div>
          </div>
        </li>
        <li>
          <div class="uk-card uk-card-default">
            <div class="uk-card-media-top">
              <img src="src/assets/img/doctors/doctor_3.jpg" width="300" height="260" alt="">
            </div>
            <div class="uk-card-body">
              <h3 class="uk-card-title">Dr. Rebecca Steffany</h3>
              <p>General Health</p>
            </div>
          </div>
        </li>
        <li>
          <div class="uk-card uk-card-default">
            <div class="uk-card-media-top">
              <img src="src/assets/img/doctors/doctor_3.jpg" width="300" height="260" alt="">
            </div>
            <div class="uk-card-body">
              <h3 class="uk-card-title">Dr. Rebecca Steffany</h3>
              <p>General Health</p>
            </div>
          </div>
        </li>
      </ul>

      <a class="uk-position-center-left uk-position-small uk-hidden-hover" href uk-slidenav-previous
         uk-slider-item="previous"></a>
      <a class="uk-position-center-right uk-position-small uk-hidden-hover" href uk-slidenav-next
         uk-slider-item="next"></a>

    </div>

    <ul class="uk-slider-nav uk-dotnav uk-flex-center uk-margin"></ul>

  </div>

</template>

<style scoped>
.slider {
  position: relative;
  margin-top: 53rem;
}

.slider h2 {
  text-align: center;
  font-size: 2.5rem;
  margin-bottom: 3rem;
}

.slider li {
  margin: 0 4rem;
}

@media (max-width: 1120px) {
  .slider {
    margin-top: 80rem;
  }
}
</style>