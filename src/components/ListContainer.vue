<script setup lang="ts">
import { Skeleton } from './ui/skeleton';
import Movie from './Movie.vue';
</script>

<template>
    <div class="flex gap-5 overflow-x-auto pb-2">
        <template v-for="i in 5" >
            <div class="flex flex-col gap-3">
                <Movie />
                <Skeleton class="h-6 rounded-lg" />
            </div>
        </template>
    </div>
</template>