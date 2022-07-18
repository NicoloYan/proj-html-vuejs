<template>
    <div class="flex">
        <div class="info_area">
            <span class="heading">
                ABOUT THE NETWORK
            </span>
            <h2>
                <span class="the">The</span> Company
            </h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras iaculis diam varius diam ultricies lacinia.</p>
            <div class="flex_space_between">
                <div class="card">
                    <span class="number">
                        0
                    </span>
                    <h3>
                        Employees
                    </h3>
                    <p>
                        Lorem ipsum dolor sit amet.
                    </p>
                </div>
                <div class="card">
                    <span class="number">
                        0
                    </span>
                    <h3>
                        Partners
                    </h3>
                    <p>
                        Lorem ipsum dolor sit amet.
                    </p>
                </div>
                <div class="card">
                    <span class="number">
                        0
                    </span>
                    <h3>
                        Customers
                    </h3>
                    <p>
                        Lorem ipsum dolor sit amet.
                    </p>
                </div>
            </div>
            <div>
                <a class="get_in_touch" href="#">
                    GET IN TOUCH
                </a>
                <a class="read_more" href="#">
                    READ MORE
                </a>
            </div>
        </div>
        <div class="bg">
            <img src="../assets/img/about-5.jpg" alt="office image">
        </div>
    </div>
</template>

<script>
export default {
    name: 'TheCompanySection'
}
</script>

<style lang="scss" scoped>
.info_area {
    width: 50%;
    padding-left: 265px;
    padding-right: 50px;
    padding-top: 100px;
    padding-bottom: 100px;
    display: flex;
    flex-direction: column;
    gap: 30px;
}
.bg {
    width: 50%;
    img {
        height: 601px;
    }
}
.flex {
    display: flex;
}
.the {
    color: #00a5a5;
    background-color: #daeced;
    padding: 10px;
    border-radius: 5%;
}
h2 {
    font-size: 30px;
    font-weight: 800;
}
.card {
    margin-top: 20px;
    display: flex;
    flex-direction: column;
    width: 30%;
    gap: 30px;
}
.number {
    color: #00a5a5;
    font-size: 30px;
    font-weight: 800;
    margin-left: 15px;
}
.get_in_touch {
    color: white;
    background-color: #00a5a5;
    padding: 5px 20px;
    border-radius: 5%;
}
.read_more {
    padding: 5px 20px;
    margin-left: 15px;
    color: #00a5a5;
    border: 1px solid #00a5a5;
    border-radius: 5%;
}
</style>