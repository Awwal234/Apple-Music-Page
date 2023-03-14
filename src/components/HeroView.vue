<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({
    components: {

    },
});
</script>

<template>
    <div class="px-[90px] w-full mt-[237px]">
        <div class="md:block lg:flex lg:items-center w-full">
            <!--starting block one-->
            <div class="lg:w-[60%] md:w-[80%]">
                <div class="font-[700] text-[64px] text-[#211D27] leading-[70.29px]">
                    Get 75 million songs free for 1 month.
                </div>
                <div
                    class="font-[300] font-[Roboto] mt-[17px] lg:w-[80%] md:w-[90%] mb-[37px] text-[30px] text-[#8C8B8F] leading-[39.36px]">
                    Plus your entire music library on all your
                    devices. 1 month free, then $ 1/month.
                </div>
                <button
                    class="bg-[#E6444F] py-[12px] px-[43px] rounded-[8px] font-[500] text-[#F5F5F5] text-[22px] leading-[28.86px]">
                    Try it Free
                </button>
            </div>
            <!--end block one-->
            <!--starting block two-->
            <div class="w-fit md:mx-auto lg:w-[40%] lg:mx-[0px] h-fit">
                <div><img src="/img/headpod.png" class="lg:w-full" alt="" /></div>
            </div>
            <!--end block one-->
        </div>
        <!--end flex table-->
        <!--footer-->
        <div class="py-[75px] relative bottom-0">
            <div class="flex cursor-pointer items-center justify-center space-x-[8px] mx-auto">
                <div><img src="/img/musiclogo.svg" class="" alt="music_logo" /></div>
                <div class="font-[Roboto] font-[300] text-[22px] text-[#8C8B8F] leading-[28.66px]">Open in Music</div>
                <div><img src="/img/uparrow.svg" class="" alt="arrow" /></div>
            </div>
        </div>
        <!--end footer-->
    </div>
    <!--screen-->
</template>