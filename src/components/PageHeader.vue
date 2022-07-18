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
                    <span>+1 (305) 1234-5678</span>
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
    </header>
</template>

<script>
export default {
    name: 'PageHeader'
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
    margin-left: 5px;
}
</style>