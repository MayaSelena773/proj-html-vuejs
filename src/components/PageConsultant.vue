<template>
<!--Sezione consulenti-->
    <section class="section-consultant">
        <h3 class="med-title padd">Trusted by Leading Organisations</h3>

        <div class="flex-cards">
            <div class="card">
                <img src="../assets/img/case-studies-1.jpg" alt="case1" class="cons-img"> 
                <div>
                    <p class="large-text padd">How Spaces attracted five million visitors by improving the content</p>
                    <h3 class="med-title padd">200 %</h3>
                    <p>Higher revenue from digital</p>
                </div>
            </div>
            <div class="card">
                <img src="../assets/img/case-studies-4.jpg" alt="case4" class="cons-img">
                <div>
                    <p class="large-text padd">Creativity helped Hemisferio to increase their brand reach vertically</p>
                    <h3 class="med-title padd">10x</h3>
                    <p>Sales increase with the same ad spend</p>
                </div>
            </div>
            <div class="card">
                <img src="../assets/img/case-studies-6-1200x1349.jpg" alt="case6" class="cons-img">
                <div>
                    <p class="large-text padd">How DigitalBox used Al-powered data insight to boost sales</p>
                    <h3 class="med-title padd">3-year</h3>
                    <p>Partnership with Avada Consultant</p>
                </div>
            </div>
        </div>

        <div class="button btn-orange padd-btn">Read More Case Studies</div>

    </section>
</template>

<script>
export default {
    name:'PageConsultant'
}
</script>

<style lang="scss" scoped>
@import './style/vars.scss';

.section-consultant {
    text-align: center;
    margin: 6rem 0;

    .flex-cards {
        display: flex;
        justify-content: center;

        .card {
            width: 350px;
            margin-block: 4rem;
            margin-right: 3rem;
            text-align: left;

            .cons-img {
                width: auto;
                height: 400px;
            }
        }
    }

    
}

</style>


