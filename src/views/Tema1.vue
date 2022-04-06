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
        .cajon.color-primario.bg-3-claro.p-4.mb-4.col-11.esp2
          p La Petición es demandar, pedir o solicitar algo que se requiere o se necesita, la petición se eleva ante una persona sea natural o jurídica, el proceso de petición hace referencia a dudas que se tiene de un procedimiento en alguna de sus etapas de ejecución, un cuestionamiento sobre algún paso o proceso no entendido. 
          


        p Ahora se presentan algunos aspectos clave de la definición y configuración de la metodología Scrum; aquí es importante hacer uso de la libreta personal de apuntes para registrar datos importantes.
      .col.col-12.col-lg-4.position-relative
        picture
          img(src='@/assets/curso/tema1/vec1.svg', alt='Ubicación de mercancía', class='img-fluid')

    

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
