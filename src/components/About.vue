<template>
<div class="about-part">
    <div class="about-part-inner">
        <div class="about-part-mobile">
            <p class=" about-text">About Us</p>
            <h1>Delicious food provider since 1990</h1>
            <p class="about-text-p">Good lights it very to above. Days image to sea. Over there seasons and<br>spirit beast in. Greater bearing creepeth very behold fourth night morning<br>seed moved.</p><br>
            <p class="about-text-p ">Good lights it very to above. Days image to sea. Over seasons and spirit<br>beast in over greater bearing creepeth.</p><br><br>
            <button class="about-button">Learn More</button>
        </div>
        <div class="about-part-img">
            <img src="../assets/ezgif-1-ca6736de0e.jpg" alt="">
        </div>
    </div>
</div>
</template>

<style scoped>
.about-part {
    position: relative;
    bottom: 300px;
    display: grid;
}

.about-part-inner {
    background-color: white;
    color: white;
    display: flex;
    gap: 150px;
}

.about-part-mobile {
    margin-right: 10px;
}

.about-text {
    font-size: 18px;
    text-transform: capitalize;
    color: #d6ad86;
    font-weight: 400;
    font-family: "Montserrat", sans-serif;
    line-height: 40px;
}

.about-part-inner h1 {
    font-size: 46px;
    width: 500px;
    margin: 9px 0 30px;
    font-family: "Playfair Display", serif;
    color: black
}

.about-text-p {
    line-height: 25px;
    color: #555555;
}

.about-button {
    display: inline-block;
    font-size: 15px;
    color: #fff;
    background-color: #000;
    text-transform: capitalize;
    -webkit-transition: 0.5s;
    transition: 0.5s;
    position: relative;
    z-index: 1;
    padding: 14px 37.5px;
    font-family: "Montserrat", sans-serif;
    cursor: pointer;
}

@media only screen and (min-width:990px) {
    .about-part-inner {
        padding: 70px 70px;
    }

    .about-part {
        justify-content: center;
    }
}

@media only screen and (max-width:1200px) {
    .about-part {
        bottom: 250px;
    }

    .about-part-inner {
        gap: 1px;
    }

    .about-part-img img {
        width: 300px;
    }

    .about-text-p p {
        font-size: 15px;
        font-family: "Montserrat", sans-serif;
    }

    .about-part-inner h1 {
        width: 400px;
        font-size: 30px;
        line-height: 45px;
    }
}

@media only screen and (max-width:990px) {
    .about-part-inner {
        display: grid;
        min-width: 100%;
        padding: 30px 30px;

    }

    .about-part {
        bottom: 50px;
        width: 70%;
        background-color: white;
        box-shadow: 0px 20px 40px 0px rgba(221, 221, 221, 221);
        margin: 0 auto;
    }

    .about-part-inner h1 {
        font-size: 30px;
    }

    .about-part-img img {
        width: 100%;
        margin-left: 1px;
    }
}

@media only screen and (max-width:670px) {
    .about-part {
        width: 90%;
    }

    .about-part-img {
        width: 90%;
    }

    .about-part-img img {
        width: 100%;
    }

    .about-text-p {
        width: 100%;
    }

    .about-part-inner h1 {
        font-size: 30px;
        width: 100%;
    }
}
</style>
