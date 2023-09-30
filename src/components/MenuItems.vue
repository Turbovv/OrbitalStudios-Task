<template>
<div class="food-menu">
    <div class="food-menu-inner">
        <p class="center food-menu-inner-text">Popular Menu</p>
        <h1 class="center food-menu-inner-text-h1">Delicious Food Menu</h1>
        <div class="food-menu-center">
            <div class="flex-wrap">
                <div v-for="item in items" :key="item.id" class="single-food-item">
                <div> <img :src="item.image" alt=""></div>
                <div class="single-food-desc">
                    <h3>{{ item.title }}</h3>
                    <p>They're wherein heaven seed hath nothing</p>
                    <h5>Form $40.00</h5>
                </div>

            </div>
            </div>
        </div>
    </div>
</div>
</template>

<script lang="ts">
import porksandwich from "../assets/porksandwich.jpg";
import easterdelight from "../assets/easterdelight.jpg";
import roastedmarrow from "../assets/roastedmarrow.jpg";
import tienerschnitze from "../assets/tienerschnitze.jpg";
import summercooking from "../assets/summercooking.jpg";
import chickenroast from "../assets//chickenroast.jpg";
export default {
    data() {
        return {
            items: [{
                    id: 1,
                    image: porksandwich,
                    title: 'PORK SANDWICH'
                },
                {
                    id: 2,
                    image: easterdelight,
                    title: 'EASTER DELIGHT'
                },
                {
                    id: 3,
                    image: roastedmarrow,
                    title: 'ROASTED MARROW'
                },
                {
                    id: 4,
                    image: tienerschnitze,
                    title: 'TIENER SCHNITZE'
                },
                {
                    id: 5,
                    image: summercooking,
                    title: 'SUMMER COOKING'

                },
                {
                    id: 6,
                    image: chickenroast,
                    title: 'CHICKEN ROAST'
                },
            ]
        }
    }
}
</script>

<style scoped>
.food-menu-inner {
    /* border: 1px solid red; */
    margin: 0 auto;
    position: relative;
    bottom:150px;
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

.single-food-desc {
    padding: 30px 30px;
}

.single-food-desc h3 {
    font-size: 24px;
    font-weight: 400;
    text-transform: uppercase;
}

.single-food-desc p {
    font-family: "Montserrat", sans-serif;
    line-height: 1.7;
    font-size: 15px;
    margin-bottom: 0px;
    color: #555555;
}

.single-food-desc h5 {
    font-size: 20px;
    font-weight: 700;
    color: #000;
    margin-top: 20px;
    font-family: "Montserrat", sans-serif;
}
</style>
