<template>
  <div id="app">
    <PageHeader :links="navLinks"/>
    <PageMain />
    <PageFooter :infos="contactInfo"/>
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
  },
  data() {
        return {
            navLinks: [
                {
                    text: 'HOME',
                    url: '#',
                    active: false
                },
                {
                    text: 'ABOUT',
                    url: '#',
                    active: false
                },
                {
                    text: 'PROJECTS',
                    url: '#',
                    active: false
                },
                {
                    text: 'PROCESS',
                    url: '#',
                    active: true
                },
                {
                    text: 'TESTIMONIALS',
                    url: '#',
                    active: false
                }
                
                
            ],
            contactInfo: [
                {
                    icon: "fa-solid fa-phone",
                    text: '1 (305) 1234-5678'
                },
                {
                    icon: "fa-solid fa-envelope",
                    text: 'hello@example.com'
                },
                {
                    icon: "fa-solid fa-location-dot",
                    text: 'Main Avenue, 987'
                }
            ]
        }
    },
   props: {
        links: Array,
        infos: Array
    },
}
</script>

<style lang="scss">
@import '@/assets/scss/style.scss';
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;900&display=swap');
body {
  font-family: 'Roboto', sans-serif;
}
</style>
