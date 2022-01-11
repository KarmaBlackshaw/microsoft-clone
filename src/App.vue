<template>
  <div id="nav">
    <TheNavbar/>
  </div>

  <router-view/>
</template>

<script>
import TheNavbar from '@/components/the-navbar/TheNavbar'

export default {
  components: {
    TheNavbar
  },

  setup () {
    return {}
  }
}
</script>
