<template> 
    <div class="container-main">


        <div class="container">
            <div class="section">
                <h4>Our Business Areas</h4>
                <h2>Excellence in <span>Services</span> </h2>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Adipisci commodi placeat beatae odit velit animi sint assumenda inventore?</p>
                <button @click="rispReg()" >See all</button>
            </div>
            
            <div class="cards">
                <div class="card">
                    <i class="fab fa-audible"></i>  <i class="fas fa-arrow-right arrow"></i>
                    <h3>Audit & Assurance</h3>
                    <p>Lorem ipsum dolor sit amet consectetur amet consectetur adipisicing elit.</p>
                </div>
                <div class="card">
                    <i class="fas fa-briefcase"></i>  <i class="fas fa-arrow-right arrow"></i>
                    <h3>Financial Advisory</h3>
                    <p>Lorem ipsum dolor sit amet consectetur amet consectetur adipisicing elit.</p>
                </div>
                <div class="card">
                    <i class="fas fa-signal"></i> <i class="fas fa-arrow-right arrow"></i>
                    <h3>Analytics and M&A</h3>
                    <p>Lorem ipsum dolor sit amet consectetur amet consectetur adipisicing elit.</p>
                </div>
                <div class="card">
                    <i class="fas fa-plane"></i> <i class="fas fa-arrow-right arrow"></i>
                    <h3>Middle Marketing</h3>
                    <p>Lorem ipsum dolor sit amet consectetur amet consectetur adipisicing elit.</p>
                </div>
                <div class="card">
                    <i class="fas fa-balance-scale"></i> <i class="fas fa-arrow-right arrow"></i>
                    <h3>Legal Consulting</h3>
                    <p>Lorem ipsum dolor sit amet consectetur amet consectetur adipisicing elit.</p>
                </div>
                <div class="card">
                    <i class="fas fa-cash-register"></i> <i class="fas fa-arrow-right arrow"></i>
                    <h3>Regularity Risk</h3>
                    <p>Lorem ipsum dolor sit amet consectetur amet consectetur adipisicing elit.</p>
                </div>
            </div>    
        </div>       
    </div>
</template>

<script>
export default {
name : 'MainCSliderlight',
    methods: {
        rispReg() {
            window.alert('Sito in manutenzione')
        }
    }
}

</script>

<style scoped lang=scss>
    @import '@/style/0Commons.scss';
    @import '@/style/5mainSliderLight.scss';    
</style>