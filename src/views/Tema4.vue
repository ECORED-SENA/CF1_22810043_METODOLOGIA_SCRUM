<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1  Artefactos  

    
    .row.p-4.mb-5.fondo-8.align-items-center.justify-content-center
      .col-lg-6
        figure
          img(src='@/assets/curso/tema4/img1.png' alt='')
      .col-lg-6
        p.mb-4 La idea de las premisas en Scrum es que la satisfacción del producto, no sea solo parte del cliente, sino que también debe ser para cada uno de los integrantes del equipo ejecutor. 
        span Como parte de la metodología, las premisas favorecen la comprensión conceptual de la misma y dan soporte argumental a su propuesta; ellas están directamente relacionadas con los valores Scrum, y son las máximas orientaciones para la efectividad de la aplicación de esta metodología.
    separador
      

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
