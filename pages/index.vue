<template>
  <div>
    <section class="hero is-light is-fullheight">
      <navbar />
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title has-text-black is-size-1-tablet">
            Patrick Kubica
          </h1>
          <h2 class="subtitle has-text-black is-size-2-tablet">
            Full-Stack Web Developer
          </h2>
          <p class="is-size-4-tablet">
            Lead Software Developer at Sitewards GmbH, Frankfurt am Main
          </p>
          <p class="is-size-4-tablet">
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
            <li>Git</li>
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
      <h1 class="title is-size-1-tablet">
        Berufserfahrung
      </h1>
      <div class="columns is-multiline">
        <jobcard job-title="Lead Software Developer" company="Sitewards GmbH" date="März 2018 - Heute" />
        <jobcard job-title="Software Developer" company="Sitewards GmbH" date="August 2017 - Februar 2018" />
        <jobcard job-title="Junior Software Developer" company="Sitewards GmbH" date="März 2015 - Juli 2017" />
        <jobcard job-title="Software Team Assistent" company="Sitewards GmbH" date="November 2012 - Februar 2015" />
      </div>
    </fhsection>
    <fhsection section-id="education">
      <h1 class="title is-size-1-tablet">
        Bildungsweg
      </h1>
      <div class="columns is-multiline">
        <div class="column is-half is-offset-one-quarter">
          <div class="card">
            <div class="card-content">
              <div class="content">
                <h1 class="title has-text-black is-size-4-mobile">
                  Hochschule Darmstadt
                </h1>
                <h2 class="subtitle has-text-black is-size-6-mobile">
                  Bachelor of Science Informatik
                </h2>
                <p>
                  Abschluss in Regelstudienzeit
                </p>
                <p>
                  Note: 1,4
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="column is-half is-offset-one-quarter">
          <div class="card">
            <div class="card-content">
              <div class="content">
                <h1 class="title has-text-black is-size-4-mobile">
                  Bachgauschule Babenhausen
                </h1>
                <h2 class="subtitle has-text-black is-size-6-mobile">
                  Abitur
                </h2>
                <p>
                  Note: 1,5
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </fhsection>
    <fhsection section-id="awards" additional-classes="is-light">
      <h1 class="title has-text-black is-size-1-tablet">
        Abschluss &amp; Zertifizierungen
      </h1>
      <ul class="is-size-5-tablet has-text-weight-bold">
        <li>Bachelor of Science Informatik</li>
        <li>Spryker Bootcamp Certification</li>
        <li>Magento Certified Developer</li>
      </ul>
    </fhsection>
    <fhsection section-id="contact">
      <a class="is-size-1-tablet is-size-4-mobile" href="mailto:mail@patrickkubica.de">mail@patrickkubica.de</a>
    </fhsection>
  </div>
</template>

  <script>
import Fhsection from '~/components/Fhsection.vue'
import Navbar from '~/components/Navbar.vue'
import Jobcard from '~/components/Jobcard.vue'

export default {
  components: {
    Fhsection,
    Navbar,
    Jobcard
  }
}
</script>

<style lang="scss">
</style>
