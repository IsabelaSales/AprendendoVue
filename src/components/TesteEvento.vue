<template>
    <div class="Teste-Evento">
        <h2>Teste Evento</h2>
        <p @click="deixarMaiuscila">{{mensagem}}</p>
    </div>
</template>
<script>
export default {
    nome: 'TesteEvento',
    data() {
        return{
            mensagem: 'Allan o Gostoso'
        }
    },
    methods: {
        deixarMaiuscila(){
            this.mensagem =this.mensagem.toUpperCase();
        }
    }

}
</script>
<style scoped>

</style>