<template>
  <div class="column is-one-quarter-tablet">
    <article class="message is-info has-text-left">
      <div class="message-body">
        <slot />
      </div>
    </article>
  </div>
</template>
<script>
export default {
  props: {
    jobTitle: {
      type: String,
      default: ''
    },
    company: {
      type: String,
      default: ''
    },
    date: {
      type: String,
      default: ''
    }
  }
}
</script>
