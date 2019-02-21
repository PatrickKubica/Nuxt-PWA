<template>
  <div class="column is-half">
    <div class="card">
      <div class="card-content">
        <div class="media">
          <div class="media-content">
            <p class="title is-size-4-mobile">
              {{ jobTitle }}
            </p>
            <p class="subtitle is-size-6-mobile">
              {{ company }}
            </p>
          </div>
        </div>
        <div class="content">
          {{ date }}
        </div>
      </div>
    </div>
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
