<template>
    <main>
        <PageJumbotron />
        <PageBusiness />
    </main>
</template>

<script>
import PageJumbotron from './PageJumbotron.vue'
import PageBusiness from './PageBusiness.vue'

export default {
    name:'PageMain',
    components: {
        PageJumbotron,
        PageBusiness
    }
}
</script>

<style lang="scss" scoped>

</style>


