<template>
    <section>
        <div class="container65 flex_space_between">
            <div class="card">
                <div class="icon_container">
                    <!-- ICONA ORIGINALE NON TROVATA -->
                    <i class="fa-solid fa-user-group"></i>
                </div>
                <h3>
                    Human Capital
                </h3>
                <p>
                    Humanizing business: Harness the power of technology to improve the way people work.
                </p>
            </div>
            <div class="card">
                <div class="icon_container">
                    <!-- ICONA ORIGINALE NON TROVATA -->
                    <i class="fa-solid fa-heart-pulse"></i>
                </div>
                <h3>
                    Core Business
                </h3>
                <p>
                    It takes innovative approaches to tranform, modernize, and run existing platforms.
                </p>
            </div>
            <div class="card">
                <div class="icon_container">
                    <!-- ICONA ORIGINALE NON TROVATA -->
                    <i class="fa-solid fa-gauge-high"></i>
                </div>
                <h3>
                    Performance
                </h3>
                <p>
                    Achieving maximum impact and value from investments in finance and supply chain.
                </p>
            </div>
        </div>
        <div class="dots">
            <div class="dots_x_3">
                <i class="fa-solid fa-ellipsis"></i>
                <i class="fa-solid fa-ellipsis"></i>
                <i class="fa-solid fa-ellipsis"></i>
            </div>
            <div class="dots_x_3">
                <i class="fa-solid fa-ellipsis"></i>
                <i class="fa-solid fa-ellipsis"></i>
                <i class="fa-solid fa-ellipsis"></i>
            </div>
            <div class="dots_x_3">
                <i class="fa-solid fa-ellipsis"></i>
                <i class="fa-solid fa-ellipsis"></i>
                <i class="fa-solid fa-ellipsis"></i>
            </div>
            <div class="dots_x_3">
                <i class="fa-solid fa-ellipsis"></i>
                <i class="fa-solid fa-ellipsis"></i>
                <i class="fa-solid fa-ellipsis"></i>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'CardSection'
}
</script>

<style lang="scss" scoped>
section {
    background-color: #eef4ed;
    position: relative;
}
.container65 {
    padding: 100px 0;
}
.card {
    display: flex;
    flex-direction: column;
    gap: 20px;
    width: 30%;
    padding: 50px 30px;
    background-color: white;
    border-radius: 5%;
}
.icon_container {
    background-color: #daeced;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    i {
        color: #00a5a5;
    }
}
.dots {
    position: absolute;
    bottom: -16px;
    left: 718px;
    z-index: 10;
}
.dots_x_3 {
    display: flex;
    i {
        font-size: 30px;
        color: rgba($color: #00a5a5, $alpha: 0.3);
        margin: 0 1px;
        height: 12px;
    }
}
</style>