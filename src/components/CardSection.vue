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
}
.container65 {
    padding: 100px 0;
}
.card {
    display: flex;
    flex-direction: column;
    gap: 20px;
    width: 30%;
    padding: 50px;
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
}
</style>