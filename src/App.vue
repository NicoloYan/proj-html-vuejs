<template>
  <div id="app">
    <PageHeader />
    <PageMain />
    <PageFooter />
  </div>
</template>

<script>
import PageHeader from './components/PageHeader.vue'
import PageMain from './components/PageMain.vue'
import PageFooter from './components/PageFooter.vue'

export default {
  name: 'App',
  components: {
    PageHeader,
    PageMain,
    PageFooter
  }
}
</script>

<style lang="scss">
@import '@/assets/scss/style.scss';
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;900&display=swap');
body {
  font-family: 'Roboto', sans-serif;
}
</style>
