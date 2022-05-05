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
        .cajon.color-secundario.bg-3-claro.p-4.mb-4.col-12
          p La Petición es demandar, pedir o solicitar algo que se requiere o se necesita, la petición se eleva ante una persona sea natural o jurídica, el proceso de petición hace referencia a dudas que se tiene de un procedimiento en alguna de sus etapas de ejecución, un cuestionamiento sobre algún paso o proceso no entendido. 
        p Ahora se presentan algunos aspectos clave de la definición y configuración de la metodología Scrum; aquí es importante hacer uso de la libreta personal de apuntes para registrar datos importantes.
      .col.col-12.col-lg-4.position-relative
        picture
          img(src='@/assets/curso/tema1/vec1.svg', alt='Ubicación de mercancía', class='img-fluid')
    
    .tarjeta.col-md-12.col-10.pos12.gris.mb-5
      SlyderA(tipo="b")
        .row.fondo-slyder
          .col-lg-5.col-7.center
            figure
              img.p-y-1(src='@/assets/curso/tema1/1.png', alt='AvatarTop', style="width:350px; display:block; margin:auto 2rem;").m-auto
        
          .col-lg-7.align-items-center
            h5.aling-1 Origen del término
              p.mt-3 Hace referencia, en castellano, a decir “melé”, referenciando una formación característica del rugby o fútbol americano.
          
        .row.fondo-slyder_2
          .col-lg-7.align-items-center
            h5.aling-1 Concentración de esfuerzos humanos
              p.mt-3 En este tipo de formación el equipo aúna esfuerzos humanos con el objetivo de tener la pelota. Scrum, es una buena declaración para realizar trabajo en equipo, es un marco de trabajo para la gestión de proyectos.
          
          .col-lg-5.col-7.center
            figure
              img.p-y-1(src='@/assets/curso/tema1/2.png', alt='AvatarTop', style="width:350px; display:block; margin:auto 2rem;").m-auto
        
        .row.fondo-slyder
          .col-lg-5.col-7.center
            figure
              img.p-y-1(src='@/assets/curso/tema1/3.png', alt='AvatarTop', style="width:350px; display:block; margin:auto 2rem;").m-auto
        
          .col-lg-7.align-items-center
            h5.aling-1 Organización y articulación
              p.mt-3 Scrum planea la forma de organizarse, laborar y obtener resultados, proponiendo un buen rendimiento del trabajo en equipo, definiendo responsabilidades, laborando con herramientas para la mejora continua y trabajo de calidad.
          
        .row.fondo-slyder_2
          .col-lg-7.align-items-center
            h5.aling-1 Proyectos de desarrollo de software
              p.mt-3 Scrum se trata de un marco de trabajo para desarrollo ágil de software, aunque actualmente esta metodología se expande a otras áreas, dada su eficacia, facilidad de aplicación y utilidad práctica. 
          
          .col-lg-5.col-7.center
            figure
              img.p-y-1(src='@/assets/curso/tema1/2.png', alt='AvatarTop', style="width:350px; display:block; margin:auto 2rem;").m-auto

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
      .tarjeta.bg-amarillo-claro.p-4(x="3.8%" y="64%" numero="")
        h5 <b>1. Transparencia</b>  
        p Todos los aspectos del proyecto deben ser completamente conocidos por cada uno de sus integrantes, debe lograrse la misma percepción de todos, de forma clara y precisa.
   
      .tarjeta.bg-amarillo-claro.p-4(x="36.4%" y="94.2%" numero="")
        h5 <b>2. Inspección</b>  
        p Los procesos son guiados hacia un objetivo y cada participante debe estar autoevaluando, de acuerdo con sus resultados y el proceso mismo, detectando posibles desviaciones con rapidez.
           
      .tarjeta.bg-amarillo-claro.p-4(x="96.4%" y="74%" numero="")
        h5 <b>3. Adaptación</b> 
        p Al lograr identificar una desviación, se deben adaptar mediante acciones que ayuden a la corrección o reconfigurar el objetivo.  
    
    p.til.mb-5 Scrum se basa en procesos de mejora continua, apoyándose en el ciclo Deming, así:
    
    ImagenInfografica.color-acento-botones.mb-5.col-8.pos12.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema1/vec3.svg', alt='Texto que describa la imagen')
      .tarjeta.bg-amarillo-claro.p-3(x="34.5%" y="20.5%" numero="")
        p <b>1. Plan, planifica:</b> ¿qué hacer?, ¿cómo hacerlo?
   
      .tarjeta.bg-amarillo-claro.p-3(x="73.5%" y="20.5%" numero="")
        p  <b>2. Do, ejecuta:</b> realizar lo planificado.
           
      .tarjeta.bg-amarillo-claro.p-3(x="33%" y="86%" numero="")
        p  <b>3. Check, comprueba:</b> ¿se pudo actuar frente a lo planeado? 
    
      .tarjeta.bg-amarillo-claro.p-3(x="72.5%" y="86%" numero="")
        p  <b>4. Act (actúa):</b> ¿cómo mejoramos para el siguiente ciclo?  
    
    .row
      .col-md-12
        a.picture.indicador__container(@click="modal1 = true")
          img(src='@/assets/curso/tema1/importante.svg', alt='Ubicación de mercancía', style="width: 263px").center
        .col
            a.lnk(@click="modal1 = true") 
        ModalA(:abrir-modal.sync="modal1")
          .row.align-items-center
            .col-md-6.mb-4.mb-md-0
              p <i>Scrum</i>, además de buscar resultados apropiados y rápidos, también trata de lograr que los integrantes del equipo, en el desarrollo del proyecto, sientan responsabilidad y satisfacción.
            
            .col-md-6
              figure
                img(src='@/assets/curso/tema1/vec5.svg', alt='Texto que describa la imagen')
    separador


    .titulo-segundo.color-acento-contenido#t_1_1
      h2 1.1.	Premisas Scrum 

    .row.justify-content-center.align-items-center.mb-5
      .col-lg.order-2.order-lg-1
        .custom_box_rigth 
          p.mb-4 La idea de las premisas en Scrum es que la satisfacción del producto, no sea solo parte del cliente, sino que también debe ser para cada uno de los integrantes del equipo ejecutor. 
          span Como parte de la metodología, las premisas favorecen la comprensión conceptual de la misma y dan soporte argumental a su propuesta; ellas están directamente relacionadas con los valores Scrum, y son las máximas orientaciones para la efectividad de la aplicación de esta metodología.
      .col-auto.mb-5.mb-lg-0.onTop.order-1.order-lg-1
        img(src="@/assets/curso/tema1/vec4.svg" alt='AvatarTop', style="width:330px; display:block; margin:-6rem -1rem;").m-auto

    .row.til.mb-5
      p  A su vez, los valores de la metodología Scrum, son:

    .row.mb-5
      .col-md-3.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img_1.svg' alt='AvatarTop')
          .tarjeta.bg-secundario.w-100
            .text-center.p-2.mt-3.text-system
              h4 Enfoque

      .col-md-3.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img_2.svg' alt='AvatarTop')
          .tarjeta.bg-color-primario.w-100
            .text-center.p-2.mt-3.text-system
              h4 Compromiso

      .col-md-3.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img_3.svg' alt='AvatarTop')
          .tarjeta.bg-secundario.w-100
            .text-center.p-2.mt-3.text-system
              h4 Coraje

      .col-md-3.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img_4.svg' alt='AvatarTop')
          .tarjeta.bg-color-primario.w-100
            .text-center.p-2.mt-3.text-system
              h4 Respeto

      .col-md-3.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img_5.svg' alt='AvatarTop')
          .tarjeta.bg-secundario.w-100
            .text-center.p-2.mt-3.text-system
              h4 Organización abierta
            
    p.mb-5 En el siguiente recurso didáctico, se conocerá y profundizará en las premisas que configuran la metodología Scrum; se debe prestar mucha atención y llevar registro de lo más destacado en la libreta personal de apuntes:

    .row.justify-content-center.mb-5
      .col-md-12
        .video
          iframe(width="942" height="530" src="https://www.youtube.com/embed/yGtQE5dNdnk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    separador


    #t_1_2.titulo-segundo.color-acento-contenido.mb-4
      h2 1.2.	Premisas Scrum

    .row.mb-5
      .col.col-12.col-lg-6.position-relative
        picture
          img(src='@/assets/curso/tema1/img1.png', alt='Scrum', class='img-fluid')
      .col.col-12.col-lg-6
        p.mb-4 Los conceptos y las entidades ayudan a plantear la forma de trabajo en Scrum. Para lograr trabajar de manera adecuada en esta metodología, se pueden identificar las unidades, que son las llamadas historias de usuario o <i>user stories</i>.
        .cajon.color-primario.p-4.mb-4.col-12(style='background-color: #F0F1F5')
          p De igual forma, existen unidades que suelen ser muy complejas para individualizarlas o demasiado simples para tratarlas como grandes descripciones de un proyecto. Se debe, entonces, iniciar siempre desde las más sencillas y avanzar hasta las más complejas.
        p Las siguientes son las entidades concebidas desde la metodología Scrum; aquí es importante tener presente que se deben jerarquizar los niveles para solucionar las incertidumbres:
      
    ImagenInfografica.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/template/vec1.svg', alt='Texto que describa la imagen')

      .tarjeta.color-acento-contenido.p-3(x="16.8%" y="70.1%" numero="+")
          .h5.mb-2 Tareas
          p Es un trabajo concreto, realizado por una persona, con límite de días, lenguaje técnico del trabajo.

      .tarjeta.color-acento-contenido.p-3(x="34.4%" y="26.2%" numero="+")
          .h5.mb-2 Historias de usuario
          p Es donde se define el lenguaje del negocio que hace el <i>product owner (PO)</i> de los requisitos o necesidades para realizar el trabajo. Estos requisitos se desintegran en unidades más pequeñas para ejecutarlas.

      .tarjeta.color-acento-contenido.p-3(x="80.2%" y="59.5%" numero="+")
          .h5.mb-2 Épicas
          p Es la agrupación de historias de usuario que construyen grandes bloques operativos para realizar junto al proyecto. 

    SlyderB.mb-5(:datos="datosSlyder")
    separador
    
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    modal1: false,
    indicadorTarjetaFlip: true,
    datosSlyder: [
      {
        titulo: 'Velocidad',
        texto: 'Define la capacidad del equipo para ejecutar las actividades.',
        imagen: require('@/assets/curso/tema1/slyder1.jpg'),
      },
      {
        titulo: 'Herramientas',
        texto:
          'Existen diferentes tipos de herramientas según el tipo de proyecto. Las más utilizadas son el uso de paneles con etiquetas adhesivas o post-it. Por lo general, se utiliza el <i>backlog</i>.',
        imagen: require('@/assets/curso/tema1/slyder2.jpg'),
      },
      {
        titulo: 'Entorno de trabajo',
        texto:
          'Se debe dar gran importancia a la comunicación y a la difusión de la información, seguido de la colaboración y el entendimiento básico de los aspectos o tareas de trabajo.',
        imagen: require('@/assets/curso/tema1/slyder3.jpg'),
      },
    ],
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
