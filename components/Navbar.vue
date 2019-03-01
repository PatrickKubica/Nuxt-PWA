<template>
  <div class="hero-head">
    <header class="navbar is-fixed-top">
      <div class="container has-text-black">
        <div class="navbar-brand">
          <span
            class="navbar-burger burger"
            data-target="navbarMenuHeroC"
            @click="toggleActiveState"
          >
            <span />
            <span />
            <span />
          </span>
        </div>
        <div id="navbarMenuHeroC" class="navbar-menu" :class="{ 'is-active': isNavActive }">
          <div class="navbar-end">
            <a class="navbar-item" href="#" @click="hideNavIfActive">Home</a>
            <a class="navbar-item" href="#skills" @click="hideNavIfActive">Softwareentwicklung</a>
            <a class="navbar-item" href="#experience" @click="hideNavIfActive">Berufserfahrung</a>
            <a class="navbar-item" href="#education" @click="hideNavIfActive">Bildungsweg</a>
          </div>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      isNavActive: false
    }
  },
  methods: {
    toggleActiveState: function() {
      this.isNavActive = !this.isNavActive
    },
    hideNavIfActive: function() {
      if (this.isNavActive) {
        this.isNavActive = false
      }
    }
  }
}
</script>
