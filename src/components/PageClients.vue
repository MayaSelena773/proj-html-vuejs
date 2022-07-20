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

        <!--Seconda parte (relationship)-->
        <div class="flex padd-section">
            <div class="big-box padd-text">
                <div class="m-b">
                    <p class="large-text">We Build Relationships</p>
                    <p>Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</p>
                </div>
                <div class="m-b">
                    <p class="large-text">Propietary Processes</p>
                    <p>Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</p>
                </div>
            </div>

            <div class="big-box">
                <div class="flex m-b">
                    <span><i class="fa-solid fa-magnifying-glass-plus orange-icon"></i></span> 
                    <span>
                        <p class="med-text">Accountability</p>
                        <p>Curabitur ac leo nunc vestibulum.</p>
                    </span>
                </div>

                <div class="flex m-b">
                    <span><i class="fa-solid fa-folder-plus orange-icon"></i></span> 
                    <span>
                        <p class="med-text">Transparency</p>
                        <p>Curabitur ac leo nunc vestibulum.</p>
                    </span>
                </div>

                <div class="flex m-b">
                    <span><i class="fa-solid fa-square-poll-vertical orange-icon"></i></span> 
                    <span>
                        <p class="med-text">Investment</p>
                        <p>Curabitur ac leo nunc vestibulum.</p>
                    </span>
                </div>
            </div>
        </div>

        <!--Terza parte (awards)-->
        <div>
            <p class="large-text text-center">Awards</p>

            <div class="cards flex">
                <div class="card-award">
                    <img src="../assets/img/award-a-200x191.png" alt="seo" class="azure">
                    <p>Winner Seo master MAGT Smart Start Award 2017</p>
                </div>
                <div class="card-award">
                    <img src="../assets/img/award-b-200x191.png" alt="social" class="orange-img"> 
                    <p>Top social Media Agencies Next Partner 2018</p>
                </div>
                <div class="card-award">
                    <img src="../assets/img/award-c-200x191.png" alt="provider" class="pink">
                    <p>10 Fastest Growing Abstract Solution Provider 2019</p>
                </div>
                <div class="card-award">
                    <img src="../assets/img/award-d-200x191.png" alt="exellence" class="blue">
                    <p>National Exellence Agencie Award Winner 2020</p>
                </div>
            </div>
        </div>

        <!--Quarta parte (team Avada)-->
        <div class="bg-white flex">
            <div class="big-box">
                <img src="../assets/img/large-testimonial.jpg" alt="l-testimonial" class="large-cons">
            </div>
            <div class="big-box flex-justify-center padd-text">
                <p class="large-text">"The team at Avada Marketing Consultant is fabulous. They helped us unlock our potential online and offline. We have experienced year on year growth due to their progressive approach." </p>
                <p>Kate Schadler</p>
                <p>Marketing Consultant - Abstract</p>
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
    .card-award {
        width: 200px;
        text-align: center;
        margin: 3rem;

        img {
            width: 130px;
        }
        .azure {
            filter: hue-rotate(170deg);
        }
        .orange-img {
            filter: hue-rotate(10deg);
        }
        .pink {
            filter: hue-rotate(340deg);
        }
        .blue {
            filter: hue-rotate(200deg);
        }
    }
}
.bg-white {
    background-color: white;
    width: 100%;
    display: flex;
    justify-content: center;
    padding: 5rem 0;

    .large-cons {
        width: 550px;
        border-radius: 5px;
    }
}
</style>


