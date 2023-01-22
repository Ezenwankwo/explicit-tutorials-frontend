<template>
    <div class="container mx-auto p-4 md:p-8">
        <AppBackButton />
        <div>
            <h2 class="text-lg text-blue-500 font-medium mt-4">
                Affiliate Login
            </h2>
        </div>
        <div class="grid sm:grid-cols-1 md:grid-cols-2 xl:grid-cols-5 gap-x-8">
            <div class="sm:col-span-1 md:col-span-1 lg:col-span-2">
                <div class="flex flex-col">
                    <div class="py-6">
                        <p class="text-medium text-gray-700">
                            Kindly input your correct <span class="text-orange-500">Affiliate login</span> details to onboard.
                        </p>
                    </div>
                    <img src="~/assets/img/register.png" class="hidden md:block w-full object-cover" alt="Image">
                </div>

            </div>
            <div class="sm:col-span-1 md:col-span-1 lg:col-span-3">
                <form class="rounded-lg">
                    <div class="form-control w-full lg:w-2/3 mb-4">
                        <label class="label">
                            <span class="label-text">Email</span>
                        </label>
                        <input type="email" class="input input-bordered w-full" required />
                    </div>
                    <div class="form-control w-full lg:w-2/3 mb-2">
                        <label class="label">
                            <span class="label-text">Password</span>
                        </label>
                        <input type="password" class="input input-bordered w-full" required />
                    </div>
                    <div class="text-xs text-orange-500 mb-4">
                        <NuxtLink to="/">Forgot password?</NuxtLink>
                    </div>
                    <button class="btn bg-blue-500 border-blue-500 hover:bg-blue-700 hover:border-blue-700 focus:bg-blue-700 focus:border-blue-700 mb-4">Login</button>
                    <div class="text-xs">You dont have an account? <NuxtLink to="/affiliate" class="text-blue-500">Sign up here.</NuxtLink></div>
                </form>

            </div>
        </div>
    </div>
</template>