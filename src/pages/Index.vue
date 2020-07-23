<template>
  <Layout>

    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <g-image alt="Example image" src="~/favicon.png" width="135" />

    <h2>We're getting married!</h2>
    <h1>Michael & Berlin</h1>
    <h2>06.26.21</h2>


    <h1>Ceremony</h1>
    <h2>4:00 PM</h2>
    <p>
      Front Lawn <br>
      Olivas Adobe Historic Park <br>
      4200 Olivas Park Drive <br>
      San Buenaventura, California 93001
    </p>
    <p>
      <a href="https://goo.gl/maps/Pwi6ZTkzNBYTkga38" target="_blank" rel="noopener">Map</a>
    </p>

    <h1>Reception</h1>
    <h2>4:30 PM - 10:30 PM</h2>
    <p>
      Plaza <br>
      Olivas Adobe Historic Park <br>
      4200 Olivas Park Drive <br>
      San Buenaventura, California 93001
    </p>
    <p>
      <a href="https://goo.gl/maps/Pwi6ZTkzNBYTkga38" target="_blank" rel="noopener">Map</a>
    </p>

    <h1>See how it all started</h1>
    <button class="primary">Our Story</button>

    <p class="home-links">
      <a href="https://gridsome.org/docs/" target="_blank" rel="noopener">Gridsome Docs</a>
      <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
    </p>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Berlin & Michael Wedding'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
