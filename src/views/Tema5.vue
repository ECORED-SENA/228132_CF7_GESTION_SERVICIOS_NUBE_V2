<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5.bg12
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Planes de mantenimiento 
    .row.bg1.align-items-center.py-4
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center

          .row.align-items-center.justify-content-center
            .col-lg-5.col-md-8.mb-4.mb-lg-0(data-aos="fade-right")
              img(src="@/assets/curso/temas/27.png")
            .col-lg-7.mb-4.mb-lg-0(data-aos="fade-left")
              .bg2.mb-4.p-3.mnl-22
                p.mb-0 Las interrupciones del servicio pueden ser causadas además por labores de mantenimiento o actualización. Estas interrupciones programadas afectan la disponibilidad del servicio y por lo tanto deben ser planificadas para minimizar el impacto. Se deben aprovechar franjas horarias de inactividad para realizar las tareas que implican la degradación o interrupción del servicio.
              .row.align-items-center
                .col-1.up
                  img(src="@/assets/curso/temas/26.svg")
                .col-11.up
                  p.mb-0 Para ejecutar un mantenimiento es necesario realizar las siguientes actividades:       

    .row.justify-content-center.align-items-center.my-5           
      .col-lg-7
        .titulo-sexto.color-acento-contenido
          h5 Figura 6 
          span Actividades de Mantenimiento
        img.img-a.img-t(src="@/assets/curso/temas/29.svg", alt="Esquema gráfico que enuncia las actividades por ejecutar en el proceso de mantenimiento.")
</template>

<script>
export default {
  name: 'Tema5',
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
