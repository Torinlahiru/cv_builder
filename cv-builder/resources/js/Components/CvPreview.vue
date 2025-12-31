<template>
    <div class="bg-white p-6 shadow">
        <h1 class="text-xl font-bold">{{ cv.personal?.name }}</h1>
        <p>{{ cv.personal?.summary }}</p>
    </div>
</template>

<script setup>
defineProps({ cv: Object });
</script>
