<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  },
};
</script>

<template>
  <h1>Template</h1>
</template>

<style lang="scss">
@use './assets/scss/partials/reset' as *;
</style>
