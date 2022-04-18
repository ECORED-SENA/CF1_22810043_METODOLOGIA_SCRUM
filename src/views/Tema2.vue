<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1  Ciclo de vida Scrum      
   
    .row.justify-content-center
      .col-10.mb-5
        picture
          img(src='@/assets/curso/tema2/cicloscrum.png', alt='Ciclo de vida Scrum', class='img-fluid')

      .col-10.mb-3
        p La metodología Scrum en un proyecto se ejecuta en ciclos temporales, cortos y definidos en su duración. Es decir, son iteraciones de 2, 3 o 4 semanas, dependiendo del proyecto y su replanteamiento, si se necesita. Cada iteración debe mostrar un resultado completo y los objetivos deben ser priorizados para su desarrollo y cumplimento.

      .col-10.cajon.color-secundario.p-4.mb-4(style='background-color: #B9CAF9')
        p Los roles determinan las responsabilidades del proyecto en el equipo de trabajo (<i>Scrum team</i>). El negocio será representado por el <i>product owner</i> (principal responsable) y junto al Scrum master (facilitador o entrenador del equipo) se conforma el gobierno del proyecto. Luego siguen los <i>stakeholders</i>: usuarios clave que conocen el negocio y saben lo que se necesita en el proyecto.

    .row.justify-content-center
      .col-lg-3
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema2/avatar1.svg' alt='AvatarTop')
          .tarjeta.color-primario
            .p-2
              h2.m-2 Los roles

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
