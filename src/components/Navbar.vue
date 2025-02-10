<script setup lang="ts">

</script>
<template>
    <nav class="w-full p-4 flex justify-between bg-slate-600 text-white text-lg">
        <div>
            <font-awesome-icon :icon="['fas', 'bars']" />
        </div>
        <h1 class="font-bold text-xl uppercase">movie list</h1>
        <div class="flex gap-5">
            <div>
                <font-awesome-icon :icon="['fas', 'bell']" />
            </div>
            <div>
                <font-awesome-icon :icon="['fas', 'user']" />
            </div>
        </div>
    </nav>
</template>