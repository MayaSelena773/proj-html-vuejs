<template>
<!--SEZIONE CLIENTI-->
    <section class="section-clients">

        <!--Prima parte-->
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

        <!--Seconda parte-->
        <div class="flex padd-section">
            <div class="big-box padd-text">
                <p class="large-text">We Build Relationships</p>
                <p>Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</p>
                <p class="large-text">Propietary Processes</p>
                <p>Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</p>
            </div>

            <div class="big-box">
                <div class="flex">
                    <span><i class="fa-solid fa-magnifying-glass-plus orange-icon"></i></span> 
                    <span>
                        <p class="med-text">Accountability</p>
                        <p>Curabitur ac leo nunc vestibulum.</p>
                    </span>
                </div>

                <div class="flex">
                    <span><i class="fa-solid fa-folder-plus orange-icon"></i></span> 
                    <span>
                        <p class="med-text">Transparency</p>
                        <p>Curabitur ac leo nunc vestibulum.</p>
                    </span>
                </div>

                <div class="flex">
                    <span><i class="fa-solid fa-square-poll-vertical orange-icon"></i></span> 
                    <span>
                        <p class="med-text">Investment</p>
                        <p>Curabitur ac leo nunc vestibulum.</p>
                    </span>
                </div>
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
    .padd-section {
        padding: 6rem 0;
    }
    .orange-icon {
        color: $brand_primary_color;
        font-size: 30px;
        border: 3px solid $brand_primary_color;
        border-radius: 10px;
        padding: 15px;
        margin-left: 50px;
        margin-right: 15px;
    }
}
</style>


