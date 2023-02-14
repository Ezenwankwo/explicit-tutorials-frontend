<template>
    <div class="py-12">
        <div class="container mx-auto px-8">
            <h2 class="text-4xl font-bold text-center text-gray-700 mb-8">Our Classes</h2>
            <div class="flex flex-wrap">
                <AppTutorialClass />
                <AppTutorialClass />
                <AppTutorialClass />
                <AppTutorialClass />
            </div>
        </div>
    </div>
</template>

<script>
definePageMeta({
    layout: "external",
});
</script>