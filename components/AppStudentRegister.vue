<template>
    <div class="container mx-auto p-4 md:p-8">
        <AppBackButton />
        <div>
            <h2 class="text-lg text-blue-500 font-medium mt-4">
                Student Registration
            </h2>
        </div>
        <div class="grid sm:grid-cols-1 md:grid-cols-2 xl:grid-cols-5 gap-x-8">
            <div class="sm:col-span-1 md:col-span-1 lg:col-span-2">
                <div class="flex flex-col">
                    <div class="py-6">
                        <p class="text-medium text-gray-700">
                            As a Student preparing for exams, Explicit Online tutorial is
                            designed to make learning easy anywhere you are, with success quaranteed.
                        </p>
                    </div>
                    <img src="~/assets/img/register.png" class="hidden md:block w-full object-cover" alt="Image">
                </div>

            </div>
            <div class="sm:col-span-1 md:col-span-1 lg:col-span-3">
                <form class="rounded-lg">

                    <div class="grid sm:grid-cols-1 lg:grid-cols-2 gap-4 mb-4">
                        <div class="form-control w-full">
                            <label class="label">
                                <span class="label-text">Full Name</span>
                            </label>
                            <input type="text" class="input input-bordered w-full" required />
                        </div>
                        <div class="form-control w-full">
                            <label class="label">
                                <span class="label-text">Email</span>
                            </label>
                            <input type="email" class="input input-bordered w-full" required />
                        </div>
                    </div>

                    <div class="grid sm:grid-cols-1 lg:grid-cols-2 gap-4 mb-4">
                        <div class="form-control w-full">
                            <label class="label">
                                <span class="label-text">Phone Number</span>
                            </label>
                            <input type="tel" class="input input-bordered w-full" required />
                        </div>

                        <div class="form-control w-full">
                            <label class="label">
                                <span class="label-text">Plan</span>
                            </label>
                            <select class="select select-bordered">
                                <option disabled selected>Select Plan</option>
                                <option>Basic</option>
                                <option>Premium</option>
                            </select>
                        </div>
                    </div>

                    <div class="grid sm:grid-cols-1 lg:grid-cols-2 gap-4 mb-4">
                        <div class="form-control w-full">
                            <label class="label">
                                <span class="label-text">Referral ID(Optional)</span>
                            </label>
                            <input type="text" class="input input-bordered w-full" />
                        </div>
                        <div class="form-control my-auto">
                            <label class="label cursor-pointer">
                                <input type="checkbox" class="checkbox" />
                                <span class="label-text">I accept the <a href="#" class="text-blue-500">terms
                                    of use</a> and <a href="#" class="text-blue-500">privacy policy</a>.</span>
                            </label>
                        </div>
                    </div>

                    <button class="btn bg-blue-500 border-blue-500 hover:bg-blue-700 hover:border-blue-700 focus:bg-blue-700 focus:border-blue-700 mb-4">Submit</button>
                </form>

            </div>
        </div>
    </div>
</template>