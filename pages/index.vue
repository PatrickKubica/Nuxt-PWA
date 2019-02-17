<template>
  <div>
    <section class="hero is-light is-fullheight">
      <div class="hero-head">
        <header class="navbar is-fixed-top">
          <div class="container has-text-black">
            <div class="navbar-brand">
              <span
                class="navbar-burger burger"
                onclick="document.querySelector('.navbar-menu').classList.toggle('is-active');"
                data-target="navbarMenuHeroC"
              >
                <span />
                <span />
                <span />
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
          <h1 class="title has-text-black">
            Patrick Kubica
          </h1>
          <h2 class="subtitle has-text-black">
            Full-Stack Web Developer
          </h2>
        </div>
      </div>
    </section>
    <fhsection section-id="skills">
      <h1 class="title">
        Softwareentwicklung
      </h1>
    </fhsection>
    <fhsection section-id="experience" additional-classes="is-light">
      <h1 class="title has-text-black">
        Berufserfahrung
      </h1>
    </fhsection>
    <fhsection section-id="education">
      <h1 class="title">
        Bildungsweg
      </h1>
    </fhsection>
    <fhsection section-id="awards" additional-classes="is-light">
      <h1 class="title has-text-black">
        Abschluss &amp; Zertifizierungen
      </h1>
    </fhsection>
    <fhsection section-id="contact">
      <h1 class="title">
        Kontakt
      </h1>
    </fhsection>
  </div>
</template>

<script>
import Fhsection from '~/components/Fhsection.vue'

export default {
  components: {
    Fhsection
  }
}
</script>

<style>
</style>
