<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.bg-color2(data-aos="zoom-in")
      .col-12.px-5
        .row.justify-content-center
          .col-12.d-block.d-lg-none
            figure
              img(src='@/assets/curso/intro/img2.png').m-auto
          .col-12.d-none.d-lg-block
            figure
              img(src='@/assets/curso/intro/img1.png').m-auto
          .col-11.bg-color1
            .p-3
              p.mb-0 Le damos la bienvenida al componente formativo “Gestión de los servicios en la nube”. Para comenzar el recorrido por el mismo, visite el recurso didáctico que se muestra a continuación:
        figure.mb-5
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/di6Sz8o85DI?si=80wfEL4DHb1GCoEo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
          figcaption Video. Gestión de los servicios en la nube: introducción

        .bloque-texto-a.color-secundario.p-4.p-md-4(data-aos="zoom-in")
          .row.m-0.align-items-center.justify-content-between
            .col-lg-2.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/intro/img1.svg' style="width: 100px").m-auto
            .col-lg-10
              .bloque-texto-a__texto.p-4
                p Para este componente es importante adoptar buenas prácticas para la gestión de los servicios en la nube, en este caso vamos a utilizar los puntos 2.3, 2.3.1, 2.3.2, 2.3.3, 2.4, 2.5, 2.6 y 2.8 de la #[span.txt-deco1 G.ST.01 Guía del dominio de servicios tecnológicos la cual nos sugiere que los servicios tecnológicos hacen parte del dominio del marco de referencia de arquitectura de TI] que establece estándares y lineamientos para la gestión de la infraestructura tecnológica los cuales soportan los sistemas y los servicios de información, además de los servicios requeridos para su operación.    


</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
