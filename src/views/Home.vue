<template>
<div class="home">
  <Intro />
  <OqueFazemos />
  <Metodologia />
</div>
</template>

<script>

import Intro from '@/components/pages/Intro'
import OqueFazemos from '@/components/pages/OqueFazemos'
import Metodologia from '@/components/pages/Metodologia'

export default {
  name: 'App',
  components: {
    Intro,
    OqueFazemos,
    Metodologia
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
