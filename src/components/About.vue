<template>
<div class="about-part">
    <div class="about-part-inner">
        <div>
            <p class=" about-text">About Us</p>
            <h1>Delicious food provider<br>since 1990</h1>
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
    padding: 0 19%;
    position: relative;
    bottom: 300px;
}

.about-part-inner {
    background-color: white;
    padding: 70px 70px;
    color: white;
    display: flex;
    gap:150px;
    box-shadow: 0px 20px 40px 0px rgba(221, 221, 221, 221)
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
    margin: 9px 0 30px;
    font-family: "Playfair Display", serif;
    color:black
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
</style>
