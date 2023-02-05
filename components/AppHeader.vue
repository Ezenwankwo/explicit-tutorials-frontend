<template>
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
</template>