<template>
    <header>
        <div class="container65 flex_space_between">
            <div>
                <!-- ICONA CLOCK-->
                Open Hours: Mon - Sat - 9:00 - 18:00
            </div>
            <div class="flex_space_between">
                <div>
                    <!-- ICONA TELEFONO -->
                    +1 (305) 1234-5678
                </div>
                <div>
                    <!-- ICONA MAIL -->
                    hello@example.com
                </div>
                <div>
                    <!-- ICONA FACEBOOK -->
                </div>
                <div>
                    <!-- ICONA TWITTER -->
                </div>
                <div>
                    <!-- ICONA LINKEDIN -->
                </div>
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
</style>