<template>
<div class="footer-area">
    <div class="footer-area-inner">
        <div>
            <h2 class="area-text">BURI.</h2>
            <p>+880 253 356 263</p>
            <span>burires@contact.com</span>
        </div>
        <div>
            <h2 class="area-text">Quick links</h2>
            <div class="d-flex">
                <div>
                    <a>About</a><br>
                    <a>Menu</a><br>
                    <a>Reservation</a><br>
                    <a>Blog</a><br>
                </div>
                <div>
                    <a>Breakfast</a><br>
                    <a>Lunch</a><br>
                    <a>Dinner</a>
                </div>
            </div>
        </div>
        <div>
            <h2 class="area-text">Subscribe newsletter</h2>
            <input type="email" placeholder="Email Address" class="area-text">
            <h4>Subscribe newsletter to get all<br>updates about discount and offers.</h4>
        </div>
    </div>
</div>
</template>

<!-- 
<script>
export default {

}
</script> -->

<style scoped>
.footer-area {
    background-color: #1c1a18;
    padding: 100px 0px 25px;
    height: 500px;
    min-width: 100%;
}

.footer-area-inner {
    margin: 0 auto;
    gap: 20%;
    left:50px;
    position: relative;
    color: white;
    display: grid;
    grid-template-columns: auto auto auto;
    width:1200px;
}

.footer-area-inner p {
    color: #a9a9a9;
    font-size: 15px;
    line-height: 40px;
    font-family: "Montserrat", sans-serif;
}

.footer-area-inner span {
    color: #d6ad86;
}

.d-flex {
    display: flex;
    gap: 50px;
}
a {
    line-height: 30px;
    color: #a9a9a9;
    -webkit-transition: 0.5s;
    transition: 0.5s;
    font-size: 15px;
    cursor: pointer;
    font-family: "Montserrat", sans-serif;
}
a:hover {
    color: #d6ad86;
}
.area-text {
    margin-bottom: 30px;
}
input {
    padding: 10px 25px;
    outline: none;
    border: none;
}
h4 {
    color: #a9a9a9;
    font-size: 15px;
    line-height: 25px;
    font-family: "Montserrat", sans-serif;
    font-weight: 400;
}
</style>
