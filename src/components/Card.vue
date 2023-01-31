<script setup>
let props = defineProps({
    heading: String,
    content: String
})
</script>

<template>
    <div class="max-w-sm p-6 bg-eestech-2 hover:bg-eestech-3 border border-gray-200 rounded-lg shadow h-full">
        <slot></slot>
        <h4>
            <h5 class="my-3 text-2xl font-semibold tracking-tight text-white text-center">{{heading}}</h5>
        </h4>
        <p class="mb-3 font-normal text-white text-center">{{content}}</p>
    </div>
</template>