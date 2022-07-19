<template>
<!--CONTAINER BOXES-->
    <section class="container">
        <!--Primo blocco con immagine e testo-->
        <div class="flex block">
            <div class="side-box"><img src="../assets/img/sales-development-training.webp" alt="training" class="img-left"></div>
             
            <div class="side-box">
                <p>Business Growth</p>
                <h3 class="med-title">Increase Brand Awareness</h3>
                <p class="med-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.</p>
                <span class="button btn-orange padd-btn">Get a Consultation</span>
            </div>
        </div>

        <!--Secondo blocco con testo e immagine-->
        <div class="flex block">
            <div class="side-box">
                <p>Investors In People</p>
                <h3 class="med-title">In-House Sales Training</h3>
                <p class="med-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.</p>
                <span class="button btn-orange padd-btn">Get a Consultation</span>
            </div> 
            <div class="side-box"><img src="../assets/img/1660179-full.jpg" alt="woman" class="img-right"></div>
        </div>

        <!--Terzo blocco con immagine e testo-->
        <div class="flex block">
            <div class="side-box"><img src="../assets/img/digital-marketing-strategy.webp" alt="strategy" class="img-left"></div> 
            <div class="side-box">
                <p>Social Media Analysis</p>
                <h3 class="med-title">Harness Your Social Proof</h3>
                <p class="med-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.</p>
                <span class="button btn-orange padd-btn">Get a Consultation</span>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name:'PageBusiness'
}
</script>

<style lang="scss" scoped>
@import './style/vars.scss';

.container {
    margin-top: 2rem;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;

    .block {
        margin: 6rem 0;
    }

    .side-box {
        width: 500px;
        height: 500px;

        .img-left {
            width: 90%;
        } 

        .img-right {
            width: 600px;
            height: 500px;
        }

        h3 {
            line-height: 3rem;
            margin: 1rem;
        }

        p {
            line-height: 1.5rem;
            margin: 1rem;
        }
    }
}
</style>


