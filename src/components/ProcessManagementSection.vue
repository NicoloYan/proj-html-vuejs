<template>
    <section>
        <span class="text_center heading">
            HOW IT WORKS IN PRACTICE
        </span>
        <h2 class="text_center">
            <span class="process">Process</span> Management
        </h2>
        <p class="text_center">
            We work with innovative methodologies to ensure that the entire reformatting process is done from start to finish as planned.
        </p>
        <div class="cards_area flex_space_between">
            <div class="card">
                <div class="number_container">
                    01
                </div>
                <h3  class="text_center">
                    Collection of information
                </h3>
                <p class="text_center">
                    Lorem ipsum dolor sit amet consectetur.
                </p>
            </div>

            <div class="card">
                <div class="number_container">
                    02
                </div>
                <h3  class="text_center">
                    Strategic planning
                </h3>
                <p class="text_center">
                    Lorem ipsum dolor sit amet consectetur.
                </p>
            </div>

            <div class="card">
                <div class="number_container">
                    03
                </div>
                <h3  class="text_center">
                    Assignment of responsibilities
                </h3>
                <p class="text_center">
                    Lorem ipsum dolor sit amet consectetur.
                </p>
            </div>

            <div class="card">
                <div class="number_container">
                    04
                </div>
                <h3  class="text_center">
                    Formatting process
                </h3>
                <p class="text_center">
                    Lorem ipsum dolor sit amet consectetur.
                </p>
            </div>

            <div class="card">
                <div class="number_container">
                    05
                </div>
                <h3  class="text_center">
                    Continuity formalization
                </h3>
                <p class="text_center">
                    Lorem ipsum dolor sit amet consectetur.
                </p>
            </div>
        </div>
        <div class="blue_line"></div>
    </section>
</template>

<script>
export default {
    name: 'ProcessManagementSection'
}
</script>

<style lang="scss" scoped>
section {
    padding: 100px 0;
    position: relative;
}
.heading {
    display: block;
    margin-bottom: 40px;
}
h2 {
    font-size: 40px;
    margin-bottom: 40px;
}
.process {
    color: #00a5a5;
    background-color: #daeced;
    padding: 10px;
    border-radius: 5%;
}
.cards_area {
    width: 80%;
    margin: 0 auto;
    padding-top: 70px;
}
.card {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
    width: calc((100% / 5) - 10px);
}
.number_container {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 50px;
    height: 50px;
    border-radius: 50px;
    background-color: #daeced;
    color: #068283;
    z-index: 10;
}
.blue_line {
    height: 5px;
    background-color: #daeced;
    position: absolute;
    top: 355px;
    width: 100%;
}
</style>