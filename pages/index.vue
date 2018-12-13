<template lang="pug">
  section.container
    div
      logo
      h1.title myHomeApp
      h2.subtitle My home control the Features.

      .links
        a(href="/switch").button--green Goto Switch
      br
      br
      .links
        a(href="https://github.com/yoshiki-0428/myHomeApp" target="_blank").button--grey GitHub

</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
