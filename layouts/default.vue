<template>
    <section class="bg-black w-full h-screen flex ">
        <div class="h-screen min-w-[375px] max-w-[400] bg-black border-r-2 border-amber-50">
            <navBar/>
        </div>
        <slot/>
    </section>
</template>

<script setup>
import navBar from '@/components/navBar.vue';
</script>