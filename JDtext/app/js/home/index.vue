<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Money/>
        <Product/>
        <Insurance/>
        <!--<Novice/>
        <Borrow/>-->
        <Life/>
        <Footor/>
        <Navbar/> 
    </div>
</template>

<script>
import Heador from "../public/header.vue"
import Footor from "../public/footer.vue"
import Navbar from "../public/navbar.vue"
import Slider from "./hslider.vue"
// import Novice from "./novice.vue"
// import Borrow from "./borrow.vue"
import Money from "./money.vue"
import Product from "./product.vue"
import Insurance from "./insurance.vue"
import Life from "./life.vue"
export default {
    components: {
        Heador,
        Slider,
        // Novice,
        // Borrow,
        Money,
        Product,
        Insurance,
        Life,
        Footor,
        Navbar,
    },
}
</script>