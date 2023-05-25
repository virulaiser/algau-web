<template>
<div>
    <b-nav fluid class="colorFondo fle">
    
         <b-nav>
          <b-img src="logo.png" class="rounded img-thumbnail logo ms-2" alt="foto logo"></b-img>
         </b-nav>

         <b-nav-item  >
            <b-nav-dropdown  text="Actividades"   id="dropdown"   type ="button"  class=" btn bg-secondary" >
              <b-dropdown-item> <li><nuxt-link class="dropdown-item " to="/">Volver</nuxt-link></li></b-dropdown-item>
            </b-nav-dropdown>
          </b-nav-item>


    <b-nav-item >
            <b-nav-dropdown  text="Administración"  id="dropdown-1"   type ="button"  class=" btn bg-secondary" >
            <b-dropdown-item ><li><nuxt-link class="dropdown-item" to="/directiva">Directiva</nuxt-link></li></b-dropdown-item>
            <b-dropdown-item> <li><nuxt-link class="dropdown-item " to="/">Volver</nuxt-link></li></b-dropdown-item>
     </b-nav-dropdown>
      

    </b-nav-item>

    <b-nav-item  >
      <b-nav-dropdown  rounded="sm"  text="Carrera"   id="dropdown-2"   type ="button"  class=" btn bg-secondary" >
      
      <b-dropdown-item> <li><nuxt-link class="dropdown-item" to="/misvis">Misión/Visión</nuxt-link></li></b-dropdown-item>
      <b-dropdown-item> <li><nuxt-link class="dropdown-item" to="/sabemos">Competencias</nuxt-link></li></b-dropdown-item>
      <b-dropdown-item><li><nuxt-link class="dropdown-item" to="/carrera">Carrera</nuxt-link></li></b-dropdown-item>
      <b-dropdown-item> <li><nuxt-link class="dropdown-item " to="/">Volver</nuxt-link></li></b-dropdown-item>
     </b-nav-dropdown>
    </b-nav-item>

  </b-nav>
   
    <div class="m-2 text-center" >
      <hr class="border border-warning border-3 opacity-50">
      <h2 class="h2">Asociación de Licenciados en Gestión Agropecuaria del Uruguay </h2>
    </div>
    <hr class="border border-warning border-3 opacity-75">

</div>
</template>

<script>
export default {
  data(){},
  name:'nav'

}
</script>

<style>
.logo{
  width: 80px;
  margin:10px;
}

.btn{margin-top: 10px;
    color:white;
    background-color: rgb(160, 173, 40); 
   
    font-size:1.5rem}

.fle{display:flex;}

.h2{font-size: 2rem;
  font-family: Roboto ;
 
}


span{font-size:1.8rem;
color:White}
</style>