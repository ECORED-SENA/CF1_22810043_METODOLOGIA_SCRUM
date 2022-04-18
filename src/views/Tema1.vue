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
    
    .tarjeta.p-2.col-12.pos12.gris.mb-5
      SlyderA(tipo="b")
        img(src='@/assets/curso/tema1/img1.svg', alt='Texto que describa la imagen')
        
        img(src='@/assets/curso/tema1/img2.svg', alt='Texto que describa la imagen')

        img(src='@/assets/curso/tema1/img3.svg', alt='Texto que describa la imagen')

        img(src='@/assets/curso/tema1/img4.svg', alt='Texto que describa la imagen')

    .row.justify-content-center.align-items-center.mt-5.mb-5      
      .col-lg-10(data-aos="fade-down")
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="zoom-in")
          .bloque-texto-g__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/img1.jpg')})`}")
          .bloque-texto-g__texto.p-4
            p(data-aos="fade-down").mb-0 La metodología Scrum, por definición, es el proceso donde se aplican buenas prácticas, trabajando colaborativamente. Con ella se logra el desarrollo del proyecto por medio de fases o etapas en las que no se avanza si no se termina la fase en la que se está trabajando. 

    p.til.mb-5 Ahora bien, estas son los tres pilares de proceso en que se basa la metodología Scrum:
    
    ImagenInfografica.color-acento-botones.mb-5.col-8.pos12.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema1/vec2.svg', alt='Texto que describa la imagen')
      .tarjeta.bg-amarillo-claro.p-3(x="3.8%" y="64%" numero="")
        .texto-seis-alt.color-acento-botones
          p <b>1. Transparencia</b>  
          p Todos los aspectos del proyecto deben ser completamente conocidos por cada uno de sus integrantes, debe lograrse la misma percepción de todos, de forma clara y precisa.
   
      .tarjeta.bg-amarillo-claro.p-3(x="36.4%" y="94.2%" numero="")
        .texto-seis-alt.color-acento-botones
          p  <b>2. Inspección</b>  
          p Los procesos son guiados hacia un objetivo y cada participante debe estar autoevaluando, de acuerdo con sus resultados y el proceso mismo, detectando posibles desviaciones con rapidez.
           
      .tarjeta.bg-amarillo-claro.p-3(x="96.4%" y="74%" numero="")
        .texto-seis-alt.color-acento-botones
          p  <b>3. Adaptación</b> 
          p Al lograr identificar una desviación, se deben adaptar mediante acciones que ayuden a la corrección o reconfigurar el objetivo.  
    
    p.til.mb-5 Scrum se basa en procesos de mejora continua, apoyándose en el ciclo Deming, así:
    
    ImagenInfografica.color-acento-botones.mb-5.col-8.pos12.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema1/vec3.svg', alt='Texto que describa la imagen')
      .tarjeta.bg-amarillo-claro.p-3(x="34.5%" y="20.5%" numero="")
        .texto-seis-alt.color-acento-botones
          p <b>Plan, planifica:</b> ¿qué hacer?, ¿cómo hacerlo?
   
      .tarjeta.bg-amarillo-claro.p-3(x="73.5%" y="20.5%" numero="")
        .texto-seis-alt.color-acento-botones
          p  <b>Do, ejecuta:</b> realizar lo planificado.
           
      .tarjeta.bg-amarillo-claro.p-3(x="33%" y="86%" numero="")
        .texto-seis-alt.color-acento-botones
          p  <b>Check, comprueba:</b> ¿se pudo actuar frente a lo planeado? 
    
      .tarjeta.bg-amarillo-claro.p-3(x="72.5%" y="86%" numero="")
        .texto-seis-alt.color-acento-botones
          p  <b>Act (actúa):</b> ¿cómo mejoramos para el siguiente ciclo?  
    
    .col-3.pos12.mb-5
      picture
        img(src='@/assets/curso/tema1/importante.svg', alt='Ubicación de mercancía', class='img-fluid')
    separador

    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1.	Premisas Scrum

    
    .row.align-items-center.justify-content-center.fondo-7.p-4.mb-5
      .col-lg-8.ofVisible
        p.mb-5.small.text La idea de las premisas en Scrum es que la satisfacción del producto, no sea solo parte del cliente, sino que también debe ser para cada uno de los integrantes del equipo ejecutor. 
        span Como parte de la metodología, las premisas favorecen la comprensión conceptual de la misma y dan soporte argumental a su propuesta; ellas están directamente relacionadas con los valores Scrum, y son las máximas orientaciones para la efectividad de la aplicación de esta metodología.
      .col-lg-4.lg-0
        figure
          img(src='@/assets/curso/tema1/vec4.svg' alt='' style="width:293px; display:block; margin:1rem 0;")
    
    .row.til.mb-5
      p  A su vez, los valores de la metodología Scrum, son:
    

    .row.mb-4
      .col-md-3.col-lg.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img_1.svg' alt='AvatarTop' style="width: 90px")
          .tarjeta.bg-secundario
            h3.text-center.m-5 Enfoque

      .col-md-3.col-lg.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img_2.svg' alt='AvatarTop' style="width: 90px")
          .tarjeta.bg-color-primario
            h3.text-center.m-5 Compromiso

      .col-md-3.col-lg.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img_3.svg' alt='AvatarTop' style="width: 90px")
          .tarjeta.bg-secundario
            h3.text-center.m-5 Coraje

      .col-md-3.col-lg.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img_4.svg' alt='AvatarTop' style="width: 90px")
          .tarjeta.bg-color-primario
            h3.text-center.m-5 Respeto

      .col-md-3.col-lg.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img_5.svg' alt='AvatarTop' style="width: 90px")
          .tarjeta.bg-secundario.p-4
            h3.text-center.m-4 Organización abierta.
            
    p.mb-5 En el siguiente recurso didáctico, se conocerá y profundizará en las premisas que configuran la metodología Scrum; se debe prestar mucha atención y llevar registro de lo más destacado en la libreta personal de apuntes:

    .row.justify-content-center.mb-4
      .col-md-12
        .video
          iframe(width="942" height="530" src="https://www.youtube.com/embed/yGtQE5dNdnk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

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
