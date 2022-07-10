<template>
    <button class="p-4 text-gray-100 rounded-xl border border-red-400 bg-red-400">
        {{ text }}
    </button>
</template>

<script setup>
defineProps({
    text: String
});
</script>