<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Welfare/>
        <Service/>
        <Footor/>
        <Navbor/>
    </div>
</template>

<script>
import Heador from "../public/header.vue"
import Footor from "../public/footer.vue"
import Navbor from "../public/navbar.vue"
import Slider from "./islider.vue"
import Welfare from "./welfare.vue"
import Service from "./service.vue"

export default {
    components: {
        Heador,
        Slider,
        Footor,
        Navbor,
        Welfare,
        Service
    }
}
</script>
