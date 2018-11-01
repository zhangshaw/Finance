<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Ada/>
        <Money/>
        <Adb/>
        <Finance/>
        <Adc/>
        <Footor cname="mfooter"/>
        <Navbor/>
    </div>
</template>

<script>
import Heador from "../public/header.vue"
import Footor from "../public/footer.vue"
import Navbor from "../public/navbar.vue"
import Slider from "./mslider.vue"
import Ada from "./ada.vue"
import Money from "./money.vue"
import Adb from "./adb.vue"
import Finance from "./finance.vue"
import Adc from "./adc.vue"

export default {
    components: {
        Heador,
        Slider,
        Footor,
        Navbor,
        Ada,
        Money,
        Adb,
        Finance,
        Adc
    }
}
</script>

<style lang="scss">
    .mfooter{
        margin-top: 0 !important;
        ul{
            li:first-child{
                display: none;
            }
        }
    }
</style>
