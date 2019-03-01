<template>
    <v-layout fluid="true" 
    row wrap
    >
        
            <v-flex xs12 md6> 
                <v-parallax src="http://i68.tinypic.com/2hg5q38.jpg"></v-parallax>
            </v-flex>
            <v-flex xs12 md6> 
                <v-container grid-list-lg>
                    <h1 class="display-2 text-md-center primary--text oct-mg-top-2x">Como Fazemos</h1>
                    
                    <p class="subheading oct-mg-top">Para maximizar o processo de trabalho utilizamos o <strong class="primary--text">Double Diamond</strong>, que nada mais é do que uma maneira simples de descrever o processo <em>Design thinking</em>, Usamos sua estrutura para entender os clientes ou usuários e seus problemas, explorando modos inovadores e criativos de solucioná-los e com isso causar um impacto positivo para os usuários.</p>
                    <p class="subheading oct-mg-top">Utilizando o <strong class="primary--text">double Diamond</strong> podemos abordar problemas e soluções usando 2 tipos diferentes de pensamentos: <em>Convergir</em> e <em>divergir</em>.</p>
                    <br>
                    <div class="text-md-center">

                        <v-btn outline large 
                        color="accent"
                        class="oct-btn"
                        router
                        >
                            Saiba Mais                    
                        </v-btn>
                    </div>
                </v-container>
            </v-flex>
    </v-layout>
</template>

<style>
    .oct-mg-top{
        margin-top: 24px;
    }
    .oct-mg-top-2x{
        margin-top: 48px;
    }
</style>

<script>
export default {
    
}
</script>