<template>
    <main>
        <PageJumbotron />
        <PageBusiness />
        <PageBrands />
        <PageConsultant />
    </main>
</template>

<script>
import PageJumbotron from './PageJumbotron.vue'
import PageBusiness from './PageBusiness.vue'
import PageBrands from './PageBrands.vue'
import PageConsultant from './PageConsultant.vue'

export default {
    name:'PageMain',
    components: {
        PageJumbotron,
        PageBusiness,
        PageBrands,
        PageConsultant
    }
}
</script>

<style lang="scss" scoped>

</style>


