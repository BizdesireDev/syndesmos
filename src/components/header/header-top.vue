<template>
    <div class="headerTop w-[100%] relative h-[100% ] ml-[auto] mr-[auto] pl-[20px] pr-[20px] lg:pl-[0] lg:pr-[0] bg-primary-100">
        <div class="flex justify-between items-center lg:justify-center lg:items-end lg:h-[30px] flex-wrap pt-[10px] pb-[10px] lg:pt-[0] lg:pb-[3px]">
            <div class="hidden lg:block">

            </div>
            <div class="">
                <ul class="list-none m-0 p-0 inline-flex">
                    <li class="font-Manrope text-white text-[12px] leading-[22px] pr-[8px] pl-[8px] lg:pr-[14px] lg:pl-[14px]">Εταιρία</li>
                    <li class="font-Manrope text-white text-[12px] leading-[22px] pr-[8px] pl-[8px] lg:pr-[14px] lg:pl-[14px]">Νέα</li>
                    <li class="font-Manrope text-white text-[12px] leading-[22px] pr-[8px] pl-[8px] lg:pr-[14px] lg:pl-[14px]">Επικοινωνία</li>
                    <li class="font-Manrope text-white text-[12px] leading-[22px] pr-[8px] pl-[8px] lg:pr-[14px] lg:pl-[14px]">Κατηγορίες</li>
                </ul>
            </div>
            <div class="flex justify-center items-center lg:absolute lg:right-[18px]">
                <p class="font-Manrope text-white text-[12px] leading-[22px] hidden lg:block">Χρειάζεστε βοήθεια?  Καλέστε μας: 210 269 3600  &nbsp;&nbsp;&nbsp;</p>
                <a href="tel:+210 269 3600" ><img :src="mobile" /> </a>
            </div>
        </div>
    </div>
</template>
<script>
    import mobile from '../../assets/image/mobile.png'
    export default{
        data: function () {
            return {
                mobile: mobile,
            }
        }
    }
</script>
