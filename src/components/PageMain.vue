<template>
    <main>
        <PageJumbotron />
        <PageBusiness />
        <PageBrands />
    </main>
</template>

<script>
import PageJumbotron from './PageJumbotron.vue'
import PageBusiness from './PageBusiness.vue'
import PageBrands from './PageBrands.vue'

export default {
    name:'PageMain',
    components: {
        PageJumbotron,
        PageBusiness,
        PageBrands
    }
}
</script>

<style lang="scss" scoped>

</style>


