<template>
    <v-container grid-list-lg> 
        <v-layout row wrap 
        class="oct-intro-height"
        align-center="true">
            <v-flex xs12 md12 class="text-md-center">
                <h1 class="display-4 accent--text font-weight-bold hidden-sm-and-down">
                    Inovar e transformar com criatividade.
                </h1>
                <h1 class="display-2 accent--text font-weight-bold hidden-md-and-up text-md-center">
                    Inovar e transformar com criatividade.
                </h1>
                <p class="headline primary--text">Ajudamos você e sua empresa a criar produtos inovadores de forma ágil e criativa.</p>
                <br>
                <br>
                <v-btn outline large 
                color="accent"
                class="oct-btn"
                >
                     Saiba Mais                    
                </v-btn>
            </v-flex>
        </v-layout>
    </v-container>

  <!-- <v-parallax src="https://cdn.vuetifyjs.com/images/parallax/material.jpg"></v-parallax> -->
</template>

<style>
    .oct-intro-height{
        min-height: 70vh;
    }
    button.oct-btn{
        color:#2A0845 !important;
        border-color: #46CAA5 !important;
    }
    .oct-btn:hover{
        background: #2A0845 !important;
        color: #46CAA5 !important;
        border: none !important;
    }
</style>
<script>
export default {
    
}
</script>