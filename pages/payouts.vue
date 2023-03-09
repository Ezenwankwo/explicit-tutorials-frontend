<template>
    <div class="bg-[#C6DBFB] p-6 rounded">
        <div class="flex lg:justify-between items-center">
            <h3>Payouts</h3>
            <div class="flex flex-column items-center">
                <p class="text-[#020EB0] font-bold mr-4">Balance: &#8358;15,000</p>
                <button class="btn btn-sm bg-[#136FFB] border-[#136FFB] capitalize" @click="toggle">Request payout</button>
            </div>
        </div>
        <div class="overflow-x-auto w-full my-8">
            <table class="table w-full">
                <thead>
                    <tr>
                        <th class="capitalize">Account Name</th>
                        <th class="capitalize">Date & Time</th>
                        <th class="capitalize">Amount</th>
                        <th class="capitalize">Status</th>
                    </tr>
                </thead>
                <tbody>
                    <!-- row 1 -->
                    <tr>
                        <td>
                            <div class="flex items-center space-x-3">
                                <div>
                                    <div class="font-bold">Hart Hagerty</div>
                                </div>
                            </div>
                        </td>
                        <td>
                            June 15 2022, 10:45:16 AM
                        </td>
                        <td>&#8358; 10,000</td>
                        <th class="font-normal">
                            Completed
                        </th>
                    </tr>
                    <!-- row 2 -->
                    <tr>
                        <td>
                            <div class="flex items-center space-x-3">
                                <div>
                                    <div class="font-bold">Brice Swyre</div>
                                </div>
                            </div>
                        </td>
                        <td>
                            June 15 2022, 10:45:16 AM
                        </td>
                        <td>&#8358; 18,500</td>
                        <th class="font-normal text-[#FF0000]">
                            Pending
                        </th>
                    </tr>
                    <!-- row 3 -->
                    <tr>
                        <td>
                            <div class="flex items-center space-x-3">
                                <div>
                                    <div class="font-bold">Marjy Ferencz</div>
                                </div>
                            </div>
                        </td>
                        <td>
                            June 15 2022, 10:45:16 AM
                        </td>
                        <td>&#8358; 15,000</td>
                        <th class="font-normal">
                            Completed
                        </th>
                    </tr>
                </tbody>
            </table>
        </div>


        <!--payout modal-->
        <!-- Put this part before </body> tag -->
        <input type="checkbox" id="my-modal-3" class="modal-toggle" />
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
definePageMeta({
    layout: "internal",
});
</script>