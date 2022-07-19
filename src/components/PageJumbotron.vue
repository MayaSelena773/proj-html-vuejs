<template>
<!--JUMBOTRON-->
    <section class="jumbotron">

        <!--Titolo e presentazione a sinistra-->
        <div class="text-left">
            <h1 class="large-title">Unlock Your Online Growth Potential</h1>
            <p class="large-text padd">Online marketing to secure customer retention, leads, and sales. We focus on the bigger picture.</p>
            <span class="button btn-white">Our Services <i class="fa-solid fa-arrow-right"></i></span>
        </div>

        <!--Inputs contatti centrale-->
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

        <!--Box piccoli Demos e Sales in alto a destra-->
        <div class="sale">
            <div class="box">
                <i class="fa-solid fa-box little-icon"></i> 
                <span>Demos</span> 
            </div>
            <div class="box">
                <span class="large-text green"><small><sup>$</sup></small>39</span>
                <span>On Sale</span>
            </div>
        </div>

    </section>
</template>

<script>
export default {
    name: 'PageJumbotron'
}
</script>

<style lang="scss" scoped>
@import './style/vars.scss';

.jumbotron {
    background-image: url(../assets/img/marketing-intro.jpg);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    color: white;
    height: 700px;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    position: relative;

    .text-left {
        text-align: left;
        padding: 0 5rem;
        margin-left: 150px;
        width: 45%;
        
        .btn-white {
            background-color: white;
            color: black;
            display: inline-block;
            margin: 2rem 0;
        }
    }
    .contacts-input {
        background-color: white;
        border-radius: 10px;
        color: black;
        text-align: center;
        line-height: 2rem;
        padding: 25px;
        position: absolute;
        bottom: -20px;
        right: 275px;
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
    .sale {
        position: absolute;
        top: 30px;
        right: 10px;

        .box {
            background-color: white;
            color: rgb(54, 69, 92);
            border-radius: 5px;
            margin: 0.5rem;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 0.5rem;

            .little-icon {
                font-size: 30px;
            }

            .green {
                color: rgb(79, 208, 135);
            }
        }
    }
}
</style>


