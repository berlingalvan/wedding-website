<template>
  <Layout>
  <body>
    <section class="section is-medium">
      <div class="container has-text-centered">
          <h1 class="title is-1 pt-2 pb-2">How it all began.</h1>
          <g-image src="~/assets/images/waist-horizontal.jpg" class="image" quality="100"/>
      </div>
    </section>
    <!--- Quotes -->
    <section class="section is-small mb-3 pt-2">
      <div class="container">
        <div class="column level-right is-centered">
          <h2 class="title is-3">"I am dead certain that 8 years from now I will be marrying THAT girl." <br>- Michael Hooten</h2>
        </div>
        <div class="column level-right is-centered">
          <h2 class="title is-3">"Nice pajama pants." <br>- Berlin Galvan</h2>
        </div>
      </div>
    </section>
    <!--- The Story -->
    <section class="section is-small">
      <div class="container">
        <div class="columns is-vcentered">
          <div class="column is-half level-left">
            <g-image src="~/assets/images/kiss-vertical.jpg" class="image" width="600" quality="100"/>
          </div>
          <div class="column level-right is-centered">
            <p class="is-size-4 pb-2">
              Michael and Berlin met in the spring of 2013. Berlin was an uninvited designated driver at a party
              that Michael's house mate was hosting. Michael was downstairs pouring himself a glass of water when
              Berlin introduced herself to him and complimented his plaid pajama pants.</p>
              </br>
              </br>
            <p class="is-size-4 pb-2">
              As days passed, Berlin reached out to Michael to see if he knew the whereabouts of a sweater her
              friend lost. The sweater was never seen again, but it gave Michael a good reason to ask for
              Berlin's number in case it ever came up.
            </p>
            </br>
            </br>
            <p class="is-size-4 pb-2">
              Fast forward 7 years later, Michael and Berlin now live together in Santa Barbara where they hike, climb,
              and enjoy the outdoors. They are excited for the next chapter of their lives as husband and wife.
            </p>
            <hr class="style2">
          </div>
        </div>
      </div>
    </section>
     </body>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Our Story'
  }
}
</script>
