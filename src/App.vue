<script lang="ts">
import Header from './components/Header.vue'
import About from './components/About.vue'
import MenuItems from './components/MenuItems.vue'
import IntroVideo from './components/IntroVideo.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'

export default {
    components: {
        Header,
        About,
        MenuItems,
        IntroVideo,
        Contact,
        Footer
    }
}
</script>

<template>
<div>
    <Header />
    <About />
    <MenuItems />
    <IntroVideo />
    <Contact />
    <Footer />
</div>
</template>
