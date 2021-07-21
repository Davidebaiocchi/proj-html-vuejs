<template>
    <div class="container">
       <div class="section">
            <h4>Our Business Areas</h4>
            <h2>Latest <span>News</span> </h2>
            <p>Every week we publish content about what is best in the business world.</p>
            <button @click="rispReg()">See all</button>
        </div>
        <div class="cards">
            <div class="card1 card">
                <span>Incrising creativity is possible for everyone</span>
            </div>
            <div class="card2 card">
                <span> Because market research is part of the business plan</span>
            </div>
            <div class="card3 card">
                <span>Working from home is now a trend</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
name : 'MainFNews',
    methods: {
            rispReg() {
                window.alert('Sito in manutenzione')
            }
        }
    }
</script>

<style scoped lang=scss>
    @import '@/style/8MainNews.scss';
    @import '@/style/0Commons.scss';
</style>