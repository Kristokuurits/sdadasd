<template>
    <navbar />
    <router-view />
</template>

<script setup lang="ts">
    import { defineProps } from "vue";
    import navbar from "./components/Navbar.vue"
    defineProps<{ isAthlete: Boolean, hasChosen: Boolean}>();
</script>


