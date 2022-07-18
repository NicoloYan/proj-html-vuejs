<template>
    <div class="jumbotron">
        <div class="container65">
            <div class="flex_space_between align">
                <div class="nex_gen_logo">
                    <img src="https://nexgen.codings.dev/wp-content/uploads/2021/03/logo.svg" alt="nex gen logo">
                </div>
                <!-- NAVBAR -->
                <nav class="flex_space_between">
                    <!-- DA RIMPIAZZARE CON CICLO FOR -->
                    <div>
                        HOME
                    </div>
                    <div>
                        ABOUT
                    </div>
                    <div>
                        PROJECTS
                    </div>
                    <div>
                        PROCESS
                    </div>
                    <div>
                        TESTIMONIALS
                    </div>
                    <div>
                        <!-- ICONA USER-->
                        ICONA
                    </div>
                    <div class="get_in_touch_btn">
                        HOME
                    </div>
                </nav>
            </div>

            <!-- SLOGAN -->
            <div class="slogan">
                <span class="hr">
                    HUMAN RESOURCES
                </span>
                <h1>
                    GET MORE PRODUCTIVITY
                </h1>
                <p>
                    Planning, recruitment and selection process and performance evaluation of employees.
                </p>
                <div class="slogan_btns">
                    <a class="get_in_touch_btn" href="#">
                        GET IN TOUCH
                    </a>
                    <a class="read_more_btn" href="#">
                        READ MORE
                    </a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'PageJumbotron'
}
</script>

<style lang="scss" scoped>
.jumbotron {
    background-image: linear-gradient(rgba(0, 0, 0, 0.527),rgba(0, 0, 0, 0.5)) , url('../assets/img/bg-4.jpg');
    color: white;
    background-size: cover;
}
.nex_gen_logo {
    width: 120px;
}
.align {
    align-items: center;
    padding-top: 20px;
}
.flex_space_between {
    gap: 20px;
}
.get_in_touch_btn {
    background-color: #00a5a5;
    padding: 5px 20px;
}
.read_more_btn {
    margin-left: 15px;
    padding: 5px 20px;
    border: 1px solid #00a5a5;
}
h1 {
    font-size: 50px;
}
.slogan {
    display: flex;
    flex-direction: column;
    gap: 30px;
    width: 60%;
    padding: 150px 0;
}
.hr {
    color: #00a5a5;
}
</style>