<template>
    <home/>
    <suggestions /> 
    <your-music />
</template>

<script>
import Home from "./Home.vue"
import Suggestions from "./Suggestions.vue";
import YourMusic from './YourMusic.vue';
export default {
    name: 'Root',
    components: {
        Home,
        Suggestions,
        YourMusic
    }
}
</script>
