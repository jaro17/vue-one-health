<script setup></script>

<template>
  <section>
    <div class="uk-container">
      <h2>Latest News</h2>
      <div class="cards-container" uk-grid>
        <div>
          <div class="uk-card uk-card-default">
            <div class="uk-card-media-top">
              <img
                src="src/assets/img/blog/blog_1.jpg"
                width=""
                height=""
                alt=""
              />
            </div>
            <div class="uk-card-body">
              <a class="uk-card-title"
                >List of Countries without Coronavirus case</a
              >
              <div class="site-info">
                <div class="uk-flex uk-flex-middle uk-margin-small-top">
                  <img
                    class="img uk-margin-medium-right"
                    src="src/assets/img/person/person_1.jpg"
                    alt=""
                  />
                  <p>Roger Adams</p>
                </div>
                <div class="uk-flex uk-flex-left uk-flex-middle">
                  <span
                    class="icon uk-margin-small-right"
                    uk-icon="icon: clock"
                  ></span>
                  <p>1 week ago</p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div>
          <div class="uk-card uk-card-default">
            <div class="uk-card-media-top">
              <img
                src="src/assets/img/blog/blog_2.jpg"
                width=""
                height=""
                alt=""
              />
            </div>
            <div class="uk-card-body">
              <a class="uk-card-title"
                >Recovery Room: News beyond the pandemic</a
              >
              <div class="site-info">
                <div class="uk-flex uk-flex-middle uk-margin-small-top">
                  <img
                    class="img uk-margin-medium-right"
                    src="src/assets/img/person/person_2.jpg"
                    alt=""
                  />
                  <p>Walter White</p>
                </div>
                <div class="uk-flex uk-flex-left uk-flex-middle">
                  <span
                    class="icon uk-margin-small-right"
                    uk-icon="icon: clock"
                  ></span>
                  <p>1 week ago</p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div>
          <div class="uk-card uk-card-default">
            <div class="uk-card-media-top">
              <img
                src="src/assets/img/blog/blog_3.jpg"
                width=""
                height=""
                alt=""
              />
            </div>
            <div class="uk-card-body">
              <a class="uk-card-title"
                >What is the impact of eating too much sugar?</a
              >
              <div class="site-info">
                <div class="uk-flex uk-flex-middle uk-margin-small-top">
                  <img
                    class="img uk-margin-medium-right"
                    src="src/assets/img/person/person_3.jpg"
                    alt=""
                  />
                  <p>Diego Simmons</p>
                </div>
                <div class="uk-flex uk-flex-left uk-flex-middle">
                  <span
                    class="icon uk-margin-small-right"
                    uk-icon="icon: clock"
                  ></span>
                  <p>1 week ago</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <button class="uk-button uk-button-default login-button uk-border-rounded uk-text-capitalize">
        Read More
      </button>
    </div>
  </section>
</template>

<style scoped>
section {
  margin-top: 5rem;
  background-color: var(--light);
  padding-bottom: 4rem;
}

h2 {
  text-align: center;
  font-size: 2.5rem;
  margin-top: 4rem;
}

.uk-container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.cards-container {
  margin-top: 3rem;
}

.uk-card {
  width: 16rem;
  margin-right: 2rem;
  margin-left: 2rem;
}

.uk-card-body a {
  font-size: 1rem;
}

button {
  background-color: var(--green);
  color: #fff;
  position: relative;
  padding: 0.8rem 1.5rem;
  border: 1px solid var(--green);
  width: 14rem;
  margin-top: 3rem;
  font-size: 1.1rem;
}

button:hover {
  background-color: var(--grey);
  color: #fff;
  transition: background-color 0.3s;
}

.site-info p {
  font-size: 0.8rem;
}

.site-info .icon {
  width: 10px;
  font-weight: bold;
}

.site-info .img {
  border-radius: 50%;
  width: 30px;
  height: 30px;
}

@media (max-width: 1120px) {
  .uk-card {
    margin-right: 1rem;
    margin-left: 1rem;
    width: 13rem;
  }
}

@media (max-width: 860px) {
  .cards-container {
    display: flex;
    flex-direction: column;
  }

  .uk-card {
    width: 18rem;
  }
}
</style>
