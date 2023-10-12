<script setup>

</script>

<template>
  <div class="top-bar">
    <div class="uk-container uk-flex uk-flex-between">
      <div class="site-info">
        <span class="icon uk-margin-small-right" href="" uk-icon="icon: receiver"></span>
        <a class="numbers uk-margin-small-right uk-link-reset uk-text-small">+00 123 4455 6666</a> |
        <span class="icon uk-margin-small-right uk-margin-small-left" href="" uk-icon="icon: mail"></span>
        <a class="numbers uk-link-reset uk-text-small">mail@example.com</a>
      </div>
      <div class="social-buttons">
        <a href="" class="icon" uk-icon="icon: facebook"></a>
        <a href="" class="icon" uk-icon="icon: twitter"></a>
        <a href="" class="icon" uk-icon="icon: dribbble"></a>
        <a href="" class="icon" uk-icon="icon: instagram"></a>
      </div>
    </div>
  </div>
  <hr>
  <div class="uk-navbar-container uk-navbar-transparent">
    <div class="uk-container">
      <div uk-navbar>
        <div class="uk-navbar-left">
          <a class="uk-navbar-item uk-logo uk-text-bold "><span :style="{ color: 'var(--green)' }">One</span>-Health</a>
          <div class="uk-inline">
            <a class="uk-form-icon" href="#" uk-icon="icon: search" :style="{ color: 'var(--green)' }"></a>
            <input class="uk-input" type="text" aria-label="Clickable icon">
          </div>
        </div>
        <div class="uk-navbar-right">
          <ul class="navbar uk-navbar-nav uk-flex uk-flex-middle">
            <li><a href="" class="uk-text-capitalize">Home</a></li>
            <li><a href="" class="uk-text-capitalize" :style="{ color: 'var(--green)' }">About Us</a></li>
            <li><a href="" class="uk-text-capitalize">Doctors</a></li>
            <li><a href="" class="uk-text-capitalize">News</a></li>
            <li><a href="" class="uk-text-capitalize">Contact</a></li>
            <li>
              <button class="uk-button-default login-button uk-border-rounded">Login/Register</button>
            </li>
          </ul>
          <a class="uk-navbar-toggle" uk-navbar-toggle-icon href="" uk-toggle="target: #offcanvas-nav"></a>

          <div id="offcanvas-nav" uk-offcanvas="overlay: true">
            <div class="uk-offcanvas-bar">

              <ul class="uk-nav uk-nav-default">
                <li><a href="" class="uk-text-capitalize">Home</a></li>
                <li><a href="" class="uk-text-capitalize" :style="{ color: 'var(--green)' }">About Us</a></li>
                <li><a href="" class="uk-text-capitalize">Doctors</a></li>
                <li><a href="" class="uk-text-capitalize">News</a></li>
                <li><a href="" class="uk-text-capitalize">Contact</a></li>
                <li>
                  <button class="uk-button-default login-button uk-border-rounded uk-margin-small-top">Login/Register</button>
                </li>
              </ul>

            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.top-bar {
  margin: 0.4rem;
}

.site-info .icon {
  color: var(--green);
}

.site-info .numbers {
  color: var(--light-grey) !important;
}

.social-buttons .icon {
  color: var(--light-grey);
  margin-right: 0.5rem;
  width: 14px;
  height: 14px;
}

hr {
  margin: 0;
}

.uk-navbar-item.uk-logo.uk-text-bold span {
  margin-right: -0.4rem;
}

.uk-navbar-right.uk-navbar-nav a.uk-text-capitalize {
  font-size: 1.2em;
}

.uk-navbar-right .uk-navbar-nav button {
  background-color: var(--green);
  color: #fff;
  position: relative;
  padding: 0.8rem 1.5rem;
  font-size: 14px;
}

a.uk-text-capitalize {
  font-size: 1rem;
}

@media (max-width: 1120px) {
  .navbar {
    display: none;
  }

  .uk-navbar-toggle svg {
    display: block;
  }
}

button.uk-button-default {
  background-color: var(--green);
  color: #fff;
  position: relative;
  padding: 0.6rem 1.3rem;
  font-size: 14px;
}
</style>