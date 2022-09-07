<template>
    <div class="flex w-full ">
        <Sidebar />
        <div class="flex w-full max-w-6xl mx-auto px-4 ">
            <div class="w-full relative">
                <nuxt />
            </div>
        </div>
    </div>
</template>

<script>
import Sidebar from '../components/Sidebar.vue';
export default {
    components: {
        Sidebar
    }
}
</script>