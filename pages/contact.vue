<template>
  <div class="container mx-auto py-12 bg-white">
    <div class="isolate bg-white px-6 lg:px-8">
      <div class="mx-auto max-w-2xl text-center">
        <h2 class="text-2xl md:text-4xl font-bold text-center text-gray-700 mb-4">Contact Us</h2>
        <p class="text-medium leading-6 text-gray-700">
          Let's talk about your needs.
        </p>
      </div>
      <form action="#" method="POST" class="mx-auto mt-16 max-w-xl">
        <div class="grid grid-cols-1 gap-y-4 gap-x-8 sm:grid-cols-2">
          <div class="form-control w-full mb-2">
            <label class="label">
              <span class="label-text">First name</span>
            </label>
            <input type="email" class="input input-bordered w-full" required />
          </div>
          <div class="form-control w-full mb-2">
            <label class="label">
              <span class="label-text">Last name</span>
            </label>
            <input type="email" class="input input-bordered w-full" required />
          </div>
          <div class="form-control w-full mb-2">
            <label class="label">
              <span class="label-text">Email address</span>
            </label>
            <input type="email" class="input input-bordered w-full" required />
          </div>
          <div class="form-control w-full mb-2">
            <label class="label">
              <span class="label-text">Phone number</span>
            </label>
            <input type="email" class="input input-bordered w-full" required />
          </div>
        </div>
        <div class="form-control w-full mb-2 mt-4">
          <label for="message" class="label">
            <span class="label-text">Message</span>
          </label>
          <textarea name="message" id="message" rows="4"
            class="block textarea textarea-bordered textarea-md w-full"></textarea>
        </div>
        <div class="flex flex-col mt-8">
          <button
            class="btn w-2/3 mx-auto bg-[#020EB0] border-[#020EB0] capitalize hover:bg-blue-700 hover:border-blue-700 focus:bg-blue-700 focus:border-blue-700 mb-4">Let's talk</button>

        </div>
      </form>
    </div>
  </div>
</template>

<script>
definePageMeta({
  layout: "external",
});
const firstName = ref('')
const lastName = ref('')
const email = ref('')
const phone = ref('')
const message = ref('')
</script>