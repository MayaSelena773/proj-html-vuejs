<template>
    <main>
        <PageJumbotron />
        <PageBusiness />
        <PageBrands />
        <PageConsultant />
        <PageClients />
    </main>
</template>

<script>
import PageJumbotron from './PageJumbotron.vue'
import PageBusiness from './PageBusiness.vue'
import PageBrands from './PageBrands.vue'
import PageConsultant from './PageConsultant.vue'
import PageClients from './PageClients.vue'

export default {
    name:'PageMain',
    components: {
        PageJumbotron,
        PageBusiness,
        PageBrands,
        PageConsultant,
        PageClients
    }
}
</script>

<style lang="scss" scoped>

</style>


