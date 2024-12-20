<script setup lang="ts">
import { defineComponent } from 'vue';
import { NSpace } from 'naive-ui'

defineComponent({
    components: {
        NSpace
    }
})
</script>
<template>
    <nav>
        <n-space justify="space-between">
            <p>Menu</p>
            <p>Icon</p>
        <n-space>
            <p>bell</p>
            <p>user</p>
        </n-space>
        </n-space>
    </nav>
</template>