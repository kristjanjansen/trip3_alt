<template>
    <main>
        <div class="p-4">
            <inertia-link class="font-medium text-gray-800" href="/"
                >First</inertia-link
            >
            &nbsp;
            <inertia-link class="font-medium text-gray-800" href="/second"
                >Second</inertia-link
            >
        </div>
        <slot />
    </main>
    <!-- <basegrid /> -->
</template>
