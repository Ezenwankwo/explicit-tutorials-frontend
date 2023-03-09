<template>
    <div class="flex bg-white">
        <AppSideBar />

        <div class="flex-1 flex flex-col overflow-hidden">
            <AppDashboardHeader />

            <main class="flex-1 bg-sky-50">
                <div class="container mx-auto px-6 py-8">
                    <slot />
                </div>
            </main>
        </div>
    </div>
</template>