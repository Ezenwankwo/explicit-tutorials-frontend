<template>
    <div class="bg-[#C6DBFB] p-12 rounded">
        <div class="flex">
            <div class="w-full md:w-1/3">
                <div class="avatar">
                    <div class="w-60 rounded">
                        <img src="~/assets/img/user.png" />
                    </div>
                </div>
            </div>
            <div class="w-full md:w-2/3">
                <div class="flex justify-between items-center">
                    <p class="text-[#1A1919] text-2xl">Augustus Ezenwankwo</p>
                    <NuxtLink to="/profile-update">
                        <button class="btn btn-sm capitalize border-[#FB9139] text-[#FFFFFF] bg-[#FB9139]">Edit profile</button>
                    </NuxtLink>
                </div>
                <div class="text-[#1A1919]">
                    <p>Referral ID: 002856AD</p>
                    <p>Plan: Premium</p>
                </div>
                <div class="flex flex-col-reverse divide-gray-400 divide-y divide-y-reverse mt-8">
                    <div></div>
                    <div></div>
                </div>
                <div class="flex justify-between items-center mt-8 text-sm">
                    <div class="flex flex-col">
                        <div>
                            <p class="opacity-50">Phone Number</p>
                            <p class="mt-2">08183096264</p>
                        </div>
                        <div class="mt-8">
                            <p class="opacity-50">Email</p>
                            <p class="mt-2">ezewankwog@gmail.com</p>
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div>
                            <p class="opacity-50">Date Joined</p>
                            <p class="mt-2">Mon 6, Nov 2022</p>
                        </div>
                        <div class="mt-8">
                            <p class="opacity-50">Last Active</p>
                            <p class="mt-2">Mon 6, Nov 2022 08:39am</p>
                        </div>
                    </div>
                    <div class="flex flex-col">
                        <div>
                            <p class="opacity-50">Total Referrals</p>
                            <p class="mt-2">48</p>
                        </div>
                        <div class="mt-8">
                            <p class="opacity-50">Plan</p>
                            <p class="mt-2">Basic</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
definePageMeta({
    layout: "internal",
});
</script>