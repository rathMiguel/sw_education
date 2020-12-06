<template lang="pug">
  div
    header
      nav.navbar.navbar-dark.bg-dark
        a.navbar-brand(href='#')
          img(src="~assets/img/logo.png", alt="alt", width="40").mr-2
          |わっちゃ！
    Nuxt
    footer
      p.text-center: small Copyright (c) Allrights reserved.
</template>

<style lang="scss" scoped>
  .navbar{
    background-color: dark-orage;
  }
  footer{
    color: #000;
    background-color: #EEE;
    padding-top: 1em;
    padding-bottom: .2em;
  }
</style>
