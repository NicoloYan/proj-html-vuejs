<template>
    <div class="jumbotron">
        <div class="container65">

            <!-- SLOGAN -->
            <div class="slogan">
                <span class="heading">
                    HUMAN RESOURCES
                </span>
                <h1>
                    Get More Productivity
                </h1>
                <div class="blue_line"></div>
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
.flex_space_between {
    gap: 20px;
}
.get_in_touch_btn {
    background-color: #00a5a5;
    padding: 10px 20px;
    border-radius: 5px;
}
.read_more_btn {
    margin-left: 15px;
    padding: 10px 20px;
    border: 1px solid #00a5a5;
    border-radius: 5px;
}
h1 {
    font-size: 70px;
    position: relative;
    z-index: 10;
}
.blue_line {
    background-color: #266466;
    height: 25px;
    width: 385px;
    bottom: 285px;
    left: 268px;
    position: absolute;

}
.slogan {
    display: flex;
    flex-direction: column;
    gap: 30px;
    width: 60%;
    padding: 175px 0;
}
.slogan_btns {
    margin-top: 20px;
}
</style>