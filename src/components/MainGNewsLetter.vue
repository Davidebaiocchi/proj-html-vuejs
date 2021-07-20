<template>
    <div class="container-main">
        <div class="container">
            <div class="left">
                <h4>NewsLetter</h4>
                <h2><span>Know</span> First</h2>
                <p>Follow closely and receive content about our company and the news of the current market.</p>
            </div>
            <div class="right">
                <input type="text" placeholder="Name">
                <input type="text" placeholder="Email">
                <br>
                <button @click="rispReg()">Subscribe</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
name : 'MainGNewsLetter',

    methods: {
        rispReg() {
            window.alert('Ciao')
        }
    }
}
</script>


<style scoped lang=scss>
    @import '@/style/9MainNewsLetter.scss';
</style>