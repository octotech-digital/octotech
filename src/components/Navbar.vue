<template>
    <v-toolbar flat color="white" app height="100"
    data-scroll-header
    >
      <v-toolbar-title class="headline text-uppercase">
        <span class="oct-title purple--text">
            <img src="../../public/logo-horizontal.png" alt="" height="50" width="auto">
        </span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn flat color="primary" 
        v-for="link in links"
        :key="link.text"
        data-scroll :href="link.route"
        >
          <!-- <v-icon left>{{ link.icon }}</v-icon> -->
          <span>{{ link.text }}</span>
        </v-btn>
      </v-toolbar-items>
    </v-toolbar>
</template>


<script>
export default {
    data() {
      return {
        links: [
          { icon: 'fingerprint', text: 'O que fazemos', route: '#OqueFazemos' },
          { icon: 'favorite_border', text: 'Como fazemos', route: '#metodologia' },
          { icon: 'devices_other', text: 'Cases', route: '#oct-clientes' },
          { icon: 'mail_outline', text: 'Contato', route: '#oct-contato' }
        ]
      }
    }
}
</script>