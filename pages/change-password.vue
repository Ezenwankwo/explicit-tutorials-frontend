<template>
    <div class="bg-[#C6DBFB] p-12 rounded">
        <h3 class="mb-8">Change Password</h3>
        <form action="">
            <div class="form-control w-full md:w-1/2 mb-4">
                <label class="label">
                    <span class="label-text">Current Password</span>
                </label>
                <input type="text" class="input input-bordered w-full" required />
            </div>
            <div class="form-control w-full md:w-1/2 mb-4">
                <label class="label">
                    <span class="label-text">New Password</span>
                </label>
                <input type="text" class="input input-bordered w-full" required />
            </div>
            <div class="form-control w-full md:w-1/2 mb-4">
                <label class="label">
                    <span class="label-text">Confirm New Password</span>
                </label>
                <input type="text" class="input input-bordered w-full" required />
            </div>
            <button
                        class="btn mx-auto bg-[#020EB0] border-[#020EB0] hover:bg-blue-700 hover:border-blue-700 focus:bg-blue-700 focus:border-blue-700 mt-4">Save</button>
        </form>
    </div>
</template>

<script>
definePageMeta({
    layout: "internal",
});
</script>