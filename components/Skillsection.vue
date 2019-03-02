<template>
  <div class="container has-text-centered">
    <h1 class="title is-size-2-tablet pb-1-5">
      Software&shy;entwicklung
    </h1>
    <div class="columns is-multiline is-mobile is-centered">
      <div v-for="(skill, index) in skills" :key="index" class="column is-one-quarter-tablet is-three-quarters-mobile">
        <article class="message has-text-left-tablet">
          <div class="message-body">
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
</style>
