<template>
    <div>
        <Heador/>
        <Slider/>
        <Welfare/>
        <Service/>
        <Footer/>
        <Navbar/>
    </div>
</template>

<script>
import Heador from '../public/header.vue'
import Footer from '../public/footer.vue'
import Navbar from '../public/navbar.vue'
import Slider from './islider.vue'
import Service from './service.vue'
import Welfare from './welfare.vue'
export default {
  components:{
    Heador,
    Footer,
    Navbar,
    Slider,
    Service,
    Welfare
  }
}
</script>