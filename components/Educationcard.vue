<template>
  <div class="column is-half is-offset-one-quarter is-dark">
    <article class="message is-dark" />
    <div class="message-header" />
    <slot />
  </div>
</template>

<style lang="scss" scoped>
.message-body {
  background-color: whitesmoke;
}
.message-header {
  padding: 0.5em 1em;
  background-color: $highlight-text;
}
</style>
