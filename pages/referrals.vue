<template>
    <div class="bg-[#C6DBFB] p-6 rounded">
        <div class="flex justify-between items-center">
            <h3>Referrals</h3>
            <select class="select">
                <option>All</option>
                <option>7 days ago</option>
                <option>30 days ago</option>
                <option>90 days ago</option>
                <option>One year ago</option>
            </select>
        </div>
        <div class="overflow-x-auto w-full my-8">
            <table class="table w-full">
                <thead>
                    <tr>
                        <th class="capitalize">Name</th>
                        <th class="capitalize">Date</th>
                        <th class="capitalize">Type</th>
                        <th class="capitalize">Plan</th>
                    </tr>
                </thead>
                <tbody>
                    <!-- row 1 -->
                    <tr>
                        <td>
                            <div class="flex items-center space-x-3">
                                <div class="avatar placeholder">
                                    <div class="bg-neutral-focus text-neutral-content rounded-full w-8">
                                        <span class="text-xs">HH</span>
                                    </div>
                                </div>
                                <div>
                                    <div class="font-bold">Hart Hagerty</div>
                                </div>
                            </div>
                        </td>
                        <td>
                            10:45:16 AM
                        </td>
                        <td>Student</td>
                        <th class="font-normal">
                            Basic
                        </th>
                    </tr>
                    <!-- row 2 -->
                    <tr>
                        <td>
                            <div class="flex items-center space-x-3">
                                <div class="avatar placeholder">
                                    <div class="bg-neutral-focus text-neutral-content rounded-full w-8">
                                        <span class="text-xs">BS</span>
                                    </div>
                                </div>
                                <div>
                                    <div class="font-bold">Brice Swyre</div>
                                </div>
                            </div>
                        </td>
                        <td>
                            10:45:16 AM
                        </td>
                        <td>Affiliate</td>
                        <th class="font-normal text-[#FF0000]">
                            Premium
                        </th>
                    </tr>
                    <!-- row 3 -->
                    <tr>
                        <td>
                            <div class="flex items-center space-x-3">
                                <div class="avatar placeholder">
                                    <div class="bg-neutral-focus text-neutral-content rounded-full w-8">
                                        <span class="text-xs">MF</span>
                                    </div>
                                </div>
                                <div>
                                    <div class="font-bold">Marjy Ferencz</div>
                                </div>
                            </div>
                        </td>
                        <td>
                            10:45:16 AM
                        </td>
                        <td>Student</td>
                        <th class="font-normal">
                            Basic
                        </th>
                    </tr>
                    <!-- row 1 -->
                    <tr>
                        <td>
                            <div class="flex items-center space-x-3">
                                <div class="avatar placeholder">
                                    <div class="bg-neutral-focus text-neutral-content rounded-full w-8">
                                        <span class="text-xs">HH</span>
                                    </div>
                                </div>
                                <div>
                                    <div class="font-bold">Hart Hagerty</div>
                                </div>
                            </div>
                        </td>
                        <td>
                            10:45:16 AM
                        </td>
                        <td>Student</td>
                        <th class="font-normal">
                            Basic
                        </th>
                    </tr>
                    <!-- row 2 -->
                    <tr>
                        <td>
                            <div class="flex items-center space-x-3">
                                <div class="avatar placeholder">
                                    <div class="bg-neutral-focus text-neutral-content rounded-full w-8">
                                        <span class="text-xs">BS</span>
                                    </div>
                                </div>
                                <div>
                                    <div class="font-bold">Brice Swyre</div>
                                </div>
                            </div>
                        </td>
                        <td>
                            10:45:16 AM
                        </td>
                        <td>Affiliate</td>
                        <th class="font-normal text-[#FF0000]">
                            Premium
                        </th>
                    </tr>
                    <!-- row 3 -->
                    <tr>
                        <td>
                            <div class="flex items-center space-x-3">
                                <div class="avatar placeholder">
                                    <div class="bg-neutral-focus text-neutral-content rounded-full w-8">
                                        <span class="text-xs">MF</span>
                                    </div>
                                </div>
                                <div>
                                    <div class="font-bold">Marjy Ferencz</div>
                                </div>
                            </div>
                        </td>
                        <td>
                            10:45:16 AM
                        </td>
                        <td>Student</td>
                        <th class="font-normal">
                            Basic
                        </th>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
</template>

<script>
definePageMeta({
    layout: "internal",
});
</script>