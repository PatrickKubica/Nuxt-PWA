<template>
  <div>
    <section class="hero is-light is-fullheight has-background has-background-first">
      <navbar />
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title is-size-2-mobile is-size-1-tablet has-text-white">
            Patrick Kubica
          </h1>
          <h2 class="subtitle is-size-4-mobile is-size-3-tablet has-text-white">
            Head of Technology
          </h2>
          <p class="is-size-4-tablet has-text-white">
            Bachelor of Science Informatik
          </p>
        
          <div class="socialicons">
            <a class="has-text-white" href="mailto:mail@patrickkubica.de" aria-label="E-Mail">
              <font-awesome-icon :icon="['fa', 'envelope']" class="fa-3x animate-text animation-delay-1" />
            </a>
            <a class="has-text-white" href="https://www.linkedin.com/in/patrick-kubica-002027156" aria-label="LinkedIn">
              <font-awesome-icon :icon="['fab', 'linkedin']" class="fa-3x animate-text animation-delay-2" />
            </a>
            <a class="has-text-white" href="https://www.xing.com/profile/Patrick_Kubica2" aria-label="Xing">
              <font-awesome-icon :icon="['fab', 'xing']" class="fa-3x animate-text animation-delay-3" />
            </a>
            <a class="has-text-white" href="https://github.com/PatrickKubica" aria-label="GitHub">
              <font-awesome-icon :icon="['fab', 'github']" class="fa-3x animate-text animation-delay-4" />
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
        <jobcard job-title="Head of Technology &amp; Deputy Site Manager" company="Sitewards GmbH" date="Februar 2020 - Heute" />
        <jobcard job-title="Full Stack Developer" company="asuro GmbH" date="Mai 2019 - Januar 2020" />
        <jobcard job-title="Lead Software Developer" company="Sitewards GmbH" date="März 2018 - April 2019" />
        <jobcard job-title="Software Developer" company="Sitewards GmbH" date="August 2017 - Februar 2018" />
        <jobcard job-title="Junior Software Developer" company="Sitewards GmbH" date="März 2015 - Juli 2017" />
        <jobcard job-title="Software Team Assistent" company="Sitewards GmbH" date="November 2012 - Februar 2015" />
      </div>
    </fhsection>
    <span id="education" class="educationanchor" />
    <section id="education-section" class="section">
      <div class="container has-text-centered">
        <div class="educationgrid">
          <educationcard>
            <div class="message-body">
              <h1 class="title is-size-4-mobile">
                Bachelor of Science Informatik
              </h1>
              <h2 class="subtitle is-size-6-mobile">
                Hochschule Darmstadt
              </h2>
              <p>
                Note: 1,4
              </p>
            </div>
          </educationcard>
          <educationcard>
            <div class="message-body">
              <h1 class="title is-size-4-mobile">
                Abitur
              </h1>
              <h2 class="subtitle is-size-6-mobile">
                Bachgauschule Babenhausen
              </h2>
              <p>
                Note: 1,5
              </p>
            </div>
          </educationcard>
          <educationcard>
            <div class="message-body">
              <h1 class="title is-size-4-mobile">
                Spryker Bootcamp 
                <br>
                Certification
              </h1>
              <a class="subtitle" href="https://www.credential.net/ehuo4m6n" aria-label="Zertifizierung" target="_blank" rel="noopener">
                <font-awesome-icon :icon="['fa', 'file-alt']" class="fa-lg" />
              </a>
            </div>
          </educationcard>
          <educationcard>
            <div class="message-body">
              <h1 class="title is-size-4-mobile">
                Magento Certified
                <br>
                Developer
              </h1>
              <a class="subtitle" href="https://u.magento.com/certification/directory/dev/2124989/" aria-label="Zertifizierung" target="_blank" rel="noopener">
                <font-awesome-icon :icon="['fa', 'file-alt']" class="fa-lg" />
              </a>
            </div>
          </educationcard>
          <educationcard>
            <div class="message-body">
              <h1 class="title is-size-4-mobile">
                Flutter and Dart
                <br>
                Development course 
              </h1>
              <a class="subtitle" href="https://www.udemy.com/certificate/UC-L0SUPM7B/" aria-label="Zertifizierung" target="_blank" rel="noopener">
                <font-awesome-icon :icon="['fa', 'file-alt']" class="fa-lg" />
              </a>
            </div>
          </educationcard>
          <educationcard>
            <div class="message-body">
              <h1 class="title is-size-4-mobile">
                Flutter Development Bootcamp 
                <br>
                with Dart course 
              </h1>
              <a class="subtitle" href="https://www.udemy.com/certificate/UC-OVJNTO16/" aria-label="Zertifizierung" target="_blank" rel="noopener">
                <font-awesome-icon :icon="['fa', 'file-alt']" class="fa-lg" />
              </a>
            </div>
          </educationcard>
          <educationcard>
            <div class="message-body">
              <h1 class="title is-size-4-mobile">
                SCRUM - Agil denken und 
                <br>
                arbeiten course 
              </h1>
              <a class="subtitle" href="https://www.udemy.com/certificate/UC-AVHTC9J6/" aria-label="Zertifizierung" target="_blank" rel="noopener">
                <font-awesome-icon :icon="['fa', 'file-alt']" class="fa-lg" />
              </a>
            </div>
          </educationcard>
        </div>
      </div>
    </section>
    <fhsection section-id="contact" additional-classes="is-light has-background has-background-third">
      <h1 class="title is-size-4-mobile is-size-1-tablet">
        <a class="has-text-white" href="mailto:mail@patrickkubica.de">mail@patrickkubica.de</a>
      </h1>
      <div class="socialicons-contact">
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
        'Flutter / iOS and Android Apps',
        'Dart',
        'MySQL / Microsoft SQL',
        'OOP',
        'Progressive Web Apps',
        'Spryker',
        'Magento',
        'Amazon Echo Skills',
        'HTML',
        'CSS / Sass / Less',
        'Bootstrap / Material / Bulma',
        'Test-Driven Development',
        'Server Administration',
        'Jira and Office Administration'
      ]
    }
  }
}
</script>
