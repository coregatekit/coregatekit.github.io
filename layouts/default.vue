<template>
  <div>
    <Topbar></Topbar>
    <b-container class="sk-container">
      <Nuxt></Nuxt>
    </b-container>
  </div>
</template>

<script>
import Topbar from '~/components/Topbar.vue'
export default {}
</script>

<style>
.sk-container {
  margin: 40px;
}
</style>