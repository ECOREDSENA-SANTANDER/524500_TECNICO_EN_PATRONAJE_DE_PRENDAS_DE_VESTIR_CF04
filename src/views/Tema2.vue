<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Trazo y corte manual
    
    .row.justify-content-center.align-items-center.mt-4(data-aos="zoom-in-left")
      .col-sm-12.col-md-8.col-lg-9
        p La industria textil se destaca por tener diferentes procesos productivos para elaborar prendas de vestir; cuando se habla de trazo y corte a nivel general, consiste en toda la optimización o acomodación de moldes sobre el material textil.
        .cajon.color-primario 
          p.p-5 #[b  Para abordar este tema, y de acuerdo con la necesidad de la industria textil frente al perfil de un patronista, se brindarán los conocimientos y se entregarán las herramientas técnicas requeridas en el área de prototipado o muestreo de producto.  ]
      .col-7.col-md-4.col-lg-3.p-3
        img(src="@/assets/curso/temas/tema2/imagen1.svg", alt="Imagen recortando molde")
    
    Separador 
    .row.mb-4
      #t_2_1.titulo-segundo.color-primario
        h2 2.1  Reconocimiento de las prendas

    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-md-12.col-lg-4
        h3 ¿Para qué?
        p El reconocimiento de las partes que componen una prenda de vestir es sumamente importante para el proceso de trazo y corte, de esto depende una adecuada interpretación de los requerimientos de corte.
      .col-sm-12.col-md-12.col-lg-8
        .row.justify-content-center
          .col-10.col-md-4.col-lg-4
            img(src="@/assets/curso/temas/tema2/imagen2a.svg", alt="La imagen detalla varios bocetos de prendas de vestir diseñadas para mujeres. Las prendas incluyen una camiseta de manga larga, una camisa de botones, un top sin mangas, un conjunto de pijama, un pantalón, un vestido de tirantes, una bata corta y una bata larga con cinturón. Cada prenda está detalladamente ilustrada, indicando diferentes estilos y diseños para ropa femenina.")
          .col-10.col-md-4.col-lg-4
            img(src="@/assets/curso/temas/tema2/imagen2b.svg", alt="La imagen detalla varios bocetos de prendas de vestir diseñadas para mujeres. Las prendas incluyen una camiseta de manga larga, una camisa de botones, un top sin mangas, un conjunto de pijama, un pantalón, un vestido de tirantes, una bata corta y una bata larga con cinturón. Cada prenda está detalladamente ilustrada, indicando diferentes estilos y diseños para ropa femenina.")
          .col-10.col-md-4.col-lg-4
            img(src="@/assets/curso/temas/tema2/imagen2c.svg", alt="La imagen detalla varios bocetos de prendas de vestir diseñadas para mujeres. Las prendas incluyen una camiseta de manga larga, una camisa de botones, un top sin mangas, un conjunto de pijama, un pantalón, un vestido de tirantes, una bata corta y una bata larga con cinturón. Cada prenda está detalladamente ilustrada, indicando diferentes estilos y diseños para ropa femenina.")


    .row.justify-content-center.mt-4.fondoespecial.mb-5(data-aos="zoom-in-left")
      .col-7.col-md-5.col-lg-5.mb-5.mt-5
        img(src="@/assets/curso/temas/tema2/imagen3.svg", alt="La imagen presenta bocetos técnicos de una chaqueta, destacando detalles específicos del diseño. Incluye pantallazo frontal y posterior de la chaqueta, así como ampliaciones de características particulares: un ojal tipo ribete, un cuello alto con pinza y una manga tipo sastre con pinza. Estas ampliaciones resaltan los elementos de confección y estilo de la prenda.")
      .col-sm-12.col-md-5.col-lg-5.mt-5
        h3 Dibujo técnico
        p Representación detallada de una prenda y las partes que la componen, permite identificar todas sus características técnicas, pespuntes, botones, costuras, pinzas, acabados. No tiene movimiento, pero se puede identificar la parte delantera y posterior. 

    TabsA.color-acento-botones(data-aos="zoom-in-left")
      .tarjeta.color-acento-botones--borde.p-4(titulo="Componentes de las prendas")
        .row.align-items-center
          .col-sm-12.col-md-8.col-lg-8.p-5
            h3.mt-4.mb-4 Componentes de las prendas
            p Los componentes son los elementos y/o partes de las que están formadas las prendas de vestir.
            p Estos pueden ser:
            ul.lista-ul--color.fa-ul.color-primario.ps-1
              li 
                i.fas.fa-plus
                | Exteriores.
              li
                i.fas.fa-plus
                | Interiores.
              li
                i.fas.fa-plus
                | Hilos.
              li
                i.fas.fa-plus
                | Fornituras y complementos.
          .col-8.col-md-4.col-lg-4.p-5
            img(src="@/assets/curso/temas/tema2/imagen4.svg", alt="La imagen describe los componentes de una prenda de vestir, utilizando la ilustración de un traje para mostrar las distintas partes. Los componentes se dividen en cuatro categorías: exteriores, interiores, hilos, y fornituras y complementos. ")
      .tarjeta.color-acento-botones--borde.p-4(titulo="Componentes exteriores")
        .row.align-items-center
          .col-sm-12.col-md-7.col-lg-7.p-5
            h4 Componentes exteriores
            p Son todas las partes del material textil base con la que está elaborada la prenda en el exterior.
            ol.lista-ol--cuadro.fa-ol
              li 
                .lista-ol--cuadro__vineta.bgamarillo
                  span 1 
                | Delanteros y posteriores.
              li 
                .lista-ol--cuadro__vineta.bgamarillo
                  span 2 
                | Cuellos.
              li 
                .lista-ol--cuadro__vineta.bgamarillo
                  span 3
                | Mangas.
              li 
                .lista-ol--cuadro__vineta.bgamarillo
                  span 4
                | Bolsillos.
              li 
                .lista-ol--cuadro__vineta.bgamarillo
                  span 5
                | Puños, entre otros.
          .col-8.col-md-5.col-lg-5.p-5
           img.mt-5.mb-5(src="@/assets/curso/temas/tema2/imagen5.svg", alt="La imagen presenta un abrigo destacando sus componentes exteriores, que incluyen delanteros y posteriores, cuellos, mangas, bolsillos y puños, entre otros. Estos elementos están formados por el material textil base utilizado para confeccionar la prenda en su exterior.")
      .tarjeta.color-acento-botones--borde.p-4(titulo="Componentes interiores")
        .row.align-items-center
          .col-sm-12.col-md-7.col-lg-7.p-5
            h4 Componentes interiores
            p Todos aquellos elementos y/o partes que van en el interior o revés de la prenda, estos pueden ser:
            ol.lista-ol--cuadro.fa-ol
              li 
                .lista-ol--cuadro__vineta.bgamarillo
                  span 1 
                | Foro.
              li 
                .lista-ol--cuadro__vineta.bgamarillo
                  span 2 
                | Entretela.
              li 
                .lista-ol--cuadro__vineta.bgamarillo
                  span 3
                | Guata.
              li 
                .lista-ol--cuadro__vineta.bgamarillo
                  span 4
                | Sesgo.
          .col-8.col-md-4.col-lg-4
            img.mt-5.mb-5(src="@/assets/curso/temas/tema2/imagen6.png", alt="La imagen expone los componentes interiores de una prenda, que incluyen el forro, la entretela, la guata y el sesgo. Estos elementos son las partes que se encuentran en el interior o el revés de la prenda. ")
      .tarjeta.color-acento-botones--borde.p-4(titulo="Hilos")
        .row.align-items-center
          .col-sm-12.col-md-7.col-lg-7.p-5
            h4 Hilos
            p Son uno de los elementos principales que logran unir las diferentes partes de la prenda.
            ol.lista-ol--cuadro.fa-ol
              li 
                .lista-ol--cuadro__vineta.bgamarillo
                  span 1 
                | Pespuntes.
              li 
                .lista-ol--cuadro__vineta.bgamarillo
                  span 2 
                | Puntadas decorativas.
              li 
                .lista-ol--cuadro__vineta.bgamarillo
                  span 3
                | Bastas.
              li 
                .lista-ol--cuadro__vineta.bgamarillo
                  span 4
                | Puntadas manuales.
          .col-8.col-md-4.col-lg-4.col-4
            img(src="@/assets/curso/temas/tema2/imagen7.png", alt="La imagen destaca el uso de hilos en la confección de prendas, indicando que son esenciales para unir las diferentes partes. Se exponen ejemplos de pespuntes, puntadas decorativas, bastas y puntadas manuales, que son los tipos principales de costuras utilizados en la creación de ropa. ")

    .row.justify-content-center.mt-4(data-aos="zoom-in-left")
      .col-sm-12.col-md-12.col-lg-3.mt-5
        h3.mb-4 Fornituras y complementos
        p Las fornituras son el conjunto de accesorios y adornos que puede llevar una prenda de vestir. Dentro de ellos se identifican: los botones, las cremalleras, corchetes, broches de presión, hebillas, ojetes, vivos, puntillas, cintas, apliques, gomas, cordones, etc.
      .col-12.col-md-12.col-lg-9.mb-5.mt-5
        img(src="@/assets/curso/temas/tema2/imagen8.png", alt="La imagen exponen tres prendas de vestir modernas y detalladas. A la izquierda, hay una chaqueta verde con múltiples bolsillos y detalles en negro, incluyendo correas y cremalleras. En el centro, se presenta un conjunto rojo ajustado con un diseño de cremallera frontal y recortes decorativos. A la derecha, se ve una chaqueta negra con pespuntes contrastantes en color marrón y botones grandes, destacando un estilo estructurado y moderno. ")


    .row.justify-content-center.mt-4.mb-4(style="background-color: #E8DDFF")(data-aos="zoom-in-left")
      .col-7.col-md-5.col-lg-5
        img.mt-5.mb-5(src="@/assets/curso/temas/tema2/imagen9.svg", alt="La imagen expone los patrones de tela recortados para ensamblar una chaqueta. Los patrones incluyen piezas para las mangas, el cuello, los puños y otras partes esenciales del diseño. En una esquina, se presenta una imagen pequeña de la chaqueta completa, indicando cómo se ensamblan las piezas para formar la prenda final.")
      .col-sm-12.col-md-12.col-lg-3
        h3.mt-5 Identificación de piezas
        p Cada prenda está compuesta por piezas que tienen un nombre específico de acuerdo con la ubicación. Cada pieza tiene especificaciones técnicas de acuerdo con el proceso de extendido y corte del textil.
        
    .row.justify-content-center.mt-4.mb-4
      h3.mt-4 Reconocimiento de las partes que conforman una prenda de vestir

    .tarjeta.tarjeta--azul.p-4.mb-4.borde-redondo(style="background-color: #F8F5FF")(data-aos="zoom-in-left")
      SlyderA(tipo="b")
        .row.justify-content-center.my-lg-4
          .col-12.mb-4.mb-md-0
            img.p-3(src="@/assets/curso/temas/tema2/tarjeta1/imagen1.svg", alt='La imagen expone un esquema técnico de un pantalón, con anotaciones que identifican sus distintas partes. Estas incluyen: pretina, pasador, vista delantera, bolsillo lateral, delantero, línea de quiebre, entrepierna, bota, sistema de cierre (aletilla o aletillón), tiro delantero, bolsillo de ribete doble, tiro posterior y posterior. Cada componente está claramente señalado para resaltar su ubicación y función en el diseño del pantalón. ')
        .row.justify-content-center.my-lg-4
          .col-12.mb-4.mb-md-0
            img.p-3(src="@/assets/curso/temas/tema2/tarjeta1/imagen2.svg", alt='La imagen describe un esquema técnico de un pantalón, con anotaciones que identifican sus distintas partes. Las partes señaladas incluyen: pretina, pasador, vista delantera, bolsillo monedero, tiro delantero, delantero, entrepierna, bota, sistema de cierre (aletilla o aletillón), cotilla o canesú, bolsillo de parche, tiro posterior y posterior. Cada componente está claramente etiquetado para mostrar su ubicación y función en el diseño del pantalón. ')
        .row.justify-content-center.my-lg-4
          .col-12.mb-4.mb-md-0
            img.p-3(src="@/assets/curso/temas/tema2/tarjeta1/imagen3.svg", alt='La imagen presenta un esquema técnico de un pantalón deportivo, con anotaciones que identifican sus distintas partes. Las partes señaladas incluyen: sistema de cierre acordonado, bolsillo lateral, tiro delantero, delantero, entrepierna, bota encauchada, corte lateral, pretina acordonada o encauchada, tiro posterior y posterior. Cada componente está claramente etiquetado para exponer su ubicación y función en el diseño del pantalón deportivo.')
    br

    TabsA.color-acento-botones(data-aos="zoom-in-left")
      .tarjeta.color-acento-botones--borde.p-4(titulo="Despiece pantalón")
        h4 Despiece pantalón
        img(src="@/assets/curso/temas/tema2/tarjeta2/imagen1.svg", alt='La imagen presenta el despiece de un pantalón, ilustrando todos los patrones necesarios para su confección. Incluye imágenes de las técnicas del pantalón terminado, así como las piezas individuales del patrón, como las piernas, bolsillos, cintura y otras partes. Cada pieza del patrón está detallada con marcas y anotaciones que facilitan su ensamblaje. ')
      .tarjeta.color-acento-botones--borde.p-4(titulo="Despiece cargo")
        h4 Despiece cargo
        img(src="@/assets/curso/temas/tema2/tarjeta2/imagen2.svg", alt='La imagen detalla el despiece de un pantalón cargo. Incluye técnicas del pantalón terminado, con detalles como bolsillos laterales y un sistema de cierre acordonado. A la derecha, se presentan las piezas individuales del patrón necesarias para su confección, cada una con anotaciones y marcas para guiar el ensamblaje. ')
      .tarjeta.color-acento-botones--borde.p-4(titulo="Despiece de camisa")
        h4 Despiece de camisa
        img(src="@/assets/curso/temas/tema2/tarjeta2/imagen3.svg", alt='La imagen expone el despiece de una camisa. Incluye una vista técnica de la camisa terminada y los patrones necesarios para su confección. Las piezas del patrón incluyen partes como las mangas, el delantero, la espalda, el cuello y los puños, cada una con sus respectivas anotaciones y marcas para facilitar el ensamblaje.')
      .tarjeta.color-acento-botones--borde.p-4(titulo="Despiece de blusa")
        h4 Despiece de blusa
        img(src="@/assets/curso/temas/tema2/tarjeta2/imagen4.svg", alt='La imagen detalla el despiece de una blusa. Incluye vistas técnicas de la blusa terminada y los patrones necesarios para su confección. Las piezas del patrón abarcan partes como el delantero, la espalda, las mangas y el cuello, cada una con anotaciones y marcas detalladas para guiar el ensamblaje de la prenda.')
      .tarjeta.color-acento-botones--borde.p-4(titulo="Despiece de chaqueta")
        h4 Despiece de chaqueta
        img(src="@/assets/curso/temas/tema2/tarjeta2/imagen5.svg", alt='La imagen expone el despiece de una chaqueta. Incluye técnicas de la chaqueta terminada y los patrones necesarios para su confección. Las piezas del patrón abarcan partes como las mangas, el delantero, la espalda, el cuello y otros detalles, cada una con anotaciones y marcas específicas para facilitar el ensamblaje de la prenda.')

    Separador    
    .row.mb-4
      #t_2_2.titulo-segundo.color-primario
        h2 2.2  Concepto de trazo y corte

    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-md-10.col-lg-10
        .tarjeta.color-acento-botones.borde-redondo
          .row.justify-content-around.align-items-center
            .col-5.col-md-4.col-lg-2
              img.mt-4.mb-4.ps-5(src="@/assets/curso/temas/tema2/admiracion.png")
            .col-sm-12.col-md-8.col-lg-10
              p.p-3.mb-0 #[b Trazo y corte ]
              p.ps-3 En el proceso de trazo y corte se revisa y analiza el mejor aprovechamiento de los tejidos mediante técnicas de marcadas, dependiendo en gran parte, de la calidad de la confección de la prenda; por tal motivo, constituye una tarea determinante en el costo total del producto.

    .subt(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/temas/subt.svg', alt='')
        h3.mb-0.ms-2 ¿Qué es el trazo?
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-md-12.col-lg-12
        .row.align-items-center.justify-content-center
          .col-sm-12.col-md-12.col-lg-9
            p.mb-4 Procedimiento que se realiza sobre el material textil con jaboncillo o tiza, teniendo en cuenta las características dimensionales del tejido a cortar.
            .row.justify-content-center.p-4
              .col-5.col-md.col-lg
                img(src="@/assets/curso/temas/tema2/iconosv/icono1.svg", alt='Diseñadora')
                p.text-center Patrones
              .col-5.col-md.col-lg
                img(src="@/assets/curso/temas/tema2/iconosv/icono2.svg", alt='Diseñadora')
                p.mb-0.text-center Escuadras o reglas
              .col-5.col-md.col-lg
                img(src="@/assets/curso/temas/tema2/iconosv/icono3.svg", alt='Diseñadora')
                p.mb-0.text-center Papel de trazo
              .col-5.col-md.col-lg
                img(src="@/assets/curso/temas/tema2/iconosv/icono4.svg", alt='Diseñadora')
                p.text-center Lápices
              .col-5.col-md.col-lg
                img(src="@/assets/curso/temas/tema2/iconosv/icono5.svg", alt='Diseñadora')
                p.text-center Metro
              .col-5.col-md.col-md
                img(src="@/assets/curso/temas/tema2/iconosv/icono6.svg", alt='Diseñadora')
                p.mb-0.text-center Jaboncillo de tiza
              .col-5.col-md.col-lg
                img(src="@/assets/curso/temas/tema2/iconosv/icono7.svg", alt='Diseñadora')
                p.text-center Mesa
          .col-7.col-md-5.col-lg-3
            img(src="@/assets/curso/temas/tema2/imagen10.svg", alt='Diseñadora')

  
    .row.mt-4.mb-4
      p La marcación de las piezas que componen la prenda, sea manual o asistida por computador, requiere la adecuada distribución de los patrones sobre la extensión de la tela. El trazo se debe realizar por cada material, por ejemplo:
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-lg-10
        .row.justify-content-between.align-items-center
          .col-sm-12.col-md-3.col-lg-3
            .tarjeta.bgamarilloclaro.p-4.borde-redondo
              .row.justify-content-center.mb-3
                .col-sm-4.col-md-10.col-lg-8
                  img(src="@/assets/curso/temas/tema2/tar14/t1.svg", alt='Diseñadora')
                h3.text-center.mb-3 Trazos en tela
          .col-sm-12.col-md-3.col-lg-3
            .tarjeta.bgamarilloclaro.p-4.borde-redondo
              .row.justify-content-center.mb-3
                .col-sm-4.col-md-10.col-lg-8
                  img(src="@/assets/curso/temas/tema2/tar14/t2.svg", alt='Diseñadora')
                h3.text-center.mb-3 Forro
          .col-sm-12.col-md-3.col-lg-3
            .tarjeta.bgamarilloclaro.p-4.borde-redondo
              .row.justify-content-center.mb-3
                .col-sm-4.col-md-10.col-lg-8
                  img(src="@/assets/curso/temas/tema2/tar14/t3.svg", alt='Diseñadora')
                h3.text-center.mb-3 Entretelas

    .row.justify-content-center.mt-4.mb-4(data-aos="zoom-in-left")
      .col-sm-12.col-md-10.col-lg-10
        .cajon.color-primario 
          p.p-5.mb-0 #[b  Se debe tener en cuenta cantidades y tallas según orden de corte. En el caso del corte troquelado se realiza mediante el uso de plantillas colocadas a presión y se procede a cortar.  ]

    Separador
    .subt(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/temas/subt.svg', alt='')
        h3.mb-0.ms-2 ¿Qué es el corte?

    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-md-7.col-lg-6
        p.mt-2 El corte se define como el proceso de transformación de la materia prima textil (tejido o tela) en piezas útiles para confeccionar prendas de vestir, este proceso de transformación se realiza utilizando máquinas especializadas de corte o con tijeras convencionales.
        p Para obtener excelentes resultados en el proceso de corte se requiere de:
        ul.lista-ul--color.fa-ul.color-primario.ps-1
          li 
            i.fas.fa-plus
            | Maquina de corte o tijeras convencionales.
          li
            i.fas.fa-plus
            | Otras herramientas.
      .col-8.col-md-5.col-lg-4
        img(src="@/assets/curso/temas/tema2/imagen13.svg", alt='Diseño')

    .subt(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/temas/subt.svg', alt='')
        h3.mb-0.ms-2 Tipos de corte
    
    .row.mt-4.mb-4(data-aos="zoom-in-left")
      .col-sm-12.col-md-7.col-lg-7
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Manual")
            .col-md-12.mb-4.mb-md-0
              p Requiere la utilización de tijeras más o menos de 8 pulgadas, usadas solo para corte de tela; se colocan directamente los moldes y se procede a cortar.
          .row(numero="2" titulo="Convencional")
            .col-md-12.mb-4.mb-md-0
              p Utiliza maquinaria y equipos electromecánicos, disminuyendo la intervención de operaciones manuales.  
          .row(numero="3" titulo="Automático")
            .col-md-12.mb-4.mb-md-0
              p Comprende mesa, unidad de control conformado por el ordenador con  #[em software ] especializado, cabezal de corte y carro extendedor automático, permitiendo optimizar el espacio y tiempos de corte. 
      .col-8.col-md-4.col-lg-4
        img.p-2(src="@/assets/curso/temas/tema2/imagen14.svg", alt='Modista cortando')

    Separador 
    .subt.mb-5(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/temas/subt.svg', alt='')
        h3.mb-0.ms-2 Herramientas

    .row.justify-content-center.align-items-center.mb-5.mt-5(data-aos="zoom-in-left")
      .col-sm-12
        SlyderF(columnas="col-lg-6 col-xl-4")
          .tarjeta.bgmoradoclaro.p-4.borde-redondo
            .row.justify-content-center.mb-3
              .col-8
                img.p-4(src="@/assets/curso/temas/tema2/tarjeta3/imagen1.svg" alt="La figura describe una sección titulada “Herramientas” que contiene iconos representados en cuadros morados. Cada cuadro tiene un ícono central con un texto descriptivo debajo. El primer ícono es de “Patrones” y describe un molde de ropa, el segundo ícono es de “Reglas” y  un triángulo con una regla, el tercer ícono es de “Metro” que expone una cinta métrica enrollada. El cuarto ícono es de “Jaboncillo o tizas” y expone dos tizas, el quinto ícono es de “Papel trazo” y un rollo de papel, y por último el sexto ícono es de “Mesa de corte” que presenta una mesa.")
            p.text-center #[b Patrones ]
          .tarjeta.bgmoradoclaro.p-4.borde-redondo
            .row.justify-content-center.mb-3
              .col-8
                img.p-4(src="@/assets/curso/temas/tema2/tarjeta3/imagen2.svg" alt="La figura describe una sección titulada “Herramientas” que contiene iconos representados en cuadros morados. Cada cuadro tiene un ícono central con un texto descriptivo debajo. El primer ícono es de “Patrones” y describe un molde de ropa, el segundo ícono es de “Reglas” y  un triángulo con una regla, el tercer ícono es de “Metro” que expone una cinta métrica enrollada. El cuarto ícono es de “Jaboncillo o tizas” y expone dos tizas, el quinto ícono es de “Papel trazo” y un rollo de papel, y por último el sexto ícono es de “Mesa de corte” que presenta una mesa.")
            p.text-center #[b Reglas ]
          .tarjeta.bgmoradoclaro.p-4.borde-redondo
            .row.justify-content-center.mb-3
              .col-8
                img.p-4(src="@/assets/curso/temas/tema2/tarjeta3/imagen3.svg" alt="La figura describe una sección titulada “Herramientas” que contiene iconos representados en cuadros morados. Cada cuadro tiene un ícono central con un texto descriptivo debajo. El primer ícono es de “Patrones” y describe un molde de ropa, el segundo ícono es de “Reglas” y  un triángulo con una regla, el tercer ícono es de “Metro” que expone una cinta métrica enrollada. El cuarto ícono es de “Jaboncillo o tizas” y expone dos tizas, el quinto ícono es de “Papel trazo” y un rollo de papel, y por último el sexto ícono es de “Mesa de corte” que presenta una mesa.")
            p.text-center #[b Metro ]
          .tarjeta.bgmoradoclaro.p-4.borde-redondo
            .row.justify-content-center.mb-3
              .col-8
                img.p-4(src="@/assets/curso/temas/tema2/tarjeta3/imagen4.svg" alt="La figura describe una sección titulada “Herramientas” que contiene iconos representados en cuadros morados. Cada cuadro tiene un ícono central con un texto descriptivo debajo. El primer ícono es de “Patrones” y describe un molde de ropa, el segundo ícono es de “Reglas” y  un triángulo con una regla, el tercer ícono es de “Metro” que expone una cinta métrica enrollada. El cuarto ícono es de “Jaboncillo o tizas” y expone dos tizas, el quinto ícono es de “Papel trazo” y un rollo de papel, y por último el sexto ícono es de “Mesa de corte” que presenta una mesa.")
            p.text-center #[b Jaboncillo o tizas ]
          .tarjeta.bgmoradoclaro.p-4.borde-redondo
            .row.justify-content-center.mb-3
              .col-8
                img.p-4(src="@/assets/curso/temas/tema2/tarjeta3/imagen5.svg" alt="La figura describe una sección titulada “Herramientas” que contiene iconos representados en cuadros morados. Cada cuadro tiene un ícono central con un texto descriptivo debajo. El primer ícono es de “Patrones” y describe un molde de ropa, el segundo ícono es de “Reglas” y  un triángulo con una regla, el tercer ícono es de “Metro” que expone una cinta métrica enrollada. El cuarto ícono es de “Jaboncillo o tizas” y expone dos tizas, el quinto ícono es de “Papel trazo” y un rollo de papel, y por último el sexto ícono es de “Mesa de corte” que presenta una mesa.")
            p.text-center #[b Papel trazo ]
          .tarjeta.bgmoradoclaro.p-4.borde-redondo
            .row.justify-content-center.mb-3
              .col-8
                img.p-4(src="@/assets/curso/temas/tema2/tarjeta3/imagen6.svg" alt="La figura describe una sección titulada “Herramientas” que contiene iconos representados en cuadros morados. Cada cuadro tiene un ícono central con un texto descriptivo debajo. El primer ícono es de “Patrones” y describe un molde de ropa, el segundo ícono es de “Reglas” y  un triángulo con una regla, el tercer ícono es de “Metro” que expone una cinta métrica enrollada. El cuarto ícono es de “Jaboncillo o tizas” y expone dos tizas, el quinto ícono es de “Papel trazo” y un rollo de papel, y por último el sexto ícono es de “Mesa de corte” que presenta una mesa.")
            p.text-center #[b Mesa de corte ]

    .subt.mb-5.mt-5(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/temas/subt.svg', alt='')
        h3.mb-0.ms-2 Máquinas de corte industrial

    .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
      .col-sm-12.col-md-10.col-lg-10
        .row.p-2
          .col-sm-12.col-md-6.col-lg-4
            .tajeta.bgamarilloclaro.borde-redondo.p-2
              img.mb-0(src='@/assets/curso/temas/tema2/tar15/imagen1.png', alt='La imagen presenta varias cortadoras utilizadas en la confección textil, incluyendo una cortadora automática, una cortadora sin fin, una cortadora vertical, una cortadora circular y una cortadora de mano. Además, expone un guante de malla que se utiliza como equipo de seguridad al manejar estas herramientas de corte. ')
              p.text-center #[b Cortadora automática ] 
          .col-sm-12.col-md-6.col-lg-4
            .tajeta.bgamarilloclaro.borde-redondo.p-2
              img.mb-0(src='@/assets/curso/temas/tema2/tar15/imagen2.png', alt='La imagen presenta varias cortadoras utilizadas en la confección textil, incluyendo una cortadora automática, una cortadora sin fin, una cortadora vertical, una cortadora circular y una cortadora de mano. Además, muestra un guante de malla que se utiliza como equipo de seguridad al manejar estas herramientas de corte.')
              p.text-center #[b Cortadora sin fin ]
          .col-sm-12.col-md-6.col-lg-4
            .tajeta.bgamarilloclaro.borde-redondo.p-2
              img.mb-0(src='@/assets/curso/temas/tema2/tar15/imagen3.png', alt='La imagen presenta varias cortadoras utilizadas en la confección textil, incluyendo una cortadora automática, una cortadora sin fin, una cortadora vertical, una cortadora circular y una cortadora de mano. Además, muestra un guante de malla que se utiliza como equipo de seguridad al manejar estas herramientas de corte.')
              p.text-center #[b Cortadora vertical ]
        .row.p-2
          .col-sm-12.col-md-6.col-lg-4
            .tajeta.bgamarilloclaro.borde-redondo.p-2
              img.mb-0(src='@/assets/curso/temas/tema2/tar15/imagen4.png', alt='La imagen presenta varias cortadoras utilizadas en la confección textil, incluyendo una cortadora automática, una cortadora sin fin, una cortadora vertical, una cortadora circular y una cortadora de mano. Además, muestra un guante de malla que se utiliza como equipo de seguridad al manejar estas herramientas de corte.')
              p.text-center #[b Cortadora circular ]
          .col-sm-12.col-md-6.col-lg-4
            .tajeta.bgamarilloclaro.borde-redondo.p-2
              img.mb-0(src='@/assets/curso/temas/tema2/tar15/imagen5.png', alt='La imagen presenta varias cortadoras utilizadas en la confección textil, incluyendo una cortadora automática, una cortadora sin fin, una cortadora vertical, una cortadora circular y una cortadora de mano. Además, muestra un guante de malla que se utiliza como equipo de seguridad al manejar estas herramientas de corte.')
              p.text-center #[b  Cortadora de mano  ]
          .col-sm-12.col-md-6.col-lg-4
            .tajeta.bgamarilloclaro.borde-redondo.p-2
              img.mb-0(src='@/assets/curso/temas/tema2/tar15/imagen6.png', alt='La imagen presenta varias cortadoras utilizadas en la confección textil, incluyendo una cortadora automática, una cortadora sin fin, una cortadora vertical, una cortadora circular y una cortadora de mano. Además, muestra un guante de malla que se utiliza como equipo de seguridad al manejar estas herramientas de corte.')
              p.text-center #[b  Guante malla  ]

    Separador 

    .subt.mb-5(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/temas/subt.svg', alt='')
        h3.mb-0.ms-2 Otras herramientas

    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-md-8.col-lg-8
        .row
          .col-sm-12.col-md-6.col-lg-3
            .tajeta.bgamarilloclaro.borde-redondo
              img.mb-0(src='@/assets/curso/temas/tema2/tar15/imagen7.png', alt='La imagen describe herramientas esenciales para la confección textil, incluyendo tijeras, un punzón, una máquina perforadora y agujas o alfileres para la sujeción del textil. Cada herramienta está ilustrada con su respectiva etiqueta, indicando su uso específico en el proceso de confección. ')
              p.text-center.p-2 #[b Tijeras ]
          .col-sm-12.col-md-6.col-lg-3
            .tajeta.bgamarilloclaro.borde-redondo
              img.mb-0(src='@/assets/curso/temas/tema2/tar15/imagen8.png', alt='La imagen describe herramientas esenciales para la confección textil, incluyendo tijeras, un punzón, una máquina perforadora y agujas o alfileres para la sujeción del textil. Cada herramienta está ilustrada con su respectiva etiqueta, indicando su uso específico en el proceso de confección.')
              p.text-center.p-2 #[b Punzón ]
          .col-sm-12.col-md-6.col-lg-3
            .tajeta.bgamarilloclaro.borde-redondo
              img.mb-0(src='@/assets/curso/temas/tema2/tar15/imagen9.png', alt='La imagen describe herramientas esenciales para la confección textil, incluyendo tijeras, un punzón, una máquina perforadora y agujas o alfileres para la sujeción del textil. Cada herramienta está ilustrada con su respectiva etiqueta, indicando su uso específico en el proceso de confección. ')
              p.text-center.p-2 #[b Máquina perforadora ]
          .col-sm-12.col-md-6.col-lg-3
            .tajeta.bgamarilloclaro.borde-redondo
              img.mb-0(src='@/assets/curso/temas/tema2/tar15/imagen10.png', alt='La imagen describe herramientas esenciales para la confección textil, incluyendo tijeras, un punzón, una máquina perforadora y agujas o alfileres para la sujeción del textil. Cada herramienta está ilustrada con su respectiva etiqueta, indicando su uso específico en el proceso de confección.')
              p.text-center #[b Agujas o alfileres para sujeción del textil ]

    AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--grisos")(data-aos="zoom-in-left")
      .row(titulo="Urdimbre y trama")
        .col-md-7.mb-4.mb-md-0
          p.ps-5.p-3 #[b Urdimbre: ] la serie longitudinal de los hilos recibe el nombre de urdimbre, y cada uno de los elementos que la constituyen se denomina hilo. Los hilos verticales son la urdimbre.
          p.ps-5.p-3 #[b Trama: ] la serie transversal recibe el nombre de trama, y cada una de sus unidades se denomina pasada. Las pasadas horizontales son la trama.
        .col-md-3
            img(src='@/assets/curso/temas/tema2/imagen17.png', alt='La imagen expone un diagrama de un tejido con indicaciones de los componentes principales. La “Urdimbre” está indicada con una flecha roja y corresponde a los hilos longitudinales que se mantienen tensos en un telar. La “Trama” está indicada con una flecha azul y corresponde a los hilos transversales que se entrelazan con la urdimbre. Debajo del diagrama principal, hay tres ilustraciones que describen diferentes patrones de entrelazado de hilos: a la izquierda se expone el esquema de la urdimbre, en el centro la forma en que se teje la trama, y a la derecha la combinación de ambos elementos en el tejido final.')
      .row(titulo="Hilo de tela")
        .col-md-7.mb-4.mb-md-0
          p.ps-5.p-3 El hilo de tela se conoce también como sentido de hilo, y se refiere a la dirección que siguen los hilos de urdimbre (longitudinal) y trama (transversal).
          p.ps-5.p-3 La línea que atraviesa la urdimbre y la trama en sentido diagonal es conocida con el nombre de sesgo o bies.
        .col-md-3
          img(src="@/assets/curso/temas/tema2/imagen18.png" alt="La imagen describe  tres piezas de un patrón de costura sobre un fondo de tela con puntos. Cada pieza del patrón tiene flechas rojas indicando la dirección del hilo de la tela. La pieza a la izquierda es de forma irregular, probablemente una manga, con las flechas indicando la dirección del hilo paralelo al borde inferior. Las otras dos piezas, que parecen ser partes del cuerpo de una prenda, también tienen flechas indicando la dirección del hilo a lo largo del largo de las piezas. Cada pieza del patrón tiene un pequeño rectángulo blanco en el centro, que es una etiqueta o una marca de referencia." )
      .row(titulo="Sesgo o bies")
        .col-md-6.mb-4.mb-md-0
          p.ps-5.p-3 Se llama sesgo o bies al sentido diagonal de las telas en un ángulo de 45° grados; diagonal o al sesgo aporta mejor caída y cierta elasticidad. En algunos casos es necesario cortar las piezas de una prenda al sesgo debido a su diseño.
        .col-md-5
          img(src="@/assets/curso/temas/tema2/imagen19.png" alt="La imagen ilustra la orientación de los patrones en la tela, mostrando las direcciones del recto hilo, el contrahílo y el bies. A la izquierda, se presenta un cuadrado de tela con las direcciones señaladas. A la derecha, se muestra cómo colocar los patrones en la tela, alineándolos según el recto hilo y el centro del pliegue para asegurar un corte preciso y adecuado. " )
  
    Separador
    .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
      .col-sm-12.col-md-7.col-lg-7
        h3.text-center En el material textil
        img.mb-5(src="@/assets/curso/temas/tema2/imagen20.png" alt="La imagen describe dos rollos de material textil desenrollados parcialmente, ilustrando las direcciones del recto hilo, el contrahílo y el bies. En el rollo de la izquierda, se indican las direcciones con flechas y etiquetas, mostrando cómo identificar el sesgo o bies, el largo de la tela y el orillo o borde. En el rollo de la derecha, se repiten las indicaciones para el largo de la tela, el orillo y el sesgo o bies. Estas directrices son esenciales para cortar la tela correctamente y asegurar la orientación adecuada de las piezas del patrón. " )

    .subt.mb-5(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/temas/subt.svg', alt='')
        h3.mb-0.ms-2 Anchos de las telas
    p Los anchos de las telas que se pueden encontrar normalmente en los puntos de venta tienen diferentes medidas que suelen estar normalizados. Estos anchos vienen de fábrica y se dividen en:

    .row.mt-4.mb-4(data-aos="zoom-in-left")
      .col-sm-6.col-lg-3.mb-4.mb-lg-0
        .tarjeta--boton.color-adicional-2.p-4
          .row.justify-content-center.mb-3
            .col-7
              img(src="@/assets/curso/temas/tema2/tarjeta4/imagen1.png")
          h4.text-center Ancho simple
          p.text-center Están elaborados a partir de 70 cm a 90 cm de ancho, en este grupo se encuentran cambre, paños, fieltro, blonda, satén, lino, etc.
      .col-sm-6.col-lg-3.mb-4.mb-lg-0
        .tarjeta--boton.color-adicional-2.p-4
          .row.justify-content-center.mb-3
            .col-7
              img(src="@/assets/curso/temas/tema2/tarjeta4/imagen2.png") 
          h4.text-center Ancho angosto
          p.text-center Están elaborados a partir de 0,5 mm hasta 25 cm de ancho, en este grupo se encuentran los encajes, franjas, cintas, elásticos, etc.
      .col-sm-6.col-lg-3.mb-4.mb-sm-0
        .tarjeta--boton.color-adicional-2.p-4
          .row.justify-content-center.mb-3
            .col-7
              img(src="@/assets/curso/temas/tema2/tarjeta4/imagen3.png") 
          h4.text-center Ancho doble
          p.text-center Están elaborados a partir de 140 cm y 150 cm de ancho, en este grupo se encuentran paños, tafetán, popelina, crepé, entretelas, denim, etc.
      .col-sm-6.col-lg-3
        .tarjeta--boton.color-adicional-2.p-4
          .row.justify-content-center.mb-3
            .col-7
              img(src="@/assets/curso/temas/tema2/tarjeta4/imagen4.png") 
          h4.text-center Ancho especial
          p.text-center.mb-4.p-1 Están elaborados a partir de 2,80 cm, en este  grupo se encuentran la  tapicería y la decoración.
        
    .row.justify-content-center.mb-4.mt-5(data-aos="zoom-in-left")
      .col-sm-12.col-md-7.col-lg-3
        h3.mb-4.mt-4 Orillos de tela
        p.mb-2 Son los bordes longitudinales de la tela, están tejidos con una apariencia diferente y densa, como consecuencia de tratamientos de humectación y secado, que sufren una vez han sido tejidas para su estabilización.
      .col-10.col-md-5.col-lg-5
        img.p-2(src="@/assets/curso/temas/tema2/imagen21.png" alt="La figura describe dos imágenes de primeros planos de orillos de tela. El orillo es el borde terminado de la tela, que no se deshilacha. En la imagen a la izquierda, se observa un orillo blanco con texto impreso en color oscuro que parece ser parte del nombre de la empresa fabricante. La imagen a la derecha muestra varios orillos de diferentes telas, cada uno con colores y patrones distintos, además de texto impreso que incluye nombres de diseñadores, fabricantes y posiblemente información de copyright. Estos orillos muestran una variedad de colores y diseños, indicando la diversidad en la producción textil." )

    br
    .row.justify-content-center.mb-4.mt-4(data-aos="zoom-in-left")
      .col-sm-12.col-md-12.col-lg-10
        .tarjeta.color-acento-botones.borde-redondo
          .row.justify-content-around.align-items-center
            .col-6.col-md-3.col-lg-2
              img.mt-4.mb-4.ps-5(src="@/assets/curso/temas/tema2/admiracion.png")
            .col-sm-12.col-md-9.col-lg-10
              p.p-3.mb-0 #[b ¿Cómo surgen? ]
              p.ps-3 Los agujeritos de los orillos son realizados por unas plaquetas de agujas situadas en los laterales de los hornos encargados de secar las telas y que hacen que estas se mantengan sujetas y estiradas en su ancho durante todo el proceso. Suelen perforar el tejido desde el revés hacia el derecho, por lo que, por regla general, las rebabas de las perforaciones en los orillos indican el #[b derecho de la tela. ]


    .subt.mb-5.mt-5(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/temas/subt.svg', alt='')
        h3.mb-0.ms-2 Tipos de orillos
    p El propósito del orillo es que la tela no se deshilache. Según el diseño o fabricante los orillos de la tela se dividen en:
    
    .row.mt-4.mb-4(data-aos="zoom-in-left")
      .col-sm-12.col-md-7.col-lg-7
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Orillo metido")
            .col-md-12.mb-4.mb-md-0
              p Una aguja especial en forma de gancho impulsada por una leva, después de que esta se corta, la inserción del extremo del hilo retorna, formando así un borde fuerte. Este sistema es usado generalmente en las telas de peso ligero a medio.
          .row(numero="2" titulo="Orillo leno")
            .col-md-12.mb-4.mb-md-0
              p Estos orillos se obtienen uniendo la trama con fuertes hilos adicionales y eliminando mediante corte los extremos de la trama que sobresalen. Este sistema es usado generalmente en las telas de peso pesado.  
          .row(numero="3" titulo="Orillo de puntada cadeneta")
            .col-md-12.mb-4.mb-md-0
              p Este tipo de orillo se produce mayoritariamente en un mecanismo de tejido de punto, se realiza principalmente en una máquina de tejer por medio de agujas. 
          .row(numero="4" titulo="Orillos fusionados")
            .col-md-12.mb-4.mb-md-0
              p Se obtiene presionando unos elementos mecánicos calientes en el borde de la tela, este método se puede aplicar en textiles de fibras sintéticas. 
          .row(numero="5" titulo="Orillos lisos")
            .col-md-12.mb-4.mb-md-0
              p Este tipo de orillo también llamado orillo de estampación es usado para controlar los colores básicos que tiene el dibujo, enumerándolos en el orden de estampación, además añade la marca del fabricante. 
          .row(numero="6" titulo="Orillos de cinta")
            .col-md-12.mb-4.mb-md-0
              p Este tipo de orillo es utilizado por los fabricantes de textiles clásicos como paños, también tejen sus nombres en el orillo para que sean identificados fácilmente en las sastrerías a medida. 
      .col-8.col-md-4.col-lg-4
        img.p-3.mt-4(src="@/assets/curso/temas/tema2/imagen22.png", alt='telas')

    Separador    
    .row.mb-4
      #t_2_3.titulo-segundo.color-primario
        h2 2.3  Proceso de extendido

    .row.justify-content-center
      .col-md-10
        h3 ¿Qué es el extendido?
        p El tendido o extendido consiste en ubicar la tela sobre una superficie plana (mesa de corte), ya sea una capa de tela o varias según la orden de producción; se extiende la tela considerando las características del textil, se prepara y selecciona los materiales e instrumentos necesarios para la ejecución de la tarea; el extendido se puede realizar de dos formas: 

    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-md-6.col-lg-5      
        .tarjeta--boton.p-3(style="background-color: #FFF5D3")
          .row.align-items-center.justify-content-center
            .col-3
              img(src="@/assets/curso/temas/tema2/tarjeta5/imagen1.png") 
            .col-9
              h3.p-2.mb-0 Con carro extendedor
              p.ps-2.mb-0 Extendedora automática, extendedora de codo.
      .col-sm-12.col-md-6.col-lg-5      
        .tarjeta--boton.p-3(style="background-color: #FFF5D3")
          .row.align-items-center.justify-content-center
            .col-3
              img(src="@/assets/curso/temas/tema2/tarjeta5/imagen2.png") 
            .col-9
              h3.p-2.mb-0 Manual
              p.ps-2 Extendedora de carro o coche.

    .row.justify-content-center.align-items-center.mt-4.mb-4
      h3.mt-4.mb-4.text-center Herramientas
      .row.justify-content-center.align-items-center
        .col-sm-12.col-md-6.col-lg-3      
          .tarjeta--boton.p-3(style="background-color: #F4EDD4")
            img.p-3(src="@/assets/curso/temas/tema2/tar16/img1.png" alt="La imagen detalla tres herramientas utilizadas en la confección textil: pesas, pinzas y agujas o alfileres para sujeción textil. Estas herramientas son esenciales para asegurar y manipular las piezas de tela durante el proceso de corte y ensamblaje. ") 
            h3.text-center Pesas
        .col-sm-12.col-md-6.col-lg-3      
          .tarjeta--boton.p-3(style="background-color: #F4EDD4")
            img.p-3(src="@/assets/curso/temas/tema2/tar16/img2.png" alt="La imagen detalla tres herramientas utilizadas en la confección textil: pesas, pinzas y agujas o alfileres para sujeción textil. Estas herramientas son esenciales para asegurar y manipular las piezas de tela durante el proceso de corte y ensamblaje. ") 
            h3.text-center Pinzas
        .col-sm-12.col-md-6.col-lg-3      
          .tarjeta--boton.p-3(style="background-color: #F4EDD4")
            img.p-3(src="@/assets/curso/temas/tema2/tar16/img3.png" alt="La imagen detalla tres herramientas utilizadas en la confección textil: pesas, pinzas y agujas o alfileres para sujeción textil. Estas herramientas son esenciales para asegurar y manipular las piezas de tela durante el proceso de corte y ensamblaje. ") 
            h3.text-center.mb-0 Agujas o alfileres para sujeción textil.

    .row.justify-content-center.align-items-center.mt-5.mb-5.fondoespecial2(data-aos="zoom-in-left")
      .col-6.col-md-5.col-lg-3
        img.p-4(src="@/assets/curso/temas/tema2/imagen24.svg") 
      .col-sm-12.col-md-7.col-lg-7
        h3.ps-5.mb-5 Extendido manual
        p.ps-5.mb-0 En el extendido manual se sitúa la pieza de textil en un extremo de la mesa, mientras dos operarios efectúan el estirado de la tela (pueden también utilizar un carro de extendido) hasta el largo previamente establecido.

    .row.justify-content-center.align-items-center.mt-4.mb-4(data-aos="zoom-in-left")
      p.mt-4.mb-4 Recomendaciones:

    .row.justify-content-center.mt-4.mb-4(data-aos="zoom-in-left")
      .col-sm-12.col-md-8.col-lg-8
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Alineación")
            .col-md-12.mb-4.mb-md-0
              p Se recomienda que el textil se encuentre completamente alineado al orillo, de ser posible alinear los dos orillos.
          .row(numero="2" titulo="Tensión")
            .col-md-12.mb-4.mb-md-0
              p En lo posible evitar la tensión en la tela, ya que después del corte las piezas pueden quedar reducidas (pequeñas con relación al tamaño real del molde).  
          .row(numero="3" titulo="Arrugas")
            .col-md-12.mb-4.mb-md-0
              p Evitar que la tela se encuentre arrugada en el tendido para que no se formen burbujas de aire, que ocasionan distorsiones en el corte. 
          .row(numero="4" titulo="Consumo")
            .col-md-12.mb-4.mb-md-0
              p Cortar solamente lo necesario para evitar más consumo de tela, controlando el desperdicio de acuerdo con la acomodación de los moldes. 
      .col-6.col-md-4.col-lg-4
        img.p-3.mt-4(src="@/assets/curso/temas/tema2/imagen25.svg")

    .row.justify-content-center.align-items-center.mt-4.mb-4.borde-redondo.bgmoradoclaro(data-aos="zoom-in-left")
      .col-sm-6.col-md-5.col-lg-3
        img.p-3(src="@/assets/curso/temas/tema2/imagen26.svg") 
      .col-sm-12.col-md-7.col-lg-7
        h3.mt-4.mb-4 Preparación del textil
        p Algunos textiles se pueden encoger o aumentar después de ser sometidos al lavado o planchado, por tal motivo, se sugiere que antes de realizar cualquier proceso de extendido y corte, el textil sea sometido a lo siguiente:
        ul.lista-ul--color.fa-ul.color-primario
          li 
            i.fas.fa-plus
            | Pruebas de % de elongación o reducción.
          li
            i.fas.fa-plus
            | Pruebas de fusionado.
          li
            i.fas.fa-plus
            | Pruebas de fusionado.
          li
            i.fas.fa-plus
            | Lavado.
          li
            i.fas.fa-plus
            | Planchado.
          li
            i.fas.fa-plus
            | Identificación de defectos textiles.

    .row.mt-4.mb-4(data-aos="zoom-in-left")
      h3.mb-4 Disposición de la tela sobre la mesa
      p Extienda el textil sobre la mesa y defina el tipo de extendido de acuerdo con los patrones que desea trabajar: 

    .tarjeta.tarjeta--azul.p-4.mb-4.borde-redondo(style="background-color: #F8F5FF")(data-aos="zoom-in-left")
      SlyderA(tipo="b")
        .row.justify-content-center.my-lg-4
          p #[b Tendido abierto  ]
          .col-md-10
            img(src="@/assets/curso/temas/tema2/tarjeta6/imagen1.svg", alt='La imagen presenta cómo alinear y cortar patrones en la tela. A la izquierda, se ven patrones colocados sobre una tela, alineados con el recto hilo y el orillo de la tela para asegurar un corte preciso. A la derecha, se ilustra cómo una pieza del patrón debe estar alineada con el orillo de la tela para que salga completa y correctamente cortada. Las instrucciones enfatizan la importancia de seguir la dirección del recto hilo y el orillo para obtener un resultado adecuado. La imagen muestra cómo alinear y cortar patrones en la tela. A la izquierda, se ven patrones colocados sobre una tela, alineados con el recto hilo y el orillo de la tela para asegurar un corte preciso. A la derecha, se ilustra cómo una pieza del patrón debe estar alineada con el orillo de la tela para que salga completa y correctamente cortada. Las instrucciones enfatizan la importancia de seguir la dirección del recto hilo y el orillo para obtener un resultado adecuado. La imagen muestra cómo alinear y cortar patrones en la tela. A la izquierda, se ven patrones colocados sobre una tela, alineados con el recto hilo y el orillo de la tela para asegurar un corte preciso. A la derecha, se ilustra cómo una pieza del patrón debe estar alineada con el orillo de la tela para que salga completa y correctamente cortada. Las instrucciones enfatizan la importancia de seguir la dirección del recto hilo y el orillo para obtener un resultado adecuado. La imagen muestra cómo alinear y cortar patrones en la tela. A la izquierda, se ven patrones colocados sobre una tela, alineados con el recto hilo y el orillo de la tela para asegurar un corte preciso. A la derecha, se ilustra cómo una pieza del patrón debe estar alineada con el orillo de la tela para que salga completa y correctamente cortada. Las instrucciones enfatizan la importancia de seguir la dirección del recto hilo y el orillo para obtener un resultado adecuado. ')
        .row.justify-content-center.my-lg-4
          p #[b Tendido cerrado  ]
          .col-md-10
            img(src="@/assets/curso/temas/tema2/tarjeta6/imagen2.svg", alt='La imagen presenta cómo alinear y cortar patrones en la tela. A la izquierda, se ven patrones colocados sobre una tela, alineados con el recto hilo y el orillo de la tela para asegurar un corte preciso. A la derecha, se ilustra cómo una pieza del patrón debe estar alineada con el orillo de la tela para que salga completa y correctamente cortada. Las instrucciones enfatizan la importancia de seguir la dirección del recto hilo y el orillo para obtener un resultado adecuado.')

    .row.mt-4.mb-4(data-aos="zoom-in-left")
      h3.mb-4.mt-4 Extendido industrial
      p El proceso de extendido industrial se realiza a través del  #[em software ] especializado (CAD, sistemas de diseño asistido por computador: Optitex, Lectra, Audaces). Este proceso se realiza según las especificaciones de la orden de corte o ficha técnica. Los extendidos utilizados en la industria son:

    AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--purple")(data-aos="zoom-in-left")
      .row.borde-redondo-tmorada(titulo="Extendido cara arriba")
        .col-md-4.mb-4.mb-md-0
          p.p-5 La capa de tela se extiende según el largo del trazo, es importante determinar cuál es el derecho de la tela, ya que esta debe quedar mirando hacia arriba con respecto a la mesa. Se extiende la capa desde el inicio del trazo hasta el final del largo del trazo y se procede a cortar; nuevamente se desplaza la siguiente capa desde el inicio y se repite el proceso el número de veces que requiera las capas.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema2/tarjeta7/imagen1.svg" alt="La figura es un diagrama de varias capas de tela apiladas, indicando partes clave como el “Derecho de la tela” y el “Orillo”. Las flechas señalan la “Dirección de la tela” a lo largo de las capas, que están etiquetadas con “dirección del tejido” y “derecho del tejido”. Es crucial extender la capa de tela según el largo del trazo y determinar cuál es el derecho de la tela para asegurar que todas las piezas se corten en la misma orientación, manteniendo la consistencia en la apariencia y el comportamiento del tejido en la prenda final. ")
      .row.borde-redondo-tmorada(titulo="Extendido al lomo o doblez de tela")
        .col-md-4.mb-4.mb-md-0
          p.p-5 Se realiza cuando la tela se dobla a la mitad de su ancho, se une orillo con orillo formando un doblez de tela en un extremo, conocido como lomo. Al doblar la tela queda derecho con derecho, lo que se denomina careado o cara a cara. Este tipo de extendido se utiliza para cortar prototipos, es utilizado por modistas o sastres.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema2/tarjeta7/imagen2.svg" alt="La figura describe un diagrama en blanco y negro de varias capas de tela apiladas, indicando claramente el “Derecho de la tela”, el “Revés de la tela”, y el “Doblez de tela”. Las flechas señalan la “Dirección de la tela” y los “Orillos”, que son los bordes terminados. Cada capa está etiquetada con “dirección del tejido” y “derecho del tejido”. Es crucial extender la capa de tela según el largo del trazo y determinar cuál es el derecho de la tela para asegurar que todas las piezas se corten en la misma orientación, manteniendo la consistencia en la apariencia y el comportamiento del tejido en la prenda final. ")
      .row.borde-redondo-tmorada(titulo="Extendido cara a cara")
        .col-md-4.mb-4.mb-md-0
          p.p-5 La capa de tela se extiende según el largo del trazo, es importante determinar cuál es el derecho de la tela, ya que la primera capa debe quedar con el derecho hacia arriba con respecto a la mesa. Se extiende la capa desde el inicio del trazo hasta el final del largo del trazo y se procede a cortar.
          p.ps-5 Se repite el proceso con la siguiente capa, pero teniendo en cuenta que esta debe quedar con el derecho de tela hacia abajo, quedando cada a cara con la primera capa. Las siguientes capas deben quedar en pares, derecho con derecho de la tela.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema2/tarjeta7/imagen3.svg" alt="La figura describir un diagrama en blanco y negro de varias capas de tela apiladas, destacando el “Derecho de la tela” y el “Revés de la tela”. Las flechas indican la “Dirección de la tela” a lo largo de las capas. Cada capa está etiquetada con “dirección del tejido”, “derecho del tejido” y “revés del tejido”. Es crucial extender la capa de tela según el largo del trazo y determinar cuál es el derecho de la tela para asegurar que todas las piezas se corten en la misma orientación, manteniendo la consistencia en la apariencia y el comportamiento del tejido en la prenda final. ")
      .row.borde-redondo-tmorada(titulo="Extendido  <em>zigzag</em>")
        .col-md-4.mb-4.mb-md-0
          p.p-5 El proceso es igual al extendido cara a cara, la diferencia es que no se cortan los extremos. Una vez llegado al extremo dobla sobre sí mismo para hacer el recorrido en sentido contrario. De esta forma las capas de tela deben quedar pares cara con cara y revés con revés.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema2/tarjeta7/imagen4.svg" alt="La figura expone un diagrama en blanco y negro de varias capas de tela apiladas, destacando las etiquetas de “Derecho de la tela” y “Revés de la tela”. Las flechas indican la “Dirección de la tela” y señalan que las capas están dobladas, lo que también se señala con la etiqueta “doblez de tela” en una de las capas. Cada capa está etiquetada con “dirección del tejido”, “derecho del tejido” y “revés del tejido”. Es crucial extender la capa de tela según el largo del trazo y determinar cuál es el derecho de la tela para asegurar que todas las piezas se corten en la misma orientación, manteniendo la consistencia en la apariencia y el comportamiento del tejido en la prenda final. ")
      .row.borde-redondo-tmorada(titulo="Extendido escalonado o espiga")
        .col-md-4.mb-4.mb-md-0
          p.p-5 Es un extendido cara arriba en el que los largos de las capas de tela no son iguales. Las capas más largas se colocan debajo y las más cortas se colocan arriba formando un escalón, este tipo de extendido se emplea para ajustar en un solo trazo diferentes cantidades en relación con tallas y colores de prendas a cortar.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema2/tarjeta7/imagen5.svg" alt="Se exponen dos figuras relacionados con el apilamiento y corte de telas. En la parte superior, se expone un apilamiento de capas de tela, cada una etiquetada con dirección del tejido y derecho del tejido. En la parte inferior, se presenta un apilamiento de telas con patrones de corte dispuestos sobre ellas, listos para ser cortados. Los patrones están alineados y optimizados para el corte, asegurando que todas las piezas se corten de manera consistente y eficiente. Este proceso es crucial para mantener la orientación correcta del tejido y asegurar la calidad de las piezas finales.")

    Separador    
    .row
      #t_2_4.titulo-segundo.color-primario
        h2 2.4  Tipos de trazo
    
    .row.justify-content-center.align-items-center.mb-5
      h3.ps-5.mb-5 Tipos de trazo según requerimientos de patronaje:
      .col-sm-12.col-md-6.col-lg-3
        .tarjeta.color-acento-botones.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta8/imagen1.png" alt="La imagen describe una sección con tres cuadros, cada uno representando un aspecto del proceso de confección textil. El primer cuadro, con fondo amarillo, está titulado “Requerimientos desde patronaje” y muestra un diagrama de un patrón de costura. El segundo cuadro, con fondo morado, titulado “Tendido y marcación”, muestra manos trabajando sobre una tela con una herramienta de marcación. El tercer cuadro, también con fondo amarillo, titulado “Características del material”, muestra patrones colocados sobre una tela con puntos. Estos elementos indican los pasos importantes en la preparación y corte de la tela para confección. ")
          h4.text-center.mb-0 #[b Requerimientos desde patronaje. ]
      .col-sm-12.col-md-6.col-lg-3
        .tarjeta.color-primario.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta8/imagen2.png", alt="La imagen describe una sección con tres cuadros, cada uno representando un aspecto del proceso de confección textil. El primer cuadro, con fondo amarillo, está titulado “Requerimientos desde patronaje” y muestra un diagrama de un patrón de costura. El segundo cuadro, con fondo morado, titulado “Tendido y marcación”, muestra manos trabajando sobre una tela con una herramienta de marcación. El tercer cuadro, también con fondo amarillo, titulado “Características del material”, muestra patrones colocados sobre una tela con puntos. Estos elementos indican los pasos importantes en la preparación y corte de la tela para confección. ")
          h4.mb-4.text-center.color-white #[b Tendido y marcación. ]
      .col-sm-12.col-md-6.col-lg-3
        .tarjeta.color-acento-botones.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta8/imagen3.png", alt="La imagen describe una sección con tres cuadros, cada uno representando un aspecto del proceso de confección textil. El primer cuadro, con fondo amarillo, está titulado “Requerimientos desde patronaje” y muestra un diagrama de un patrón de costura. El segundo cuadro, con fondo morado, titulado “Tendido y marcación”, muestra manos trabajando sobre una tela con una herramienta de marcación. El tercer cuadro, también con fondo amarillo, titulado “Características del material”, muestra patrones colocados sobre una tela con puntos. Estos elementos indican los pasos importantes en la preparación y corte de la tela para confección. ")
          h4.text-center.mb-4 #[b Características del material. ]
    
    .row.justify-content-center.mb-4.mt-4
      .col-sm-12.col-md-7.col-lg-7
        h3.mb-4 Señalización
        p.mb-4 Para tener claro los requerimientos desde el área de patronaje es importante identificar y conocer la respectiva señalización de patrones:
        .row
          .col-sm-12.col-md-6.col-lg-6
            ul.lista-ul--color.fa-ul.color-primario
              li 
                i.fas.fa-plus
                span.mb-0 Hilo de tela.
              li
                i.fas.fa-plus
                span.mb-0 Referencia o diseño.
              li
                i.fas.fa-plus
                span.mb-0 Nombre de la pieza.
              li
                i.fas.fa-plus
                span.mb-0 Número de veces a cortar.
          .col-sm-12.col-md-6.col-lg-6
            ul.lista-ul--color.fa-ul.color-primario
              li 
                i.fas.fa-plus
                span.mb-0 Tipo de material.
              li
                i.fas.fa-plus
                span.mb-0 Número de pieza en el tendido.
              li
                i.fas.fa-plus
                span.mb-0 Piquetes.
              li
                i.fas.fa-plus
                span.mb-0 Plantilla.
      .col-8.col-md-5.col-lg-3
        img.p-3(src="@/assets/curso/temas/tema2/imagen27.svg")

    br
    .row.mb-4.mt-4
      h3.text-center Señalización - Hilos de tela
      p.text-center Para tener claro los requerimientos desde el área de patronaje es importante identificar y conocer la respectiva señalización de patrones:

    .row.justify-content-center.mt-4.mb-4(data-aos="zoom-in-left")
      .col-sm-12.col-md-6.col-lg-3
        .tarjeta.color-primario.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta9/imagen1.png", alt="La imagen describe tres cuadros explicativos sobre el tejido textil. El primero, titulado “Urdimbre”, ilustra los hilos longitudinales de la tela; el segundo, “Trama”, muestra los hilos transversales; y el tercero, “Sesgo o bies”, indica una tela cortada en un ángulo de 45 grados para mayor elasticidad. Debajo, una frase mnemotécnica ayuda a recordar la correcta orientación de los hilos: “Hilo de tela una cabeza hacia arriba, hilo de tela una cabeza hacia abajo, hilo de tela una cabeza doble”.")
          p.text-center #[b Urdimbre ]
      .col-sm-12.col-md-6.col-lg-3
        .tarjeta.color-acento-botones.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta9/imagen2.png", alt="La imagen describe tres cuadros explicativos sobre el tejido textil. El primero, titulado “Urdimbre”, ilustra los hilos longitudinales de la tela; el segundo, “Trama”, muestra los hilos transversales; y el tercero, “Sesgo o bies”, indica una tela cortada en un ángulo de 45 grados para mayor elasticidad. Debajo, una frase mnemotécnica ayuda a recordar la correcta orientación de los hilos: “Hilo de tela una cabeza hacia arriba, hilo de tela una cabeza hacia abajo, hilo de tela una cabeza doble”.")
          p.text-center.color-white #[b Trama ]
      .col-sm-12.col-md-6.col-lg-3
        .tarjeta.color-primario.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta9/imagen3.png", alt="La imagen describe tres cuadros explicativos sobre el tejido textil. El primero, titulado “Urdimbre”, ilustra los hilos longitudinales de la tela; el segundo, “Trama”, muestra los hilos transversales; y el tercero, “Sesgo o bies”, indica una tela cortada en un ángulo de 45 grados para mayor elasticidad. Debajo, una frase mnemotécnica ayuda a recordar la correcta orientación de los hilos: “Hilo de tela una cabeza hacia arriba, hilo de tela una cabeza hacia abajo, hilo de tela una cabeza doble”.")
          p.text-center #[b Sesgo o bies ]
      p.mb-4.mt-4.text-center Hilo de tela una cabeza hacia arriba, hilo de tela una cabeza hacia abajo, hilo de tela una cabeza doble.

    AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--grisos")(data-aos="zoom-in-left")
      .row(titulo="Trazo bidireccional, vello en ambos sentidos")
        .col-md-6.mb-4.mb-md-0
          p.ps-5 Este trazo/marcado se realiza cuando el hilo de tela tiene la cabeza doble; se pueden colocar los patrones en dos sentidos de dirección.
          p.ps-5 El material textil que se utilice no debe tener restricción con respecto a sus características.
          p.ps-5.mb-0 Hilo de tela una cabeza doble.
        .col-md-5
            img(src='@/assets/curso/temas/tema2/imagen28.png', alt='La imagen expone cómo posicionar patrones de una prenda en la tela, destacando la orientación del hilo de tela. Se exponen tres piezas del patrón con flechas rojas que indican la dirección del hilo. Las instrucciones resaltan la necesidad de colocar el hilo de la tela de una camisa hacia arriba o hacia abajo según corresponda, asegurando que todas las piezas se corten correctamente alineadas con el hilo para mantener la coherencia en el diseño final de la prenda. ')
      .row(titulo="Bidireccional, vello en ambos sentidos")
        .col-md-6.mb-4.mb-md-0
        .col-md-5
          img(src="@/assets/curso/temas/tema2/imagen29.png", alt="La imagen detalla la disposición de patrones en la tela, destacando la orientación correcta respecto al borde cortado y el orillo. En ambos ejemplos, las piezas del patrón están alineadas con flechas rojas que indican la dirección del hilo. A la izquierda, las piezas están colocadas cerca del orillo y el borde cortado, mientras que a la derecha, las piezas están alineadas con el orillo y el borde cortado de la tela, asegurando que las piezas se corten correctamente siguiendo la dirección del hilo para una confección precisa. ")
      .row(titulo="Trazo direccional, vello en un solo sentido")
        .col-md-9.mb-4.mb-md-0
          p.ps-5 Este trazo/marcado se realiza cuando el hilo de tela tiene la cabeza sea hacia arriba o hacia abajo; se deben colocar los patrones en un sentido de dirección. El procedimiento de marcado tendrá por resultado un producto con la más elevada calidad. Este tipo de trazo se usa para materiales que tienen restricción con respecto a sus características en cuanto a brillo, cambio de color al tacto, estampados, dirección de pelo/vello, entre otros.
          p.ps-5.mb-0 Hilo de tela una cabeza hacia arriba - Hilo de tela una cabeza hacia abajo
        .col-md-2
            img(src='@/assets/curso/temas/tema2/imagen30.png', alt='La imagen detalla dos piezas de un patrón de prenda, destacando la orientación del hilo de la tela. Una pieza tiene la flecha del hilo apuntando hacia arriba, indicando “hilo de tela una cabeza hacia arriba”, y la otra pieza tiene la flecha del hilo apuntando hacia abajo, indicando “hilo de tela una cabeza hacia abajo”. Estas instrucciones aseguran que las piezas del patrón se coloquen correctamente en la tela para mantener la consistencia del diseño y la estructura de la prenda.')
      .row(titulo="Direccional - vello en un solo sentido")
        .col-md-6.mb-4.mb-md-0
        .col-md-5
          img(src="@/assets/curso/temas/tema2/imagen31.png", alt="La imagen expone la colocación de patrones en la tela, destacando la dirección del hilo. A la izquierda, las piezas del patrón están alineadas con flechas rojas que apuntan hacia el orillo de la tela, marcadas como “fold” (dobladillo) y “selvage edge” (orillo). A la derecha, las piezas del patrón también están alineadas con flechas que indican la dirección del hilo y se colocan cerca del orillo y el borde cortado de la tela. Estas guías aseguran que las piezas se corten correctamente para mantener la estructura y el diseño adecuado de la prenda.")
      .row(titulo="Señalización")
        .col-md-8.mb-4.mb-md-0
          ul.lista-ul--color.fa-ul.color-primario
            li 
              i.fas.fa-plus
              span.mb-0 #[b Referencia o diseño:] ref:20201208.
            li
              i.fas.fa-plus
              span.mb-0 #[b Nombre de la pieza:] delantero o frente.
            li
              i.fas.fa-plus
              span.mb-0 #[b Número de veces a cortar o marcadas:] x 3 veces.
            li
              i.fas.fa-plus
              span.mb-0 #[b Tipo de material:] x 1 v material base   x 1 v material forro  x 1 v material entretela.
            li
              i.fas.fa-plus
              span.mb-0 #[b Número de pieza en el tendido:] 1/2.
        .col-md-3
            img(src='@/assets/curso/temas/tema2/imagen32.png', alt='La imagen detalla una pieza de patrón de una prenda, específicamente una camisa sin mangas, con una flecha roja que indica la dirección del hilo de tela desde arriba hacia abajo. Esto asegura que la pieza del patrón se alinee correctamente con el hilo de la tela durante el corte para mantener la integridad y el ajuste del diseño final de la prenda.')


    Separador    
    .row.mb-4.mt-4
      #t_2_5.titulo-segundo.color-primario
        h2 2.5  Tendido marcación y corte
      p El tendido y marcación son una parte clave para el proceso de corte, este procedimiento requiere de precisión y técnica. Una vez identificados los requerimientos desde el área de patronaje se procede a realizar el tendido y marcación, para ello es importante seguir los siguientes pasos:
     
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-3.mb-cus
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/uno.png')
          .tarjeta.color-primario.w-100.borde-redondo
            .p-4.text-center
              h4.text-center.mt-4.text-white Identificar el ancho útil
      .col-sm-12.col-lg-3.mb-cus
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/dos.png')
          .tarjeta.color-primario.w-100.borde-redondo
            .p-4.text-center
              h4.text-center.mt-4 Ubicación de patrones
      .col-sm-12.col-lg-3.mb-cus
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/tres.png')
          .tarjeta.color-primario.w-100.borde-redondo
            .p-4.text-center
              h4.text-center.mt-4 Marcación
      .col-sm-12.col-lg-3
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/cuatro.png')
          .tarjeta.color-primario.w-100.borde-redondo
            .p-4.text-center
              h4.text-center.mt-4  Corte

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12
        h3.mt-4.mb-4 Ancho útil
        p Es importante identificar el ancho útil del material textil antes de empezar a desarrollar el trazo; se sugiere lo siguiente:

    .tarjeta--container.row.mb-5
      .col-sm-12.col-md-6.col-lg-6.tarjeta.color-primario.p-5.h-card-ctl
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema2/boton1.png', alt='La imagen expone dos pasos para trabajar con textiles, cada uno ilustrado con una fotografía. En el primer paso, con fondo morado, se muestra a una persona identificando el ancho total del textil, con la instrucción “Identificar el ancho total del textil”. En el segundo paso, con fondo amarillo, se observa a la misma persona definiendo cuánto mide el orillo del textil, acompañado del texto “Definir cuánto mide el orillo”. Ambos pasos están enmarcados en círculos y resaltados con un contorno morado.')
        h4.text-center 1.	Identificar el ancho total del textil
      .col-sm-12.col-md-6.col-lg-6.tarjeta.color-acento-botones.p-5.h-card-ctl
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema2/boton2.png', alt='La imagen expone dos pasos para trabajar con textiles, cada uno ilustrado con una fotografía. En el primer paso, con fondo morado, se muestra a una persona identificando el ancho total del textil, con la instrucción “Identificar el ancho total del textil”. En el segundo paso, con fondo amarillo, se observa a la misma persona definiendo cuánto mide el orillo del textil, acompañado del texto “Definir cuánto mide el orillo”. Ambos pasos están enmarcados en círculos y resaltados con un contorno morado.')
        h4.text-center 2.	Definir cuánto mide el orillo

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8  
        p.mb-4.mt-4.text-center El ancho útil se halla restando al ancho total de la tela, el orillo.
        img(src="@/assets/curso/temas/tema2/imagen35.png" alt="La imagen ilustra cómo medir y demarcar el ancho útil de una pieza de tela. Se muestra que el ancho total de la tela es de 160 cm, con un orillo de 2 cm a cada lado, lo que reduce el ancho útil a 156 cm. Las instrucciones indican marcar el ancho útil con lápiz o tiza para asegurar que las piezas del patrón se corten dentro de estas dimensiones, manteniendo el orillo fuera del área de corte. Esta práctica es esencial para maximizar el uso de la tela y garantizar que las piezas cortadas tengan la anchura correcta. ")
  
    Separador 
    .row.justify-content-center.align-items-center
      .col-lg-12
        h3 Ubicar patrones
        p Una vez identificado, analizado y alistado:
    
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-3.mb-cus
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/uno.png')
          .tarjeta.color-primario.w-100.borde-redondo
            .p-4.text-center
              h4.text-center.mt-4.text-white Los requerimientos del patrón desde el área de patronaje
      .col-sm-12.col-lg-3.mb-cus
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/dos.png')
          .tarjeta.color-primario.w-100.borde-redondo
            .p-4.text-center
              h4.text-center.mt-4 El tipo de extendido/tendido a trabajar
      .col-sm-12.col-lg-3.mb-cus
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/tres.png')
          .tarjeta.color-primario.w-100.borde-redondo
            .p-4.text-center
              h4.text-center.mt-4 El ancho útil

    .row.justify-content-center.mt-4.mb-4
      p.text-center Se procede a hacer el trazo o marcación del molde o patrón en el textil.
      .col-sm-12.col-md-7.col-lg-7
        img.mt-4(src="@/assets/curso/temas/tema2/imagen37.png" alt="La imagen indica cómo colocar una pieza de patrón sobre la tela alineando correctamente el hilo de la tela. Se utilizan reglas para medir la distancia entre el hilo del patrón y el orillo de la tela, asegurando que sea igual a ambos lados (20 cm en este caso). Esto garantiza que la pieza del patrón esté correctamente alineada con el hilo de la tela, manteniendo la dirección del tejido consistente y evitando distorsiones en la prenda final. ")
    
    .row.mt-5.mb-3
      h3 ¿Cómo transferir patrones?

    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-3.mb-cus
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/uno.png')
          .tarjeta.color-primario.w-100.borde-redondo
            .p-4.text-center
              h4.text-center.mt-4.text-white Marcar con tiza o jabón
      .col-sm-12.col-lg-3.mb-cus
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/dos.png')
          .tarjeta.color-primario.w-100.borde-redondo
            .p-4.text-center
              h4.text-center.mt-4 Pinar o alfileres
      .col-sm-12.col-lg-3.mb-cus
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/tres.png')
          .tarjeta.color-primario.w-100.borde-redondo
            .p-4.text-center
              h4.text-center.mt-4 Pesas para sujetar

    Separador 
    .row.mt-4.mb-4
      h3 Tipos de marcación 
      p Para transferir patrones al textil existen dos formas que son las más implementadas.

    SlyderF(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in-left")
      .tarjeta.color-acento-contenido.p-4.borde-redondo
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta10/imagen1.png" alt="La imagen describe una serie de tarjetas con iconos e inscripciones en español, representando diferentes herramientas o suministros. De izquierda a derecha, las tarjetas muestran los siguientes elementos: una “Tiza de cal” , “Jabón regular” (una barra de jabón), “Lápiz tela” (un lápiz marcador para tela), un “Marcador tela” (un rotulador para tela), “Rodaja” (una rueda pequeña), y “Papel oxido o calco” ( papel de calco para transferir imágenes).")
        p.text-center #[b Tiza de cal ]
      .tarjeta.color-acento-contenido.p-4.borde-redondo
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta10/imagen2.png" alt="La imagen describe una serie de tarjetas con iconos e inscripciones en español, representando diferentes herramientas o suministros. De izquierda a derecha, las tarjetas muestran los siguientes elementos: una “Tiza de cal” , “Jabón regular” (una barra de jabón), “Lápiz tela” (un lápiz marcador para tela), un “Marcador tela” (un rotulador para tela), “Rodaja” (una rueda pequeña), y “Papel oxido o calco” ( papel de calco para transferir imágenes).")
        p.text-center #[b Jabón regular ]
      .tarjeta.color-acento-contenido.p-4.borde-redondo
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta10/imagen3.png" alt="La imagen describe una serie de tarjetas con iconos e inscripciones en español, representando diferentes herramientas o suministros. De izquierda a derecha, las tarjetas muestran los siguientes elementos: una “Tiza de cal” , “Jabón regular” (una barra de jabón), “Lápiz tela” (un lápiz marcador para tela), un “Marcador tela” (un rotulador para tela), “Rodaja” (una rueda pequeña), y “Papel oxido o calco” ( papel de calco para transferir imágenes).")
        p.text-center #[b Lapiz tela ]
      .tarjeta.color-acento-contenido.p-4.borde-redondo
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta10/imagen4.png" alt="La imagen describe una serie de tarjetas con iconos e inscripciones en español, representando diferentes herramientas o suministros. De izquierda a derecha, las tarjetas muestran los siguientes elementos: una “Tiza de cal” , “Jabón regular” (una barra de jabón), “Lápiz tela” (un lápiz marcador para tela), un “Marcador tela” (un rotulador para tela), “Rodaja” (una rueda pequeña), y “Papel oxido o calco” ( papel de calco para transferir imágenes).")
        p.text-center #[b Marcador tela ]
      .tarjeta.color-acento-contenido.p-4.borde-redondo
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta10/imagen5.png" alt="La imagen describe una serie de tarjetas con iconos e inscripciones en español, representando diferentes herramientas o suministros. De izquierda a derecha, las tarjetas muestran los siguientes elementos: una “Tiza de cal” , “Jabón regular” (una barra de jabón), “Lápiz tela” (un lápiz marcador para tela), un “Marcador tela” (un rotulador para tela), “Rodaja” (una rueda pequeña), y “Papel oxido o calco” ( papel de calco para transferir imágenes).")
        p.text-center #[b Rodaja ]
      .tarjeta.color-acento-contenido.p-4.borde-redondo
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta10/imagen6.png" alt="La imagen describe una serie de tarjetas con iconos e inscripciones en español, representando diferentes herramientas o suministros. De izquierda a derecha, las tarjetas muestran los siguientes elementos: una “Tiza de cal” , “Jabón regular” (una barra de jabón), “Lápiz tela” (un lápiz marcador para tela), un “Marcador tela” (un rotulador para tela), “Rodaja” (una rueda pequeña), y “Papel oxido o calco” ( papel de calco para transferir imágenes).")
        p.text-center #[b Papel onix o calco ]
    
    .row.justify-content-center.align-items-center.mb-4.mt-4.fondoespecial4
      .col-sm-12.col-md-7.col-lg-6
        p.p-5 Es el método más utilizado por los sastres para marcaciones especiales sobre el textil; este método tiene puntos con hebras de hilo que sirven de guía, sin llegar a manchar el textil. Esta es una puntada suelta en bucle como una indicación de dónde coser finalmente.
      .col-7.col-md-5.col-lg-3
        img.mt-5.mb-4(src="@/assets/curso/temas/tema2/imagen40.png")
    
    .row.align-items-center.justify-content-center.mt-4.mb-4
      .col-sm-12.col-md-9.col-lg-9
        h3.mt-4.mb-4 Tipos de marcación, alfileres
        p Fijar patrones con alfileres. Los alfileres vienen en una variedad de tamaños. Si la tela es gruesa use alfileres grandes y largos, si la tela es delgada y delicada como la seda utilice alfileres pequeños y cortos para evitar dañarla.
        .cajon.color-primario 
          p.p-5 #[b  Inserte los alfileres cada 3 cm al rededor del patrón y en puntos claves, evite coger mucha cantidad del textil para evitar los bucles y malformaciones a la hora de pinar, es recomendable ubicar los alfileres de forma diagonal. ]
      .col-6.col-md-3.col-lg-3
        img.p-3(src="@/assets/curso/temas/tema2/imagen41.svg")

    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-md-5.col-lg-3
        img.align-items-center.mb-2(src="@/assets/curso/temas/tema2/imagen42.svg")
      .col-sm-12.col-md-7.col-lg-7
        .tarjeta.color-acento-botones.borde-redondo
          .row.justify-content-around.align-items-center
            .col-6.col-md-4.col-lg-3
              img.p-4.ps-5(src="@/assets/curso/temas/tema2/admiracion.png")
            .col-sm-12.col-md-8.col-lg-9
              p.ps-3.mb-0 #[b Pinar ]
              p.ps-3 Insertar alfileres en el textil para asegurar el molde.
        .row
          .col-sm-12.col-md-6.col-lg-6
            p.mb-4.mt-4 #[b Lo que no se debe hacer ]
            ul.lista-ul--color.fa-ul.color-primario.ps-1
              li 
                i.fas.fa-plus
                | Asegurar con cinta.
              li
                i.fas.fa-plus
                | No fijar los patrones.
          .col-sm-12.col-md-6.col-lg-6
            ul.lista-ul--color.fa-ul.color-primario.ps-1.mt-5
              li
                i.fas.fa-plus
                | No cortar el margen del patrón de forma inadecuada.
              li
                i.fas.fa-plus
                | Marcar con tiza de forma inadecuada.

    Separador 
    .row
      h3.mb-5 Proceso de corte

    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema2/imagen43.svg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Luego de realizar y seguir cada uno de los pasos para una adecuada calidad del proceso, se continúa con el corte del textil de acuerdo con la marcación. Para ello, es importante conocer las herramientas fundamentales para este proceso y elegir las adecuadas, lo cual garantiza un mejor trabajo.
    
    .row.mb-4.mt-4
      p #[b Herramientas ]

    SlyderF(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in-left")
      .tarjeta.color-acento-contenido.p-4.borde-redondo
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta11/imagen1.png" alt="La imagen expone una colección de herramientas de corte para textiles, cada una enmarcada en un círculo con fondo morado. Comienza con las “Tijeras castellana”, diseñadas con orificios iguales y recomendadas para textiles ligeros. Siguen las “Tijeras sastre”, con un diseño que permite apoyarlas en la mesa, adecuadas para tejidos de peso mediano a pesado. Las “Tijeras zigzag” tienen hojas dentadas que cortan en zigzag para prevenir el deshilachado de los textiles. El “Cortador térmico” se utiliza para cortar y sellar simultáneamente acrílico y textiles, evitando el deshilachado. Finalmente, el “Cúter rotatorio” es óptimo para cortar una variedad de materiales, desde telas hasta vinilos, con un mango que mejora la precisión y facilita el uso con reglas para mayor exactitud en el corte.")
        p.text-center #[b Tijeras castellana ]
        p.text-small Tienen los dos orificios para los dedos del mismo tamaño, suelen tener un tamaño medio y son bastante ligeras, se recomiendan para textiles de peso liviano.
      .tarjeta.color-acento-contenido.p-4.borde-redondo
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta11/imagen2.png" alt="La imagen expone una colección de herramientas de corte para textiles, cada una enmarcada en un círculo con fondo morado. Comienza con las “Tijeras castellana”, diseñadas con orificios iguales y recomendadas para textiles ligeros. Siguen las “Tijeras sastre”, con un diseño que permite apoyarlas en la mesa, adecuadas para tejidos de peso mediano a pesado. Las “Tijeras zigzag” tienen hojas dentadas que cortan en zigzag para prevenir el deshilachado de los textiles. El “Cortador térmico” se utiliza para cortar y sellar simultáneamente acrílico y textiles, evitando el deshilachado. Finalmente, el “Cúter rotatorio” es óptimo para cortar una variedad de materiales, desde telas hasta vinilos, con un mango que mejora la precisión y facilita el uso con reglas para mayor exactitud en el corte.")
        p.text-center #[b Tijeras sastre ]
        p.text-small Uno de los lados de la hoja no sobresale a su mango, permitiendo de esta manera apoyar las tijeras en la mesa a la hora de cortar la tela; tienen un tamaño y peso mayor. Se recomiendan para textiles de peso mediano a pesado.
      .tarjeta.color-acento-contenido.p-4.borde-redondo
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta11/imagen3.png" alt="La imagen expone una colección de herramientas de corte para textiles, cada una enmarcada en un círculo con fondo morado. Comienza con las “Tijeras castellana”, diseñadas con orificios iguales y recomendadas para textiles ligeros. Siguen las “Tijeras sastre”, con un diseño que permite apoyarlas en la mesa, adecuadas para tejidos de peso mediano a pesado. Las “Tijeras zigzag” tienen hojas dentadas que cortan en zigzag para prevenir el deshilachado de los textiles. El “Cortador térmico” se utiliza para cortar y sellar simultáneamente acrílico y textiles, evitando el deshilachado. Finalmente, el “Cúter rotatorio” es óptimo para cortar una variedad de materiales, desde telas hasta vinilos, con un mango que mejora la precisión y facilita el uso con reglas para mayor exactitud en el corte.")
        p.text-center #[b Tijeras  #[em zigzag ] ]
        p.text-small Poseen dientes en las hojas, lo que crea un patrón de corte en  #[em zig zag ]. La función principal de este tipo de tijeras es la de evitar que se deshilache el textil después del corte.
      .tarjeta.color-acento-contenido.p-4.borde-redondo
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta11/imagen4.png" alt="La imagen expone una colección de herramientas de corte para textiles, cada una enmarcada en un círculo con fondo morado. Comienza con las “Tijeras castellana”, diseñadas con orificios iguales y recomendadas para textiles ligeros. Siguen las “Tijeras sastre”, con un diseño que permite apoyarlas en la mesa, adecuadas para tejidos de peso mediano a pesado. Las “Tijeras zigzag” tienen hojas dentadas que cortan en zigzag para prevenir el deshilachado de los textiles. El “Cortador térmico” se utiliza para cortar y sellar simultáneamente acrílico y textiles, evitando el deshilachado. Finalmente, el “Cúter rotatorio” es óptimo para cortar una variedad de materiales, desde telas hasta vinilos, con un mango que mejora la precisión y facilita el uso con reglas para mayor exactitud en el corte.")
        p.text-center #[b Cortadores térmicos ]
        p.text-small Estos cortadores se emplean para el corte de acrílico y textiles. Una vez cortada la tela queda sellada y no se deshilacha.
      .tarjeta.color-acento-contenido.p-4.borde-redondo
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta11/imagen5.png" alt="La imagen expone una colección de herramientas de corte para textiles, cada una enmarcada en un círculo con fondo morado. Comienza con las “Tijeras castellana”, diseñadas con orificios iguales y recomendadas para textiles ligeros. Siguen las “Tijeras sastre”, con un diseño que permite apoyarlas en la mesa, adecuadas para tejidos de peso mediano a pesado. Las “Tijeras zigzag” tienen hojas dentadas que cortan en zigzag para prevenir el deshilachado de los textiles. El “Cortador térmico” se utiliza para cortar y sellar simultáneamente acrílico y textiles, evitando el deshilachado. Finalmente, el “Cúter rotatorio” es óptimo para cortar una variedad de materiales, desde telas hasta vinilos, con un mango que mejora la precisión y facilita el uso con reglas para mayor exactitud en el corte.")
        p.text-center #[b Cúter rotatorio ]
        p.text-small Se caracteriza por ser el mejor cortador para telas, lonas, láminas plásticas, hule, vinilos y otros materiales textiles tejidos o no tejidos (fieltro). Su mango facilita el manejo, perfección y agilidad a la hora de cortar, se puede apoyar con reglas y otros elementos para una mejor precisión del corte.

    .row.justify-content-center.align-items-center
      .col-sm-12.col-md-7.col-lg-7
        p #[b Tips de corte ]
        br
        ul.lista-ul--color.fa-ul.color-primario
          li 
            i.fas.fa-plus
            | Con una mano sostenga la tela y con la otra realice el corte.
          li
            i.fas.fa-plus
            | Realice cortadas amplias.
          li
            i.fas.fa-plus
            | El tendido no se mueve, lo que se mueve son las tijeras, la mano y el operario a medida que se va cortando.
          li
            i.fas.fa-plus
            | En cada piquete, hacer un pequeño corte de máximo 3 mm de profundidad.
      .col-10.col-md-5.col-lg-3
        img.p-5(src="@/assets/curso/temas/tema2/imagen44.svg")

    Separador    

    .row.mb-4.mt-4
      #t_2_6.titulo-segundo.color-primario
        h2 2.6  Características del material
      
    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-md-10.col-lg-10
        h3.mb-4 Tipos de trazo
        .row.justify-content-center
          .col-sm-12.col-md-6.col-lg-4
            .tarjeta.color-acento-botones.borde-redondo.p-5
              img.p-4(src="@/assets/curso/temas/tema2/tarjeta12/imagen1.png" alt="La imagen ilustra tres tipos de trazos utilizados en la confección de textiles, cada uno representado en un recuadro con diferentes colores de fondo. El primer recuadro, con fondo morado, se titula “Requerimientos desde patronaje” y muestra un esquema de patrones de costura. El segundo recuadro, con fondo amarillo, se titula “Tendido y marcación” y muestra a una persona marcando una tela con tiza. El tercer recuadro, nuevamente con fondo morado, se titula “Características del material” y muestra un patrón de corte superpuesto sobre un diseño de tela. En la parte superior de la imagen, se encuentra el título “Tipos de trazo”.")
              h4.text-center.mb-0 #[b Requerimientos desde patronaje ]
          .col-sm-12.col-md-6.col-lg-4
            .tarjeta.color-primario.borde-redondo.p-5
              img.p-4(src="@/assets/curso/temas/tema2/tarjeta12/imagen2.png" alt="La imagen ilustra tres tipos de trazos utilizados en la confección de textiles, cada uno representado en un recuadro con diferentes colores de fondo. El primer recuadro, con fondo morado, se titula “Requerimientos desde patronaje” y muestra un esquema de patrones de costura. El segundo recuadro, con fondo amarillo, se titula “Tendido y marcación” y muestra a una persona marcando una tela con tiza. El tercer recuadro, nuevamente con fondo morado, se titula “Características del material” y muestra un patrón de corte superpuesto sobre un diseño de tela. En la parte superior de la imagen, se encuentra el título “Tipos de trazo”.")
              h4.mb-4.text-center.color-white #[b Tendido y marcación ]
          .col-sm-12.col-md-6.col-lg-4
            .tarjeta.color-acento-botones.borde-redondo.p-5
              img.p-4(src="@/assets/curso/temas/tema2/tarjeta12/imagen3.png" alt="La imagen ilustra tres tipos de trazos utilizados en la confección de textiles, cada uno representado en un recuadro con diferentes colores de fondo. El primer recuadro, con fondo morado, se titula “Requerimientos desde patronaje” y muestra un esquema de patrones de costura. El segundo recuadro, con fondo amarillo, se titula “Tendido y marcación” y muestra a una persona marcando una tela con tiza. El tercer recuadro, nuevamente con fondo morado, se titula “Características del material” y muestra un patrón de corte superpuesto sobre un diseño de tela. En la parte superior de la imagen, se encuentra el título “Tipos de trazo”.")
              h4.mb-4.text-center #[b Características del material ]
    
    .row.mb-4.mt-4
      p.mt-4.mb-4 #[b ¿Para qué? ]
      p.mb-0 El reconocimiento de las características del material textil a trabajar es sumamente importante para asegurar una calidad óptima en la prenda al cortar y ensamblar. Antes de cada proceso de tendido, marcación y corte se deben verificar dichas características.
    
    .row.justify-content-center.mb-4-mt-4
      .col-lg-9
        img.p-4(src="@/assets/curso/temas/tema2/imagen45.png" alt="La imagen detalla dos ilustraciones que explican la dirección del pelo en las telas. A la izquierda, se presentan dos direcciones del pelo en la tela, una hacia arriba y otra hacia abajo, indicadas con flechas. A la derecha, una mano acaricia una tela en la dirección del pelo, demostrando cómo se debe sentir la textura para determinar la orientación correcta. Estas guías son importantes para asegurar que todas las piezas del patrón se corten en la misma dirección del pelo, evitando diferencias de color y textura en la prenda final. ")

    .row.justify-content-center.mb-4-mt-4
      .col-sm-12.col-md-8.col-lg-9
        p.mb-3.mt-5 #[b ¿Qué es la textura #[em nap] (#[em velvet], pelusa, #[em fleece])?]
        p Nap es la textura de los textiles que van en una dirección particular. Esta propiedad de la prenda es fundamental para garantizar la calidad de la misma. En algunos textiles se logra evidenciar el nap a simple vista como #[em velvet, fleece,] piel sintética, denim cepillado, franela, gamuza sintética, sarga, elástica, tela de felpa, etc.
        .tarjeta.color-acento-botones.borde-redondo.mt-4
          .row.justify-content-around.align-items-center
            .col-6.col-md-4.col-lg-2
              img.mt-4.mb-4.ps-5(src="@/assets/curso/temas/tema2/admiracion.png")
            .col-sm-12.col-md-8.col-lg-10
              p.ps-3.mb-0 #[b ¿Por qué es importante el #[em nap]? ]
              p.ps-3.mb-0 El #[em nap] es muy importante para determinar cómo se establece el patrón en el textil, en este caso se trabaja siempre un trazo direccional. Se debe tener en cuenta lo siguiente:
      .col-6.col-md-4.col-lg-3
        img.p-2(src="@/assets/curso/temas/tema2/imagen46.png")

    .row.justify-content-center.align-items-center.mb-5.mt-3
      .col-sm-12.col-md-5.col-lg-5.p-3
        .row.estilo1
          .col-8.col-md-3.col-lg-3
            img.p-2.mt-3(src='@/assets/curso/temas/tema2/uno.svg' alt='AvatarTop')
          .col-sm-12.col-md-9.col-lg-9
            p.p-2.mt-3 #[b Acabados de la prenda ]
            p.ps-2.mb-5 Si no se tiene en cuenta el  #[em nap ] al momento de cortar la prenda, la prenda terminaría con brillos diferentes en cada pieza, necesitan un color y una textura uniforme en toda la pieza.
      .col-sm-12.col-md-5.col-lg-5.p-3
        .row.estilo1
          .col-8.col-md-3.col-lg-3
            img.p-2.mt-3(src='@/assets/curso/temas/tema2/dos.svg' alt='AvatarTop')
          .col-sm-12.col-md-9.col-lg-9
            p.p-2.mt-3 #[b Determinar el consumo del textil ]
            p.ps-2.mb-4 Se debe determinar el consumo de material que requiere la prenda para garantizar que todo el textil sea suficiente para el corte, lo cual es una clara desventaja, ya que se desperdicia mucha tela al seguir un trazo direccional.

    .row.justify-content-center.mb-4-mt-4
      .col-sm-12.col-md-12.col-lg-5
        p #[b ¿Cómo identificar el #[em nap]?]
        p Al pasar las manos suavemente por el textil para sentir el  #[em nap]/pelusa
        ul.lista-ul--color.fa-ul.color-primario
          li 
            i.fas.fa-plus
            span.mb-0 La sensación más suave es la dirección con  #[em nap]/pelusa.
          li
            i.fas.fa-plus
            span.mb-0 La sensación más áspera es la dirección contraria al  #[em nap]/pelusa.
          li
            i.fas.fa-plus
            span.mb-0 El brillo de la tela es diferente cuando se ve desde diferentes direcciones.
      .col-10.col-md-7.col-lg-7
        img(src="@/assets/curso/temas/tema2/imagen48.svg" alt="La imagen detalla la correcta e incorrecta dirección del pelo al cortar piezas de un patrón. La sección superior, marcada como “Correct”, indica que todas las piezas del patrón están alineadas con el pelo en la misma dirección, lo cual es correcto. La sección inferior, marcada como “Incorrect”, expone piezas del patrón con el pelo en diferentes direcciones, lo cual es incorrecto. Esto asegura que la textura y apariencia de la prenda final sean uniformes. ")

    .row.justify-content-center.align-items-center.mb-5.mt-5
      .col-sm-12.col-md-12.col-lg-3
        p #[b Trazo o marcado ]
        p Se recomienda que cuando se utilice este tipo de textiles con #[em nap], el proceso de transferir los moldes al textil se trabaje preferiblemente en un tendido abierto, sujetado con alfileres. Para marcar pinzas o elementos clave se recomienda los hilvanes o  #[em tailor tacks].
      .col-8.col-md-7.col-lg-7
        img(src="@/assets/curso/temas/tema2/imagen49.png" alt="La imagen expone dos pasos en el proceso de confección. A la izquierda, se ve un patrón colocado sobre la tela con marcas realizadas con hilos para indicar puntos importantes del diseño. A la derecha, una persona utiliza tijeras para cortar la tela siguiendo las marcas del patrón. Estas imágenes destacan la importancia de marcar correctamente la tela antes de cortarla para asegurar precisión en el ensamblaje de la prenda.")

    .row.justify-content-center.mb-5-mt-5
      .col-sm-12.col-md-7.col-lg-7
        p #[b Piel sintética ]
        p La piel sintética también cuenta con  #[em nap]/siesta que es mucho más sencilla para identificar la dirección del vello. En este caso se debe trabajar:
        ul.lista-ul--color.fa-ul.color-primario
          li 
            i.fas.fa-plus
            span.mb-0 Trazo direccional.
          li
            i.fas.fa-plus
            span.mb-0 Tendido abierto.
          li
            i.fas.fa-plus
            span.mb-0 Marcación por el revés con tiza.
        p Algunas tienen el vello más largo que otras, por eso es importante realizar un trazo, marcado y corte de forma adecuada.
      .col-7.col-md-5.col-lg-3
        img.mt-3(src="@/assets/curso/temas/tema2/imagen50.svg")

    .row.justify-content-center.align-items-center.mb-5.mt-5
      .col-sm-12.col-md-10.col-lg-10
        .row.estilo2
          .col-sm-12.col-md-6.col-lg-6
            .row.bgamarillo
              p.mt-5.ps-5 #[b Tips de corte, piel sintética ]
              p.p-5 Cortar en el sentido del  #[em nap]/vello. Realice cortadas pequeñas, preferible con la punta de la tijeras. Una vez cortado se sugiere eliminar el exceso de vello/pelo por el margen de costura, teniendo en cuenta la dirección del pelo se recomienda confeccionarlo en esa misma dirección.
          .col-10.col-md-6.col-lg-6
            .row.align-items-center
              img.mt-5(src="@/assets/curso/temas/tema2/imagen51.svg" alt="La imagen da las  instrucciones para cortar y trabajar con telas de pelaje o velour. Primero, se debe cortar en el sentido del vellón o nap, como se ilustra con una mano alineando el corte. Es recomendable realizar cortes pequeños, preferiblemente con la punta de la tijera, como se observa en una imagen de tijeras cortando tela rosa. Además, se aconseja tener en cuenta la dirección del pelo y confeccionarlo en esa misma dirección, mostrada en una tela gris con el pelo alineado. Finalmente, una vez cortado, se sugiere eliminar el exceso de vellón o pelo por el margen de costura, como se ve en la imagen de la tela rosa después del corte.")

    .row.justify-content-center.mb-4-mt-4
      .col-sm-col-md-4.col-lg-4
        p #[b Textiles estampados ]
        p Los textiles estampados también se deben trabajar con un trazo direccional, ya que de esto depende la dirección del estampado que se desee en la prenda terminada. Esto significa que todas las piezas deben cortarse en la misma dirección para que el estampado quede acorde al diseño.
      .col-6.col-md-6.col-lg-6
        img(src="@/assets/curso/temas/tema2/imagen52.svg" alt="La imagen expone el proceso de colocar patrones sobre la tela para el corte. En la parte superior derecha, se ve una tela extendida con varias piezas del patrón colocadas, alineadas con el hilo y el orillo de la tela. En la parte inferior izquierda, se muestran dos piezas del patrón, con una marcada como “centro frente”, indicando la alineación central en la tela. Estas imágenes enfatizan la importancia de alinear correctamente los patrones con el hilo y el orillo de la tela para garantizar precisión en el corte y la confección de la prenda.")

    .row.align-items-center.justify-content-center.mt-4
      .col-7.col-md-3.col-lg-3.p-3
        img(src="@/assets/curso/temas/tema2/imagen53.png")
      .col-sm-12.col-md-7.col-lg-7
        p #[b Textiles de cuadros ]
        p La continuidad de las líneas y el dibujo/cuadros en las prendas producen un efecto agradable a la vista.
        .cajon.color-primario 
          p.p-5 #[b  Hacer coincidir cada una de las líneas, cuadros o elementos del dibujo del textil requiere precisión; sin embargo, esto se utiliza en prendas de muy altos estándares de calidad, ya que el corte se debe hacer preferiblemente individual.  ]

    .row.justify-content-center.mb-4.mt-5
      .col-sm-12.col-md-5.col-lg-5
        p #[b Tendido y corte ]
        p Para los textiles de cuadros se recomienda trabajarlos de la siguiente manera:
        ul.lista-ul--color.fa-ul.color-primario
          li 
            i.fas.fa-plus
            | Trabajar despiece sin costura.
          li
            i.fas.fa-plus
            | Trazo direccional.
          li
            i.fas.fa-plus
            | Tendido abierto cara arriba.
          li
            i.fas.fa-plus
            | Marcación por el revés con tiza.
          li
            i.fas.fa-plus
            | Fijar los patrones con alfileres.
      .col-sm-12.col-md-5.col-lg-5
        img.mt-5(src="@/assets/curso/temas/tema2/imagen54.png" alt="La imagen presenta dos diagramas de una chaqueta a cuadros, destacando diferentes partes y detalles de la prenda con números y círculos. Estos diagramas probablemente señalan características específicas de la chaqueta, como costuras, botones, bolsillos y otros elementos de diseño tanto en la vista frontal como en la vista posterior. La anotación numérica facilita la identificación y referencia a las distintas partes de la chaqueta para su análisis o confección. ")

    .row.justify-content-center.align-items-center.mb-4.mt-5
      p.text-center #[b Tips de corte para cuadros ]

    .row.justify-content-center.mt-4.mb-4(data-aos="zoom-in-left")
      .col-sm-12.col-md-6.col-lg-3
        .tarjeta.color-acento-botones.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta13/imagen1.png" alt="La imagen proporciona tips para cortar telas con cuadros. Primero, se deben ubicar los patrones en el textil y alinear las líneas para que coincidan. Luego, se traza en los patrones las líneas correspondientes. Este proceso debe repetirse para cada una de las piezas de la prenda. Finalmente, una vez ubicados los patrones, se deben pintar y, con la tiza, agregar el margen de costura. Cada tip está ilustrado en un recuadro con diferentes colores de fondo: amarillo para los primeros y tercer tip, y morado para el segundo y cuarto tip. En la parte superior de la imagen se encuentra el título “Tips de corte para cuadros”.")
          p.text-center #[b Ubicar los patrones en el textil y alinear para que coincidan las líneas. ]
      .col-sm-12.col-md-6.col-lg-3
        .tarjeta.color-primario.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta13/imagen2.png" alt="La imagen proporciona tips para cortar telas con cuadros. Primero, se deben ubicar los patrones en el textil y alinear las líneas para que coincidan. Luego, se traza en los patrones las líneas correspondientes. Este proceso debe repetirse para cada una de las piezas de la prenda. Finalmente, una vez ubicados los patrones, se deben pintar y, con la tiza, agregar el margen de costura. Cada tip está ilustrado en un recuadro con diferentes colores de fondo: amarillo para los primeros y tercer tip, y morado para el segundo y cuarto tip. En la parte superior de la imagen se encuentra el título “Tips de corte para cuadros”.")
          p.text-center.color-white #[b Trazar en los patrones las líneas. ]
          <br> <br>

        // intento colocar mt o mb y no lo toma

      .col-sm-12.col-md-6.col-lg-3
        .tarjeta.color-acento-botones.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta13/imagen3.png" alt="La imagen proporciona tips para cortar telas con cuadros. Primero, se deben ubicar los patrones en el textil y alinear las líneas para que coincidan. Luego, se traza en los patrones las líneas correspondientes. Este proceso debe repetirse para cada una de las piezas de la prenda. Finalmente, una vez ubicados los patrones, se deben pintar y, con la tiza, agregar el margen de costura. Cada tip está ilustrado en un recuadro con diferentes colores de fondo: amarillo para los primeros y tercer tip, y morado para el segundo y cuarto tip. En la parte superior de la imagen se encuentra el título “Tips de corte para cuadros”.")
          p.text-center #[b Realizar esto con cada una de las piezas de la prenda. ]
          br
      .col-sm-12.col-md-6.col-lg-3
        .tarjeta.color-primario.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta13/imagen4.png" alt="La imagen proporciona tips para cortar telas con cuadros. Primero, se deben ubicar los patrones en el textil y alinear las líneas para que coincidan. Luego, se traza en los patrones las líneas correspondientes. Este proceso debe repetirse para cada una de las piezas de la prenda. Finalmente, una vez ubicados los patrones, se deben pintar y, con la tiza, agregar el margen de costura. Cada tip está ilustrado en un recuadro con diferentes colores de fondo: amarillo para los primeros y tercer tip, y morado para el segundo y cuarto tip. En la parte superior de la imagen se encuentra el título “Tips de corte para cuadros”.")
          p.text-center.color-white #[b Una vez ubicados se debe ir pintando y con la tiza ir agregando margen de costura. ]

    .row.mt-5.mb-4(data-aos="zoom-in-left")
      p #[b Ejemplo de tipos de tendido con diferentes características del material ]
      p En el desarrollo de los contenidos se han identificado términos técnicos de la industria, los cuales se irán apropiando con mayor rigor en la práctica; la inmersión en la industria y el mercado permitirá afianzar cada vez más los conocimientos teóricos; sin embargo, con el fin de sintetizar de una manera más gráfica se hará la contextualización aplicada en diferentes tipos de materiales con una serie de moldes a escala que permitirán poner en práctica los conceptos explicados.
    
    .row.justify-content-center.mt-4.mb-4(data-aos="zoom-in-left")
      .col-sm-12.col-md-8.col-lg-8
        .tarjeta.borde-redondo.p-4.mb-5(style='background-color: #673AB7')
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-9.mb-sm-0
                  p.mb-0.text-white Para una mejor comprensión del tema revisar el siguiente video de “ejemplo sobre tipos de tendido con diferentes características del material”.
                .col-sm-12.col-lg-3
                  a.boton.color-boton(href="https://www.youtube.com/watch?v=-nkWodY_bPE" target="_blank")
                    span.texto-negro Ir al sitio
                    i.fas.fa-video

    Separador    
    .row(data-aos="zoom-in-left")
      #t_2_7.titulo-segundo.color-primario
        h2 2.7  Terminología industrial de trazo y corte
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-md-7.col-lg-7
        h3 #[b Tiqueteado ]
        p Consiste en rotular cada una de las piezas cortadas, identificando el lote, nombre de la pieza, talla y un consecutivo para contribuir en el orden del sistema operacional.
        .cajon.color-primario 
          p.p-5 #[b  Se usa tiqueteadora con su papel adhesivo; es importante definir la ubicación en la pieza, se trabaja por el revés de la tela.  ]
      .col-7.col-md-3.col-lg-3.p-3
        img(src="@/assets/curso/temas/tema2/imagen55.svg")
                    
    .row.mb-4.mt-4(data-aos="zoom-in-left")
      h3.mb-4 Operaciones auxiliares de corte
      p Interviene personal auxiliar para apoyar el proceso. 

    AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--purple")(data-aos="zoom-in-left")
      .row.borde-redondo-tmorada(titulo="Fusionado")
        .col-md-12.mb-4.mb-md-0
          p.p-5 Una vez se corta la tela y la entretela, para entretelar se utiliza una máquina fusionadora, que a través de presión y calor adhiere la entretela a la tela. Es importante el control de temperatura según el textil, ya que puede generar encogimiento.
      .row.borde-redondo-tmorada(titulo="Paqueteo")
        .col-md-12.mb-4.mb-md-0
          p.p-5 Consiste en separar por bloques las piezas cortadas, paqueteando la cantidad definida de todas las piezas que conforman la prenda, amarrando y conformando paquetes de 10 a 20 unidades; para así facilitar el control de producción y de calidad. Una vez se paquetee es importante el almacenamiento, utilizando la técnica de Kanban para entregarlas a ensamble.
      .row.borde-redondo-tmorada(titulo="Tecnología en corte")
        .col-md-12.mb-4.mb-md-0
          p.p-5 La tecnología en el área de corte inicia con el trazo asistido por computador a través de programas especializados, los cuales ahorran tiempo y espacio. Para el transporte de telas y paquetes cortados se usan bandas o carros, que son utilizados también para entregar los paquetes al área de ensamble.
      .row.borde-redondo-tmorada(titulo="<i>Software</i> de corte")
        .col-md-12.mb-4.mb-md-0
          p.p-5 Los programas empleados en la industria textil como Audaces, Gerber, Optitex o Lectra cuentan con módulos especializados en trazo, que facilitan el corte de las prendas, siendo más precisos, optimizando los tiempos y disminuyendo el desperdicio de materia prima. Además del computador y del programa se requiere el plotter para poder imprimir los trazos. En el caso de que el corte sea automático, el cabezal irá cortando sobre la tela sin previa impresión del trazo.

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
