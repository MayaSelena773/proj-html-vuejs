<template>
<!--HEADER con: logo, nav link, numero e button-->
    <header>
        <div class="flex-center">
            <img class="logo" src="../assets/img/avada-marketing-logo-2x-200x37.png" alt="logo">
        </div>

        <div>
            <ul class="flex">
                <li v-for="(navItem, index) in navItems" :key="index">
                    <a :href="navItem.link" class="orange">{{navItem.name}}</a>
                    <i class="fa-solid fa-chevron-down little-icon"></i>
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
    name:'PageHeader',
    data(){
        return {
            navItems: [
                {
                    name:"Home",
                    link:"#",
                },
                {
                    name:"Services",
                    link:"#",
                },
                {
                    name:"Why Us",
                    link:"#",
                },
                {
                    name:"Case Studies",
                    link:"#",
                },
                {
                    name:"About",
                    link:"#",
                },
                {
                    name:"Blog",
                    link:"#",
                }
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
@import './style/vars.scss';

header {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100px;

    div {
        padding: 20px;
    }

    ul {
        list-style-type: none;

        li {
            padding-left: 10px;
            padding-right: 15px;
        }
    }

    .logo {
        display: inline-block;
    }

    p {
        font-weight: bold;
        padding-left: 15px;
    }

    i {
        padding-right: 10px;
    }

    .little-icon {
        font-size: 10px;
        padding-left: 5px;
    }
}

</style>


