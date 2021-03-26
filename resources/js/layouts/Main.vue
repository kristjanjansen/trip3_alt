<script setup>
import { ref } from "vue";
const grid = ref(false);
</script>

<template>
    <div>
        <div class="p-4 flex gap-4">
            <inertia-link class="font-sans font-medium text-gray-800" href="/"
                >First</inertia-link
            >
            <inertia-link
                class="font-sans font-medium text-gray-800"
                href="/second"
                >Second</inertia-link
            >
            <button
                @click="grid = !grid"
                class="focus:outline-none font-sans font-medium text-gray-800"
            >
                Toggle grid
            </button>
        </div>
        <slot />
        <basegrid v-if="grid" />
    </div>
</template>
