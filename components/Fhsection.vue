<template>
  <section :id="sectionId" class="hero is-fullheight" :class="additionalClasses">
    <div class="hero-body">
      <div class="container has-text-centered">
        <slot />
      </div>
    </div>
  </section>
</template>
<script>
export default {
  props: {
    sectionId: {
      type: String,
      default: ''
    },
    additionalClasses: {
      type: String,
      default: ''
    }
  }
}
</script>

<style>
</style>
