<template>
    <main>
        <PageJumbotron />
        <CardSection />
        <TheCompanySection />
    </main>
</template>

<script>
import PageJumbotron from './PageJumbotron.vue'
import CardSection from './CardSection.vue'
import TheCompanySection from './TheCompanySection.vue'
export default {
    name: 'PageMain',
    components: {
        PageJumbotron,
        CardSection,
        TheCompanySection
    }
}
</script>

<style lang="scss" scoped>

</style>