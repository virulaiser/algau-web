<template>
<div class="m-4">
   <h1 class="ms-2">Descripción de la Carrera </h1>

<p class=""><strong>Licenciatura en Gestión Agropecuaria</strong>
    La carrera está orientada a formar profesionales capaces de participar y asesorar en el proceso de toma de decisiones implícita en la actividad agropecuaria.
    
    Las habilidades y conocimientos adquiridos, tanto en el área técnico productiva como económico financiera, le permitirán al egresado planificar, controlar y evaluar la actividad agropecuaria, orientándola a la optimización del uso de los recursos en la búsqueda de sistemas productivos sostenibles.
    
    Con conocimientos específicos de gestión empresarial podrá asesorar en la comercialización y el marketing de los productos derivados de la actividad.
    
    Su formación le permitirá desarrollar las siguientes competencias:
    
    Colaborar en la sostenibilidad de los procesos y sistemas de producción agroalimentaria.
    Utilizar sus conocimientos en el diagnóstico y solución de problemas de la producción agropecuaria, considerando los aspectos socioeconómicos y ambientales.
    Administrar, planificar, dirigir, controlar y evaluar la actividad de las empresas de producción y servicios agropecuarios.
    Asesorar en la comercialización y el marketing de los productos agroalimentarios derivados de la actividad de las empresas agropecuarias.
    Elaborar proyectos de inversión, considerando las diferentes variables que intervienen en el proceso productivo agropecuario, agroalimentario y agroindustrial.
    Gerenciar sistemas y procesos, desempeñándose en las empresas agropecuarias, los mercados y las cadenas agroindustriales.
    Duración
    4 años ( 2.400 horas / 8 semestres )
    
    Condiciones de Ingreso
    Tener terminado Bachillerato de Secundaria todas las Orientaciones, Bachilleratos Tecnológicos del CETP.
    La Facultad permite el ingreso condicional con hasta 2 materias pendientes que se deberán aprobar antes del mes de julio del año de ingreso. </p>

 <p>fuente : www.fca-ude.edu.uy/licenciatura-en-gestion-agropecuaria.php</p>
    
 <p>Plan de Estudio</p>

 <b-table  :items="dato1" class="table-success" :fields="tabla1"></b-table>  

 <b-table  :items="dato2" class="table-success"  :fields="tabla2"></b-table>  
 
 <b-table  :items="dato3" class="table-success"  :fields="tabla3"></b-table>  


 </div>
</template>

<script>
export default {
    data(){
        return {
             tabla1:['primer_semestre','segundo_semestre','tercer_semestre'],
            dato1:[ {primer_semestre: 'Anatomía y Fisiología Animal ',segundo_semestre: 'Agro Climatología',tercer_semestre:'3er Semestre'},
            {primer_semestre: ' Botánica y Fisiología Vegetal',segundo_semestre: 'Derecho de la Empresa Agraria I',tercer_semestre:'Administración I'},
            {primer_semestre: ' Computación',segundo_semestre: 'Sanidad Animal',tercer_semestre:'Derecho de la Empresa Agraria II'},
            {primer_semestre: 'Genética / Zootecnia ',segundo_semestre: 'Maquinaria Agrícola',tercer_semestre:'Economía I'},
            {primer_semestre: 'Matemática Aplicada al Agro ',segundo_semestre: 'Nutrición Animal',tercer_semestre:'Forrajeras I'},
            {primer_semestre: 'Suelos del Uruguay Suelos',segundo_semestre: 'Fertilidad y Fertilizantes',tercer_semestre:'',tercer_semestre:'Ovinos I'},
            {primer_semestre: ' ',segundo_semestre: '',tercer_semestre:'Suelos del Uruguay Suelos '}],
            
            tabla2:['cuarto_semestre','quinto_semestre','sexto_semestre'],
             dato2:[{cuarto_semestre: 'Administración II',quinto_semestre: 'Bovinos para Leche I',sexto_semestre:'Bovinos para Leche II '},
             {cuarto_semestre: 'Suinos ',quinto_semestre: 'Cereales I',sexto_semestre:'	Cereales II'},
             {cuarto_semestre: 'Economía',quinto_semestre: 'Contabilidad I',sexto_semestre:'	Contabilidad II'},
             {cuarto_semestre: ' Forrajeras II',quinto_semestre: 'Forestación',sexto_semestre:'Bienestar Animal '},
             {cuarto_semestre: 'Ovinos II ',quinto_semestre: 'Gestión Ambiental',sexto_semestre:'Estadística'},
             {cuarto_semestre: ' Fertilidad y Fertilizantes',quinto_semestre: 'Proyecto I',sexto_semestre:'Proyecto II '},
             {cuarto_semestre: ' ',quinto_semestre: '',sexto_semestre:'	Sociología Rural '},
           ],
             tabla3:['septimo_semestre','octavo_semestre'],
             dato3:[
             {septimo_semestre: 'Administración Financiera ',octavo_semestre: 'Marketing y Agro alimentos'},
             {septimo_semestre: ' Extensión Rural',octavo_semestre: 'Cereales II'},
             {septimo_semestre: 'Políticas Agropecuarias ',octavo_semestre: 'Cadenas Agroindustriales'},
             {septimo_semestre: ' Programa de Asesoramiento a la Gestión I',octavo_semestre: 'Programa de Asesoramiento a la Gestión II'},
             {septimo_semestre: ' Taller de Informática I  ',octavo_semestre: 'Taller de Informática II'},
             {septimo_semestre: ' Taller de Proyecto I',octavo_semestre: 'Taller de Proyecto II'},
             {septimo_semestre: ' ',octavo_semestre: 'Proyecto Final'},
             
             ]

            }
          

        }}
       
  
    


</script>

<style>

</style>