<template>
<!--HEADER con: logo, nav link, numero e button-->
    <header>
        <div class="flex">
            <img class="logo" src="../assets/img/mc-favicon.png" alt="logo">
            <p>AvadaConsultant</p>
        </div>

        <div>
            <ul class="flex">
                <li>
                    <a href="#">link</a>
                </li>
                <li>
                    <a href="#">Link</a>
                </li>
                <li>
                    <a href="#">link</a>
                </li>
                <li>
                    <a href="#">link</a>
                </li>
                <li>
                    <a href="#">link</a>
                </li>
                <li>
                    <a href="#">link</a>
                </li>
            </ul>
        </div>

        <div class="flex">numero tel e button</div>
    </header>
</template>

<script>
export default {
    name:'PageHeader'
}
</script>

<style lang="scss" scoped>

header {
    display: flex;
    justify-content: center;
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
}

</style>


