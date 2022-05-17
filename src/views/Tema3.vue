<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Roles 

    .bg_grad-06  
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-lg-6.order-1.order-lg-2
        .custom_box_left 
          p.mb-4 Como en cualquier proyecto o equipo de trabajo, los roles son aquellas funciones específicas desarrolladas por personas o equipos. En la metodología Scrum, estos ayudan a determinar las responsabilidades del proyecto, garantizando la información clara, la construcción adecuada y la comunicación permanente.
      .col-auto.mb-5.mb-lg-1.onTop.order-2.order-lg-1
        img(src='@/assets/curso/tema3/1.png' alt='AvatarTop', style="width:334px; display:block; margin:1rem 0;").m-auto
      
    p.mb-5.text-center Los roles destacados en Scrum son:

    .row.mb-4(data-aos="fade-down")
      .col-md-4.col-lg.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/tema3/icon1.svg' alt='AvatarTop' style="width: 100px")
          .tarjeta.bg-secundario
            p.text-center.m-4 <i><b>Product owner</b></i> es el dueño del proyecto.

      .col-md-4.col-lg.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/tema3/icon2.svg' alt='AvatarTop' style="width: 100px")
          .tarjeta.bg-color-primario
            p.text-center.m-4 <i><b>Scrum master</b></i> es el mentor, enlace; reporta y propone.

      .col-md-4.col-lg.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/tema3/icon3.svg' alt='AvatarTop' style="width: 100px")
          .tarjeta.bg-secundario
            p.text-center.m-4 <i><b>Development team</b></i> es el equipo de trabajo.

      .col-md-4.col-lg.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/tema3/icon4.svg' alt='AvatarTop' style="width: 100px")
          .tarjeta.bg-color-primario
            p.text-center.m-4 <i><b>Stakeholders</b></i> los usuarios clave.
            
    p.mb-4 A continuación, se detallan las especificidades de cada rol dentro de la metodología Scrum; se deben identificar las características, particularidades y generalidades de cada uno y su correlación con los demás roles:
    
    figure.mb-5(data-aos="fade-down")
      .video
        iframe(width="942" height="530" src="https://www.youtube.com/embed/9MaFAIVuGVY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      
    .row
      .col-md-12
        a.picture.indicador__container(@click="modal1 = true")
          img(src='@/assets/curso/tema3/importante.svg', alt='Ubicación de mercancía', style="width: 263px").center
        .col
            a.lnk(@click="modal1 = true") 
        ModalA(:abrir-modal.sync="modal1")
          .row.align-items-center
            .col-md-6.mb-4.mb-md-0
              p La suma de todos los roles, es lo que se conoce como Equipo Scrum.
            
            .col-md-6
              figure
                img(src='@/assets/curso/tema3/vec2.svg', alt='Texto que describa la imagen')
</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    modal1: false,
    indicadorTarjetaFlip: true,
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
