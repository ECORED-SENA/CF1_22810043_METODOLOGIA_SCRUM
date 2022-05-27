<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1  Artefactos  
      
    .bg_grad-07  
      .row.justify-content-center.align-items-center.mb-5(data-aos="fade-right")
        .col-lg.order-1.order-lg-2
          .custom_box_left 
            p.mb-4 Estos hacen referencia a los elementos que garantizan la transparencia y el registro de la información importante en el avance del proyecto de desarrollo de <i>software</i>. En otras palabras, se trata de los recursos que fortalecen la productividad y calidad en la entrega del proyecto.
            span El trabajo Scrum destaca los artefactos identificados como <i>Product backlog</i> y <i>Sprint backlog</i>, dentro de los cuales pueden identificarse otros artefactos que, por correspondencia e intercorrelación los configuran, a saber:
        .col-auto.mb-5.mb-lg-2.onTop.order-2.order-lg-1
          img(src='@/assets/curso/tema4/img1.png' alt='AvatarTop', style="width:583px; display:block; margin:1rem 0;").m-auto
      separador

      #t_4_1.titulo-segundo.color-acento-contenido.mb-4(data-aos="fade-right")
        h2 4.1.	<i>Product backlog</i>

      .row.mb-5(data-aos="fade-left")
        .co-12.col-md-7.mb-4
          p Es la lista de funcionalidades o acciones que llevan a conformar los productos por construir. Se redacta con el idioma del cliente y se construye a través de las historias de usuario. El encargado de priorizar y detallar la información es el <i>Product Owner</i> (PO); sin embargo, puede estar apoyado por el equipo de producto, <i>stakeholders</i> o del equipo Scrum y, de esta manera, se crean las prioridades como equipo.
          span Si se desea saber cuáles son las características del artefacto <i>product Backlog</i>, denominadas características de las tres C, por su denominación en inglés, lo invitamos a conocerlas:
        .col-12.col-md-5
          img(src='@/assets/curso/tema4/img2.png' alt='AvatarTop', style="width:483px; display:block; margin:1rem 0;").m-auto
        
      ImagenInfografica.color-acento-botones.col-12.col-lg-8.mb-5.center(data-aos="fade-down")
        template(v-slot:imagen)
          figure
            img(src='@/assets/curso/tema4/vec1.svg', alt='Texto que describa la imagen')

        .tarjeta.bg-amarillo-claro.p-4(x="3.7%" y="64.2%" numero="+")
            .h5.mb-2 1. <i>Card</i>
            p Redacción corta, clara y precisa en las tarjetas de cartulina.

        .tarjeta.bg-amarillo-claro.p-4(x="32.2%" y="94.5%" numero="+")
            .h5.mb-2 2. <i>Conversation</i>
            p Resultado de la conversación y negociación.
          
        .tarjeta.bg-amarillo-claro.p-4(x="96.2%" y="77%" numero="+")
            .h5.mb-2 3. <i>Confirmation</i>
            p Confirmación de los cumplimientos y terminaciones del proyecto. 
      
    p.mb-5 En relación con el producto <i>backlog</i>, están las características de un <i>backlog</i> DEEP <i>(Detailed, Emergent, Estimated, Priorized)</i>, las que se muestran a continuación:  
    
    .row.mx-0.mb-5(data-aos="fade-down")
      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.bgr_2.justify-content-center.align-items-center
              figure.justify-center
                img.img250.p-4(src='@/assets/curso/tema4/flip1.svg', alt='imagen 1-2')
            .tarjeta-flip__contenido.bgr_3.p-4.justify-content-center.align-items-center
              p.text-left.text-white <b>1 Detallado</b> <br><br/> Las historias de usuario deben ser definidas, entendibles y apropiadas. 

      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.bgr_2.align-items-center
              figure.justify-center
                img.img250.p-4(src='@/assets/curso/tema4/flip2.svg', alt='imagen 1-2')
            .tarjeta-flip__contenido.bgr_3.p-4.justify-content-center.align-items-center
              p.text-left.text-white <b>2 Emergente</b> <br><br/> Se debe tener en cuenta la dinámica de poder cambiar en cualquier momento; adaptable.

      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.bgr_2.align-items-center
              figure.justify-center
                img.img250.p-4(src='@/assets/curso/tema4/flip3.svg', alt='imagen 1-2')
            .tarjeta-flip__contenido.bgr_3.p-4.justify-content-center.align-items-center
              p.text-left.text-white <b>3 Estimado</b> <br><br/> Hace referencia a la valoración de las historias de usuario; asignarles valor de estimación.
             

      .col-sm-6.col-xl-3.mb-5.mb-xl-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.bgr_2.align-items-center
              figure.justify-center
                img.img250.p-4(src='@/assets/curso/tema4/flip4.svg', alt='imagen 1-2')
            .tarjeta-flip__contenido.bgr_3.p-4.justify-content-center.align-items-center
              p.text-left.text-white <b>4 Priorizado</b> <br><br/> Es la necesidad de priorizar elementos para hacer entregas progresivas y adecuadas.  
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg.order-2.order-lg-1.p-md-0.esptop
        .cajon.color-primario.p-5.mb-4(style='background-color: #F0F1F5') 
          p.col-11.mb-3 La imagen del <i>iceberg</i> representa la documentación relacionada con el <i>product backlog</i>, pequeño en la parte de arriba, con las historias ya reducidas, con tamaño mediano en la parte central y más grande y desconocido por debajo con sus historias épicas. De esta manera, se podría representar el <i>product backlog</i>, algo inesperado y desconocido que se puede presentar durante el desarrollo del proyecto.
      .col-auto.mb-5.mb-lg-0.onTop.order-1.order-lg-1.p-md-0.espa
        img(src='@/assets/curso/tema4/vec2.svg' alt='AvatarTop', style="width:399px; display:block; margin:-9rem -1rem;").m-auto
    separador

    #t_4_2.titulo-segundo.color-acento-contenido.mb-5(data-aos="fade-right")
        h2 4.2.	<i>Sprint backlog</i>

    p.mb-5 Es la lista de funcionalidades que se extraen del <i>Product backlog</i> para incorporarse al sprint. El <i>Product Owner</i> (PO), asigna las prioridades en función de la velocidad del equipo (<i>team velocity</i>) para cubrir el trabajo. Si es necesario, el PO puede volver a priorizar las funcionalidades.
    
    figure.center.col-md-6.col-12.mb-5(data-aos="fade-down")
      img(src='@/assets/curso/tema4/vec3.svg')
    br
    P.mb-5 El <i>sprint backlog</i>, contiene las funciones apropiadas para conformar las <b><i>user stories</i></b> suficientes y detalladas con miras a facilitar la construcción del trabajo; tales funciones son:

    .bg_grad-08
      .tarjeta.col-md-12.col-12.pos12.gris.mb-5(data-aos="fade-down")
          SlyderA(tipo="b")
            .row.fondo-slyder_3
              .col-lg-7.align-items-center
                h5.aling-1 <i>Graphs</i>
                  p.mt-3 Se propone un gráfico como herramienta para lograr visualizar un proyecto, llamado <i>burndown</i> y se compone de dos vistas: la cantidad de trabajo que queda por hacer (eje Y) en un día determinado desde que se empezó a trabajar (eje X) y hasta que se complete el trabajo. Es responsable el PO, puesto que le permite ver la evolución del proyecto y realizar ajustes en los <i>sprint review</i>.
              .col-lg-5.col-10.center
                figure
                  img(src='@/assets/curso/tema4/1.png', alt='AvatarTop', style="height:auto; width:auto; display:block; margin: 2rem;").m-auto
              
            .row.fondo-slyder_3
              .col-lg-7.align-items-center
                h5.aling-1 <i>Sprint burn-down</i>
                  p.mt-3 Especifica la evolución del <i>sprint</i>. Se hace responsable el <i>scrum master</i>, es actualizado siempre por la consulta del <i>scrum board</i>, en la cual se conoce la evolución del <i>sprint</i>. El gráfico representa la métrica de previsión para la valoración en horas de las tareas y la evolución real que identifica el consumo de horas en cada tarea.
              .col-lg-5.col-10.center
                figure
                  img(src='@/assets/curso/tema4/2.png', alt='AvatarTop', style="height:auto; width:auto; display:block; margin:auto 2rem;").m-auto
              
            .row.fondo-slyder_3
              .col-lg-7.align-items-center
                h5.aling-1 <i>Impediments Backlog</i> (IB)
                  p.mt-3 Es el listado de problemas que se registran para que el <i>scrum master</i> logre soluciones. Podrían llegar a catalogarse como de difícil solución para el equipo.
              .col-lg-5.col-10.center
                figure
                  img(src='@/assets/curso/tema4/3.png', alt='AvatarTop', style="height:auto; width:auto; display:block; margin:auto 2rem;").m-auto
              
            .row.fondo-slyder_3
              .col-lg-7.align-items-center
                h5.aling-1 <i>Incident backlog</i>
                  p.mt-3 Lista de problemas referenciados a un <i>sprint</i>. Registra problemas que sí tienen solución y se logran corregir.
                
              .col-lg-5.col-10.center
                figure
                  img(src='@/assets/curso/tema4/4.png', alt='AvatarTop', style="height:auto; width:auto; display:block; margin:auto 2rem;").m-auto

            .row.fondo-slyder_3
              .col-lg-7.align-items-center
                h5.aling-1 <i>Parking backlog</i>
                  p.mt-3 Es la lista de tareas atascadas en un <i>sprint</i>, al ser detectado un problema que impide acabarlas. El <i>parking backlog</i>, tiene que quedar vacío al finalizar un <i>sprint</i>.
                
              .col-lg-5.col-10.center
                figure
                  img(src='@/assets/curso/tema4/5.png', alt='AvatarTop', style="height:auto; width:auto; display:block; margin:auto 2rem;").m-auto

            .row.fondo-slyder_3
              .col-lg-7.align-items-center
                h5.aling-1 <i>Scrum board</i>
                  p.mt-3 Es la herramienta visual del estado del <i>sprint</i> para el <i>scrum team</i>. Demuestra la situación real del <i>sprint</i>. 
                
              .col-lg-5.col-10.center
                figure
                  img(src='@/assets/curso/tema4/6.png', alt='AvatarTop', style="height:auto; width:auto; display:block; margin:auto 2rem;").m-auto

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
