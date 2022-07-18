<template>
    <main>
        <PageJumbotron />
        <CardSection />
        <TheCompanySection />
        <ProjectsSection />
    </main>
</template>

<script>
import PageJumbotron from './PageJumbotron.vue'
import CardSection from './CardSection.vue'
import TheCompanySection from './TheCompanySection.vue'
import ProjectsSection from './ProjectsSection.vue'
export default {
    name: 'PageMain',
    components: {
        PageJumbotron,
        CardSection,
        TheCompanySection,
        ProjectsSection
    }
}
</script>

<style lang="scss" scoped>

</style>