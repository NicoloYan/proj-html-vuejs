<template>
    <main>
        <PageJumbotron />
        <CardSection />
    </main>
</template>

<script>
import PageJumbotron from './PageJumbotron.vue'
import CardSection from './CardSection.vue'
export default {
    name: 'PageMain',
    components: {
        PageJumbotron,
        CardSection,
    }
}
</script>

<style lang="scss" scoped>

</style>