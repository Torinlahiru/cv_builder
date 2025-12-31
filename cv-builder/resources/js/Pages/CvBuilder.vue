<template>
    <div class="grid grid-cols-2 gap-4">
        <CvForm @update="cv = $event" />
        <CvPreview :cv="cv" />
    </div>
</template>

<script setup>
import { ref } from "vue";
import CvForm from "@/Components/CvForm.vue";
import CvPreview from "@/Components/CvPreview.vue";

const cv = ref({});
</script>
