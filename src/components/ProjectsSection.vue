<template>
    <section>
        <div class="container65">
            <span class="text_center heading">
                WE DO MORE FOR EVERYONE
            </span>
            <h2 class="text_center">
                Actions & <span class="projects">Projects</span>
            </h2>
            <div class="text_center menu_items">
                <a class="selected" href="#">
                    ALL
                </a>
                <a href="#">
                    INSTITUTIONAL
                </a>
                <a href="#">
                    SOCIAL
                </a>
                <a href="#">
                    EVENTS
                </a>
                <a href="#">
                    INNOVATION
                </a>
                <a href="#">
                    ENVIRONMENT
                </a>
                <a href="#">
                    TECHNOLOGY
                </a>
            </div>
            <div class="cards_area flex_space_between">
                <div class="card">
                    <img src="../assets/img/project-1.jpg" alt="project 1">
                    <span class="card_text">Academic professional program in social media</span>
                </div>

                <div class="card">
                    <img src="../assets/img/project-2.jpg" alt="project 1">
                    <span class="card_text">President's speech at the annual meeting</span>
                </div>

                <div class="card">
                    <img src="../assets/img/project-3.jpg" alt="project 1">
                    <span class="card_text">International business trip to Shanghai</span>
                </div>

                <div class="card">
                    <img src="../assets/img/project-4.jpg" alt="project 1">
                    <span class="card_text">Technology workshop with education theme</span>
                </div>

                <div class="card">
                    <img src="../assets/img/project-5.jpg" alt="project 1">
                    <span class="card_text">Donation of clothes and food to the partner NGO</span>
                </div>

                <div class="card">
                    <img src="../assets/img/project-6.jpg" alt="project 1">
                    <span class="card_text">Confraternization of the procurement team</span>
                </div>

            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'ProjectsSection'
}
</script>

<style lang="scss" scoped>
section {
    color: white;
    background-color: black;
}
.heading {
    display: block;
    margin-bottom: 40px;
}
.container65 {
    padding: 100px 0;
}
.projects {
    background-color: #0e272d;
    padding: 10px;
}
.selected {
    background-color: #0e272d;
    padding: 10px;
}
h2 {
    margin-bottom: 70px
}
.menu_items {
    align-items: center;
    margin-bottom: 40px;
    display: block;
    a {
        margin: 0 10px;
    }
}
.cards_area {
    flex-wrap: wrap;
}
.card {
    width: calc((100% / 3) - 20px);
    position: relative;
    margin-bottom: 20px;
    img {
        filter: brightness(50%);
    }
}
.card_text {
    display: block;
    text-align: center;
    position: absolute;
    top: 220px;
    font-size: 20px;
    font-weight: 800;
}
</style>