<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Welfare/>
        <activity/>
        <Service/>
        <Footor/>
        <Navbar/>
    </div>
</template>

<script>
import Heador from "../public/header.vue"
import Footor from "../public/footer.vue"
import Navbar from "../public/navbar.vue"
import Slider from "./islider.vue"
import Welfare from "./welfare.vue"
import Activity from "./activity"
import Service from "./service.vue"
export default {
    components: {
        Heador,
        Slider,
        Welfare,
        Activity,
        Service,
        Footor,
        Navbar,
    },
}
</script>
