<template>
    <div>
        <Heador/>
        <Slide/>
        <Ada/>
        <Money/>
        <Adb/>
        <Finance/>
        <Adc/>
        <Footer/>
        <Navbar/>
    </div>
</template>

<script>
import Heador from '../public/header.vue'
import Slide  from './mslider.vue'
import Ada from './ada.vue'
import Footer from '../public/footer.vue'
import Navbar from '../public/navbar.vue'
import Money from './money.vue'
import Adb from './adb.vue'
import Finance from './finance.vue'
import Adc from './adc.vue'
export default {
  components:{
    Heador,
    Slide,
    Ada,
    Footer,
    Navbar,
    Money,
    Adb,
    Finance,
    Adc
  }
}
</script>