<template>
  <div>
    <Navbar />
  </div>
</template>

<script>
import Navbar from "../components/navbar.vue"

export default {
  name: 'IndexPage',
  components: {
    Navbar,
  }
}
</script>

<style lang="scss">
  * {
    font-family:  'SF Pro Display', sans-serif;
  }
</style>
