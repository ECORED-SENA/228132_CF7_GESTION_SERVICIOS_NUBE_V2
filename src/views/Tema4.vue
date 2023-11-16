<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido.mb-0
      .titulo-principal__numero
        span 4
      h1 Mejor práctica: mesa de ayuda

    .row.bg10.align-items-center.py-4
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center      
          .row.align-items-center.justify-content-center
            .col-lg-8
              .row.align-items-center.mb-4
                .col-1
                  img(src="@/assets/curso/tema4/img2.svg")
                .col-11
                  p.mb-0 La mesa de servicio es el punto de contacto de toda la organización TI con clientes y usuarios, es por lo tanto imprescindible que:
              .row.justify-content-center.text-center(data-aos="fade-right")   
                .col-lg-3.col-md-4.my-3
                  .bg5.p-3.h-100
                    img.img-a.img-t.mb-4(src="@/assets/curso/tema4/1.svg")
                    p.mb-0 Sea fácilmente accesible.
                .col-lg-3.col-md-4.my-3
                  .bg5.p-3.h-100
                    img.img-a.img-t.mb-4(src="@/assets/curso/tema4/2.svg")
                    p.mb-0 Ofrezca un servicio de calidad consistente y homogénea.
                .col-lg-3.col-md-4.my-3
                  .bg5.p-3.h-100
                    img.img-a.img-t.mb-4(src="@/assets/curso/tema4/3.svg")
                    p.mb-0  Mantenga puntualmente informados a los usuarios y lleve un registro de toda la interacción con los mismos.
                .col-lg-3.col-md-4.my-3
                  .bg5.p-3.h-100
                    img.img-a.img-t.mb-4(src="@/assets/curso/tema4/4.svg")
                    p.mb-0 Sirva de soporte al negocio.
            .col-lg-4
              figure.mb-4.mb-lg-0
                img(src='@/assets/curso/tema4/img1.png' style="width: 450px").m-auto
    p.my-5 En la siguiente imagen, se puede apreciar la estructura de la mesa que ofrece servicios virtuales, y la relación y dinámica que se ejerce entre sí.
    .row.justify-content-center.mb-5
      .col-lg-8
        .titulo-sexto.color-acento-contenido.mb-5
          p.mb-0 #[b Figura 6]. Estructura mesa de servicios virtual
        figure(data-aos="zoom-in-up")
          img(src='@/assets/curso/tema4/img4.svg',alt="gráficamente, la estructura y funcionamiento de la mesa virtual de servicios.").m-auto
          
    p En relación con la estructura lógica, los integrantes del centro de servicios, deben:
    

    .row.justify-content-center.align-items-center    
      .col-lg-7.my-3
        AcordionA(tipo="b" clase-tarjeta="tarjeta bg8") 
          div(titulo="Conocer") Todos los protocolos de interacción con el cliente: guiones, checklists, etc.
          div(titulo="Disponer") Herramientas de software que les permitan llevar un registro de la interacción con los usuarios.
          div(titulo="Saber") Cuándo se debe realizar un escalado a instancias superiores o entrar en discusiones sobre cumplimiento de los ANS o Acuerdos de Nivel de Servicio, también conocidos como SLA, por sus siglas en ingles Service Level Agreement.
          div(titulo="Tener") Rápido acceso a las bases de conocimiento para ofrecer un mejor servicio a los usuarios.
          div(titulo="Recibir") Formación sobre los productos y servicios de la empresa.
      .col-lg-5.my-3
        img.img-t.img-a(data-aos="zoom-in")(src='@/assets/curso/temas/25.png', alt='')      

    p Dependiendo de las necesidades de servicio (locales, globales, 24/7), se debe de optar por una estructura diferente para el centro de servicios. Existen tres formatos básicos:

    .row.justify-content-center(data-aos="fade-right")   
      .col-lg-4.my-3
        .bg11.p-3.h-100.brad
          img.img-t.mb-4(src="@/assets/curso/tema4/5.svg")
          h4 Centralizado 
          p.mb-0 En este caso todo el contacto con los usuarios se canaliza a través de una sola estructura central.
      .col-lg-4.my-3
        .bg11.p-3.h-100.brad
          img.img-t.mb-4(src="@/assets/curso/tema4/6.svg")
          h4 Distribuido 
          p.mb-0 Es la estructura tradicional cuando se trata de empresas que ofrecen servicios en diferentes emplazamientos geográficos (ya sean ciudades, países o continentes).
      .col-lg-4.my-3
        .bg11.p-3.h-100.brad
          img.img-t.mb-4(src="@/assets/curso/tema4/7.svg")
          h4 Virtual 
          p.mb-0 En la actualidad y gracias a las rápidas redes de comunicación existentes, la situación geográfica de los centros de servicios puede llegar a ser irrelevante.                   
</template>

<script>
export default {
  name: 'Tema4',
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
