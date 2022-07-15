<template>
<!--HEADER con: logo, nav link, numero e button-->
    <header>
        <div class="flex-center">
            <img class="logo" src="../assets/img/mc-favicon.png" alt="logo">
            <p>AvadaConsultant</p>
        </div>

        <div>
            <ul class="flex">
                <li>
                    <a href="#" class="orange">Home <i class="fa-solid fa-chevron-down"></i></a>
                </li>
                <li>
                    <a href="#">Services <i class="fa-solid fa-chevron-down"></i></a>
                </li>
                <li>
                    <a href="#">Why Us</a>
                </li>
                <li>
                    <a href="#">Case Studies</a>
                </li>
                <li>
                    <a href="#">About</a>
                </li>
                <li>
                    <a href="#">Blog</a>
                </li>
            </ul>
        </div>

        <div class="flex-center">
            <span><i class="fa-solid fa-phone orange"></i>(555) 802 1234</span>
            <span class="button light-orange">Free Quote</span>
        </div>
    </header>
</template>

<script>
export default {
    name:'PageHeader'
}
</script>

<style lang="scss" scoped>
@import './style/vars.scss';

header {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100px;
    background-color: lightblue;

    div {
        padding: 20px;
    }

    ul {
        list-style-type: none;

        li {
            padding-left: 5px;
        }
    }

    .logo {
        display: inline-block;
    }

    p {
        font-weight: bold;
    }

    i {
        padding-right: 10px;
    }
}

</style>


