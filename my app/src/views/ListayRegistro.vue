<template>
<div style="background-color:antiquewhite;  height: 1200px;">
 <v-toolbar id="menu-fixed"
     
      
    >
      <v-img
  
  max-height="60"
  max-width="60"
  src="../assets/logo1.png"
></v-img>
  
      
  
      <h2 style="color:rgba(4, 73, 112)"></h2>
  
      <v-spacer></v-spacer>
  
      <v-toolbar-items class="hidden-sm-and-down">
         <v-btn text color="rgba(4, 73, 112)">
          
         <a class="nav-link" href="/Administrador">Administrador</a>
        </v-btn>

          <v-btn text color="rgba(4, 73, 112)">
        <a class="nav-link" href="/Listavehiculos">Vehiculos</a>
        </v-btn>
        <v-btn text color="rgba(4, 73, 112)">
          
         <a class="nav-link" href="/Preoperacional">Preoperacional</a>
        </v-btn>
  
        
  
        <v-btn text color="rgba(4, 73, 112)">
        <a class="nav-link" href="/Home">Cerrar Sesion</a>
        </v-btn>
  
       
  
       
      </v-toolbar-items>
  
      
    </v-toolbar>
    <listaconductores></listaconductores>
    <registrousuario></registrousuario>

    <Footer></Footer>
  
</div>
</template>

<script>
import Listaconductores from '../components/Listaconductores.vue'
import Registrousuario from '../components/Registrousuario.vue'
import Footer from '@/components/Footer.vue'


export default {
    components: { Listaconductores, Registrousuario, Footer},
   
        
}
</script>

<style scoped>
#menu-fixed {
	position:fixed;
	z-index:1000;
	top:0;
	/*max-width:1000px;*/
	left:0;
	width:800%;
  
	box-shadow:0px 4px 3px rgb(4, 73, 112);
}

.nav-link{
  color: #F25116  ;
  padding-left: 0px;
  padding-right: 0px;
}

.nav-link:hover{
 color: rgb(4, 73, 112);
}

a {
  font: Arial;
  font-style:inherit;
  color:rgb(4, 73, 112)
}

.footer1{
   position: relative !important; 
   bottom: 0;
   
   width: 1400px !important;
   top:174px;
 
}

</style>


