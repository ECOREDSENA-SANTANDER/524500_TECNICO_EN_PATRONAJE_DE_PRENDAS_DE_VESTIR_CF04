<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5 A continuación, se muestra un mapa conceptual con los elementos más importantes desarrollados en este componente.

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.png", alt="La Síntesis esta expuesta como un diagrama de flujo detallado dividido en dos secciones principales: “Trazado de patrones” y “Trazado y corte manual”, cada una con varios pasos organizados jerárquicamente para el proceso de diseño y confección de prendas. En “Trazado de patrones”, se detallan los procedimientos desde la preparación del área de trabajo hasta el modelado de faldas, todos enfocados en la optimización del proceso. En contraste, “Trazado y corte manual” abarca desde el reconocimiento de las prendas hasta la terminología industrial, incluyendo pasos como el extendido del material, diferentes tipos de trazo y el corte final, resaltando aspectos prácticos del manejo de materiales y técnicas de corte.")
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
