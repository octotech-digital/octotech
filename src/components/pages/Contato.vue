<template>
    <v-layout row wrap fluid="true"
    id="oct-contato"
    class="grey darken-4"
    >
        <v-container class="white--text">
            <v-layout row wrap>

            <v-flex xs12 md6>
                <h4 class="subheading">© OCTOTECH, 2019. TODOS OS DIREITOS RESERVADOS.</h4>
            </v-flex>
            <v-flex xs12 md3></v-flex>
            <v-flex xs12 md3>
                <h4 class="subheading">REDES SOCIAIS</h4>
                <v-btn flat icon dark 
                v-for="icon in icons"
                :key="icon.IconName"
                :href="icon.Link"
                target="_blank"
                >
                    <v-icon
                    class="pa-2"
                    >
                        {{ icon.IconName }}
                    </v-icon>
                </v-btn>
            </v-flex>
            </v-layout>
        </v-container>
    </v-layout>
</template>

<script>
export default {
    data() {
        return {
            icons: [
                { Link: "mailto:contato@octotech.com.br", IconName: "fas fa-envelope" },
                { Link: "https://www.linkedin.com/company/13071373/", IconName: "fab fa-linkedin" }
            ]
        }
    },
}
</script>