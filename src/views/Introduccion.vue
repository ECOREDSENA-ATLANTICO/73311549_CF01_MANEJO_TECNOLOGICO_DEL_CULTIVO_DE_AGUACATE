<template lang="pug">
.curso-main-container.introduccion
  BannerInterno.fnd1
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-7
        p Bienvenidos al programa de estudio sobre estrategia de producción y propagación del aguacate. A lo largo de esta unidad, exploraremos cómo el programa de manejo tecnológico del cultivo de aguacate está diseñado para empoderar a los agricultores con las herramientas y conocimientos necesarios para optimizar la producción de esta valiosa fruta. A través de una formación integral, se abordarán aspectos clave como la planificación de cultivos, la propagación en viveros y las mejores prácticas de cosecha y poscosecha. Nuestro objetivo es fomentar un cultivo sostenible y de alta calidad que satisfaga las crecientes demandas del mercado.
        p.mb-5 Este programa no solo se enfoca en la producción, sino también en el desarrollo de habilidades estratégicas para ingresar y mantenerse en un mercado competitivo. Los aprendices aprenderán a identificar las necesidades del consumidor y a aplicar técnicas modernas que mejoren la calidad del aguacate:

      .col-lg-5.col-md-6
        figure
          img(src='@/assets/curso/temas/tema1/img-intro.png', alt='')

    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Fuente: Sena (2024).
  
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
