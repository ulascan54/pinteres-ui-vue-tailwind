<template>
    <div class="relative group ">
        <img :src="src" alt="" class="rounded-lg ">
        <div class="absolute bg-dark opacity-50 inset-0 w-full h-full  hidden rounded-lg  group-hover:block transition-all"></div>
        <div class="absolute top-0 w-full h-full  flex-col  hidden justify-between p-3  group-hover:flex transition-all">
            <div class="flex items-center justify-between">
                <button type="button" name="button" class="flex items-center">
                    <p class="font-semibold text-white">{{board}}</p>
                    <span class="material-icons text-white">expand_more</span>
                </button>
                <button type="button" name="button" class="rounded-full py-3 px-5 font-semibold text-white bg-primary">
                    Save
                </button>
            </div>
            <div class="flex items-center">
                <button type="button" class="ml-auto mr-2 bg-white rounded-full p-2 text-dark opacity-70 hover:opacity-100 w-9 h-9 flex items-center justify-center">
                    <span class="material-icons text-base">ios_share</span>
                </button>
                <button type="button" class="bg-white rounded-full p-2 text-dark opacity-70 hover:opacity-100 w-9 h-9 flex items-center justify-center ">
                    <span class="material-icons text-base">more_horiz</span>
                </button>
            </div>
        </div>

    </div>
</template>

<script>
    export default {
        props:['src','board'],
    }
</script>

<style lang="scss" scoped>
</style>