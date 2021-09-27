<template>

 <div class="altura-responsive" style="background-color:antiquewhite;  height: 970px;">
   <Nav></Nav>
    <equipo></equipo>

    <Footer></Footer>
     </div>
    </template>

<script>
import Equipo from '../components/inicio/Equipo.vue'
import Footer from '@/components/Footer.vue'
import Nav from '@/components/inicio/Nav.vue'

export default {
    components: { Equipo, Footer, Nav},
   
        
}
</script>

<style scoped>
  @media (max-width: 1024px) {
    .altura-responsive{
      height: 100vh !important;
    }
  }
  
  @media (max-width: 768px) {
    .altura-responsive{
      height: 140vh !important;
    }
  }

  @media (max-width: 720px) {
    .altura-responsive{
      height: 340vh !important;
    }
  }
  
  .about {
    display: flex;

  justify-content: center
  }


  .footer1 {
    position: relative !important;
    bottom: 0;
    background-color: #444343;
    top:180px;
  }


</style>