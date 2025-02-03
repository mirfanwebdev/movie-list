<script setup lang="ts">
import { ref } from 'vue';

const linkList = ref([
    { name:"About", url: "#about"},
    {name: "Contact", url: "#contact"},
    {name: "Support", url: "#support"},
    {name: "Community", url: "#community"},
])
    
</script>

<template>
    <footer class="px-4 py-5 bg-slate-700 text-white flex flex-col gap-3">
        <div class="flex flex-col gap-2.5">
            <h3 class="text-2xl font-bold uppercase">movie list</h3>
            <ol>
                <li v-for="link in linkList">
                    <a :href="link.url">{{ link.name }}</a>
                </li>
            </ol>
        </div>
        <div class="flex flex-col gap-2.5">
            <div class="flex gap-4 text-3xl">
                <font-awesome-icon :icon="['fab', 'facebook']" />
                <font-awesome-icon :icon="['fab', 'twitter']" />
                <font-awesome-icon :icon="['fab', 'instagram']" />
                <font-awesome-icon :icon="['fab', 'tiktok']" />
            </div>
            <p>2025. Build with <b>VueJS</b> & <b>Shadcn.UI</b> by M. Irfan</p>
        </div>
    </footer>
</template>