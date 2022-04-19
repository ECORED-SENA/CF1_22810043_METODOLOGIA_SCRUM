<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Roles 

    .row.p-4.mb-5.fondo-8.align-items-center.justify-content-center
      .col-lg-4
        figure
          img(src='@/assets/curso/tema1/vec4.svg' alt='' style="width:293px; display:block; margin:1rem 0;")
      .col-lg-8
        p.mb-4 La idea de las premisas en Scrum es que la satisfacción del producto, no sea solo parte del cliente, sino que también debe ser para cada uno de los integrantes del equipo ejecutor. 
        span Como parte de la metodología, las premisas favorecen la comprensión conceptual de la misma y dan soporte argumental a su propuesta; ellas están directamente relacionadas con los valores Scrum, y son las máximas orientaciones para la efectividad de la aplicación de esta metodología.
      
    p.mb-4.text-center Los roles destacados en Scrum son:

    .row.mb-4
      .col-md-4.col-lg.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img_1.svg' alt='AvatarTop' style="width: 90px")
          .tarjeta.bg-secundario
            p.text-center.m-3 <b>Product owner</b> es el dueño del proyecto.

      .col-md-4.col-lg.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img_2.svg' alt='AvatarTop' style="width: 90px")
          .tarjeta.bg-color-primario
            p.text-center.m-3 <b>Scrum master</b> es el mentor, enlace; reporta y propone.

      .col-md-4.col-lg.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img_3.svg' alt='AvatarTop' style="width: 90px")
          .tarjeta.bg-secundario
            p.text-center.m-3 <b>Development team</b> es el equipo de trabajo.

      .col-md-4.col-lg.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img_3.svg' alt='AvatarTop' style="width: 90px")
          .tarjeta.bg-secundario
            p.text-center.m-3 <b>Stakeholders</b> los usuarios clave.
            
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
