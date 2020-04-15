<template>
  <div>
    <app-navbar />
    <main>
      <router-view />
    </main>
  </div>
</template>

<script>
import NavbarVue from './Navbar.vue';

export default {
  components: {
    appNavbar: NavbarVue
  }
};
</script>

<style scoped>
main {
  padding: 30px;
}
</style>
