<template>
  <v-app class="white">
    <Navbar />
    
    <v-content>
      <router-view></router-view>
    </v-content>

  </v-app>
</template>

<script>
import Navbar from '@/components/Navbar'

export default {
  name: 'App',
  components: {
    Navbar
  },
  data () {
    return {
      //
    }
  }
}
</script>

<style>
  .oct-title{
    font-family: 'Comfortaa', cursive;
    text-transform: none;
  }
</style>