<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Scrum, definición y características

    .row.mb-5
      .col.col-12.col-lg-8.pt-5
        p Hablar de Scrum es referirse a una metodología de trabajo en equipo, que ayuda a delegar responsabilidades dentro de un proyecto, para lograr su ejecución y desarrollo de manera pertinente, acertada y rápida; ello, abrirá paso al logro de objetivos a corto tiempo.
        .cajon.color-secundario.bg-3-claro.p-4.mb-4.col-11.esp2
          p La Petición es demandar, pedir o solicitar algo que se requiere o se necesita, la petición se eleva ante una persona sea natural o jurídica, el proceso de petición hace referencia a dudas que se tiene de un procedimiento en alguna de sus etapas de ejecución, un cuestionamiento sobre algún paso o proceso no entendido. 
        p Ahora se presentan algunos aspectos clave de la definición y configuración de la metodología Scrum; aquí es importante hacer uso de la libreta personal de apuntes para registrar datos importantes.
      .col.col-12.col-lg-4.position-relative
        picture
          img(src='@/assets/curso/tema1/vec1.svg', alt='Ubicación de mercancía', class='img-fluid')
    br 
    .tarjeta.p-2.col-12.pos12.gris
      SlyderA(tipo="b")
        img(src='@/assets/curso/tema1/img1.svg', alt='Texto que describa la imagen')
        
        img(src='@/assets/curso/tema1/img2.svg', alt='Texto que describa la imagen')

        img(src='@/assets/curso/tema1/img3.svg', alt='Texto que describa la imagen')

        img(src='@/assets/curso/tema1/img4.svg', alt='Texto que describa la imagen')

    .row.justify-content-center.align-items-center.mt-5      
      .col-lg-10(data-aos="fade-down")
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="zoom-in")
          .bloque-texto-g__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/img1.jpg')})`}")
          .bloque-texto-g__texto.p-4
            p(data-aos="fade-down").mb-0 La metodología Scrum, por definición, es el proceso donde se aplican buenas prácticas, trabajando colaborativamente. Con ella se logra el desarrollo del proyecto por medio de fases o etapas en las que no se avanza si no se termina la fase en la que se está trabajando. 

    .row.til
      p Ahora bien, estas son los tres pilares de proceso en que se basa la metodología Scrum:

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
