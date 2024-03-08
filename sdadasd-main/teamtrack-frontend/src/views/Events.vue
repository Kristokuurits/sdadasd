<template>
    <navbar />
    <EventList :title="title" :isAthlete="isAthlete" />
</template>
  
<script setup lang="ts">

import navbar from "../components/Navbar.vue"
import EventList from "../components/EventList.vue"
  import {defineProps} from "vue";
  
  defineProps<{ title: String, isAthlete: Boolean }>(); 
  </script>