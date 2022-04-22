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

    #t_4_1.titulo-segundo.color-acento-contenido.mb-4
      h2 4.1.	<i>Product backlog</i>

    .row.mb-5
      .co-12.col-md-7
        p Es la lista de funcionalidades o acciones que llevan a conformar los productos por construir. Se redacta con el idioma del cliente y se construye a través de las historias de usuario. El encargado de priorizar y detallar la información es el <i>Product Owner</i> (PO); sin embargo, puede estar apoyado por el equipo de producto, <i>stakeholders</i> o del equipo Scrum y, de esta manera, se crean las prioridades como equipo.
        span Si se desea saber cuáles son las características del artefacto <i>product Backlog</i>, denominadas características de las tres C, por su denominación en inglés, se invitamos a conocerlas:
      .col-12.col-md-5
        img(src='@/assets/curso/tema4/img2.png' alt='AvatarTop', style="width:483px; display:block; margin:1rem 0;").m-auto
    br    
    ImagenInfografica.color-acento-botones.col-12.col-lg-8.mb-5.center
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema4/vec1.svg', alt='Texto que describa la imagen')

      .tarjeta.color-acento-contenido.p-3(x="3.7%" y="64.2%" numero="+")
          .h5.mb-2 1. Card
          p Redacción corta, clara y precisa en las tarjetas de cartulina.

      .tarjeta.color-acento-contenido.p-3(x="32.2%" y="94.5%" numero="+")
          .h5.mb-2 2. Conversation
          p Resultado de la conversación y negociación.
      
      .tarjeta.color-acento-contenido.p-3(x="96.2%" y="77%" numero="+")
          .h5.mb-2 3. Confirmation
          p Confirmación de los cumplimientos y terminaciones del proyecto. 
      
    p.mb-5 En relación con el producto backlog, están las características de un <i>backlog</i> DEEP <i>(Detailed, Emergent, Estimated, Priorized)</i>, las que se muestran a continuación:  
    br
    .row.mx-0.mb-5
      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.bgr_2.align-items-center
              figure.justify-center
                img.img250.p-3(src='@/assets/curso/tema4/flip1.svg', alt='imagen 1-2')
            .tarjeta-flip__contenido.bgr_3.p-4.p-xl-5
              h3.text-center.text-white 1 Detallado
              p.text-center.text-white.mt-3 Las historias de usuario deben ser definidas, entendibles y apropiadas. 

      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.bgr_2.align-items-center
              figure.justify-center
                img.img250.p-3(src='@/assets/curso/tema4/flip2.svg', alt='imagen 1-2')
            .tarjeta-flip__contenido.bgr_3.p-4.p-xl-5
              h3.text-center.text-white  2 Emergente
              p.text-center.text-white.mt-5 Se debe tener en cuenta la dinámica de poder cambiar en cualquier momento; adaptable.

      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.bgr_2.align-items-center
              figure.justify-center
                img.img250.p-3(src='@/assets/curso/tema4/flip3.svg', alt='imagen 1-2')
            .tarjeta-flip__contenido.bgr_3.p-4.p-xl-5
              h3.text-center.text-white 3 Estimado
              p.text-center.text-white.mt-5 Hace referencia a la valoración de las historias de usuario; asignarles valor de estimación. 

      .col-sm-6.col-xl-3.mb-5.mb-xl-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.bgr_2.align-items-center
              figure.justify-center
                img.img250.p-3(src='@/assets/curso/tema4/flip4.svg', alt='imagen 1-2')
            .tarjeta-flip__contenido.bgr_3.p-4.p-xl-5
              h3.text-center.text-white 4 Priorizado
              p.text-center.text-white.mt-5 Es la necesidad de priorizar elementos para hacer entregas progresivas y adecuadas.  
    br
    .row.justify-content-center.align-items-center.mb-5
      .col-lg.order-2.order-lg-1
        .cajon.color-primario.p-5.mb-4.col-12(style='background-color: #F0F1F5') 
          p.mb-3 La imagen del iceberg representa la documentación relacionada con el product backlog, pequeño en la parte de arriba, con las historias ya reducidas, con tamaño mediano en la parte central y más grande y desconocido por debajo con sus historias épicas. De esta manera, se podría representar el product backlog, algo inesperado y desconocido que se puede presentar durante el desarrollo del proyecto.
      .col-auto.mb-5.mb-lg-0.onTop.order-1.order-lg-1
        img(src='@/assets/curso/tema4/vec2.svg' alt='AvatarTop', style="width:430px; display:block; margin:-6rem -1rem;").m-auto
    separador

    #t_4_2.titulo-segundo.color-acento-contenido.mb-5
        h2 4.2.	<i>Sprint backlog</i>

    p.mb-5 Es la lista de funcionalidades que se extraen del Product backlog para incorporarse al sprint. El Product Owner (PO), asigna las prioridades en función de la velocidad del equipo (team velocity) para cubrir el trabajo. Si es necesario, el PO puede volver a priorizar las funcionalidades.
    
    figure.center.col-md-6.col-12.mb-5
      img(src='@/assets/curso/tema4/vec3.svg')

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
