<template>
  <div class="layout">
    <header class="header">
      <nav class="navbar is-fixed-top" role="navigation" aria-label="main navigation">
        <div class="container is-fluid">
          <div class="navbar-menu">
            <div class="navbar-start p-2">
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
            <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
              <span aria-hidden="true"></span>
              <span aria-hidden="true"></span>
              <span aria-hidden="true"></span>
            </a>
          </div>
        </div>
      </nav>
    </header>
    <slot/>
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

