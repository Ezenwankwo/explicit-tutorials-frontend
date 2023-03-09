<template>
    <div class="bg-[#C6DBFB] p-12 rounded">
        <h3 class="mb-8">Update Profile</h3>
        <div class="flex">
            <div class="w-full md:w-1/3">
                <div class="avatar">
                    <div class="w-60 rounded">
                        <img src="~/assets/img/user.png" />
                    </div>
                </div>
            </div>
            <div class="w-full md:w-2/3">
                <form action="">
                    <div class="flex flex-row gap-4">
                        <div class="form-control w-full mb-4">
                            <label class="label">
                                <span class="label-text">First Name</span>
                            </label>
                            <input type="text" class="input input-bordered w-full" required />
                        </div>
                        <div class="form-control w-full mb-4">
                            <label class="label">
                                <span class="label-text">Last Name</span>
                            </label>
                            <input type="text" class="input input-bordered w-full" required />
                        </div>
                    </div>
                    <div class="flex flex-row gap-4">
                        <div class="form-control w-full mb-4">
                            <label class="label">
                                <span class="label-text">Email</span>
                            </label>
                            <input type="text" class="input input-bordered w-full" required />
                        </div>
                        <div class="form-control w-full mb-4">
                            <label class="label">
                                <span class="label-text">Phone Number</span>
                            </label>
                            <input type="text" class="input input-bordered w-full" required />
                        </div>
                    </div>
                    <button
                        class="btn mx-auto bg-[#020EB0] border-[#020EB0] hover:bg-blue-700 hover:border-blue-700 focus:bg-blue-700 focus:border-blue-700 mt-4">Save</button>
                </form>
            </div>
        </div>
    </div>
</template>

<script>
definePageMeta({
    layout: "internal",
});
</script>