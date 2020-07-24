<template>
  <Layout>
      <!-- Learn how to use images here: https://gridsome.org/docs/images -->
      <!-- Hero image -->
      <section class="hero is-link is-fullheight">
        <div class="hero-body" id="main-hero">
          <div class="container has-text-centered">
            <h2 class="subtitle is-4">We're getting married!</h2>
            <h1 class="title is-1 pt-2 pb-2">Michael & Berlin</h1>
            <h2 class="subtitle is-4">06.26.21</h2>
          </div>
        </div>
      </section>

    <!-- Ceremony Information -->
    <section class="section is-small">
      <div class="container">
        <div class="columns is-vcentered">
          <div class="column is-half level-left">
            <g-image src="~/assets/images/standing-vertical.jpg" class="image" width="600" quality="100"/>
          </div>
          <div class="column level-right is-centered has-text-centered">
            <h1 class="title is-1">Ceremony</h1>
            <h2 class="subtitle is-3">4:00 PM</h2>
            <p class="is-size-5">
              Front Lawn <br>
              Olivas Adobe Historic Park <br>
              4200 Olivas Park Drive <br>
              San Buenaventura, California 93001
            </p>
            <p class="is-size-5">
              <a href="https://goo.gl/maps/Pwi6ZTkzNBYTkga38" target="_blank" rel="noopener"><u>Map</u></a>
            </p>
          </div>
        </div>
      </div>
    </section>
    <!-- Reception Information -->
    <section class="section is-small">
      <div class="container">
        <div class="columns is-vcentered">
          <div class="column is-half level-left has-text-centered">
            <h1 class="title is-1">Reception</h1>
            <h2 class="subtitle is-3">4:30 PM - 10:30 PM</h2>
            <p class="is-size-5">
              The Plaza <br>
              Olivas Adobe Historic Park <br>
              4200 Olivas Park Drive <br>
              San Buenaventura, California 93001
            </p>
            <p class="m-2 p-2 is-size-5">
              <a href="https://goo.gl/maps/Pwi6ZTkzNBYTkga38" target="_blank" rel="noopener"><u>Map</u></a>
            </p>
          </div>
          <div class="column level-right is-centered">
            <g-image src="~/assets/images/walking-vertical.jpg" class="image" width="600" quality="100"/>
          </div>
        </div>
      </div>
    </section>

    <!-- How We Met -->
    <section class="section is-large">
      <div class="container">
        <div class="columns is-vcentered">
          <div class="column is-one-third has-text-centered">
            <hr class="style2">
          </div>
          <div class="column is-one-third has-text-centered">
              <h1 class="title is-3">See how it all started</h1>
              <a class="button is-primary is-large" href="/our-story/">Our Story</a>
          </div>
          <div class="column is-one-third has-text-centered">
            <hr class="style2">
          </div>
        </div>
      </div>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Berlin & Michael Wedding'
  }
}
</script>

