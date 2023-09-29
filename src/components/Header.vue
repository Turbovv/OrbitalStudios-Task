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
<div class="banner-text">
    <p class="banner-text-inner">Expensive But The Best</p>
    <h1 class="color-w text">Modern restaurant in<br>center of the city</h1>
    <button class="button">Book A Table</button>
</div>
</div>
</template>

<style scoped>
  .main-container {
    background-image: url('../assets/ezgif-4-51260a819b.jpg');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    /* background-attachment: fixed; */
    height:1080px;
  }
  
.header-container {
  display: flex;
  justify-content: center;
  align-items: center;
  color: white; 
  height: 80px;
  margin-right: 25%;
}
.header {
  display: flex;
  align-items: center;
}
.logo {
  font-size: 24px;
  font-weight: bold;
  margin-right:80px;
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
    border:1px solid red;
    padding:0 19%;
    margin-top:300px;
  }
  .banner-text-inner {
  color:white;
    font-family: "Montserrat", sans-serif;
    color: #d6ad86;
    font-size: 18px;
}
.text {
  font-family: "Playfair Display", serif;
  font-size: 65px;
    font-weight: 400;
    padding: 25px 0;
}
.color-w {
  color: white;
}

.button {
  display: inline-block;
    padding: 23px 60px;
    background-color: #d6ad86;
    font-size: 14px;
    font-weight: 400;
    color: #fff;
    text-transform: capitalize;
    line-height: 14px;
    border:none;
}

@media (max-width: 768px) {
  .menu {
    display: none;
  }
}
</style>