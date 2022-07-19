<template>
    <footer>
        <div class="container65 flex_space_between">
            <div class="form_area">
                <span class="heading">
                    SEND A MESSAGE
                </span>
                <h2>
                    Get in <span class="touch">Touch</span>
                </h2>
                <p>
                    We will respond to your message as soon as possible.
                </p>
                <div class="form">
                    <input type="text" placeholder="Name">
                    <input type="text" placeholder="Email">
                    <input type="text" placeholder="Phone">
                    <select name="more info" id="more info">
                        More info
                        <option value="More info">More info</option>
                    </select>
                    <textarea name="Message" id="message" cols="30" rows="10" placeholder="Message"></textarea>
                </div>
                <a class="send_btn" href="#">SEND</a>
            </div>
            <div class="info_area">
                <h3>
                    Example Inc.
                </h3>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                </p>
                <p>
                    Praesent diam lacus dapibus sed imperdiet consectetur.
                </p>
                <div v-for="info, index in contactInfo" 
                    :key="index" 
                    class="details">

                    <div class="icon_container">
                        <i :class="info.icon"></i>
                    </div>

                    {{ info.text }}

                </div>
                <a class="map_btn" href="#">
                    VIEW MAP
                </a>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'PageFooter',
    data() {
        return {
            contactInfo: [
                {
                    icon: "fa-solid fa-phone",
                    text: '1 (305) 1234-5678'
                },
                {
                    icon: "fa-solid fa-envelope",
                    text: 'hello@example.com'
                },
                {
                    icon: "fa-solid fa-location-dot",
                    text: 'Main Avenue, 987'
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
footer {
    background-color: black;
    color: white;
    padding: 100px 0;
    display: flex;
}
h2 {
    font-size: 50px;
}
.touch {
    padding: 10px;
    border-radius: 5%;
    background-color: #0e272d;
}
input, select {
    background-color: #1d1d23;
    color: gray;
    border: none;
    line-height: 40px;
    padding: 0 10px;
    width: calc((100% / 2) - 10px);
    border-radius: 3px;
    
}
textarea {
    background-color: #1d1d23;
    color: gray;
    border: none;
    padding-left: 10px;
    padding-top: 10px;
    width: 100%;
    border-radius: 3px;
}
.form_area {
    width: 60%;
    display: flex;
    flex-direction: column;
    gap: 30px;
}
.info_area {
    width: 35%;
    display: flex;
    flex-direction: column;
    gap: 30px;
}
.form {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 15px;
    margin-top: 40px;
}
.send_btn {
    background-color: #058283;
    padding: 10px 20px;
    border-radius: 5px;
    width: 14%;
}
.details {
    color: #058283;
    display: flex;
    align-items: center;
}
.icon_container {
    width: 50px;
    height: 50px;
    border-radius: 50px;
    background-color: #0f2128;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-right: 10px;
    i {
        font-size: 22px;
    }
}
.map_btn {
    padding: 10px 20px;
    border: 1px solid #058283;
    width: 36%;
    border-radius: 5px;
}
</style>