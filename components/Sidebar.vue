<template>
    <div class="bg-white sticky top-0 w-60 z-50 h-screen pl-12">
        <div class="mt-6 ">
            <img src="../static/images/walulel_logo.png" alt="logo" class="h-16 w-auto mx-auto" />
        </div>

        <nav class="mt-10">
            <ul class="space-y-3">
                <li v-for="link in links">
                    <nuxt-link :to="link.to" class="flex items-center hover:bg-[#E6E6E6] py-3 px-3 rounded-[10px]">
                        <img src="../static/icons/nav-icon.svg" alt="nav-icon" />
                        <div class="w-full text-center">
                            <span class="text-lg font-semibold leading-5 ">
                                {{ link.name }}
                            </span>

                        </div>
                    </nuxt-link>

                </li>

            </ul>
        </nav>
        <div class="fixed bottom-1 inset-x-0 left-12 ">
            <div class="flex space-x-3 items-center">
                <img src="../static/icons/arrow-left.svg" alt="left-arrow" />
               <button><h3 class="text-lg font-semibold leading-5">Collapse Sidebar</h3></button> 
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: "Sidebar",
    data() {
        return {
            links: [
                {
                    id: 1,
                    name: "About Us",
                    to: "/about-us"
                },
                {
                    id: 2,
                    name: "Find Job",
                    to: "/find-job"
                },
                {
                    id: 3,
                    name: "Contact Us",
                    to: "/contact-us"
                },

            ]
        }
    }

}
</script>
<style scoped>
.nuxt-link-active {
    @apply text-primary;
}
</style>