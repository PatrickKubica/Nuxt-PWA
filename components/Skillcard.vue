<template>
  <div class="column is-one-quarter-tablet is-half-mobile">
    <article class="message has-text-left">
      <div class="message-body">
        <slot />
      </div>
    </article>
  </div>
</template>

<style lang="scss" scoped>
.message-body {
  border-color: $highlight-text;
}
</style>
