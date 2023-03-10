<template>
    <div class="py-12 bg-blue-50">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl md:text-4xl font-bold text-center text-[#1A1919] mb-8">Featured classes</h2>
            <div class="flex flex-wrap">
                <AppTutorialClass />
                <AppTutorialClass />
                <AppTutorialClass />
            </div>
            <div class="text-center text-blue-700">
                <NuxtLink to="/classes" class="link link-hover">View 8+ more classes</NuxtLink>
                <Icon name="bi:caret-right-fill" />
            </div>
        </div>
    </div>

</template>