<template>
<div class="test">
    <Carousel :items-to-show="2.5" :wrap-around="true">
        <Slide v-for="slide in slides" :key="slide.id" class="satesto">
            <p class="review">Good lights it very to above. Days<br>image to sea over there
                seasons<br>and spirit beast in greater bearing<br>tool creepeth
                very behold.</p>
            <div class="d-flex gap-20">
                <img :src="slide.image" alt="">
                <div class="d-grid">
                    <div class="carousel__item">{{ slide.title }}</div>
                   <div class="d-flex gap-3">
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                   </div>
                </div>
            </div>
        </Slide>
        <template #addons>
            <Navigation />
        </template>
    </Carousel>
</div>
<img src="../assets/client_1.png.webp" alt="">
</template>

<script lang="ts">
import client1 from "../assets/client1.webp"
import client2 from "../assets/client2.webp"
import client3 from "../assets/client3.webp"
import {
    defineComponent
} from 'vue'
import {
    Carousel,
    Navigation,
    Slide
} from 'vue3-carousel'

import 'vue3-carousel/dist/carousel.css'

export default defineComponent({
    name: 'WrapAround',
    data() {
        return {
            slides: [{
                    id: 1,
                    image: client2,
                    title: 'MOSAN CAMERON'
                },
                {
                    id: 2,
                    image: client3,
                    title: 'MOSAN CAMERON'
                },
                {
                    id: 3,
                    image: client1,
                    title: 'MOSAN CAMERON'
                },
                {
                    id: 4,
                    image: client2,
                    title: 'MOSAN CAMERON'
                },
                {
                    id: 5,
                    image: client3,
                    title: 'MOSAN CAMERON'

                },
            ]
        }
    },
    components: {
        Carousel,
        Slide,
        Navigation,
    },
})
</script>

<style scoped>
.test {
    margin-top: 150px;
}

.review {
    padding: 20px 20px;
    color: #555555;
    border: 1px solid #d6ad86;

}

.satesto {
    display: grid;
    text-align: left;
    max-width:40%;
}

.d-flex {
    display: flex;
}
.gap-20 {
    gap:20px;
}
.gap-3 {
    gap:3px;
}
.fa-star {
    color: #ffb830;
}

.d-grid {
    display: grid;
}
</style>
