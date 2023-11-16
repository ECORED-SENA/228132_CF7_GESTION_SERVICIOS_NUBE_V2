<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5 Aquí finaliza el estudio de este componente formativo. Enseguida, se muestra un esquema que recoge lo más importante de los conceptos y temas vistos. Analícelo y desarrolle su propia síntesis de lo estudiado. #[b.tb ¡Adelante!]

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="Esquema general de los contenidos de este componente formativo. Tema principal: La gestión de los servicios en la nube. Temas integradores: Plan de servicios, Acuerdos de nivel de servicios, Acceso a servicios, Mesa de ayuda, Planes de mantenimiento.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
