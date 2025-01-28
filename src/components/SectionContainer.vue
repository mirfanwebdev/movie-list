<script lang="ts" setup>
defineProps({
    title: String,
    isBackground: {
        type: Boolean,
        default: false
    }
})
</script>

<template>
    <div :class="[{'bg-slate-300' : isBackground}, 'pl-4', 'pt-3', 'pb-7', 'flex', 'flex-col', 'gap-3', 'overflow-x-auto']">
        <h2 class="text-lg font-semibold">{{ title }}</h2>
        <slot></slot>
    </div>
</template>