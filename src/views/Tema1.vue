<template lang="pug">
.curso-main-container.pb-3
  BannerInterno.fnd1
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Generalidades del cultivo de aguacate
      
    
    //- .bloque-texto-a debe ir acompañado de una de una de estas clases => 
    //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
    .bloque-texto-a.color-secundario.p-4.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-4.mb-4.mb-lg-0
          h2.mb-0 Whatever can be captured in words can be conquered with understanding. 
        .col-lg-8
          .bloque-texto-a__texto.p-4
            p El cultivo de aguacate (Persea americana) ha ganado popularidad a nivel mundial debido a su demanda creciente y sus múltiples beneficios nutricionales. Se desarrolla mejor en climas cálidos y templados, con temperaturas entre 15 y 30 °C, y prefiere suelos bien drenados, ricos en materia orgánica, con un pH entre 6 y 6.5. Existen varias variedades, siendo las más conocidas el Hass, Fuerte y Bacon, cada una con características específicas en sabor, textura y época de cosecha.

    .row.pe-lg-3.justify-content-center.mb-4(data-aos="zoom-in")
      h3.mb-3 Aspectos generales del aguacate              
          
    h3.mb-0 Origen
    .row.justify-content-center.align-items-center.mb-4(data-aos="fade-right")
      .col-xl-8.order-2.order-xl-1            
        p El aguacate (<em>Persea americana Mill</em>), es originario de la zona montañosa situada al occidente de México y Guatemala, su distribución natural va hasta Perú. Varios siglos antes de la llegada de los europeos se cultivaban desde Río Bravo (norte de México) hasta Chile, la ruta en la cual se han encontrado fósiles hasta de 12 mil años de antigüedad.
        p La palabra aguacate proviene de la lengua azteca "náhuatl", pero esta fruta recibe también otros nombres según las regiones donde se cultiva, entre ellos se tiene: palta, cura, avocado o abacate.

      .col-xl-4.col-md-6.mb-4.order-1.order-xl-2
        figure
          img(src='@/assets/curso/temas/tema1/img-3.svg')

    h3.mb-5 Taxonomia

    h3 Descripción botánica
    p Esta planta se caracteriza por tener un tronco vigoroso y grueso, que en condiciones naturales puede sobrepasar los 10 metros de altura, gran ramificación, copa amplia con hojas perennifolias. Es una planta polimórfica, su sistema radicular es amplio y superficial, presenta hojas brillantes de color verde en la mayoría de las variedades y flores perfectas en racimos subterminales que se abren en dos momentos para exponer los órganos femeninos y masculinos en diferentes tiempos, evitando así la autofecundación:

    .row.justify-content-center.align-items-center.mb-5.fnd-2.p-lg-4(data-aos="fade-right")
      .tarjeta.tarjeta--azul.p-4.mb-5.fnd-2-2
        SlyderA(tipo="b")
          .row.justify-content-center.align-items-center.px-lg-4.px-md-1
            .col-xl-7
              h5
                i Raíz
              p El sistema radical de esta especie consta de una raíz pivotante principal que puede sobrepasar 1 metro de profundidad, dándole anclaje al árbol. Se ramifica en raíces secundarias y terciarias que se distribuyen en los primeros 60 centímetros del suelo, este sistema carece de pelillos absorbentes y la absorción de agua y nutrientes solo se realiza en las áreas jóvenes del sistema radical. 
              
            .col-xl-5.col-md-6.mb-0.mb-md-4
              figure
                img(src='@/assets/curso/temas/tema1/img-5.png')
          .row.justify-content-center.align-items-center.px-lg-4.px-md-1
            .col-xl-8
              h5
                i Ramificaciones
              p Esta especie cuenta con ramas gruesas y una gran cantidad de ramas delgadas de color verde en las puntas así:   
              
            .col-xl-4.mb-0.mb-md-4.col-md-6
              figure
                img(src='@/assets/curso/temas/tema1/img-6.png')

          .row.justify-content-center.align-items-center.px-lg-4.px-md-1
            .col-xl-8
              h5
                i Inflorescencias
              p Las flores están agrupadas en inflorescencias de tallo largo, que en número hasta de 10 crecen en las axilas, presentando grupos integrados que contienen hasta 450 flores, que pueden madurar en el transcurso de seis meses, de acuerdo a la temperatura y la variedad. Cada árbol puede llegar a producir hasta un millón de flores y solo entre el 0.01% el 1% se transforma en fruto, por la abscisión de numerosas flores y frutos pequeños en desarrollo. A mayor floración menor porcentaje de cuajado. (Corpoica, 2008, p. 19)
   
              
            .col-xl-4.mb-0.mb-md-4.col-md-6
              figure
                img(src='@/assets/curso/temas/tema1/img-8.png')
          .row.justify-content-center.align-items-center.px-lg-4.px-md-1
            .col-xl-8
              h5
                i Tallo
              p La planta posee un tallo vigoroso, erecto, leñoso, ramificado y con una corteza escamosa de color grisáceo a veces surcada longitudinalmente. Puede alcanzar un diámetro de hasta 80 centímetros y una altura de 25 a 30 metros en su edad adulta. La copa es de forma globosa y acampanada. Su madera puede ser utilizada en el área de la construcción y para uso doméstico.   
              
            .col-xl-4.mb-0.mb-md-4.col-md-6
              figure
                img(src='@/assets/curso/temas/tema1/img-7.png')

          .row.justify-content-center.align-items-center.px-lg-4.px-md-1
            .col-xl-8
              h5
                i Flores
              p Las flores son pequeñas, hermafroditas y agrupadas en panículas, con un cáliz de tres sépalos y corola tripétala. Tienen 12 estambres (nueve funcionales) y un pistilo con un solo carpelo y óvulo. Sus colores varían entre crema, amarillo, verde, café y rojo, y duran dos días antes de ser fecundadas o caer. Presentan protoginia, donde los órganos femeninos maduran primero, y se clasifican en tipo A y B, lo que influye en la productividad del árbol.   
              
            .col-xl-4.mb-0.mb-md-4.col-md-6
              figure
                img(src='@/assets/curso/temas/tema1/img-9.png')
          .row.justify-content-center.align-items-center.px-lg-4.px-md-1
            .col-xl-8
              h5
                i Hojas
              p Las hojas de esta especie poseen en promedio 15 cm de largo y 7 cm de ancho; son simples, alternas, bordes enteros, el haz es de color verde oscuro brillante y su envés de color blancuzco, su forma es elíptica y de textura suave, el ápice termina en punta aguda, su base es en cuña con nerviación marcada, algunas variedades presentan hojas con olores específicos (anisadas).   
              
            .col-xl-4.mb-0.mb-md-4.col-md-6
              figure
                img(src='@/assets/curso/temas/tema1/img-10.png')
          .row.justify-content-center.align-items-center.px-lg-4.px-md-1
            .col-xl-8
              h5
                i Fruto
              p El fruto del aguacate posee una sola semilla, que varía de formas según la raza (redondo, alargado, forma de botella, entre otras), su cáscara puede ser lisa o rugosa con coloraciones verde y violáceo. La consistencia de la pulpa es blanda de color blanco amarillento, que pasa a verde en la cercanía de la cáscara. La maduración del fruto solo se presenta cuando este se retira del árbol. El tamaño varía según la variedad y tiene un peso promedio entre 200 y 2.500 gramos   
              
            .col-xl-4.mb-0.mb-md-4.col-md-6
              figure
                img(src='@/assets/curso/temas/tema1/img-11.png')

      h3 Razas de aguacate
      p En esta especie se tienen tres razas → Mexicana, Guatemalteca y Antillana:

      .col-xl-6.mb-0.mb-md-6.col-md-12
        figure
          img(src='@/assets/curso/temas/tema1/img-12.png')
      .col-xl-6.mb-0.mb-md-6.col-md-12
        figure
          img(src='@/assets/curso/temas/tema1/img-13.png')
      .col-xl-6.mb-0.mb-md-6.col-md-12
        figure
          img(src='@/assets/curso/temas/tema1/img-14.png')

      h3.mb-3 Zonas de vida

      p Cada zona de vida tiene características especiales y específicas que la hacen apta para la siembra de cada especie agrícola, por lo tanto, antes de la siembra de un cultivo debe tenerse muy en cuenta este parámetro. A continuación, se presenta información precisa sobre las zonas de vida según Holdridge (1987):

      p Es importante tener en cuenta la zona de vida para la producción de aguacate, pues de esta depende la adaptación, desarrollo, crecimiento, producción y productividad de la especie. Se tienen en cuenta variables como: altura sobre el nivel del mar y factores climáticos como temperatura, brillo solar, humedad relativa, vientos y precipitación. Dichas variables son determinantes para este tipo de cultivo.

      h3.mb-3 Altura sobre el nivel del mar
      p Esta variable determina el piso térmico apto para el desarrollo del cultivo. A continuación, se relaciona la altura sobre el nivel del mar óptimo para cada una de las razas de aguacate.

      h3.mb-3 Factores climáticos
      p Los aguacates mexicanos prosperan en climas templados a cálidos, tolerando temperaturas más frías. Los guatemaltecos requieren condiciones templadas y húmedas, con menos resistencia al frío. En cambio, los antillanos son ideales para climas cálidos y húmedos, siendo más sensibles a las heladas. Todos requieren buen drenaje y estabilidad hídrica para un crecimiento óptimo y producción de frutos:





           

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
