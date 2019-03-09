<template>
  <div class="is-dark">
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
  padding: 0.25em 1em;
  background-color: #3d5d42;
}
</style>
