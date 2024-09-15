<template>
    <div class="flex flex-col h-screen">
        <Header />
        <div class="flex flex-grow justify-between p-4 space-x-4">
            <div class="rounded-lg bg-[#8cbd6b] w-2/3">
                <slot />
            </div>

            <div class="relative rounded-lg bg-[#ffcd33] w-1/3 flex justify-center items-center">
                <p class="absolute top-0 right-0 text-[#bf9000] p-4 font-bold">layouts/default.vue</p>
                <p class="text-3xl font-bold">Sidebar</p>
            </div>
        </div>
        <Footer />
    </div>
</template>