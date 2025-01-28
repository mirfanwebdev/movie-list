<script setup lang="ts">
import { Skeleton } from './ui/skeleton';
</script>

<template>
    <div class="flex gap-5 overflow-x-auto pb-2">
        <template v-for="i in 4" >
            <div class="flex flex-col gap-3">
                <Skeleton class="w-[300px] h-[160px] rounded-xl" />
                <Skeleton class="h-6 rounded-lg" />
            </div>
        </template>
    </div>
</template>