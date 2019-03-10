<template>
  <div>
    <section class="hero is-light is-fullheight has-background has-background-first">
      <navbar />
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title is-size-2-mobile is-size-1-tablet has-text-white">
            Patrick Kubica
          </h1>
          <h2 class="subtitle is-size-2-tablet has-text-white">
            Full-Stack Web Developer
          </h2>
          <p class="is-size-4-tablet has-text-white">
            Lead Software Developer at Sitewards GmbH, Frankfurt am Main
          </p>
          <p class="is-size-4-tablet has-text-white pt-05">
            Bachelor of Science Informatik
          </p>
          <div class="is-size-4-tablet mail pt-1">
            <a class="has-text-white" href="mailto:mail@patrickkubica.de">mail@patrickkubica.de</a>
          </div>
          <div class="socialicons">
            <a class="has-text-white" href="mailto:mail@patrickkubica.de" aria-label="E-Mail">
              <font-awesome-icon :icon="['fa', 'envelope']" class="fa-3x" />
            </a>
            <a class="has-text-white" href="https://www.linkedin.com/in/patrick-kubica-002027156" aria-label="LinkedIn">
              <font-awesome-icon :icon="['fab', 'linkedin']" class="fa-3x" />
            </a>
            <a class="has-text-white" href="https://www.xing.com/profile/Patrick_Kubica2" aria-label="Xing">
              <font-awesome-icon :icon="['fab', 'xing']" class="fa-3x" />
            </a>
            <a class="has-text-white" href="https://github.com/PatrickKubica" aria-label="GitHub">
              <font-awesome-icon :icon="['fab', 'github']" class="fa-3x" />
            </a>
          </div>
        </div>
      </div>
    </section>
    <span id="skills" class="skillsanchor" />
    <section id="skillssection" class="section">
      <skillsection :skills="skills" />
    </section>
    <fhsection section-id="experience" additional-classes="is-light has-background has-background-second">
      <div class="jobgrid">
        <jobcard job-title="Lead Software Developer" company="Sitewards GmbH" date="März 2018 - Heute" />
        <jobcard job-title="Software Developer" company="Sitewards GmbH" date="August 2017 - Februar 2018" />
        <jobcard job-title="Junior Software Developer" company="Sitewards GmbH" date="März 2015 - Juli 2017" />
        <jobcard job-title="Software Team Assistent" company="Sitewards GmbH" date="November 2012 - Februar 2015" />
      </div>
    </fhsection>
    <fhsection section-id="education">
      <div class="educationgrid">
        <educationcard>
          <div class="message-body">
            <h1 class="title is-size-4-mobile">
              Hochschule Darmstadt
            </h1>
            <h2 class="subtitle is-size-6-mobile">
              Bachelor of Science Informatik
            </h2>
            <p>
              Note: 1,4
            </p>
          </div>
        </educationcard>
        <educationcard>
          <div class="message-body">
            <h1 class="title is-size-4-mobile">
              Bachgauschule Babenhausen
            </h1>
            <h2 class="subtitle is-size-6-mobile">
              Abitur
            </h2>
            <p>
              Note: 1,5
            </p>
          </div>
        </educationcard>
        <educationcard>
          <div class="message-body">
            <h1 class="title is-size-4-mobile">
              Spryker Bootcamp Certification
            </h1>
          </div>
        </educationcard>
        <educationcard>
          <div class="message-body">
            <h1 class="title is-size-4-mobile">
              Magento Certified Developer
            </h1>
          </div>
        </educationcard>
      </div>
    </fhsection>
  </div>
</template>

  <script>
import Fhsection from '~/components/Fhsection.vue'
import Navbar from '~/components/Navbar.vue'
import Jobcard from '~/components/Jobcard.vue'
import Skillsection from '~/components/Skillsection.vue'
import Educationcard from '~/components/Educationcard.vue'

export default {
  components: {
    Fhsection,
    Navbar,
    Jobcard,
    Skillsection,
    Educationcard
  },
  data: function() {
    return {
      skills: [
        'PHP',
        'Laravel',
        'Javascript',
        'Vue.js / Nuxt',
        'Progressive Web Apps',
        'Node.js ',
        'Spryker',
        'Magento / Magento 2',
        'Amazon Echo Skills',
        'HTML',
        'CSS / Sass / Less',
        'Bootstrap / Material / Bulma'
      ]
    }
  }
}
</script>
