<template>
    <body>
        <HeaderVue />
        <RouterView />
        <FooterVue />
    </body>
</template>

<script setup lang="ts">
import HeaderVue from './components/Header.vue'
import FooterVue from './components/Footer.vue'

</script>
