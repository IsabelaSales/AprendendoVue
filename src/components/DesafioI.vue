<template>
    <div class="DesafioI">
        <h2>Meu Contador {{contador}}</h2>
        <button @click="butaoadd">+</button>
        <button @click="butaodmn">-</button>
    </div>
</template>
<script>
export default {
    name:'DesafioI',
    data(){
        return{
         contador: 0
        }
    },
    methods: {
        butaoadd() {
            this.contador++
        },
        butaodmn() {
            this.contador--
        }

    }
}
</script>
<style scoped>

</style>