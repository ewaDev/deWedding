<template>
  <div class="inheritHeightWidth">
    <Navbar />
    <nuxt style="height:90%"/>
  </div>
</template>

<script>
import Navbar from './partials/navbar';
export default {
  components: {
    Navbar
  },
  modules: ['bootstrap-vue/nuxt']

}
</script>


<style>

</style>
