<script lang="ts">
import Header from './components/Header.vue'
import About from './components/About.vue'
import MenuItems from './components/MenuItems.vue'

export default {
    components: {
        Header,
        About,
        MenuItems
    }
}
</script>

<template>
<div>
    <Header />
    <About />
    <MenuItems />
</div>
</template>