<template>
    <header>
        <div class="container65 flex_space_between">
            <div>
                <i class="fa-solid fa-clock"></i>
                <span>Open Hours: Mon - Sat - 9:00 - 18:00</span>
            </div>
            <div class="flex_space_between">
                <div>
                    <i class="fa-solid fa-phone"></i>
                    <span>+1 (305) 1234-5678</span>
                </div>
                <div>
                    <i class="fa-solid fa-envelope"></i>
                    <span>hello@example.com</span>
                </div>
                <a>
                    <i class="fa-brands fa-facebook-f"></i>
                </a>
                <a>
                    <i class="fa-brands fa-twitter"></i>
                </a>
                <a>
                    <i class="fa-brands fa-linkedin-in"></i>
                </a>
            </div>
        </div>
        <div class="flex_space_between align container65">
                <div class="nex_gen_logo">
                    <img src="https://nexgen.codings.dev/wp-content/uploads/2021/03/logo.svg" alt="nex gen logo">
                </div>
                <!-- NAVBAR -->
                <nav class="flex_space_between">

                    <ul>
                        <li v-for="link, index in links" :key="index" :class="{ 'active': link.active }">
                            <a :href="link.url">{{ link.text }}</a>
                        </li>
                    </ul>
                    <div>
                        <i class="fa-regular fa-user"></i>
                    </div>
                    <a href="#" class="get_in_touch_btn">
                        GET IN TOUCH
                    </a>
                </nav>
            </div>
    </header>
</template>

<script>
export default {
    name: 'PageHeader',
    props: ['links']
}
</script>

<style lang="scss" scoped>
header {
    background-color: #25333d;
    color: #c1c3cf;
    height: 50px;
    line-height: 50px;
}
.flex_space_between {
    gap: 20px;
}
span {
    margin-left: 10px;
}
.align {
    align-items: center;
    padding-top: 20px;
    background-color: transparent;
}
.nex_gen_logo {
    width: 120px;
    height: 41.95px;
}
.get_in_touch_btn {
    background-color: #00a5a5;
    padding: 0 25px;
    border-radius: 5px;
}
ul {
    display: flex;
    gap: 20px;
}
.active {
    color: #00a5a5;
}
</style>