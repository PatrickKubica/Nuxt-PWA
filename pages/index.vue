<template>
  <div>
    <section class="hero is-success is-fullheight">
      <div class="hero-head">
        <header class="navbar is-fixed-top">
          <div class="container has-text-black">
            <div class="navbar-brand">
              <span
                class="navbar-burger burger"
                onclick="document.querySelector('.navbar-menu').classList.toggle('is-active');"
                data-target="navbarMenuHeroC"
              >
                <span></span>
                <span></span>
                <span></span>
              </span>
            </div>
            <div id="navbarMenuHeroC" class="navbar-menu">
              <div class="navbar-end">
                <a class="navbar-item" href="#">Home</a>
                <a class="navbar-item" href="#skills">Softwareentwicklung</a>
                <a class="navbar-item" href="#experience">Berufserfahrung</a>
                <a class="navbar-item" href="#education">Bildungsweg</a>
                <a class="navbar-item" href="#awards">Abschluss &amp; Zertifizierungen</a>
                <a class="navbar-item" href="#contact">Kontakt</a>
              </div>
            </div>
          </div>
        </header>
      </div>

      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title">Patrick Kubica</h1>
          <h2 class="subtitle">Lead Software Developer at Sitewards GmbH, Frankfurt am Main</h2>
        </div>
      </div>
    </section>
    <section class="hero is-fullheight" id="skills">
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title">Softwareentwicklung</h1>
        </div>
      </div>
    </section>
    <section class="hero is-fullheight is-success" id="experience">
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title">Berufserfahrung</h1>
        </div>
      </div>
    </section>
    <section class="hero is-fullheight" id="education">
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title">Bildungsweg</h1>
        </div>
      </div>
    </section>
    <section class="hero is-fullheight is-success" id="awards">
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title">Abschluss &amp; Zertifizierungen</h1>
        </div>
      </div>
    </section>
    <section class="hero is-fullheight" id="contact">
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title">Kontakt</h1>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  components: {}
}
</script>

<style>
</style>
