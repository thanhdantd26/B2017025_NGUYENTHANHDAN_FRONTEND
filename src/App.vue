<script>
import AppHeader from "@/components/AppHeader.vue";

export default {
  components: {
    AppHeader,
  },
};
</script>

<template class="container">
  <div id="app">
    <AppHeader />

    <div class="container mt-3">
      <router-view />
    </div>
  </div>
</template>

<style>
.page {
  max-width: 200px;
  margin: auto;
}
</style>