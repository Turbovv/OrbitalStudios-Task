<template>
<div class="main-container">
    <div class="header-container">
        <div class="header">
            <div class="logo">BURI</div>
            <div class="menu">
                <div class="menuItem">HOME</div>
                <div class="menuItem">ABOUT</div>
                <div class="menuItem">MENU</div>
                <div class="menuItem">BLOG</div>
                <div class="menuItem">CONTACT</div>
            </div>
        </div>
    </div>
    <div class="hamburger-menu">
        <button class="hamburger-menu-inner" @click="open = !open">
            <i class="fa-solid fa-bars  test"></i>
        </button>
        <div class="hamburger-menu-inner-text" v-if="open">
            <a>HOME</a>
            <a>ABOUT</a>
            <a>MENU</a>
            <a>HOME</a>
            <a>CONTACT</a>
        </div>
    </div>
    <div class="banner-text">
        <div class="banner-text-center">
            <p class="banner-text-inner">Expensive But The Best</p>
            <h1 class="color-w text">Modern restaurant in center of the city</h1>
            <button class="button">Book A Table</button>
        </div>
    </div>
</div>
</template>

<script lang="ts">
export default {
    data() {
        return {
            open: false
        }
    }
}
</script>

<style scoped>
.main-container {
    background-image: url('../assets/ezgif-4-51260a819b.jpg');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    /* background-attachment: fixed; */
    height: 1080px;
}

.header-container {
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    height: 80px;
    position: relative;
    right: 230px;

}

.header {
    display: flex;
    align-items: center;
}

.logo {
    font-size: 24px;
    font-weight: bold;
    margin-right: 80px;
}

.menu {
    display: flex;
    margin-left: 20px;
}

.menuItem {
    margin-left: 50px;
    cursor: pointer;
}

.banner-text {
    margin-top: 300px;
    z-index: 9999 !important;
}

.banner-text-center {
    justify-content: center;
    display: grid;
    position: relative;
    right: 80px;
    z-index: 9999 !important;
}

.banner-text-inner {
    color: white;
    font-family: "Montserrat", sans-serif;
    color: #d6ad86;
    font-size: 18px;
}

.text {
    font-family: "Playfair Display", serif;
    font-size: 65px;
    font-weight: 400;
    padding: 25px 0;
    width: 60%;
}

.color-w {
    color: white;
}

.button {
    padding: 23px 0;
    background-color: #d6ad86;
    font-size: 14px;
    font-weight: 400;
    color: #fff;
    text-transform: capitalize;
    line-height: 14px;
    border: none;
    width: 250px;
}

@media only screen and (max-width:1200px) {
    .header-container {
        right: 120px;
    }

    .banner-text-center {
        right: 150px;
    }

    .banner-text {
        margin-top: 150px;
    }

    .main-container {
        height: 650px;
    }

    .text {
        font-size: 40px;
        margin-bottom: 15px;
        line-height: 1.4;
        width: 75%;
    }

    .button {
        display: none;
    }
}

@media only screen and (min-width:990px) {
    .hamburger-menu {
        display: none;
    }
}

@media only screen and (max-width:990px) {
    .banner-text-inner {
        color: white
    }

    .menu {
        display: none;
    }

    .header-container {
        right: 270px;
    }

    .banner-text-center {
        text-align: center;
        right: 5px;
        z-index: 9999 !important;
    }

    .text {
        width: 95%;
    }

    .button {
        display: block;
        justify-content: center;
        display: grid;
        margin: 0 auto;
        padding: 15px 0;
        width: 150px;
    }

    .hamburger-menu {
        position: absolute;
        width: 70%;
        left: 140px;
        color: black;
    }

    .hamburger-menu-inner {
        float: right;
        position: relative;
        bottom: 50px;
        font-size: 30px;
        background: none;
        color: white;
        border: none;
    }

    .hamburger-menu-inner-text {
        display: grid;
        background-color: white;
        padding: 20px 20px;
        min-width: 100%;
        position: absolute;
        line-height: 40px;
    }
}

@media only screen and (max-width:770px) {
    .header-container {
        right: 170px;
    }

    .text {
        width: 75%;
        justify-content: center;
        display: grid;
        margin: 0 auto;
    }
}

@media only screen and (max-width:670px) {
    .logo {
        position: absolute;
    }

    .hamburger-menu-inner-text {
        transform: translateX(-100px);
    }

    .hamburger-menu {
        right: 400px;
        width: 50%;
    }
}
</style>
