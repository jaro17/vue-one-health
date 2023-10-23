<script setup>

</script>

<template>
  <footer>
    <div class="uk-container ">
      <div class="columns">
        <div class="column">
          <h4>Company</h4>
          <p>About Us</p>
          <p>Career</p>
          <p>Editorial Team</p>
          <p>Protection</p>
        </div>

        <div class="column">
          <h4>More</h4>
          <p>Terms & Condition</p>
          <p>Privacy</p>
          <p>Advertise</p>
          <p>Join as Doctors</p>
        </div>

        <div class="column">
          <h4>Our Partner</h4>
          <p>One-Fitness</p>
          <p>One-Drugs</p>
          <p>One-Live</p>
        </div>

        <div class="column">
          <h4>Contact</h4>
          <p>351 Willow Street Franklin, MA 02038</p>
          <p>701-573-7582</p>
          <p>healthcare@temporary.net</p>
          <p></p>
        </div>
      </div>

      <div class="social-media">
        <h4>Social Media</h4>
        <div class="icons-container">
          <span class="icon" uk-icon="icon: facebook"></span>
          <span class="icon" uk-icon="icon: twitter"></span>
          <span class="icon" uk-icon="icon: google"></span>
          <span class="icon" uk-icon="icon: instagram"></span>
          <span class="icon" uk-icon="icon: linkedin"></span>
        </div>

      </div>
      <hr>
      <div class="uk-flex uk-flex-between">
        <p class="copyright" style="color: #fff">Copyright © 2022 All right reserved</p>
        <a href="#" uk-totop uk-scroll class="top"></a>
      </div>
    </div>
  </footer>
</template>

<style scoped>
footer {
  background-color: var(--black);
}

.uk-container {
  margin: 0 auto;
  padding-top: 5rem;
  padding-bottom: 3rem;
  display: flex;
  flex-direction: column;
}

.columns {
  display: flex;
  justify-content: space-between;
  width: 100%;
}

h4 {
  color: #fff;
}

p {
  color: rgba(255, 255, 255, 0.6);
}

p:hover {
  color: #fff;
  transition: all 0.2s ease-in-out;
  cursor: pointer;
}

.social-media {
  align-self: end;
}

.icon {
  color: #fff;
  background-color: #26312F;
  padding: 0.5rem;
  border-radius: 50%;
  margin-right: 0.3rem;
}

.icon:hover {
  background-color: var(--green);
  cursor: pointer;
}

.top {
  background-color: var(--light);
  border-radius: 50%;
  width: 30px;
  height: 30px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.top:hover {
  background-color: var(--green);
}

.copyright {
  cursor: default !important;
}

@media (max-width: 1120px) {

}
</style>