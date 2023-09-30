<script lang="ts">
import Header from './components/Header.vue'
import About from './components/About.vue'
import MenuItems from './components/MenuItems.vue'
import IntroVideo from './components/IntroVideo.vue'

export default {
    components: {
        Header,
        About,
        MenuItems,
        IntroVideo
    }
}
</script>

<template>
<div>
    <Header />
    <About />
    <MenuItems />
    <IntroVideo />
</div>
</template>