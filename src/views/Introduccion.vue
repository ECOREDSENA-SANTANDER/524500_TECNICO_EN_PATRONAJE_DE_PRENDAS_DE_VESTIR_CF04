<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.mt-4.mb-4
      .col-4.p-3
        img(src="@/assets/curso/introduccion/imagen1.svg", alt="Modista")
      .col-8
        p En el desarrollo y producción de prendas de vestir, desde el quehacer de un patronista, no solamente es necesario aprender o conocer las técnicas de patronaje en la elaboración de moldes de manera manual, sino que también se demanda la preparación de planos, trazos y despieces en software especializado de patronaje. La industrialización y modernización de procesos exige cada vez más el conocimiento y destrezas en el manejo de programas informáticos; sin embargo, para lograr un óptimo desempeño en el uso de herramientas digitales se hace necesario contar con el conocimiento técnico desde el trabajo manual.
        .cajon.color-primario 
          p.p-5 <strong> El software Optitex es uno de los diferentes tipos de software que existen a nivel nacional e internacional para el sector de la confección y la industria textil; el manejo de este programa permite optimizar tiempos en la preparación de  patrones en las diferentes líneas de producción; la automatización de procesos es cada vez más común en el mercado, debido a su contribución en la reducción de costos de producción y el incremento en la eficacia de los procesos. </strong>

    .row.justify-content-center.align-items-center.mb-4
      .col-10
        .row
          .col-9
            .row.borde-redondo(style='background-color: #FFD54F')
              .col-2.p-3
                <br> <br>
                img(src="@/assets/curso/introduccion/admiracion.png")
              .col-10
                p.p-4 En el desarrollo de este contenido se hará un reconocimiento de la interfaz y del manejo de diferentes tipos de herramientas, partiendo de la base que el conocimiento técnico sobre el desarrollo de patrones o moldes ya ha sido adquirido desde el trabajo manual. Dentro de la cadena de producción uno de los pasos del patronaje corresponde al trazo y corte, estos conceptos se abordarán desde un contexto general y bajo la terminología de la producción industrial, es importante aclarar que el vocabulario, herramientas y teorías que conocerá hacen parte de los conocimientos específicos en el área que debe tener un patronista.
          .col-3
            img(src="@/assets/curso/introduccion/imagen2.svg", alt="Interfaz de un software")
    
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
