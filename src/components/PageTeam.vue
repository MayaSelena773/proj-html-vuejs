<template>
<!--Sezione team-->
    <section class="bg-black">
        <div class="team-container flex">
            <!--Titolo e paragrafo-->
            <div class="side-box">
                <h2 class="large-title padd">Let's Make Things Appen</h2>
                <p class="med-text padd">Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</p>
                <hr class="padd-text">
                <p class="padd">"The team at Avada Marketing Consultant is fabulous. They helped us unlock our potential online and offline. We have experienced year on year growth due to their progressive approach."</p>
                <p>George Anderson</p>
                <p>DigitalBox CEO</p>
            </div>
            <!--Inputs contatti-->
            <div class="side-box">
                <div class="contacts-input">
                    <div class="account">
                        <img src="../assets/img/marketing-consultant-expert.jpg" alt="consultant" class="account-lg">
                        <p class="large-text">Richard Madsen</p>
                        <p class="gray-text">marketing consultant expert</p>
                        <span class="orange"><i class="fa-solid fa-phone"></i>(555) 802 1234</span>
                    </div>

                    <div class="inputs">
                        <input type="text" placeholder="Your Name*" class="single-input">
                        <input type="email" placeholder="Your Email*" class="single-input">
                        <input type="number" placeholder="Your Phone Number*" class="single-input">
                    </div>

                    <span class="button btn-orange">Get a Callback</span>
                    <p class="gray-text padd">By Submitting my data I agree to be contacted</p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name:'PageTeam'
}
</script>

<style lang="scss" scoped>
@import './style/vars.scss';

.bg-black {
    background-color: black;
    color: white;
    display: flex;
    justify-content: center;

    .team-container {
        width: 70%;
        margin: 3rem;
        .side-box {
            width: 50%;

            .contacts-input {
                background-color: white;
                margin: 2rem 4rem;
                border-radius: 10px;
                color: black;
                text-align: center;
                line-height: 2rem;
                padding: 25px;
                box-shadow: inset 0 -4px 3px lightgray;

                .account-lg {
                    width: 80px;
                    height: 80px;
                    border-radius: 50%;
                }
                .inputs {
                    display: flex;
                    flex-direction: column;

                    .single-input {
                        padding: 15px;
                        margin: 5px;
                        border-radius: 5px;
                        border-color: gray;
                    }
                }
            }
        }
    }
}
</style>


