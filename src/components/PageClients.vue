<template>
<!--Sezione clienti-->
    <section class="section-clients">

        <!--testo-->
        <div class="flex">
            <div class="big-box padd-text">
                <h3 class="med-title padd">We Boost Our Clients' Bottom Line by Optimizing Their Growth Potential.</h3>
                <p class="med-text">Quisque aliquet, libero consequat elementum convallis, erat risus inperdiet pellentesque sem eque eget.</p>
                <span class="button btn-orange padd-btn">Why Work With Us</span>
            </div>
            <!--immagine-->
            <div>
                <img src="../assets/img/we-boost-our-clients.jpg" alt="clients" class="big-box little-rad">
            </div>
        </div>

    </section>
</template>

<script>
export default {
    name:'PageClients'
}
</script>

<style lang="scss" scoped>
@import './style/vars.scss';

.section-clients {
    background-color: rgb(245, 244, 246);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 3rem;
    padding-top: 6rem;

    .padd-text {
        padding-right: 200px;
    }
    .big-box {
        width: 600px;

        p {
            line-height: 2rem;
            margin-bottom: 1rem;
        }
    }
    .little-rad {
        border-radius: 10px;
    }
}
</style>


