<template>
    <div class="container mx-auto p-8 md:px-12">
        <!--<AppBackButton />-->
        <div>
            <h2 class="text-2xl md:text-4xl text-[#020EB0] font-bold mt-8">
                Affiliate Login
            </h2>
        </div>
        <div class="grid sm:grid-cols-1 md:grid-cols-2 xl:grid-cols-5 mb-8">
            <div class="sm:col-span-1 md:col-span-1 lg:col-span-2">
                <div class="flex flex-col">
                    <div class="py-6">
                        <p class="text-medium leading-6 text-gray-700">
                            Kindly input your correct <span class="text-[#FB9139]">Affiliate login</span> details to onboard.
                        </p>
                    </div>
                    <img src="~/assets/img/register.png" class="hidden md:block w-full object-cover mt-4" alt="Image">
                </div>

            </div>
            <div class="sm:col-span-1 md:col-span-1 lg:col-span-3">
                <form class="flex flex-col rounded-lg md:w-2/3 mx-auto">
                    <div class="form-control w-full mb-4">
                        <label class="label">
                            <span class="label-text">Email</span>
                        </label>
                        <input type="email" class="input input-bordered w-full" required />
                    </div>
                    <div class="form-control w-full mb-2">
                        <label class="label">
                            <span class="label-text">Password</span>
                        </label>
                        <input type="password" class="input input-bordered w-full" required />
                    </div>
                    <div class="text-xs text-[#FB9139] mb-8">
                        <NuxtLink to="/">Forgot password?</NuxtLink>
                    </div>
                    <NuxtLink to="/dashboard" class="btn w-2/3 mx-auto bg-[#020EB0] border-[#020EB0] capitalize hover:bg-blue-700 hover:border-blue-700 focus:bg-blue-700 focus:border-blue-700 mb-4">
                        <button>Login</button>
                    </NuxtLink>
                    <div class="text-xs mx-auto">You dont have an account? <NuxtLink to="/affiliate" class="text-[#136FFB]">Sign up here.</NuxtLink></div>
                </form>

            </div>
        </div>
    </div>
</template>