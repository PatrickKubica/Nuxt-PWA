<template>
  <div class="container has-text-centered">
    <div class="skillgrid">
      <div v-for="(skill, index) in skills" :key="index">
        <article class="message has-text-left-tablet">
          <div class="message-body has-text-weight-semibold">
            {{ skill }}
          </div>
        </article>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    skills: {
      type: Array,
      default: function() {
        return []
      }
    }
  }
}
</script>

<style lang="scss" scoped>
.message-body {
  border-color: $highlight-text;
}
h1 {
  padding-bottom: 1.5rem;
  margin-top: -1rem;
}
@media screen and (max-width: 600px) {
  h1 {
    padding-bottom: 1rem;
  }
}
</style>
