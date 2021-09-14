<template>
    <div class="px-3 py-4 flex items-center justify-between">
        <div class="flex items-center">
            <button class="rounded-full hover:bg-light p-3 flex items-center justify-center" type="button" name="button">
            <img src="http://pngimg.com/uploads/pinterest/pinterest_PNG45.png" alt="" class=" h-6 w-6">
            </button>
            <button  v-for="(item,index) in tabItems" :key="index" @click="selectedTab = item.key" type="button" name="button" :class="`${selectedTab===item.key ? 'bg-dark text-light' : ' hover:bg-lightHover text-dark' } rounded-full py-3 px-4 font-semibold`">
                {{item.name}}
            </button>
        </div>
        <div class="flex-grow relative">
            <span class="material-icons absolute mt-3 ml-3 text-muted">search</span>
            <input type="text" class=" w-full hover:bg-lightHover text-muted rounded-full bg-light py-3 pr-3 pl-10 focus:outline-none border solid white focus:border-[1px]  focus:border-muted" placeholder="Search">
        </div>
        <div class="flex items-center">
            <button type=" button" class="relative rounded-full hover:bg-light flex items-center justify-center p-3">
                <span class="material-icons text-3xl text-muted">notifications</span>
                <div class="rounded-full h-5 w-5 bg-primary text-white flex items-center justify-center absolute mb-5 ml-5">4</div>
            </button>
            <button type=" button" class="relative rounded-full hover:bg-light flex items-center justify-center p-3">
                <span class="material-icons text-3xl text-muted">textsms</span>
                <div class="rounded-full h-5 w-5 bg-primary text-white flex items-center justify-center absolute mb-5 ml-5">5</div>
            </button>
            <button class="rounded-full hover:bg-light p-3 flex items-center justify-center" type="button" name="button">
            <img src="https://yt3.ggpht.com/yti/APfAmoG83tGd_mcU-UmVuAYB2jRsFEYVk-ePyBDOazilaw=s88-c-k-c0x00ffffff-no-rj-mo" class=" h-7 w-7 rounded-full object-cover object-center">
            </button>
            <button type="button" name="button" class="w-6 h-6 hover:bg-light rounded-full flex items-center justify-center">
                <span class="material-icons text-3xl text-muted">expand_more</span>
            </button>
            
            
        </div>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                tabItems:[
                    {name:'Home', key:'home'},
                    {name:'Today', key:'today'},
                ],
                selectedTab:'home'
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>