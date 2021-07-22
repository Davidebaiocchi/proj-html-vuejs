<template>
    <div class="container">
        <div class="consulting">
            <h3>Fusion & Acquisition</h3>
            <h2>Insurance <br> Consulting</h2>
            <input type="text" placeholder="Name">
            <input type="text" placeholder="Email">
            <br>
            <input type="text" placeholder="Phone">
            <input type="text" placeholder="More info">
            <br>
            <button @click="rispReg()">get it touch</button>
            <button @click="rispReg()" class="btn-white">Read more</button>
        </div>
    </div>
</template>

<script>
export default {
name : 'MainJumbotron',
methods: {
        rispReg() {
            window.alert('Ciao')
        }
    }
}

</script>

<style scoped lang=scss>
    @import '@/style/3mainJumbotron.scss';
</style>