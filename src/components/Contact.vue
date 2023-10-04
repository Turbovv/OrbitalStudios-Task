<template>
<div class="contact-part">
    <div class="contact-part-inner">
        <h3 class="single-contact-text">Contact Us</h3>
        <h5>Address</h5>
        <p>240, Kings street, New York city USA</p><br>
        <div class="single-contact">
            <h5 class="single-contact-text">we are open </h5>
            <p>Mon - Fri (9.00-19.00)</p>
            <p>Sat - Sun (9.00-19.00)</p>
        </div><br>
        <div>
            <h5 class="single-contact-text">reservation</h5>
            <p>+880 367 251 167</p>
            <p>barires@contact.com </p>
        </div>
    </div>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
.contact-part {
    background-image: url('../assets/ezgif-1-85c4bfa039.png');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    height: 700px;
    margin-top: 250px;
}

.contact-part-inner {
    background-color: white;
    border: 1px solid white;
    width: 500px;
    padding: 40px 40px;
    display: grid;
    margin: 0 auto;
    right: 310px;
    position: relative;
    top: 150px;
}

.contact-part-inner h5 {
    line-height: 40px;
}

.single-contact-text {
    line-height: 40px;
}

h5 {
    font-size: 16px;
    text-transform: uppercase;
    font-family: "Montserrat", sans-serif;
    font-weight: 400;
}

p {
    color: #555555;
}

@media only screen and (max-width:1200px) {
    .contact-part-inner {
        right: 190px;
    }
}

@media only screen and (max-width:990px) {
    .contact-part-inner {
        right: 5px;
        width: 70%;
    }
}

@media only screen and (max-width:670px) {}
</style>
