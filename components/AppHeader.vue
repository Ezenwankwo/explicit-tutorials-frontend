<template>
    <header>
        <nav class="mx-auto flex max-w-7xl items-center justify-between p-6 lg:px-8" aria-label="Global">
            <div class="flex lg:flex-1">
                <a href="#" class="-m-1.5 p-1.5">
                    <span class="sr-only">Your Company</span>
                    <img class="h-8 w-auto" src="~/assets/img/logo.png" alt="logo">
                </a>
                <div class="hidden lg:flex lg:gap-x-12 ml-12 px-1 text-white">
                    <NuxtLink to="/" activeClass="font-semibold">Home</NuxtLink>
                    <NuxtLink to="/classes" activeClass="font-semibold">Classes</NuxtLink>
                    <NuxtLink to="/pricing" activeClass="font-semibold">Pricing</NuxtLink>
                    <NuxtLink to="/contact" activeClass="font-semibold">Contact</NuxtLink>
                </div>
            </div>
            <div class="flex lg:hidden">
      <button type="button" class="-m-2.5 inline-flex items-center justify-center rounded-md p-2.5 text-gray-700" @click="toggle">
        <span class="sr-only">Open main menu</span>
        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
        </svg>
      </button>
    </div>
            <div class="hidden lg:flex lg:flex-1 lg:justify-end">
                <NuxtLink to="/register" class="btn btn-primary capitalize">Register Now</NuxtLink>
                <NuxtLink to="/login" class="btn btn-primary btn-outline capitalize ml-4">Affiliate Login</NuxtLink>
            </div>
        </nav>
        <!-- Mobile menu, show/hide based on menu open state. -->
        <div :class="[isOpen ? '' : 'hidden', 'md:hidden']" role="dialog" aria-modal="true">
            <!-- Background backdrop, show/hide based on slide-over state. -->
            <div class="fixed inset-0 z-10"></div>
            <div
                class="fixed inset-y-0 right-0 z-10 w-full overflow-y-auto bg-white px-6 py-6 sm:max-w-sm sm:ring-1 sm:ring-gray-900/10">
                <div class="flex items-center justify-between">
                    <a href="#" class="-m-1.5 p-1.5">
                        <span class="sr-only">Your Company</span>
                        <img class="h-8 w-auto" src="~/assets/img/logo.png" alt="logo">
                    </a>
                    <button type="button" class="-m-2.5 rounded-md p-2.5 text-gray-700" @click="toggle">
                        <span class="sr-only">Close menu</span>
                        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
                            aria-hidden="true">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
                        </svg>
                    </button>
                </div>
                <div class="mt-6 flow-root">
                    <div class="-my-6 divide-y divide-gray-500/10">
                        <div class="space-y-2 py-6">
                            <NuxtLink to="/" activeClass="bg-[#136FFB] text-white"
                                class="-mx-3 block rounded-lg py-2 px-3 font-medium hover:bg-[#136FFB] hover:text-white" @click="toggle">
                                Home</NuxtLink>
                            <NuxtLink to="classes" activeClass="bg-[#136FFB] text-white"
                                class="-mx-3 block rounded-lg py-2 px-3 font-medium hover:bg-[#136FFB] hover:text-white" @click="toggle">
                                Classes</NuxtLink>
                            <NuxtLink to="/pricing" activeClass="bg-[#136FFB] text-white"
                                class="-mx-3 block rounded-lg py-2 px-3 font-medium hover:bg-[#136FFB] hover:text-white" @click="toggle">
                                Pricing</NuxtLink>
                            <NuxtLink to="/contact" activeClass="bg-[#136FFB] text-white"
                                class="-mx-3 block rounded-lg py-2 px-3 font-medium hover:bg-[#136FFB] hover:text-white" @click="toggle">
                                Contact</NuxtLink>
                        </div>
                        <div class="py-6">
                            <NuxtLink to="/register" class="btn btn-primary capitalize" @click="toggle">Register Now</NuxtLink>
                            <NuxtLink to="/login" class="btn btn-primary btn-outline capitalize ml-4" @click="toggle">Affiliate Login
                            </NuxtLink>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    data() {
        return {
            isOpen: false
        }
    },
    methods: {
        toggle() {
            this.isOpen = !this.isOpen
        }
    }
}
</script>

<!--
        <div class="container navbar px-4 lg:px-12">
        <div class="navbar-start">
            <div class="dropdown">
                <label tabindex="0" class="btn btn-ghost lg:hidden">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                        stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M4 6h16M4 12h8m-8 6h16" />
                    </svg>
                </label>
                <ul tabindex="0"
                    class="menu menu-compact dropdown-content mt-3 p-2 shadow  rounded-box w-52">
                    <li><NuxtLink to="/classes">Classes</NuxtLink></li>
                    <li><NuxtLink to="/pricing">Pricing</NuxtLink></li>
                    <li><NuxtLink to="/contact">Contact</NuxtLink></li>
                </ul>
            </div>
            <NuxtLink to="/">
                <img src="~/assets/img/logo.png" alt="logo">
            </NuxtLink>
            <div class="navbar-center hidden lg:flex ml-4">
                <ul class="menu menu-horizontal px-1 text-white">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/classes">Classes</NuxtLink></li>
                    <li><NuxtLink to="/pricing">Pricing</NuxtLink></li>
                    <li><NuxtLink to="/contact">Contact</NuxtLink></li>
                </ul>
            </div>
        </div>
        <div class="navbar-end">
            <NuxtLink to="/register" class="btn btn-primary capitalize">Register Now</NuxtLink>
            <NuxtLink to="/login" class="btn btn-primary btn-outline capitalize ml-4">Affiliate Login</NuxtLink>
        </div>
    </div>
-->