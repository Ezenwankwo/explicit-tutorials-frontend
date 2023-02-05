<template>
    <div class="bg-home">
        <AppHeader />
        <slot />
        <AppFooter />
    </div>
</template>


<style>
.bg-home {
    background-image: url(~/assets/img/home.svg);
    background-repeat: no-repeat;
}
</style>