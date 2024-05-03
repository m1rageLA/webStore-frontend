<template lang="">
    <VueHeader/>
</template>
<script lang="ts">


import VueHeader from '@/components/Header/VueHeader.vue';
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'MainPage',
    components: {
        VueHeader
    }
});
</script>
<style lang="scss"></style>