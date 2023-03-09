<template>
    <div class="container mx-auto p-8 md:px-12">
        <!--<AppBackButton />-->
        <div>
            <h2 class="text-2xl md:text-4xl text-[#020EB0] font-bold mt-8">
                Ace Your Exams At One Sitting<br> with Expilicit online tutorials.
            </h2>
        </div>
        <div class="grid sm:grid-cols-1 md:grid-cols-2 xl:grid-cols-5 gap-x-8 mb-8">
            <div class="sm:col-span-1 md:col-span-1 lg:col-span-2">
                <div class="flex flex-col">
                    <div class="py-6">
                        <p class="text-medium leading-6 text-gray-700">
                            As a <span class="text-[#FB9139]">Student preparing for exams</span>, Explicit Online
                            tutorial is
                            designed to make learning easy anywhere you are, with success quaranteed.
                        </p>
                    </div>
                    <img src="~/assets/img/register.png" class="hidden md:block w-full object-cover" alt="Image">
                </div>

            </div>
            <div class="sm:col-span-1 md:col-span-1 lg:col-span-3">
                <form class="flex flex-col rounded-lg md:w-2/3 mx-auto">

                    <div class="form-control w-full mb-4">
                        <label class="label">
                            <span class="label-text">Full Name</span>
                        </label>
                        <input type="text" v-model="name" class="input input-bordered w-full" required />
                    </div>
                    <div class="form-control w-full mb-4">
                        <label class="label">
                            <span class="label-text">Email</span>
                        </label>
                        <input type="email" v-model="email" class="input input-bordered w-full" required />
                    </div>

                    <div class="form-control w-full mb-4">
                        <label class="label">
                            <span class="label-text">Phone Number</span>
                        </label>
                        <input type="tel" v-model="phone" class="input input-bordered w-full" required />
                    </div>

                    <div class="form-control w-full mb-4">
                        <label class="label">
                            <span class="label-text">Plan</span>
                        </label>
                        <select v-model="plan" class="select select-bordered">
                            <option disabled selected>Select Plan</option>
                            <option>Basic</option>
                            <option>Premium</option>
                        </select>
                    </div>

                    <div class="form-control w-full mb-4">
                        <label class="label">
                            <span class="label-text">Referral ID(Optional)</span>
                        </label>
                        <input type="text" class="input input-bordered w-full" />
                    </div>
                    <div class="form-control my-auto mb-8">
                        <label class="label cursor-pointer">
                            <input type="checkbox" v-model="terms" class="checkbox" />
                            <span class="label-text">I accept the <a href="#" class="text-[#136FFB]">terms
                                    of use</a> and <a href="#" class="text-[#136FFB]">privacy policy</a>.</span>
                        </label>
                    </div>

                    <button
                        class="btn w-2/3 mx-auto bg-[#020EB0] border-[#020EB0] capitalize hover:bg-blue-700 hover:border-blue-700 focus:bg-blue-700 focus:border-blue-700 mb-4"
                        @click="toggle">Submit</button>
                </form>

            </div>
        </div>
        <input type="checkbox" id="my-modal-3" class="modal-toggle"/>
        <div class="modal" :class="{ 'modal-open': isModalOpen }">
            <div class="modal-box relative">
                <label for="my-modal-3" class="btn btn-sm btn-circle absolute right-2 top-2" @click="toggle">✕</label>
                <h3 class="text-lg font-bold">Congratulations random Internet user!</h3>
                <p class="py-4">You've been selected for a chance to get one year of subscription to use Wikipedia for free!
                </p>
            </div>
        </div>
    </div>
</template>

<script setup>
const isModalOpen = ref(false)
const name = ref('')
const email = ref('')
const phone = ref('')
const plan = ref('')
const terms = ref(false)
const toggle = () => {
    if (name.value !== '' && email.value !== '' && phone.value !== '') {
        isModalOpen.value = !isModalOpen.value
    }
}
</script>