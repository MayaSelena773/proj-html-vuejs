<template>
<!--SEZIONE BRANDS-->
    <section class="brands-section">
        <!--Titolo e sottotitolo-->
        <div>
            <h3 class="med-title">Some Brands We Work With</h3>
            <p class="med-text">Quisque aliquet, libero consequat elementum convallis.</p>
        </div>
        <!--Lista brands-->
        <div>
            <ul>
                <li><img src="../assets/img/abstract.png" alt="abstract"></li>
                <li><img src="../assets/img/cglobal.png" alt="cglobal"></li>
                <li><img src="../assets/img/next.png" alt="next"></li>
                <li><img src="../assets/img/hemisferio.png" alt="hemisferio"></li>
                <li><img src="../assets/img/spaces.png" alt="spaces"></li>
                <li><img src="../assets/img/digitalbox.png" alt="digitalbox"></li>
            </ul>
        </div>
        <!--Contatto consulente marketing-->
        <div class="back-shadow">
            <div class="flex">
                <img src="../assets/img/marketing-expert-cta.png" alt="expert" class="account-sm"> 
                <div>
                    <span><h4>Sandy Reiff</h4></span>
                    <span><p>Marketing Consultant Expert</p></span>
                </div>
            </div>
            <div><p class="med-text">Drive Leads and Sales with Avada</p></div>
            <div class="button light-orange"><i class="fa-solid fa-phone"></i>(555) 802 1234</div>
        </div>

    </section>
</template>

<script>
export default {
    name:'PageBrands'
}
</script>

<style lang="scss" scoped>
@import './style/vars.scss';

.brands-section {
    text-align: center;

    h3 {
        margin: 1rem 0;
    }
    ul {
        display: flex;
        justify-content: center;

        img {
            width: 150px;
            margin: 5rem 2rem;
        }
    }
    .back-shadow {
        box-shadow: inset 0 -4px 3px $brand_secondary_color;
        border-radius: 10px;
        margin: 1rem 7rem;
        height: 90px;
        display: flex;
        justify-content: space-around;
        align-items: center;

        .account-sm {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            margin-right: 10px;
        } 
    }
}

</style>


