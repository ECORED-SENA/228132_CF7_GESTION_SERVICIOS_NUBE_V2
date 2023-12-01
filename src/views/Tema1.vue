<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Plan de gestión de servicios de TI
      
    .row.bg1.align-items-center.py-4.py-lg-0
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .row.align-items-center.justify-content-center
            .col-lg-5.col-md-8.mb-4.mb-lg-0(data-aos="fade-right")
              img(src="@/assets/curso/temas/3.png")
            .col-lg-7.mb-4.mb-lg-0(data-aos="fade-left")
              .bg2.mb-4.p-3.mnl-22
                p.mb-0 La disposición de los sistemas de información requiere el establecimiento de un plan que posibilite adoptar estrategias de servicios tecnológicos. De esta forma, se puede garantizar la disponibilidad y la operación del servicio, el cual debe ser permanente y constante para sus usuarios.
              .row.align-items-center
                .col-1
                  img(src="@/assets/curso/temas/2.svg")
                .col-11
                  p.mb-0 Para el diseño del plan de gestión de servicios de TI, es importante tener en cuenta las actividades descritas en la G.ST.01 Guía del dominio de servicios tecnológicos del Ministerio de Tecnologías de la Información y las Comunicaciones (2014). Este documento permite la adopción de los elementos del dominio de los servicios tecnológicos para Colombia, en el marco de la arquitectura de TI. Por esta razón, se tomará de manera literal para su comprensión e implementación.
          .col-lg-10
            .bg3.p-3.text-center.text-white 
              p.mb-0 Las actividades en cada una de las gestiones corresponden a las descritas en la siguiente imagen, las cuales serán serán explicadas a continuación:

    .row.justify-content-center.align-items-center.my-5           
      .col-lg-5
        .titulo-sexto.color-acento-contenido
          h5 Figura 1 
          span Actividades del plan de gestión de servicios TI
        img.img-a.img-t(src="@/assets/curso/temas/4.svg", alt="Esquema sencillo que enuncia las actividades propias del plan de gestión de los servicios TI.")


    Separador 
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 1.1 Gestión de la capacidad 
    .row.bg4.align-items-center.py-4
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .row.align-items-center.justify-content-center
            .col-lg-8.mb-4.mb-lg-0(data-aos="fade-left")        
              p La gestión de la capacidad, posibilita encargarse de las TI, asegurando que la capacidad de las tecnologías de la información, cumplen los requisitos establecidos, al momento y en el futuro de la organización, y que genera un costo que puede ser asumido sin problema, tanto en la gestión de la capacidad física, como económica.
              .row.align-items-center.mb-4
                .col-1
                  img(src="@/assets/curso/temas/6.svg")
                .col-11
                  p.mb-0 Una correcta definición de los servicios de una compañía, es clave en el proceso, por esta razón debe tenerse claro cuál es la herramienta o herramientas útiles en la gestión diaria del servicio, así como los indicadores que medirán dicho servicio.  
              p Las actividades más significativas de la gestión de la capacidad, son:
            .col-lg-4.col-md-8.mb-4.mb-lg-0(data-aos="fade-right")
              img.img-a.img-t(src="@/assets/curso/temas/7.png")

          .row.justify-content-center.text-center(data-aos="fade-right")   
            .col-lg-2.col-md-4.my-3
              .bg5.p-3.h-100
                img.img-a.img-t.mb-4(src="@/assets/curso/temas/8.svg")
                h4 Desarrollo
                p.mb-0 Del plan de capacidad.
            .col-lg-2.col-md-4.my-3
              .bg5.p-3.h-100
                img.img-a.img-t.mb-4(src="@/assets/curso/temas/9.svg")
                h4 Modelado y simulación
                p.mb-0 De diferentes escenarios de capacidad.  
            .col-lg-2.col-md-4.my-3
              .bg5.p-3.h-100
                img.img-a.img-t.mb-4(src="@/assets/curso/temas/8.svg")
                h4 Monitorización
                p.mb-0 Del uso y rendimiento de la infraestructura TI.
            .col-lg-2.col-md-4.my-3
              .bg5.p-3.h-100
                img.img-a.img-t.mb-4(src="@/assets/curso/temas/9.svg")
                h4 Gestión
                p.mb-0 De la demanda. 
            .col-lg-2.col-md-4.my-3
              .bg5.p-3.h-100
                img.img-a.img-t.mb-4(src="@/assets/curso/temas/8.svg")
                h4 Creación y mantenimiento
                p.mb-0 De la base de datos de capacidad (CDB).                                             

    p.mt-5 En la siguiente figura se relacionan las actividades más significativas para la gestión de la capacidad:
    .row.justify-content-center.align-items-center.my-5           
      .col-lg-8
        .titulo-sexto.color-acento-contenido
          h5 Figura 2
          span Gestión de capacidad
        img.img-a.img-t(src="@/assets/curso/temas/4.svg", alt="Esquema sencillo que enuncia las actividades propias del plan de gestión de los servicios TI.")    

    Separador 
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 1.2 Gestión de la continuidad    

    .row(data-aos="zoom-in")
      .col-12.px-5
        .row.justify-content-center
          .col-12.d-block.d-lg-none
            figure
              img(src='@/assets/curso/temas/10.png').m-auto
          .col-12.d-none.d-lg-block
            figure
              img(src='@/assets/curso/temas/10.png').m-auto
          .col-11.bg6
            .p-3
              p.mb-0 La gestión de la continuidad se relaciona con las acciones que se realizan al interior de la organización y que permiten asegurar que todos los procesos críticos estarán disponibles para los clientes, proveedores y otras entidades que deban acceder a ellos.         

    p.text-center Las siguientes, son las actividades propias de la gestión de la continuidad:

    .row.justify-content-center.align-items-center.mb-4       
      .col-lg-5.my-3(data-aos="fade-right") 
        img.img-a.img-t.mb-4(src="@/assets/curso/temas/11.svg")

      .col-lg-7(data-aos="fade-left") 
        .row.justify-content-center
          .col-lg-6.my-3      
            .tarjeta-avatar-b.mb-4.h-100
              .tarjeta-avatar-b__img
                img.img-t(src='@/assets/curso/temas/12.svg' alt='')
              .tarjeta.bg-1.bx-sh1.j
                .p-4
                  p.mb-0 Establecer  las políticas y alcance de la ITSCM. 
          .col-lg-6.my-3      
            .tarjeta-avatar-b.mb-4.h-100
              .tarjeta-avatar-b__img
                img.img-t(src='@/assets/curso/temas/13.svg' alt='')
              .tarjeta.bg-1.bx-sh1.j
                .p-4
                  p.mb-0 Desarrollar los planes de contingencia.  
        .row.justify-content-center  
          .col-lg-6.my-3      
            .tarjeta-avatar-b.mb-4.h-100
              .tarjeta-avatar-b__img
                img.img-t(src='@/assets/curso/temas/14.svg' alt='')
              .tarjeta.bg-1.bx-sh1.j
                .p-4
                  p.mb-0 Evaluar el impacto en el negocio de una interrupción de los servicios TI. 
          .col-lg-6.my-3      
            .tarjeta-avatar-b.mb-4.h-100
              .tarjeta-avatar-b__img
                img.img-t(src='@/assets/curso/temas/15.svg' alt='')
              .tarjeta.bg-1.bx-sh1.j
                .p-4
                  p.mb-0 Poner a prueba dichos planes. 
        .row.justify-content-center   
          .col-lg-6.my-3      
            .tarjeta-avatar-b.mb-4.h-100
              .tarjeta-avatar-b__img
                img.img-t(src='@/assets/curso/temas/16.svg' alt='')
              .tarjeta.bg-1.bx-sh1.j
                .p-4
                  p.mb-0 Analizar y prever los riesgos a los que está expuesto la infraestructura TI. 
          .col-lg-6.my-3      
            .tarjeta-avatar-b.mb-4.h-100
              .tarjeta-avatar-b__img
                img.img-t(src='@/assets/curso/temas/17.svg' alt='')
              .tarjeta.bg-1.bx-sh1.j
                .p-4
                  p.mb-0 Formar al personal sobre los procedimientos necesarios para la pronta recuperación del servicio.
        .row.justify-content-center   
          .col-lg-6.my-3      
            .tarjeta-avatar-b.mb-4.h-100
              .tarjeta-avatar-b__img
                img.img-t(src='@/assets/curso/temas/18.svg' alt='')
              .tarjeta.bg-1.bx-sh1.j
                .p-4
                  p.mb-0 Establecer las estrategias de continuidad del servicio TI. 
          .col-lg-6.my-3      
            .tarjeta-avatar-b.mb-4.h-100
              .tarjeta-avatar-b__img
                img.img-t(src='@/assets/curso/temas/19.svg' alt='')
              .tarjeta.bg-1.bx-sh1.j
                .p-4
                  p.mb-0 Adoptar medidas proactivas de prevención del riesgo.                                     
        .row.justify-content-center
          .col-lg-10.my-3      
            .tarjeta-avatar-b.mb-4.h-100
              .tarjeta-avatar-b__img
                img.img-t(src='@/assets/curso/temas/20.svg' alt='')
              .tarjeta.bg-1.bx-sh1.j
                .p-4
                  p.mb-0 Revisar periódicamente los planes para adaptarlos a las necesidades reales del negocio. 

    p Estas actividades para la gestión de la calidad, se corresponden con algunos procesos de la organización, tal como se indican en la siguiente figura:

    .row.justify-content-center.align-items-center.my-5           
      .col-lg-8
        .titulo-sexto.color-acento-contenido
          h5 Figura 3 
          span Gestión de la continuidad
        img.img-a.img-t(src="@/assets/curso/temas/21.svg", alt="Esquema sencillo que enuncia las actividades propias del plan de gestión de los servicios TI.")       

    Separador 
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 1.3 Gestión de la disponibilidad 
    p Esta gestión es la encargada de asegurar que la infraestructura, así como los procesos, las herramientas y las funciones de TI, sean los adecuados para dar cumplimiento a los objetivos de disponibilidad establecidos.

    p.mb-5 Las actividades claves para la Gestión de la Disponibilidad son las siguientes: 
    .row.justify-content-center.align-items-center    
      .col-lg-7.my-3
        AcordionA(tipo="b" clase-tarjeta="tarjeta bg8") 
          div(titulo="Determinar") Cuáles son los requisitos de disponibilidad reales del negocio.
          div(titulo="Desarrollar") Un plan de disponibilidad donde se estimen las necesidades de disponibilidad futura, a corto y mediano plazo. 
          div(titulo="Mantenimiento") Del servicio en operación y recuperación del mismo en caso de fallo.
          div(titulo="Realizar") Diagnósticos periódicos sobre la disponibilidad de los sistemas y servicios. 
          div(titulo="Evaluar") La capacidad de servicio de los proveedores internos y externos. 
      .col-lg-5.my-3
        img.img-t.img-a(data-aos="zoom-in")(src='@/assets/curso/temas/22.png', alt='')         

    .row.justify-content-center.align-items-center 
      .col-lg-5.my-3
        img.img-t.img-a(data-aos="zoom-in")(src='@/assets/curso/temas/23.png', alt='')               
      .col-lg-7.my-3
        AcordionA(tipo="b" clase-tarjeta="tarjeta bg8") 
          div(titulo="Monitorizar") La disponibilidad de los servicios TI.
          div(titulo="Elaborar") Informes de seguimiento con la información recopilada sobre disponibilidad, fiabilidad, mantenibilidad y cumplimiento OLAs y UCs. 
          div(titulo="Evaluar") El impacto de las políticas de seguridad en la disponibilidad. 
          div(titulo="Asesorar") La gestión del cambio, sobre el posible impacto de un cambio en la disponibilidad. 
     

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
