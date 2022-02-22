<template>
<div class="w-full">
  <AppHeader />
  <div class="w-full flex">
    <Heros />
  </div>
</div>
</template>

<script>
  import AppHeader from "./components/AppHeader";
  import Heros from "./components/Heros"
export default {
  components: {
    AppHeader, Heros
  },
};
</script>

<style></style>
