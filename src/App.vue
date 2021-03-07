<template>
  <div id="app" class="font-sans min-h-screen p-24">
    <Dashboard />
  </div>
</template>

<script>
import Dashboard from "./components/Dashboard.vue";

export default {
  name: "app",
  components: {
    Dashboard,
  },
};
</script>
