<script lang="ts">
import Header from './components/Header.vue'
import About from './components/About.vue'
import MenuItems from './components/MenuItems.vue'
import IntroVideo from './components/IntroVideo.vue'
import Review from './components/Review.vue'
import Carousel from './components/Carousel.vue'

export default {
    components: {
        Header,
        About,
        MenuItems,
        IntroVideo,
        Review,
        Carousel
    }
}
</script>

<template>
<div>
    <Header />
    <About />
    <MenuItems />
    <IntroVideo />
    <Review />
  <div class="carou">
    <Carousel />
  </div>
</div>
</template>

<style scoped>
.carou {
    border:1px solid red;
    justify-content: center;
    max-width:80%;
    margin: 0 auto;
}
</style>