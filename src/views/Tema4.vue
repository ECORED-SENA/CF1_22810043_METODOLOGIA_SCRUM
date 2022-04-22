<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1  Artefactos  


      
    .row.justify-content-center.align-items-center.mb-5
      .col-lg.order-1.order-lg-2
        .custom_box_left 
          p.mb-4 Estos hacen referencia a los elementos que garantizan la transparencia y el registro de la información importante en el avance del proyecto de desarrollo de software. En otras palabras, se trata de los recursos que fortalecen la productividad y calidad en la entrega del proyecto.
          span El trabajo Scrum destaca los artefactos identificados como Product backlog y Sprint backlog, dentro de los cuales pueden identificarse otros artefactos que, por correspondencia e intercorrelación los configuran, a saber:
      .col-auto.mb-5.mb-lg-2.onTop.order-2.order-lg-1
        img(src='@/assets/curso/tema4/img1.png' alt='AvatarTop', style="width:583px; display:block; margin:1rem 0;").m-auto
    separador

    #t_1_2.titulo-segundo.color-acento-contenido.mb-4
      h2 4.1.	<i>Product backlog</i>
          

</template>

<script>
export default {
  name: 'Tema3',
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
