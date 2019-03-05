<template>
<div class="home">
  <Intro />
  <OqueFazemos />
  <Metodologia />
  <Clientes />
  <Contato />
</div>
</template>

<script>

import Intro from '@/components/pages/Intro'
import OqueFazemos from '@/components/pages/OqueFazemos'
import Metodologia from '@/components/pages/Metodologia'
import Clientes from '@/components/pages/Clientes'
import Contato from '@/components/pages/Contato'

export default {
  name: 'App',
  components: {
    Intro,
    OqueFazemos,
    Metodologia,
    Clientes,
    Contato
  },
  data () {
    return {
      offsetTop: 0,
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
