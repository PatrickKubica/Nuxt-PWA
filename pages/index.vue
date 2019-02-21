<template>
  <div>
    <section class="hero is-light is-fullheight">
      <navbar />
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title has-text-black is-size-1">
            Patrick Kubica
          </h1>
          <h2 class="subtitle has-text-black is-size-2">
            Full-Stack Web Developer
          </h2>
          <p class="is-size-4">
            Lead Software Developer at Sitewards GmbH, Frankfurt am Main
          </p>
          <p class="is-size-4">
            Bachelor of Science Informatik
          </p>
        </div>
      </div>
    </section>

    <fhsection section-id="skills">
      <div class="columns">
        <div class="column">
          <h1 class="title">
            Software&shy;entwicklung
          </h1>
          <ul class="is-size-5-tablet has-text-weight-bold">
            <li>PHP</li>
            <li>Javascript / jQuery</li>
            <li>Laravel</li>
            <li>Vue.js</li>
            <li>Node.js</li>
            <li>Spryker</li>
            <li>Magento / Magento 2</li>
            <li>Typo3</li>
            <li>Express</li>
            <li>MySQL / MongoDB</li>
            <li>Amazon Echo / Alexa Skills</li>
            <li>HTML</li>
            <li>CSS / Sass / Less</li>
            <li>Apache / Nginx</li>
            <li>Git</li>
            <li>PHPUnit / PHP_CodeSniffer / ESLint</li>
            <li>Gulp</li>
            <li>Composer / npm / Bower / Yarn</li>
          </ul>
        </div>
        <div class="column">
          <h1 class="title">
            Workflow
          </h1>
          <ul class="is-size-5-tablet has-text-weight-bold">
            <li>Agile Softwareentwicklung</li>
            <li>Scrum</li>
            <li>Kanban</li>
            <li>Automatisierte Codechecks und manuelle Codereviews</li>
            <li>Unit-Tests</li>
            <li>Qualitätssicherungsprozess</li>
            <li>Jira</li>
            <li>Bitbucket</li>
            <li>Confluence</li>
            <li>Office 365</li>
          </ul>
        </div>
      </div>
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

<style lang="scss">
</style>
