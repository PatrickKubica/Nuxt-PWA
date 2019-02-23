<template>
  <div class="hero-head">
    <header class="navbar is-fixed-top">
      <div class="container has-text-black">
        <div class="navbar-brand">
          <span
            class="navbar-burger burger"
            onclick="document.querySelector('.navbar-menu').classList.toggle('is-active');"
            data-target="navbarMenuHeroC"
          >
            <span />
            <span />
            <span />
          </span>
        </div>
        <div id="navbarMenuHeroC" class="navbar-menu">
          <div class="navbar-end">
            <a class="navbar-item" onclick="document.querySelector('.navbar-menu').classList.toggle('is-active');" href="#">Home</a>
            <a class="navbar-item" onclick="document.querySelector('.navbar-menu').classList.toggle('is-active');" href="#skills">Softwareentwicklung</a>
            <a class="navbar-item" onclick="document.querySelector('.navbar-menu').classList.toggle('is-active');" href="#experience">Berufserfahrung</a>
            <a class="navbar-item" onclick="document.querySelector('.navbar-menu').classList.toggle('is-active');" href="#education">Bildungsweg</a>
          </div>
        </div>
      </div>
    </header>
  </div>
</template>
