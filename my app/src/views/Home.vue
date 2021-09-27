<template>

  <div>

    <Nav></Nav>
     
    
    <sesion></sesion>

    <!-- <v-footer class="footer"
    height="60px"
    width="1000px"
      color="#444343"
    >
     
        
                 
     
  
        <v-card-text class="py-2 white--text text-center">
          <p style="color:white"> {{ new Date().getFullYear() }} — TEN TRANSPORTES. All rights reserved</p>
        </v-card-text>
      
    </v-footer> -->
    <Footer></Footer>
    </div>
</template>

<script>
import Footer from '@/components/Footer.vue'
import Nav from '@/components/inicio/Nav.vue'
import Sesion from '../components/inicio/Sesion.vue'

export default {
    components: { Sesion, Footer, Nav},
   
        
}
</script>

<style scoped>

</style>