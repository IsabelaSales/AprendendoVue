<template>
    <div class="testando-if"> 
        <h1 v-if="podeV">Teste1</h1>
        <h1 v-else>Teste2</h1>

    </div>
</template>

<script>
export default {
    name: 'TesteIf',
    data(){
        return{
            podeV: true
        }
    }
}
</script>

<style scoped>

</style>>
