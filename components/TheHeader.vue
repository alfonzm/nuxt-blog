<template lang="pug">
  header
    nav
      .tw-mr-6.tw-flex-grow
        nuxt-link.tw-text-3xl(to="/") Blog Name
      .tw-flex
        .tw-mr-6
          nuxt-link(to="/about") About
        .tw-mr-6
          nuxt-link(to="/") Link 2
        .tw-mr-6
          nuxt-link(to="/") Link 3
</template>

<style lang="sass">
nav
  @apply tw-py-3 tw-flex tw-items-center tw-justify-between
</style>
