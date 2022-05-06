<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1  Ciclo de vida Scrum      
    .bg_grad-05
    .row.justify-content-center
      .col-10.mb-5
        picture
          img(src='@/assets/curso/tema2/cicloscrum.png', alt='Ciclo de vida Scrum', class='img-fluid')

      .col-10.mb-3
        p La metodología Scrum en un proyecto se ejecuta en ciclos temporales, cortos y definidos en su duración. Es decir, son iteraciones de 2, 3 o 4 semanas, dependiendo del proyecto y su replanteamiento, si se necesita. Cada iteración debe mostrar un resultado completo y los objetivos deben ser priorizados para su desarrollo y cumplimento.

      .col-10.cajon.color-secundario.p-4.mb-4(style='background-color: #B9CAF9')
        p Los <font color="#0043FF"><b>roles</b></font> determinan las responsabilidades del proyecto en el equipo de trabajo (<i>Scrum team</i>). El negocio será representado por el <font color="#0043FF"><b><i>product owner</i></b></font> (principal responsable) y junto al <font color="#0043FF"><b><i>Scrum master</i></b></font> (facilitador o entrenador del equipo) se conforma el gobierno del proyecto. Luego siguen los <font color="#0043FF"><b><i>stakeholders</i></b></font>: usuarios clave que conocen el negocio y saben lo que se necesita en el proyecto.


    .row.justify-content-center
      .col-lg-3
        a.tarjeta-avatar-b.mb-5.indicador__container(@click="modal1 = true")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema2/avatar1.svg' alt='AvatarTop')
          .tarjeta.color-primario
            .p-2
              h2.m-2 Los roles
          .col
            a.lnk(@click="modal1 = true") 
          ModalA(:abrir-modal.sync="modal1")
            .row.align-items-center
              .col-md-6.mb-4.mb-md-0
                p <i>Scrum</i>, además de buscar resultados apropiados y rápidos, también trata de lograr que los integrantes del equipo, en el desarrollo del proyecto, sientan responsabilidad y satisfacción.
              
              .col-md-6
                figure
                  img(src='@/assets/curso/tema1/vec5.svg', alt='Texto que describa la imagen')


      .col-lg-3
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema2/avatar2.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .p-2
              h2.m-2 Las actividades

      .col-lg-3
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema2/avatar3.svg' alt='AvatarTop')
          .tarjeta.color-primario
            .p-2
              h2.m-2 Los artefactos

    p.mb-5 Conociendo lo anterior, como elementos fundamentales del ciclo de vida, Scrum proponen los siguientes roles, actividades y artefactos:

    
    .row.mb-5
      .col-lg-7
        .row.mb-5(data-aos="fade-up")
          .col-md-12.mb-4.mb-md-0
            LineaTiempoD.color-primario.text-bold
              p.text-small(numero="1" titulo="Roles").m-2
                ul.lista-ul--color
                  p <i>Scrum team</i> (ST) se forma por:
                  li 
                    i.fas.fa-users
                    span <i>Product Owner (PO)</i>
                  li 
                    i.fas.fa-users
                    span <i>Scrum Master (SM)</i>
                  li 
                    i.fas.fa-users
                    span <i>Development Team (DT)</i>
                  li 
                    i.fas.fa-users
                    span <i>Stakeholders</i>

              p.text-small(numero="2" titulo="Artefactos").m-2
                ul.lista-ul--color
                  h5 Del proyecto: 
                  li 
                    i.fas.fa-users
                    span <i>Product Backlog (PB)</i>
                  li 
                    i.fas.fa-users
                    span <i>Sprint Backlog (SB)</i>
                  li 
                    i.fas.fa-users
                    span <i>Graphs</i>
                  li 
                    i.fas.fa-users
                    span <i>Impediments bBacklogs (IB)</i>
                  br
                  h5 Del sprint:
                  li 
                    i.fas.fa-users
                    span <i>Scrum board</i>
                  li 
                    i.fas.fa-users
                    span <i>Incidence backlog</i>
                  li 
                    i.fas.fa-users
                    span <i>Parking backlog</i>


              p.text-small(numero="2" titulo="Artefactos").m-2
                ul.lista-ul--color
                  li 
                    i.fas.fa-users
                    span <i>Sprint 0 o first sprint (primer sprint).</i>
                  li 
                    i.fas.fa-users
                    span <i>Sprint.</i>
                  li 
                    i.fas.fa-users
                    span <i>Sprint planning (planificación del sprint).</i>
                  li 
                    i.fas.fa-users
                    span <i>Daily meeting (reunión diaria).</i>
                  li 
                    i.fas.fa-users
                    span <i>Sprint review (revisión del sprint)</i>
                  li 
                    i.fas.fa-users
                    span <i>Sprint retrospective (retrospectiva del sprint).</i>
      .col-lg-5  
        img(src='@/assets/curso/tema2/lineadetiempo.png')(data-aos="fade-up")

    p.mb-5 Ahora, se invita a conocer otros aspectos importantes del ciclo de vida Scrum y profundizar en ellos:

    ImagenInfografica.color-acento-botones.col-lg-10.mb-5.center
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema2/img1.svg', alt='Texto que describa la imagen')

      .tarjeta.color-acento-contenido.p-3(x="19.7%" y="9.8%" numero="+")
          .h5.mb-2 <i>Daily meetings</i> o reuniones diarias
          p Para cada <i>sprint</i>, <b><i>el scrum team</i></b> extrae las historias de usuario en tareas, y mientras dure el <i>sprint</i> se llevarán reuniones diarias <b><i>(daily meetings)</i></b>, en las cuales el equipo se sincroniza y avanza construyendo tareas. 

      .tarjeta.color-acento-contenido.p-3(x="65.5%" y="3%" numero="+")
          .h5.mb-2 Finalización del <i>sprint</i>
          p El proceso finaliza con una reunión de presentación de los resultados al usuario (<b><i>sprint review</i></b>) que aceptará o no el producto.

      .tarjeta.color-acento-contenido.p-3(x="97%" y="32.4%" numero="+")
          .h5.mb-2 Retrospectiva o <i>Scrum retrospective</i>
          p Luego, el <b><i>development team</i></b> (equipo de desarrollo) y el <b><i>Scrum master</i></b> (entrenador o facilitador), se reúnen; la intención de esta reunión se conoce como <b><i>Scrum retrospective</i></b> y en ella se busca identificar mejoras en los procesos internos e iniciar, de nuevo, con un <i>sprint</i>.
      
      .tarjeta.color-acento-contenido.p-3(x="91.5%" y="73.7%" numero="+")
          .h5.mb-2 Realizar, ordenar, priorizar, documentar
          p Para lograr identificar las grandes divisiones del trabajo por desarrollar en un proyecto, se debe realizar, ordenar priorizar y documentar. En el desarrollo de los métodos tradicionales se comete el error de confiar en que no habrá cambios, estructuras o requisitos nuevos. 
      
      .tarjeta.color-acento-contenido.p-3(x="62%" y="97%" numero="+")
          .h5.mb-2 Product backlog / potencialidad de Scrum
          p Con la potencialidad que representa Scrum, se elaboran las nuevas peticiones o requisitos de manera flexible, configurable y dinámica, denominada en este caso como <b><i>Product Backlog (PB)</i></b>. 
      
      .tarjeta.color-acento-contenido.p-3(x="17.4%" y="86%" numero="+")
          .h5.mb-2 Inicio del ciclo de vida
          p El ciclo de vida de un proyecto Scrum, inicia cuando el <b><i>Product Owner (PO)</i></b>, crea e informa sobre el <b><i>Product Backlog (PB)</i></b>. 
      
      .tarjeta.color-acento-contenido.p-3(x="2.9%" y="45.7%" numero="+")
          .h5.mb-2 Configuración del product backlog
          p El <b><i>Product Backlog (PB)</i></b> se forma por las historias de usuario definidas que ayudan a identificar, de manera clara y precisa, la funcionalidad que se requiere para el producto. 

    separador



</template>

<script>
export default {
  name: 'Tema2',
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
