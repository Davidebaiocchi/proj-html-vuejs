<template>
    <div class="container">
        <div class="section">
            <h4>Our Business Areas</h4>
            <h2>Excellence in <span>Services</span> </h2>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Adipisci commodi placeat beatae odit velit animi sint assumenda inventore <br> ea ullam nulla illum impedit doloribus laboriosam veniam exercitationem, accusamus a quas?</p>
            <button>See all</button>
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
</template>

<script>
export default {
name : 'MainCSliderlight'
}
</script>

<style scoped lang=scss>

    /* #048383 */

    .container {
        background-color: #eef4ed;
        padding: 100px 410px;
    }

    .section {
        margin-left: 30px;
    }

    button {
        color: white;
        background-color: #048383;
        height: 40px;
        padding: 0 18px;
        text-transform: uppercase;
        font-size: 14px;
        font-weight: bolder;
        border-radius: 3px;
        margin-right: 15px;
    }

    button:hover {
        cursor: pointer;
        color: black;
        background: rgb(238,174,202);
        background: radial-gradient(circle, rgba(238,174,202,1) 0%, rgba(148,187,233,1) 100%);
    }

    h4 {
        color: #048383;
        text-transform: uppercase;
    }

    h2 {
    font-size: 40px;
    color: rgb(37, 37, 37);
    margin: 20px 0;
    font-family:Verdana, Geneva, Tahoma, sans-serif ;
    }

    h2 span {
      background-color: #04838323;
      padding: 3px 10px;
      color: #048383;
    }

    p {
        color: grey;
        margin-bottom: 10px;
        display: inline-block;
        margin-right: 200px;
    }

    .cards {
        display: flex;
        flex-wrap: wrap;
    }

    .card h3 {
        margin: 10px 0;
        font-size: 22px;
        font-weight: bold;
    }

    i {
        color: #048383;
        font-size: 35px;
        position: relative;
        bottom: 30px;
    }

    .card {
        width: 300px;
        background-color: white;
        margin: 30px;
        border-radius: 10px;
        padding: 50px 30px;
    }

    .card:hover {
        scale: 1.2;
        cursor: pointer;
        background: rgb(238,174,202);
        background: radial-gradient(circle, rgba(238,174,202,1) 0%, rgba(148,187,233,1) 100%);
    }

    .card p {
        margin: 0;
    }

    .arrow {
        position: relative;
        left: 180px;
        bottom: 30px;
        font-size: 20px;
    }

</style>