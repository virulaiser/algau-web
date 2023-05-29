<template>
<div>
    <b-nav fluid  class="colorFondo ">
    
         <b-nav>
          <b-img src="logo.png" class="rounded img-thumbnail logo" alt="foto logo"></b-img>
         </b-nav>

         <b-nav-item  >
            <b-nav-dropdown  text="Actividades"   id="dropdown"   type ="button"  class=" btn bg-secondary mar" >
              <b-dropdown-item> <li><nuxt-link class="dropdown-item " to="/">Volver</nuxt-link></li></b-dropdown-item>
            </b-nav-dropdown>
          </b-nav-item>


    <b-nav-item >
            <b-nav-dropdown  text="Administración"  id="dropdown-1"   type ="button"  class=" btn bg-secondary mar" >
            <b-dropdown-item ><li><nuxt-link class="dropdown-item" to="/directiva">Directiva</nuxt-link></li></b-dropdown-item>
            <b-dropdown-item> <li><nuxt-link class="dropdown-item " to="/">Volver</nuxt-link></li></b-dropdown-item>
     </b-nav-dropdown>
      

    </b-nav-item>

    <b-nav-item  >
      <b-nav-dropdown  rounded="sm"  text="Carrera"   id="dropdown-2"   type ="button"  class=" btn bg-secondary mar" >
      
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
  width: 40px;
  margin:3 px;
}

.btn{
    color:white;
    background-color: rgb(160, 173, 40); 
    margin: 1px;
    padding:1px;
   
   }

   a{padding:1px}

.fle{display:flex;}



span{
color:White;
 margin: 1px;
    padding:1px;
    font-size:0.5rem;
}
    dropdown{padding:1px}

    b-nav-dropdown{padding:1px}
  .mar{margin:2px;
        padding:2px}

</style>