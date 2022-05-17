<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción                                        

    .cajon-b.color-secundario.p-3.mb-5(data-aos="fade-right")
      p.mb-0 Le damos la bienvenida al componente <font color="#0043FF"><b>“Scrum, descripciones y características”</b>.</font> Para comenzar, visualice el recurso que, a continuación, se muestra. <font color="#0043FF"><b>¡Adelante!</b></font>
    figure.mb-5(data-aos="zoom-in-up")
      .video
        iframe(width="942" height="530" src="https://www.youtube.com/embed/9MaFAIVuGVY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
