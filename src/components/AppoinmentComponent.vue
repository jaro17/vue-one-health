<script setup></script>

<template>
  <section>
    <div class="uk-container uk-container-xsmall">
      <h2>Make an Appoinment</h2>
      <form>
        <fieldset class="uk-fieldset">
          <div class="uk-flex uk-flex-middle uk-flex-between">
            <input
              class="uk-input uk-width-1-2 uk-margin-right"
              type="text"
              placeholder="Input"
              aria-label="Input"
            />

            <input
              class="uk-input uk-width-1-2 uk-margin-left"
              type="text"
              placeholder="Email Adress"
              aria-label="Email"
            />
          </div>

          <div class="uk-flex uk-flex-middle uk-flex-between uk-margin-top">
            <input
              class="uk-input uk-width-1-2 uk-margin-right"
              type="date"
              placeholder="Input"
              aria-label="Date"
            />

            <select class="uk-select uk-width-1-2 uk-margin-left">
              <option>General Health</option>
              <option>Cardiology</option>
              <option>Dental</option>
              <option>Neurology</option>
              <option>Orthopedics</option>
            </select>
          </div>

          <input
            class="uk-input uk-margin-top"
            type="number"
            placeholder="Number"
            aria-label="Number"
          />

          <textarea
            class="uk-textarea uk-margin-top"
            placeholder="Enter Message..."
          ></textarea>

          <button class="uk-button-default login-button uk-border-rounded">
            Submit Request
          </button>
        </fieldset>
      </form>
    </div>
  </section>
</template>

<style scoped>
section {
    padding-top: -3rem;
    padding-bottom: 3rem;
}

h2 {
  text-align: center;
  font-size: 2.5rem;
  margin-top: 4rem;
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
</style>
