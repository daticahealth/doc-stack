<template>
  <Section dots="true">
    <div class="homepage-features container post">
      <div class="grid-cols grid-cols--1 mb">
        <div style="order:2">
          <h3>Documentation Demo</h3>
          <p>We have a pile of markdown files; let's make them look decent, load fast, and be easy to search and read.</p>
          <p>This demo is a fork of <a href="https://github.com/gridsome/gridsome">Gridsome.org</a>.</p>
            <p class="home-links">
            <g-link  to="/docs" class="button primary">
                See the docs
            </g-link>
            <!-- <g-link  to="/learn" class="button">
                Tutorial
            </g-link> -->
            </p>
          </div>
      </div>
    </div>
  </Section>
</template>

<script>
import Bullet from '~/assets/images/bullet.svg'
// import VueLogo from '~/assets/images/vue-logo.svg'

export default {
  components: {
    Bullet
  },
}

</script>


<static-query>
query Example {
  example (path: "/examples/templates") {
    content
  }
}
</static-query>
