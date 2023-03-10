<template>
    <div class="md:hero min-h-screen bg-white">
        <div class="container mx-auto lg:px-12 columns-10 p-4 md:py-12 grid lg:grid-cols-12">
            <div class="mt-8 col-span-7">
                <h1 class="text-4xl md:text-6xl font-bold tracking-tight text-[#1A1919]">Ace Your Exams <br class="hidden md:block">At One Sitting</h1>
                <p class="my-6 leading-8 text-lg">Learn at your convinience with the best<br>
                     online tutors for JAMB, POST-UTME<br> and 100 levels courses</p>
                <NuxtLink to="/register" class="btn btn-primary capitalize">Register Now</NuxtLink>
                <NuxtLink to="/affiliate" class="btn btn-outline btn-primary capitalize ml-4">Become An Affiliate</NuxtLink>
                <div class="grid grid-cols-3 mt-12">
                    <div>
                        <p class="text-primary">18k+</p>
                        <span class="text-sm">Students</span>
                    </div>
                    <div class="border-x-2 border-gray-400 pl-8">
                        <p class="text-primary">2k</p>
                        <span class="text-sm">Affiliates</span>
                    </div>
                    <div class="pl-8">
                        <p class="text-primary">96%</p>
                        <span class="text-sm">Success rate</span>
                    </div>
                </div>
            </div>
            <img src="~/assets/img/hero.png" class="hidden md:block object-fit col-span-5" alt="hero image" />
        </div>
        <img src="~/assets/img/hero.png" class="block md:hidden" alt="hero image" />
    </div>
</template>