<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Acuerdo de Nivel de Servicios - ANS
    .row.bg-color6
      .col-12.px-5(data-aos="zoom-in")
        .row.justify-content-center.mb-5
          .col-12
            figure
              img(src='@/assets/curso/tema2/img1.png').m-auto
          .col-11.bg-color1
            .p-3
              p.mb-0 También conocidos como SLA, por sus siglas en inglés #[i Service Level Agreement]. Las actividades claves para la Gestión de Niveles de Servicio pueden observarse al desplegar el siguiente recurso:
        .row.justify-content-center
          .col-lg-10
            figure.mb-5(data-aos="zoom-in-up")
              img(src='@/assets/curso/tema2/img1.svg', alt="Esquema ilustrativo que enuncia las actividades propias de la gestión de los niveles de servicio." style="width: 1200px").m-auto
    p.mb-5 En la siguiente figura se describen las interacciones y funcionalidades de la gestión de niveles de servicio.
    .row.justify-content-center
      .col-lg-8
        .titulo-sexto.color-acento-contenido.mb-5
          p.mb-0 #[b Figura 5] Interacciones y funcionalidades gestión de niveles de servicio
        figure(data-aos="zoom-in")
          img(src='@/assets/curso/tema2/img2.svg', alt="Diagrama que explica las interacciones y funcionalidades de la gestión de los niveles de servicio." style="width: 800px").m-auto 

</template>

<script>
export default {
  name: 'Tema2',
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
