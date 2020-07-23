<template>
  <div class="layout">
    <header class="header">
      <strong>
        <g-link to="/">{{ $static.metadata.siteName }}</g-link>
      </strong>
      <nav class="nav">
        <g-link class="nav__link" to="/">Home</g-link>
        <g-link class="nav__link" to="/our-story/">Our Story</g-link>
        <g-link class="nav__link" to="/travel-and-stay/">Travel & Stay</g-link>
        <a class="nav__link" href="https://www.zola.com/registry/berlinandmichael" target="_blank" rel="noopener">Registry</a>
        <g-link class="nav__link" to="/rsvp/">RSVP</g-link>
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
