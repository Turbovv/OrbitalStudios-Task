<template>
    <div class="food-menu">
        <div class="food-menu-inner">
            <p class="center food-menu-inner-text">Testimonials</p>
            <h1 class="center food-menu-inner-text-h1">What they said</h1>
            <div class="food-menu-center">
                <div class="flex-wrap">
                    <div class="single-food-item">
                </div>
                </div>
            </div>
        </div>
    </div>
    </template>
    

    
    <style scoped>
    .food-menu-inner {
        /* border: 1px solid red; */
        margin: 0 auto;
        position: relative;
        top:200px;
    }
    
    .food-menu-inner .food-menu-inner-text {
        color: #d6ad86;
        font-weight: 400;
        font-family: "Montserrat", sans-serif;
    }
    
    .food-menu-inner-text .food-menu-inner-text-h1 {
        font-size: 40px;
        color: #2c3033;
        line-height: 1.25;
        font-weight: 700;
        position: relative;
        z-index: 1;
    }
    
    .food-menu-center {
        display: grid;
        justify-content: center;
        position: relative;
        margin-top:50px;
    
    }
    .flex-wrap {
        display:grid;
        gap:100px;
        grid-template-columns: auto auto;
    }
    .center {
        justify-content: center;
        display: grid;
    }
    
    .single-food-item {
        display: flex;
        border: 1px solid #f3e6da;
    }
    body {
        background-color: black;
    }
 
    </style>
    