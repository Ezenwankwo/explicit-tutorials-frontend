<template>
    <div class="container mx-auto p-8 md:px-12">
        <!--<AppBackButton />-->
        <div>
            <h2 class="text-2xl md:text-4xl text-[#020EB0] font-bold mt-8">
                Become an Affiliate and earn<br> on every referral you made.
            </h2>
        </div>
        <div class="grid sm:grid-cols-1 md:grid-cols-2 xl:grid-cols-5 gap-x-8 mb-8">
            <div class="sm:col-span-1 md:col-span-1 lg:col-span-2">
                <div class="flex flex-col">
                    <div class="py-6">
                        <p class="text-medium text-gray-700">
                            As an  <span class="text-[#FB9139]">Affiliate</span>, you earn on every refferal
                            you made based on your registration plan.
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
                        <input type="text" class="input input-bordered w-full" required />
                    </div>
                    <div class="form-control w-full mb-4">
                        <label class="label">
                            <span class="label-text">Email</span>
                        </label>
                        <input type="email" class="input input-bordered w-full" required />
                    </div>
                    <div class="form-control w-full mb-4">
                        <label class="label">
                            <span class="label-text">Phone Number</span>
                        </label>
                        <input type="tel" class="input input-bordered w-full" required />
                    </div>
                    <div class="form-control w-full mb-4">
                        <label class="label">
                            <span class="label-text">Plan</span>
                        </label>
                        <select class="select select-bordered">
                            <option disabled selected>Select Plan</option>
                            <option>Basic</option>
                            <option>Premium</option>
                        </select>
                    </div>
                    <div class="form-control w-full mb-4">
                        <label class="label">
                            <span class="label-text">Password</span>
                        </label>
                        <input type="password" class="input input-bordered w-full" required />
                    </div>
                    <div class="form-control w-full mb-4">
                        <label class="label">
                            <span class="label-text">Confirm Password</span>
                        </label>
                        <input type="password" class="input input-bordered w-full" required />
                    </div>
                    <div class="form-control w-full mb-4">
                        <label class="label">
                            <span class="label-text">Referral ID(Optional)</span>
                        </label>
                        <input type="text" class="input input-bordered w-full" />
                    </div>
                    <div class="form-control my-auto mb-8">
                        <label class="label cursor-pointer">
                            <input type="checkbox" class="checkbox" />
                            <span class="label-text">I accept the <a href="#" class="text-blue-500">terms
                                    of use</a> and <a href="#" class="text-blue-500">privacy policy</a>.</span>
                        </label>
                    </div>

                    <button
                        class="btn w-2/3 mx-auto capitalize bg-[#020EB0] border-[#020EB0] hover:bg-blue-700 hover:border-blue-700 focus:bg-blue-700 focus:border-blue-700 mb-4">Submit</button>
                </form>

            </div>
        </div>
    </div>
</template>