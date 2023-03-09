<template>
    <div>
        <div class="flex flex-wrap">
            <div class="w-full md:w-1/3 px-4 mb-8">
                <div>
                    <div class="bg-white p-6 rounded-lg shadow-lg">
                        <div class="flex flex-wrap">
                            <div class="w-3/5">
                                <Icon name="raphael:people" class="text-5xl text-[#136FFB]" />
                                <p class="text-lg text-[#020EB0] my-2">Referrals</p>
                                <p class="text-xl text-[#020EB0] my-2">48</p>
                            </div>
                            <div class="w-2/5 my-auto">
                                <img src="~/assets/img/minichart.png" alt="">
                            </div>
                        </div>
                        <span class="text-[#22BF4C]">
                            <Icon name="majesticons:academic-cap" /><small> 7.2%</small>
                        </span>
                        <span class="text-[#8C10C6]">
                            <Icon name="raphael:acw" class="ml-2" /><small> 8.5%</small>
                        </span>
                    </div>
                </div>
            </div>
            <div class="w-full md:w-1/3 px-4 mb-8">
                <div>
                    <div class="bg-white p-6 rounded-lg shadow-lg">
                        <div class="flex flex-wrap">
                            <div class="w-3/5">
                                <Icon name="tabler:currency-naira" class="text-5xl text-[#136FFB]" />
                                <p class="text-lg text-[#020EB0] my-2">Bonuses</p>
                                <p class="text-xl text-[#020EB0] my-2">&#8358; 15,000</p>
                            </div>
                            <div class="w-2/5 my-auto">
                                <img src="~/assets/img/minichart.png" alt="">
                            </div>
                        </div>
                        <span class="text-[#136FFB]">
                            <Icon name="tabler:arrow-wave-right-up" /><small> 7.2%</small>
                        </span>
                    </div>
                </div>
            </div>
            <div class="w-full md:w-1/3 px-4 mb-8">
                <div>
                    <div class="bg-white p-6 rounded-lg shadow-lg">
                        <div class="flex flex-wrap">
                            <div class="w-3/5">
                                <Icon name="material-symbols:payments-outline" class="text-5xl text-[#136FFB]" />
                                <p class="text-lg text-[#020EB0] my-2">Payouts</p>
                                <p class="text-xl text-[#020EB0] my-2">&#8358; 5,000</p>
                            </div>
                            <div class="w-2/5 my-auto">
                                <img src="~/assets/img/minichart.png" alt="">
                            </div>
                        </div>
                        <span class="text-[#136FFB]">
                            <Icon name="tabler:arrow-wave-right-up" /><small> 7.2%</small>
                        </span>
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