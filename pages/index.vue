<template>
  <div>
    <section class="hero is-light is-fullheight">
      <navbar />
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
import Navbar from '~/components/Navbar.vue'

export default {
  components: {
    Fhsection,
    Navbar
  }
}
</script>

<style>
</style>
