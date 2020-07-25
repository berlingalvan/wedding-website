<template>
    <div class="layout">
      <header class="header">
        <nav class="navbar is-fixed-top" role="navigation" aria-label="main navigation" >
          <div class="navbar-brand">
            <a class="navbar-burger burger" aria-label="menu" aria-expanded="false" @click="isOpen = !isOpen" v-bind:class="{'is-active': isOpen}">
              <span></span>
              <span></span>
              <span></span>
            </a>
          </div>
          <div class="navbar-menu" v-bind:class="{'is-active': isOpen}">
            <div class="navbar-start">
              <g-link class="navbar-item" to="/">Home</g-link>
              <g-link class="navbar-item" to="/our-story/">Our Story</g-link>
              <g-link class="navbar-item" to="/travel-and-stay/">Travel & Stay</g-link>
              <a class="navbar-item" href="https://www.zola.com/registry/berlinandmichael" target="_blank" rel="noopener">Registry</a>
            </div>
            <div class="navbar-end">
              <div class="navbar-item">
                <div class="buttons">
                  <g-link class="button is-primary" to="/rsvp/">RSVP</g-link>
                </div>
              </div>
            </div>
          </div>
        </nav>
      </header>
      <slot></slot>
      <footer class="footer">
        <div class="content has-text-centered">
          <p>
            <strong>🤍 Built by Berlin Galvan, 2020 🤍</strong>
          </p>
        </div>
      </footer>
    </div>
</template>
<script>
export default {
    data: function() {
        return {
            isOpen: false
        }
    }
}
</script>
<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

