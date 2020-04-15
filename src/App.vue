<template>
  <app-layout></app-layout>
</template>

<script>
import LayoutVue from './components/Layout.vue';

export default {
  name: 'App',

  components: {
    appLayout: LayoutVue
  },

  data: () => ({
    //
  })
};
</script>

<style lang="scss">
body {
  font-family: 'Roboto';
}
</style>
