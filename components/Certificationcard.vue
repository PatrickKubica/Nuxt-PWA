<template>
  <div class="is-dark">
    <article class="message is-dark" />
    <div class="message-header" />
    <div class="message-body">
      <h1 class="title is-size-4-mobile">
        {{ certificationTitle }} 
        <br>
        {{ certificationSubtitle }}
      </h1>
      <a class="subtitle" :href="certificationLink" aria-label="Zertifizierung" target="_blank" rel="noopener">
        <font-awesome-icon :icon="['fa', 'file-alt']" class="fa-lg" />
      </a>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    certificationTitle: {
      type: String,
      default: ''
    },
    certificationSubtitle: {
      type: String,
      default: ''
    },
    certificationLink: {
      type: String,
      default: ''
    }
  }
}
</script>


<style lang="scss" scoped>
.message-body {
  background-color: whitesmoke;
}
.message-header {
  padding: 0.25em 1em;
  background-color: #3d5d42;
}
</style>
