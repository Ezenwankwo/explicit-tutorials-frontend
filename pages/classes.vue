<template>
    <div class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl md:text-4xl font-bold text-center text-[#1A1919] mb-8">Our Classes</h2>
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