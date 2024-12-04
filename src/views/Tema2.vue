<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Selección del material vegetal y manejo de vivero para el cultivo de aguacate
      
    p La selección del material vegetal para el cultivo de aguacate es crucial para garantizar la calidad y la producción. Se deben elegir variedades adecuadas, como Hass o Fuerte, y utilizar injertos para mejorar la resistencia. El manejo de vivero incluye prácticas de riego, control de plagas y condiciones óptimas de temperatura y luz para fomentar un crecimiento saludable de las plántulas.

    h1 Selección del material vegetal
    p Para tener éxito en un sistema productivo de aguacate es indispensable contar con un buen material de propagación, con calidad sanitaria y agronómica. La selección del patrón y la yema son factores determinantes en la producción y productividad de este frutal, a continuación las selecciones de materiales vegetales: 

    .row.justify-content-center.align-items-center.mb-5.fnd-2.p-lg-4(data-aos="fade-right")
      .tarjeta.tarjeta--azul.p-4.mb-5.fnd-2-2
        SlyderA(tipo="b")
          .row.justify-content-center.align-items-center.px-lg-4.px-md-1
            .col-xl-7
              h5
                i Selección del árbol madre
              p El árbol seleccionado como patrón debe poseer las siguientes características: adaptación a la zona de vida, buena estructura morfológica (formación), desarrollo vigoroso, raíces bien formadas, resistencia a plagas y enfermedades, facilidad en la consecución de la semilla, fácil injertación, alto grado de compatibilidad con la variedad a injertar y resistencia o tolerancia a factores abióticos limitantes en la zona. Los patrones más usados en aguacate deben provenir de árboles nativos o locales que muestren los mejores resultados por su rusticidad y adaptabilidad al medio 
              
            .col-xl-5.col-md-6.mb-0.mb-md-4
              figure
                img(src='@/assets/curso/temas/tema2/img-5.png')
          .row.justify-content-center.align-items-center.px-lg-4.px-md-1
            .col-xl-8
              h5
                i Selección del fruto
              p una vez seleccionado el patrón, se procede a la selección del fruto, preferiblemente del tercio medio de la copa del árbol, este debe estar maduro, sano, bien formado y libre de plagas y enfermedades, y que posean poca pulpa. Para reducir el riesgo de contaminación con el hongo Phytophthora cinnamomi, las semillas no deben provenir de frutos caídos o en contacto con el suelo. La viabilidad de la semilla es de aproximadamente tres semanas.
           
            .col-xl-4.mb-0.mb-md-4.col-md-6
              figure
                img(src='@/assets/curso/temas/tema2/img-6.png')

          .row.justify-content-center.align-items-center.px-lg-4.px-md-1
            .col-xl-8
              h5
                i Extracción de la semilla
              p La semilla debe extraerse manualmente del fruto maduro usando herramientas cortantes. Tras su extracción, se lava para eliminar residuos y se seca en un lugar fresco y oscuro. Antes de germinar, es crucial desinfectar la semilla con productos adecuados o mediante agua caliente, seguida de un enfriamiento. Se recomienda retirar el ápice para acelerar la germinación y detectar daños. Además, la semilla no debe almacenarse por más de dos semanas, ya que esto puede afectar su capacidad de germinación. 
              
            .col-xl-4.mb-0.mb-md-4.col-md-6
              figure
                img(src='@/assets/curso/temas/tema2/img-7.png')

          .row.justify-content-center.align-items-center.px-lg-4.px-md-1
            .col-xl-8
              h5
                i Siembra directa
              p Consiste en llevar la semilla directamente al campo, después de trazar el terreno. Este método no es el más recomendado por el alto porcentaje de pérdida de semilla, por las condiciones adversas del ambiente, alta variabilidad en la germinación, árboles de porte alto y producción tardía.    
              
            .col-xl-4.mb-0.mb-md-4.col-md-6
              figure
                img(src='@/assets/curso/temas/tema2/img-8.png')

          .row.justify-content-center.align-items-center.px-lg-4.px-md-1
            .col-xl-8
              h5
                i Siembra en vivero
              p Este método es el más aconsejable, por el fácil manejo del material a propagarse. Se logra un mayor control sobre la semilla y la planta, un alto porcentaje de germinación y plantas en el campo con un menor tiempo para obtener la producción de fruta.

            .col-xl-4.mb-0.mb-md-4.col-md-6
              figure
                img(src='@/assets/curso/temas/tema2/img-9.png')

    h3 Manejo de vivero para el cultivo de aguacate
    p El procedimiento cuando se siembra en vivero es el siguiente:

       
    

  

   

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
