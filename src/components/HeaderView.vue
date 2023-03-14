<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({
    components: {

    },
});
</script>

<template>
    <header class="pt-[66px] items-center px-[90px] flex justify-between">
        <div><img src="/img/applelogo.svg" class="cursor-pointer" alt="apple_music logo" /></div>
        <div class="flex space-x-[40px]">
            <div class="flex cursor-pointer md:hidden lg:flex items-center space-x-[7px]">
                <div><img src="/img/network.svg" class="" alt="network logo" /></div>
                <div class="text-[20px] leading-[26.24px] font-[400] text-[#211D27]">Radio</div>
            </div>
            <!----->
            <div class="flex cursor-pointer md:hidden lg:flex items-center space-x-[7px]">
                <div><img src="/img/browse.svg" class="" alt="browselogo" /></div>
                <div class="text-[20px] leading-[26.24px] font-[400] text-[#211D27]">Browse</div>
            </div>
            <!----->
            <div class="flex cursor-pointer md:hidden lg:flex items-center space-x-[7px]">
                <div><img src="/img/play.svg" class="" alt="play logo" /></div>
                <div class="text-[20px] leading-[26.24px] font-[400] text-[#211D27]">Listen Now</div>
            </div>
            <!----->
            <div class="flex cursor-pointer bg-[#211D27] rounded-[8px] py-[12px] px-[15px] items-center space-x-[7px]">
                <div><img src="/img/person.svg" class="" alt="user logo" /></div>
                <div class="text-[20px] leading-[26.24px] font-[400] text-[#F5F5F5]">Sign In</div>
            </div>
            <!----->
        </div>
        <!--end header flex-->
    </header>
</template>