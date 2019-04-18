<template>
  <section class="container">
    <div>
      <app-logo/>
      <h1 class="title">
        Seattle Vue JS Meetup
      </h1>
      <h2 class="subtitle">
        Welcome to our new website!
      </h2>
      <div class="links">
        <a
          href="https://meetup.com/seattlevuejs"
          target="_blank"
          class="button--green">Meetup</a>
        <a
          href="https://github.com/seattlevuejs"
          target="_blank"
          class="button--grey">GitHub</a>
        <a
          href="https://twitter.com"
          target="_blank"
          class="button--green">Twitter</a>
        <a 
        	href="https://join.slack.com/t/seattlevuejs/shared_invite/enQtNjAwNTEwNzg2Njc1LTVjNzFjOWE1ZDdjZTFkMzg1YjAwNDc3MGFkMzZlMDE0ZmNhYzRlNGU5ZTMzNWVmYjA1NWNjYjU0OTQyMmE1NmM"
        	target="_blank"
        	class="button--grey">Slack</a>
      </div>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: #fefbf7;
 /* background-image: url("https://res.cloudinary.com/tessamero/image/upload/c_crop,h_623,w_1920/v1555557754/seattle.jpg");*/
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

