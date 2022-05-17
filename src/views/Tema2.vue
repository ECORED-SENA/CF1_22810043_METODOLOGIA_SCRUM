<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1  Ciclo de vida Scrum      
    .bg_grad-05
    .row.justify-content-center(data-aos="fade-down")
      .col-md-10.col-12.mb-5
        picture
          img(src='@/assets/curso/tema2/cicloscrum.png', alt='Ciclo de vida Scrum', class='img-fluid')

      .col-md-10.col-12.mb-3
        p La metodología Scrum en un proyecto se ejecuta en ciclos temporales, cortos y definidos en su duración. Es decir, son iteraciones de 2, 3 o 4 semanas, dependiendo del proyecto y su replanteamiento, si se necesita. Cada iteración debe mostrar un resultado completo y los objetivos deben ser priorizados para su desarrollo y cumplimento.

      .col-md-10.col-12.cajon.color-secundario.p-4.mb-4(style='background-color: #B9CAF9')
        p Los <font color="#0043FF"><b>roles</b></font> determinan las responsabilidades del proyecto en el equipo de trabajo (<i>Scrum team</i>). El negocio será representado por el <font color="#0043FF"><b><i>product owner</i></b></font> (principal responsable) y junto al <font color="#0043FF"><b><i>Scrum master</i></b></font> (facilitador o entrenador del equipo) se conforma el gobierno del proyecto. Luego siguen los <font color="#0043FF"><b><i>stakeholders</i></b></font>: usuarios clave que conocen el negocio y saben lo que se necesita en el proyecto.


    .row.mb-5(data-aos="fade-down")
      .col-lg-4.mb-3
        a.picture.indicador__container(@click="modal1 = true")
          img(src='@/assets/curso/tema2/roles.svg', alt='Ubicación de mercancía', style="width: 263px").center
          .indicador--click(v-if="mostrarIndicador")
        .col
          a.lnk(@click="modal1 = true") 
        ModalA(:abrir-modal.sync="modal1")
          .row.align-items-center
            .col-md-6.mb-4.mb-md-0
              h5 Los roles
              p Los roles ayudan a determinar las responsabilidades en el proyecto.
            .col-md-6
              figure
                img(src='@/assets/curso/tema2/1.png',)

      .col-lg-4.mb-3
        a.picture.indicador__container(@click="modal2 = true")
          img(src='@/assets/curso/tema2/actividades.svg', alt='Ubicación de mercancía', style="width: 263px").center
        .col
          a.lnk(@click="modal2 = true") 
        ModalA(:abrir-modal.sync="modal2")
          .row.align-items-center
            .col-md-6.mb-4.mb-md-0
              h5 Las actividades
              p Las actividades ayudan a establecer los tiempos de ejecución, divididos en ciclos evaluables, proporcionando una visión en todo momento sobre el producto.

            .col-md-6
              figure
                img(src='@/assets/curso/tema2/2.png',)

      .col-lg-4.mb-3
        a.picture.indicador__container(@click="modal3 = true")
          img(src='@/assets/curso/tema2/artefactos.svg', alt='Ubicación de mercancía', style="width: 263px").center
        .col
          a.lnk(@click="modal3 = true") 
        ModalA(:abrir-modal.sync="modal3")
          .row.align-items-center
            .col-md-6.mb-4.mb-md-0
              h5 Los artefactos
              p Los artefactos conforman el equipo de herramientas con el cual se ejecuta y se controla el proyecto, basado en listas de control y el Scrum board.
              
            .col-md-6
              figure
                img(src='@/assets/curso/tema2/3.png',)


    p.mb-5 Conociendo lo anterior, como elementos fundamentales del ciclo de vida, Scrum proponen los siguientes roles, actividades y artefactos:

    
    .row.mb-5.justify-content-center
      .col-lg-5
        .row.center(data-aos="fade-up")
          .col-md-12
            LineaTiempoD.color-primario.text-bold
              h5.text-small(numero="1" titulo="Roles")
                ul.lista-ul
                  h6 <i>Scrum team</i> (ST) se forma por:
                  li 
                    i.fas.fa-users
                    h6 <i>Product Owner (PO)</i>
                  li 
                    i.fas.fa-users
                    h6 <i>Scrum Master (SM)</i>
                  li 
                    i.fas.fa-users
                    h6 <i>Development Team (DT)</i>
                  li 
                    i.fas.fa-users
                    h6 <i>Stakeholders</i>

              h5.text-small(numero="2" titulo="Artefactos")
                ul.lista-ul
                  h6 Del proyecto: 
                  li 
                    i.fas.fa-users
                    h6 <i>Product Backlog (PB)</i>
                  li 
                    i.fas.fa-users
                    h6 <i>Sprint Backlog (SB)</i>
                  li 
                    i.fas.fa-users
                    h6 <i>Graphs</i>
                  li 
                    i.fas.fa-users
                    h6 <i>Impediments bBacklogs (IB)</i>
                  br
                  h6 Del sprint:
                  li 
                    i.fas.fa-users
                    h6 <i>Scrum board</i>
                  li 
                    i.fas.fa-users
                    h6 <i>Incidence backlog</i>
                  li 
                    i.fas.fa-users
                    h6 <i>Parking backlog</i>


              h5.text-small(numero="2" titulo="Actividades")
                ul.lista-ul
                  li 
                    i.fas.fa-users
                    h6 <i>Sprint 0 o first sprint (primer sprint).</i>
                  li 
                    i.fas.fa-users
                    h6 <i>Sprint.</i>
                  li 
                    i.fas.fa-users
                    h6 <i>Sprint planning (planificación del sprint).</i>
                  li 
                    i.fas.fa-users
                    h6 <i>Daily meeting (reunión diaria).</i>
                  li 
                    i.fas.fa-users
                    h6 <i>Sprint review (revisión del sprint)</i>
                  li 
                    i.fas.fa-users
                    h6 <i>Sprint retrospective (retrospectiva del sprint).</i>
      .col-lg-5  
        img(src='@/assets/curso/tema2/lineadetiempo.png' style="width: 472px")(data-aos="fade-up")

    p.mb-5 Ahora, se invita a conocer otros aspectos importantes del ciclo de vida Scrum y profundizar en ellos:

    ImagenInfografica.color-acento-botones.col-lg-10.mb-5.center(data-aos="fade-down")
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema2/img1.svg', alt='Texto que describa la imagen')

      .tarjeta.bg-amarillo-claro.p-4(x="19.7%" y="9.8%" numero="+")
          .h5.mb-3 1.  <i>Daily meetings</i> o reuniones diarias
          p Para cada <i>sprint</i>, <b><i>el scrum team</i></b> extrae las historias de usuario en tareas, y mientras dure el <i>sprint</i> se llevarán reuniones diarias <b><i>(daily meetings)</i></b>, en las cuales el equipo se sincroniza y avanza construyendo tareas. 

      .tarjeta.bg-amarillo-claro.p-4(x="65.5%" y="3%" numero="+")
          .h5.mb-3 2.   Finalización del <i>sprint</i>
          p El proceso finaliza con una reunión de presentación de los resultados al usuario (<b><i>sprint review</i></b>) que aceptará o no el producto.

      .tarjeta.bg-amarillo-claro.p-4(x="97%" y="32.4%" numero="+")
          .h5.mb-3 3.   Retrospectiva o <i>Scrum retrospective</i>
          p Luego, el <b><i>development team</i></b> (equipo de desarrollo) y el <b><i>Scrum master</i></b> (entrenador o facilitador), se reúnen; la intención de esta reunión se conoce como <b><i>Scrum retrospective</i></b> y en ella se busca identificar mejoras en los procesos internos e iniciar, de nuevo, con un <i>sprint</i>.
      
      .tarjeta.bg-amarillo-claro.p-4(x="91.5%" y="73.7%" numero="+")
          .h5.mb-3 4.   Realizar, ordenar, priorizar, documentar
          p Para lograr identificar las grandes divisiones del trabajo por desarrollar en un proyecto, se debe realizar, ordenar priorizar y documentar. En el desarrollo de los métodos tradicionales se comete el error de confiar en que no habrá cambios, estructuras o requisitos nuevos. 
      
      .tarjeta.bg-amarillo-claro.p-4(x="62%" y="97%" numero="+")
          .h5.mb-3 5.   Product backlog / potencialidad de Scrum
          p Con la potencialidad que representa Scrum, se elaboran las nuevas peticiones o requisitos de manera flexible, configurable y dinámica, denominada en este caso como <b><i>Product Backlog (PB)</i></b>. 
      
      .tarjeta.bg-amarillo-claro.p-4(x="17.4%" y="86%" numero="+")
          .h5.mb-3 6.   Inicio del ciclo de vida
          p El ciclo de vida de un proyecto Scrum, inicia cuando el <b><i>Product Owner (PO)</i></b>, crea e informa sobre el <b><i>Product Backlog (PB)</i></b>. 
      
      .tarjeta.bg-amarillo-claro.p-4(x="2.9%" y="45.7%" numero="+")
          .h5.mb-3 7.  Configuración del product backlog
          p El <b><i>Product Backlog (PB)</i></b> se forma por las historias de usuario definidas que ayudan a identificar, de manera clara y precisa, la funcionalidad que se requiere para el producto. 



</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    mostrarIndicador: true,
    indicadorModalA: true,
    modal1: false,
    modal2: false,
    modal3: false,
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
