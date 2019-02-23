<template>
  <div>
    <section class="hero is-light is-fullheight has-background has-background-first">
      <navbar />
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title is-size-1-tablet has-text-white">
            Patrick Kubica
          </h1>
          <h2 class="subtitle is-size-2-tablet has-text-white">
            Full-Stack Web Developer
          </h2>
          <p class="is-size-4-tablet has-text-white">
            Lead Software Developer at Sitewards GmbH, Frankfurt am Main
          </p>
          <p class="is-size-4-tablet has-text-white">
            Bachelor of Science Informatik
          </p>
          <div class="is-size-4-tablet mail">
            <a class="has-text-white" href="mailto:mail@patrickkubica.de">mail@patrickkubica.de</a>
          </div>
          <div class="socialicons">
            <a class="has-text-white" target="_blank" rel="noopener" href="https://www.linkedin.com/in/patrick-kubica-002027156" aria-label="LinkedIn">
              <font-awesome-icon :icon="['fab', 'linkedin']" class="fa-3x" />
            </a>
            <a class="has-text-white" target="_blank" rel="noopener" href="https://www.xing.com/profile/Patrick_Kubica2" aria-label="Xing">
              <font-awesome-icon :icon="['fab', 'xing']" class="fa-3x" />
            </a>
            <a class="has-text-white" target="_blank" rel="noopener" href="https://github.com/PatrickKubica" aria-label="GitHub">
              <font-awesome-icon :icon="['fab', 'github']" class="fa-3x" />
            </a>
          </div>
        </div>
      </div>
    </section>

    <fhsection section-id="skills">
      <h1 class="title">
        Software&shy;entwicklung
      </h1>
      <div class="columns is-multiline is-mobile">
        <skillcard>PHP</skillcard>
        <skillcard>Javascript / jQuery</skillcard>
        <skillcard>Laravel</skillcard>
        <skillcard>Vue.js</skillcard>
        <skillcard>Node.js</skillcard>
        <skillcard>Spryker</skillcard>
        <skillcard>Magento / Magento 2</skillcard>
        <skillcard>Typo3</skillcard>
        <skillcard>Express</skillcard>
        <skillcard>MySQL / MongoDB</skillcard>
        <skillcard>Amazon Echo / Alexa Skills</skillcard>
        <skillcard>HTML</skillcard>
        <skillcard>Bootstrap / Bulma</skillcard>
        <skillcard>CSS / Sass / Less</skillcard>
        <skillcard>Apache / Nginx</skillcard>
        <skillcard>PHPUnit / PHP_CS / ESLint</skillcard>
        <skillcard>Gulp</skillcard>
        <skillcard>Composer / npm / Bower / Yarn</skillcard>
        <skillcard>Agile Software&shy;entwicklung</skillcard>
        <skillcard>Scrum / Kanban</skillcard>
        <skillcard>Git</skillcard>
        <skillcard>Unit-Testing</skillcard>
        <skillcard>Jira / Bitbucket</skillcard>
        <skillcard>Confluence / Office 365</skillcard>
      </div>
    </fhsection>
    <fhsection section-id="experience" additional-classes="is-light has-background has-background-second">
      <div class="columns is-multiline">
        <jobcard job-title="Lead Software Developer" company="Sitewards GmbH" date="März 2018 - Heute" />
        <jobcard job-title="Software Developer" company="Sitewards GmbH" date="August 2017 - Februar 2018" />
        <jobcard job-title="Junior Software Developer" company="Sitewards GmbH" date="März 2015 - Juli 2017" />
        <jobcard job-title="Software Team Assistent" company="Sitewards GmbH" date="November 2012 - Februar 2015" />
      </div>
    </fhsection>
    <fhsection section-id="education">
      <div class="awards">
        <h2 class="subtitle is-size-3-tablet is-highlight-text">
          Bachelor of Science Informatik
        </h2>
        <h2 class="subtitle is-size-3-tablet is-highlight-text">
          Spryker Bootcamp Certification
        </h2>
        <h2 class="subtitle is-size-3-tablet is-highlight-text">
          Magento Certified Developer
        </h2>
      </div>
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
  </div>
</template>

  <script>
import Fhsection from '~/components/Fhsection.vue'
import Navbar from '~/components/Navbar.vue'
import Jobcard from '~/components/Jobcard.vue'
import Skillcard from '~/components/Skillcard.vue'

export default {
  components: {
    Fhsection,
    Navbar,
    Jobcard,
    Skillcard
  }
}
</script>

<style lang="scss">
.mail {
  padding-top: 1.5rem;
}
.socialicons {
  padding-top: 3rem;

  a {
    padding-left: 1rem;
    padding-right: 1rem;
  }
}
.is-section-title {
  padding-bottom: 3rem;
}
.is-highlight-text {
  color: $highlight-text;
}
.awards {
  padding-bottom: 5rem;
}

.has-background {
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}

.has-background-first {
  background-image: url('~assets/background-first.jpg');
}
.has-background-second {
  background-image: url('~assets/background-second.jpg');
}
@media only screen and (max-width: 600px) {
  .has-background-first {
    background-image: url('~assets/background-first-mobile.jpg');
  }
  .has-background-second {
    background-image: url('~assets/background-second-mobile.jpg');
  }
}
</style>
