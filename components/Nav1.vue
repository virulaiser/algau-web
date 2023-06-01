<template>
  <div>
   <b-navbar toggleable="lg" type="dark"    class="colorFondo">
     <b-nav>
       <b-img src="logo.png" class="rounded img-thumbnail logo" alt="foto logo"></b-img>
    </b-nav>
    <b-nav>
      <template #button-content>
            <em>ALGAU</em>
      </template>
    </b-nav>


    <b-navbar-toggle target="nav-collapse">
    </b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
     <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-item-dropdown  right>
          <template #button-content>
            <em>Directiva</em>
          </template>

        <b-dropdown-item >
          <li><nuxt-link class="dropdown-item" to="/directiva">Directiva</nuxt-link></li></b-dropdown-item>
        <b-dropdown-item>
          <li><nuxt-link class="dropdown-item " to="/">Volver</nuxt-link></li></b-dropdown-item>
          </b-nav-item-dropdown>

      <b-nav-item-dropdown right>
          <!-- Using 'button-content' slot -->
          <template #button-content>
            <em>Carrera</em>
          </template>
        <b-dropdown-item> 
          <li><nuxt-link class="dropdown-item" to="/misvis">Misión/Visión</nuxt-link></li></b-dropdown-item>
        <b-dropdown-item> 
          <li><nuxt-link class="dropdown-item" to="/sabemos">Competencias</nuxt-link></li></b-dropdown-item>
        <b-dropdown-item>
          <li><nuxt-link class="dropdown-item" to="/carrera">Carrera</nuxt-link></li></b-dropdown-item>
        <b-dropdown-item> 
          <li><nuxt-link class="dropdown-item " to="/">Volver</nuxt-link></li></b-dropdown-item> 
      </b-nav-item-dropdown>

      <b-nav-item-dropdown  right>
          <template #button-content>
             <em>Actividades</em>
          </template>

          <b-dropdown-item >
            <li><nuxt-link class="dropdown-item" to="/charlas">Actividades</nuxt-link></li></b-dropdown-item>
          <b-dropdown-item> 
            <li><nuxt-link class="dropdown-item " to="/">Volver</nuxt-link></li></b-dropdown-item>
      </b-nav-item-dropdown>

      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
      
        <hr class="border border-warning border-3 opacity-50">
        <b-container fluid  class=" font-weight-bold text-center"> <p class="tam">Asociación de Licenciados en Gestión Agropecuaria del Uruguay </p></b-container>
 
    <hr class="border border-warning border-3 opacity-75">
</div>
</template>

<script>
export default {

}
</script>

<style>
.tam{font-size:0.7rem;}
</style>