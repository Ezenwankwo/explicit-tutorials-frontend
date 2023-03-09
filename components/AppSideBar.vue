<template>
    <div
        class="fixed inset-0 z-20 transition-opacity bg-orange lg:hidden"></div>

    <div
        class="sidebarOpen translate-x-0 ease-out -translate-x-full ease-in fixed inset-y-0 left-0 z-30 w-64 overflow-y-auto transition duration-300 transform bg-white lg:translate-x-0 lg:static lg:inset-0">
        <div class="flex items-center justify-center mt-8">
            <div class="flex items-center">
                <img src="~/assets/img/logo.png" alt="">
            </div>
        </div>

        <nav class="mt-10">
            <NuxtLink to="/dashboard" activeClass="text-[#136FFB]" class="flex items-center px-6 py-2 mt-4 ml-12 hover:text-[#136FFB]">
                <Icon name="bi:grid-fill" />
                <span class="mx-3">Dashboard</span>
            </NuxtLink>

            <NuxtLink to="/referrals" activeClass="text-[#136FFB]" class="flex items-center px-6 py-2 mt-4 ml-12 hover:text-[#136FFB]">
                <Icon name="raphael:people" />
                <span class="mx-3">Referrals</span>
            </NuxtLink>

            <NuxtLink to="/payouts" activeClass="text-[#136FFB]" class="flex items-center px-6 py-2 mt-4 ml-12 hover:text-[#136FFB]">
                <Icon name="ic:round-featured-play-list" />
                <span class="mx-3">Payouts</span>
            </NuxtLink>

            <NuxtLink to="/profile" activeClass="text-[#136FFB]" class="flex items-center px-6 py-2 mt-4 ml-12 hover:text-[#136FFB]">
                <Icon name="ic:round-school" />
                <span class="mx-3">Profile</span>
            </NuxtLink>
        </nav>
    </div>
</template>

<script setup>

const active = () => {

}
</script>