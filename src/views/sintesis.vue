<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p El cultivo de aguacate se caracteriza por su adaptación a climas cálidos y húmedos, siendo fundamental un suelo bien drenado y rico en nutrientes. Este frutal, que puede tardar entre 3 y 5 años en producir frutos, requiere cuidados específicos en riego y fertilización para maximizar su rendimiento.
    p.mb-5 La selección del material vegetal es crucial, ya que determina la calidad y resistencia de las plantas. Se recomienda el uso de injertos de variedades superiores y la elección de patrones tolerantes a enfermedades. El manejo del vivero incluye prácticas de desinfección, control de plagas y selección de yemas adecuadas, garantizando un desarrollo óptimo y saludable de las plántulas antes de su siembra definitiva.

    .row.justify-content-center
      .col-lg-12.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="alt")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
