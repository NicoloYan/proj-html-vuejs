<template>
    <section>
        <div class="container65">
            <span class="heading text_center">
                CUSTOMER TESTIMONIALS
            </span>
            <h2 class="text_center">
                Trusted <span class="feedback">Feedback</span>
            </h2>
            <p class="info text_center">
                We work intensively in search of ideals that can add up in the lives of our customers. This is what moves us and we are grateful for the recognition.
            </p>
            <div class="cards_area flex_space_between">
                <div class="card">
                    <img src="../assets/img/logo-1.png" alt="woo commerce logo">
                    <p>Praesent volutpat justo sit amet elementum malesuada. Praesent sagittis augue justo, in accumsan orci rhoncus at pellentesque.</p>
                    <p>Lorem ipsum dolor sit amet, censectetur adipiscing elit.</p>
                    <i class="fa-solid fa-quote-right"></i>
                </div>

                <div class="card">
                    <img src="../assets/img/logo-2.png" alt="wordPress logo">
                    <p>Praesent volutpat justo sit amet elementum malesuada. Praesent sagittis augue justo, in accumsan orci rhoncus at pellentesque.</p>
                    <p>Lorem ipsum dolor sit amet, censectetur adipiscing elit.</p>
                    <i class="fa-solid fa-quote-right"></i>
                </div>

                <div class="card">
                    <img src="../assets/img/logo-3.png" alt="pingdom logo">
                    <p>Praesent volutpat justo sit amet elementum malesuada. Praesent sagittis augue justo, in accumsan orci rhoncus at pellentesque.</p>
                    <p>Lorem ipsum dolor sit amet, censectetur adipiscing elit.</p>
                    <i class="fa-solid fa-quote-right"></i>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'PartnerFeedbacks'
}
</script>

<style lang="scss" scoped>
section {
    padding: 100px 0;
    background-color: #eef4ed;
}
.heading {
    margin-bottom: 40px;
    display: block;
}
h2 {
    font-size: 40px;
    margin-bottom: 40px;
}
.feedback {
    color: #00a5a5;
    background-color: #daeced;
    padding: 10px;
    border-radius: 5%;
}
.info {
    margin: 0 auto;
    width: 60%;
}
.card {
    margin-top: 40px;
    width: calc((100% / 3) - 20px);
    background-color: white;
    padding: 30px;
    display: flex;
    flex-direction: column;
    gap: 20px;
    border-radius: 5%;
    position: relative;
    img {
        width: 120px;
    }
    i {
        position: absolute;
        color: lightgray;
        bottom: 20px;
        right: 20px;
        font-size: 30px;
    }
}
</style>