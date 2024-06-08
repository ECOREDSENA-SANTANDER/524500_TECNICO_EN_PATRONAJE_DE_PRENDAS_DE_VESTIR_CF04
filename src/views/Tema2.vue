<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Trazo y corte manual
    
    
    .row.align-items-center.mt-4
      .col-9
        p La industria textil se destaca por tener diferentes procesos productivos para elaborar prendas de vestir; cuando se habla de trazo y corte a nivel general, consiste en toda la optimización o acomodación de moldes sobre el material textil.
        .cajon.color-primario 
          p.p-5 <strong> Para abordar este tema, y de acuerdo con la necesidad de la industria textil frente al perfil de un patronista, se brindarán los conocimientos y se entregarán las herramientas técnicas requeridas en el área de prototipado o muestreo de producto. </strong>
      .col-3.p-3
        img(src="@/assets/curso/temas/tema2/imagen1.svg", alt="Imagen recortando molde")
    
    Separador 
    .row.mb-4
      .titulo-segundo.color-primario
        h2 2.1  Reconocimiento de las prendas

    .row.justify-content-center.mt-4
      .col-5
        h3.mt-4.mb-4 ¿Para qué?
        p El reconocimiento de las partes que componen una prenda de vestir es sumamente importante para el proceso de trazo y corte, de esto depende una adecuada interpretación de los requerimientos de corte.
      .col-5.p-3
        img(src="@/assets/curso/temas/tema2/imagen2.svg", alt="La imagen muestra varios bocetos de prendas de vestir diseñadas para mujeres. Las prendas incluyen una camiseta de manga larga, una camisa de botones, un top sin mangas, un conjunto de pijama, un pantalón, un vestido de tirantes, una bata corta y una bata larga con cinturón. Cada prenda está detalladamente ilustrada, indicando diferentes estilos y diseños para ropa femenina.")

    .row.justify-content-center.mt-4(style="background-color: #FFF5D3")
      .col-5.mb-5.mt-5
        img(src="@/assets/curso/temas/tema2/imagen3.svg", alt="La imagen muestra bocetos técnicos de una chaqueta, destacando detalles específicos del diseño. Incluye vistas frontal y posterior de la chaqueta, así como ampliaciones de características particulares: un ojal tipo ribete, un cuello alto con pinza y una manga tipo sastre con pinza. Estas ampliaciones resaltan los elementos de confección y estilo de la prenda.")
      .col-5.mt-5
        h3 Dibujo técnico
        p Representación detallada de una prenda y las partes que la componen, permite identificar todas sus características técnicas, pespuntes, botones, costuras, pinzas, acabados. No tiene movimiento, pero se puede identificar la parte delantera y posterior. 

    .row.justify-content-center.mt-4
      .col-5
        h3.mt-4.mb-4 Componentes de las prendas
        p Los componentes son los elementos y/o partes de las que están formadas las prendas de vestir.
        p Estos pueden ser:
        ul.lista-ul--color.fa-ul.color-primario.ps-1
          li 
            i.fas.fa-plus
            | Exteriores
          li
            i.fas.fa-plus
            | Interiores
          li
            i.fas.fa-plus
            | Hilos
          li
            i.fas.fa-plus
            | Fornituras y complementos
      .col-3.p-3
        img(src="@/assets/curso/temas/tema2/imagen4.svg", alt="La imagen muestra un abrigo destacando sus componentes exteriores, que incluyen delanteros y posteriores, cuellos, mangas, bolsillos y puños, entre otros. Estos elementos están formados por el material textil base utilizado para confeccionar la prenda en su exterior.")

    .row.justify-content-center.mt-4(style="background-color: #E8DDFF")
      .col-3
        img.mt-5.mb-5(src="@/assets/curso/temas/tema2/imagen5.svg", alt="La imagen destaca el uso de hilos en la confección de prendas, indicando que son esenciales para unir las diferentes partes. Se muestran ejemplos de pespuntes, puntadas decorativas, bastas y puntadas manuales, que son los tipos principales de costuras utilizados en la creación de ropa.")
      .col-3
        h3.mt-5 Componentes exteriores
        p Son todas las partes del material textil base con la que está elaborada la prenda en el exterior.
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span 1 
            | Delanteros y posteriores
          li 
            .lista-ol--cuadro__vineta
              span 2 
            | Cuellos
          li 
            .lista-ol--cuadro__vineta
              span 3
            | Mangas
          li 
            .lista-ol--cuadro__vineta
              span 4
            | Bolsillos 
          li 
            .lista-ol--cuadro__vineta
              span 5
            | Puños, entre otros

    .row.justify-content-center.mt-4
      .col-4
        h3.mt-5 Componentes interiores
        p Todos aquellos elementos y/o partes que van en el interior o revés de la prenda, estos pueden ser:
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span 1 
            | Foro
          li 
            .lista-ol--cuadro__vineta
              span 2 
            | Entretela
          li 
            .lista-ol--cuadro__vineta
              span 3
            | Guata
          li 
            .lista-ol--cuadro__vineta
              span 4
            | Sesgo
      .col-4
        img.mt-5.mb-5(src="@/assets/curso/temas/tema2/imagen6.svg", alt="La imagen muestra los componentes interiores de una prenda, que incluyen el forro, la entretela, la guata y el sesgo. Estos elementos son las partes que se encuentran en el interior o el revés de la prenda.")

    .row.justify-content-center.mt-4(style="background-color: #FFF5D3")
      .col-5.mt-5
        img(src="@/assets/curso/temas/tema2/imagen7.svg", alt="La imagen muestra bocetos técnicos de una chaqueta, destacando detalles específicos del diseño. Incluye vistas frontal y posterior de la chaqueta, así como ampliaciones de características particulares: un ojal tipo ribete, un cuello alto con pinza y una manga tipo sastre con pinza. Estas ampliaciones resaltan los elementos de confección y estilo de la prenda.")
      .col-3.mt-5
        h3 Hilos
        p Son uno de los elementos principales que logran unir las diferentes partes de la prenda.
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span 1 
            | Pespuntes
          li 
            .lista-ol--cuadro__vineta
              span 2 
            | Puntadas decorativas
          li 
            .lista-ol--cuadro__vineta
              span 3
            | Bastas
          li 
            .lista-ol--cuadro__vineta
              span 4
            | Puntadas manuales

    .row.justify-content-center.mt-4
      .col-3.mt-5
        h3.mb-4 Fornituras y complementos
        p Las fornituras son el conjunto de accesorios y adornos que puede llevar una prenda de vestir. Dentro de ellos se identifican: los botones, las cremalleras, corchetes, broches de presión, hebillas, ojetes, vivos, puntillas, cintas, apliques, gomas, cordones, etc.
      .col-9.mb-5.mt-5
        img(src="@/assets/curso/temas/tema2/imagen8.svg", alt="La imagen muestra tres prendas de vestir modernas y detalladas. A la izquierda, hay una chaqueta verde con múltiples bolsillos y detalles en negro, incluyendo correas y cremalleras. En el centro, se presenta un conjunto rojo ajustado con un diseño de cremallera frontal y recortes decorativos. A la derecha, se ve una chaqueta negra con pespuntes contrastantes en color marrón y botones grandes, destacando un estilo estructurado y moderno.")


    .row.justify-content-center.mt-4.mb-4(style="background-color: #E8DDFF")
      .col-5
        img.mt-5.mb-5(src="@/assets/curso/temas/tema2/imagen9.svg", alt="LLa imagen muestra los patrones de tela recortados para ensamblar una chaqueta. Los patrones incluyen piezas para las mangas, el cuello, los puños y otras partes esenciales del diseño. En una esquina, se muestra una imagen pequeña de la chaqueta completa, indicando cómo se ensamblan las piezas para formar la prenda final.")
      .col-3
        h3.mt-5 Identificación de piezas
        p Cada prenda está compuesta por piezas que tienen un nombre específico de acuerdo con la ubicación. Cada pieza tiene especificaciones técnicas de acuerdo con el proceso de extendido y corte del textil.
        
    .row.justify-content-center.mt-4.mb-4
      h3.mt-4 Reconocimiento de las partes que conforman una prenda de vestir

    .tarjeta.tarjeta--azul.p-4.mb-4.borde-redondo(style="background-color: #F8F5FF")
      SlyderA(tipo="b")
        .row.justify-content-center.my-lg-4
          .col-12.mb-4.mb-md-0
            img.p-3(src="@/assets/curso/temas/tema2/tarjeta1/imagen1.svg", alt='La imagen muestra un esquema técnico de un pantalón, con anotaciones que identifican sus distintas partes. Estas incluyen: pretina, pasador, vista delantera, bolsillo lateral, delantero, línea de quiebre, entrepierna, bota, sistema de cierre (aletilla o aletillón), tiro delantero, bolsillo de ribete doble, tiro posterior y posterior. Cada componente está claramente señalado para resaltar su ubicación y función en el diseño del pantalón.')
        .row.justify-content-center.my-lg-4
          .col-12.mb-4.mb-md-0
            img.p-3(src="@/assets/curso/temas/tema2/tarjeta1/imagen2.svg", alt='La imagen muestra un esquema técnico de un pantalón, con anotaciones que identifican sus distintas partes. Las partes señaladas incluyen: pretina, pasador, vista delantera, bolsillo monedero, tiro delantero, delantero, entrepierna, bota, sistema de cierre (aletilla o aletillón), cotilla o canesú, bolsillo de parche, tiro posterior y posterior. Cada componente está claramente etiquetado para mostrar su ubicación y función en el diseño del pantalón.')
        .row.justify-content-center.my-lg-4
          .col-12.mb-4.mb-md-0
            img.p-3(src="@/assets/curso/temas/tema2/tarjeta1/imagen3.svg", alt='La imagen muestra un esquema técnico de un pantalón deportivo, con anotaciones que identifican sus distintas partes. Las partes señaladas incluyen: sistema de cierre acordonado, bolsillo lateral, tiro delantero, delantero, entrepierna, bota encauchada, corte lateral, pretina acordonada o encauchada, tiro posterior y posterior. Cada componente está claramente etiquetado para mostrar su ubicación y función en el diseño del pantalón deportivo.')
    br

    TabsA.color-acento-botones
      .tarjeta.color-acento-botones--borde.p-4(titulo="Despiece pantalón")
        h4 Despiece pantalón
        img(src="@/assets/curso/temas/tema2/tarjeta2/imagen1.svg", alt='La imagen muestra el despiece de un pantalón, ilustrando todos los patrones necesarios para su confección. Incluye vistas técnicas del pantalón terminado, así como las piezas individuales del patrón, como las piernas, bolsillos, cintura y otras partes. Cada pieza del patrón está detallada con marcas y anotaciones que facilitan su ensamblaje.')
      .tarjeta.color-acento-botones--borde.p-4(titulo="Despiece cargo")
        h4 Despiece cargo
        img(src="@/assets/curso/temas/tema2/tarjeta2/imagen2.svg", alt='La imagen muestra el despiece de un pantalón cargo. Incluye vistas técnicas del pantalón terminado, con detalles como bolsillos laterales y un sistema de cierre acordonado. A la derecha, se presentan las piezas individuales del patrón necesarias para su confección, cada una con anotaciones y marcas para guiar el ensamblaje.')
      .tarjeta.color-acento-botones--borde.p-4(titulo="Despiece de camisa")
        h4 Despiece de camisa
        img(src="@/assets/curso/temas/tema2/tarjeta2/imagen3.svg", alt='La imagen muestra el despiece de una camisa. Incluye una vista técnica de la camisa terminada y los patrones necesarios para su confección. Las piezas del patrón incluyen partes como las mangas, el delantero, la espalda, el cuello y los puños, cada una con sus respectivas anotaciones y marcas para facilitar el ensamblaje.')
      .tarjeta.color-acento-botones--borde.p-4(titulo="Despiece de blusa")
        h4 Despiece de blusa
        img(src="@/assets/curso/temas/tema2/tarjeta2/imagen4.svg", alt='La imagen muestra el despiece de una blusa. Incluye vistas técnicas de la blusa terminada y los patrones necesarios para su confección. Las piezas del patrón abarcan partes como el delantero, la espalda, las mangas y el cuello, cada una con anotaciones y marcas detalladas para guiar el ensamblaje de la prenda.')
      .tarjeta.color-acento-botones--borde.p-4(titulo="Despiece de chaqueta")
        h4 Despiece de chaqueta
        img(src="@/assets/curso/temas/tema2/tarjeta2/imagen5.svg", alt='La imagen muestra el despiece de una chaqueta. Incluye vistas técnicas de la chaqueta terminada y los patrones necesarios para su confección. Las piezas del patrón abarcan partes como las mangas, el delantero, la espalda, el cuello y otros detalles, cada una con anotaciones y marcas específicas para facilitar el ensamblaje de la prenda.')

    Separador    
    .row.mb-4
      .titulo-segundo.color-primario
        h2 2.2  Introducción a trazo y corte

    br
    .row.justify-content-center.mb-4.mt-4
      .col-8
        .tarjeta.color-acento-botones.borde-redondo
          .row.justify-content-around.align-items-center
            .col-2
              img.mt-4.mb-4.ps-5(src="@/assets/curso/temas/tema2/admiracion.png")
            .col-10
              p.p-3.mb-0 <strong>Trazo y corte</strong>
              p.ps-3 En el proceso de trazo y corte se revisa y analiza el mejor aprovechamiento de los tejidos mediante técnicas de marcadas, dependiendo en gran parte, de la calidad de la confección de la prenda; por tal motivo, constituye una tarea determinante en el costo total del producto.

    br
    .row.justify-content-center.mb-4.mt-4
      .col-5
        h3.mt-4 ¿Qué es el trazo?
        p Procedimiento que se realiza sobre el material textil con jaboncillo o tiza, teniendo en cuenta las características dimensionales del tejido a cortar.
        .row
          .col-6
            ul.lista-ul--color.fa-ul.color-primario.ps-1
              li 
                i.fas.fa-plus
                | Patrones
              li
                i.fas.fa-plus
                | Escuadras o reglas
              li
                i.fas.fa-plus
                | Papel de trazo
              li
                i.fas.fa-plus
                | Lápices
          .col-6
            ul.lista-ul--color.fa-ul.color-primario.ps-1
              li 
                i.fas.fa-plus
                | Metro
              li
                i.fas.fa-plus
                | Jaboncillo de tiza
              li
                i.fas.fa-plus
                | Mesa
      .col-3
        img(src="@/assets/curso/temas/tema2/imagen10.svg", alt='Diseñadora')

    br
    .row.mt-4.mb-4
      p La marcación de las piezas que componen la prenda, sea manual o asistida por computador, requiere la adecuada distribución de los patrones sobre la extensión de la tela. El trazo se debe realizar por cada material, por ejemplo:
    
    .row.justify-content-center.mt-4.mb-4
      .col-9
        img(src="@/assets/curso/temas/tema2/imagen11.svg", alt='Diseñadora')
    
    .row.justify-content-center.mt-4.mb-4
      .col-9
        .cajon.color-primario 
          p.p-5.mb-0 <strong> Se debe tener en cuenta cantidades y tallas según orden de corte. En el caso del corte troquelado se realiza mediante el uso de plantillas colocadas a presión y se procede a cortar. </strong>

    Separador
    .row.mt-4.mb-4
      h3 ¿Qué es el corte?

    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema2/imagen12.svg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 El corte se define como el proceso de transformación de la materia prima textil (tejido o tela) en piezas útiles para confeccionar prendas de vestir, este proceso de transformación se realiza utilizando máquinas especializadas de corte o con tijeras convencionales.

    .row.justify-content-center.mt-4.mb-4
      .col-4
        p Para obtener excelentes resultados en el proceso de corte se requiere de:
        ul.lista-ul--color.fa-ul.color-primario.ps-1
          li 
            i.fas.fa-plus
            | Maquina de corte o tijeras convencionales
          li
            i.fas.fa-plus
            | Otras herramientas
      .col-4
        img(src="@/assets/curso/temas/tema2/imagen13.svg", alt='Diseño')

    
    .row.justify-content-center.mt-4.mb-4
      .col-4
        <br> <br>
        h3.mt-4.mb-4 Tipos de corte
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Manual")
            .col-md-12.mb-4.mb-md-0
              p.text-small Requiere la utilización de tijeras más o menos de 8 pulgadas, usadas solo para corte de tela; se colocan directamente los moldes y se procede a cortar.
          .row(numero="2" titulo="Convencional")
            .col-md-12.mb-4.mb-md-0
              p.text-small Utiliza maquinaria y equipos electromecánicos, disminuyendo la intervención de operaciones manuales.  
          .row(numero="3" titulo="Automático")
            .col-md-12.mb-4.mb-md-0
              p.text-small Comprende mesa, unidad de control conformado por el ordenador con software especializado, cabezal de corte y carro extendedor automático, permitiendo optimizar el espacio y tiempos de corte. 
      .col-4
        img.p-3(src="@/assets/curso/temas/tema2/imagen14.svg", alt='Modista cortando')

    Separador 
    h3.mb-4 Herramientas

    SlyderF(columnas="col-lg-6 col-xl-4")
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta3/imagen1.svg")
        p.text-center <strong>Patrones</strong>
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta3/imagen2.svg")
        p.text-center <strong>Reglas</strong>
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta3/imagen3.svg")
        p.text-center <strong>Metro</strong>
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta3/imagen4.svg")
        p.text-center <strong>Jaboncillo o tizas</strong>
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta3/imagen5.svg")
        p.text-center <strong>Papel trazo</strong>
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta3/imagen6.svg")
        p.text-center <strong>Mesa de corte</strong>

    <br> <br>
    .row.justify-content-center.mb-4.mt-4 
      .col-8
        h3.mb-4 Máquinas de corte industrial
        p Cortadoras automáticas - cortadora sin fin – cortadora vertical – cortadora circular – cortadora de mano – guante de malla.
        img(src="@/assets/curso/temas/tema2/imagen15.svg" alt="La imagen presenta varias cortadoras utilizadas en la confección textil, incluyendo una cortadora automática, una cortadora sin fin, una cortadora vertical, una cortadora circular y una cortadora de mano. Además, muestra un guante de malla que se utiliza como equipo de seguridad al manejar estas herramientas de corte.")

    Separador 
    .row.justify-content-center.mb-4.mt-4 
      .col-8
        h3.mb-4 Otras herramientas
        p Tijeras – punzón – máquina perforadora – agujas o alfileres para sujeción textil
        img(src="@/assets/curso/temas/tema2/imagen16.svg" alt="La imagen muestra herramientas esenciales para la confección textil, incluyendo tijeras, un punzón, una máquina perforadora y agujas o alfileres para la sujeción del textil. Cada herramienta está ilustrada con su respectiva etiqueta, indicando su uso específico en el proceso de confección.")

    <br>
    .row.justify-content-center.align-items-center.mb-4.mt-4
      .col-4
        h3.mb-4 Urdimbre y trama
        ul.lista-ul--color.fa-ul.color-primario
          li 
            i.fas.fa-plus
            | <strong>Urdimbre:</strong> la serie longitudinal de los hilos recibe el nombre de urdimbre, y cada uno de los elementos que la constituyen se denomina hilo. Los hilos verticales son la urdimbre.
          li
            i.fas.fa-plus
            | <strong>Trama:</strong> la serie transversal recibe el nombre de trama, y cada una de sus unidades se denomina pasada. Las pasadas horizontales son la trama
      .col-4
        img(src="@/assets/curso/temas/tema2/imagen17.png" )

    <br>
    .row.justify-content-center.align-items-center.mb-4.mt-4
      .col-4
        img(src="@/assets/curso/temas/tema2/imagen18.png" )
      .col-4
        h3.mb-4 Hilo de tela
        p El hilo de tela se conoce también como sentido de hilo, y se refiere a la dirección que siguen los hilos de urdimbre (longitudinal) y trama (transversal).
        p La línea que atraviesa la urdimbre y la trama en sentido diagonal es conocida con el nombre de sesgo o bies.

    <br>
    .row.justify-content-center.align-items-center.mb-4.mt-4
      .col-8
        h3.mb-4 Sesgo o bies
        p Se llama sesgo o bies al sentido diagonal de las telas en un ángulo de 45° grados; diagonal o al sesgo aporta mejor caída y cierta elasticidad. En algunos casos es necesario cortar las piezas de una prenda al sesgo debido a su diseño.
        img(src="@/assets/curso/temas/tema2/imagen19.png" alt="La imagen ilustra la orientación de los patrones en la tela, mostrando las direcciones del recto hilo, el contrahílo y el bies. A la izquierda, se presenta un cuadrado de tela con las direcciones señaladas. A la derecha, se muestra cómo colocar los patrones en la tela, alineándolos según el recto hilo y el centro del pliegue para asegurar un corte preciso y adecuado. " )

    Separador
    .row.justify-content-center.align-items-center.mb-4.mt-4
      .col-7
        h3.mb-4.text-center En el material textil
        img(src="@/assets/curso/temas/tema2/imagen20.png" alt="La imagen muestra dos rollos de material textil desenrollados parcialmente, ilustrando las direcciones del recto hilo, el contrahílo y el bies. En el rollo de la izquierda, se indican las direcciones con flechas y etiquetas, mostrando cómo identificar el sesgo o bies, el largo de la tela y el orillo o borde. En el rollo de la derecha, se repiten las indicaciones para el largo de la tela, el orillo y el sesgo o bies. Estas directrices son esenciales para cortar la tela correctamente y asegurar la orientación adecuada de las piezas del patrón. " )

    h3.mt-4.mb-4 Anchos de las telas
    p Los anchos de las telas que se pueden encontrar normalmente en los puntos de venta tienen diferentes medidas que suelen estar normalizados. Estos anchos vienen de fábrica y se dividen en:
    <br>

    .row.mt-4.mb-4
      .col-sm-6.col-lg-3.mb-4.mb-lg-0
        .tarjeta--boton.color-adicional-2.p-4
          .row.justify-content-center.mb-3
            .col-7
              img(src="@/assets/curso/temas/tema2/tarjeta4/imagen1.png")
          h3.text-center Ancho simple
          p.text-small Están elaborados a partir de 70 cm a 90 cm de ancho, en este grupo se encuentran cambre, paños, fieltro, blonda, satén, lino, etc.
      .col-sm-6.col-lg-3.mb-4.mb-lg-0
        .tarjeta--boton.color-adicional-2.p-4
          .row.justify-content-center.mb-3
            .col-7
              img(src="@/assets/curso/temas/tema2/tarjeta4/imagen2.png") 
          h3.text-center Ancho angosto
          p.text-small Están elaborados a partir de 0,5 mm hasta 25 cm de ancho, en este grupo se encuentran los encajes, franjas, cintas, elásticos, etc.
      .col-sm-6.col-lg-3.mb-4.mb-sm-0
        .tarjeta--boton.color-adicional-2.p-4
          .row.justify-content-center.mb-3
            .col-7
              img(src="@/assets/curso/temas/tema2/tarjeta4/imagen3.png") 
          h3.text-center Ancho doble
          p.text-small Están elaborados a partir de 140 cm y 150 cm de ancho, en este grupo se encuentran paños, tafetán, popelina, crepé, entretelas, denim, etc.
      .col-sm-6.col-lg-3
        .tarjeta--boton.color-adicional-2.p-4
          .row.justify-content-center.mb-3
            .col-7
              img(src="@/assets/curso/temas/tema2/tarjeta4/imagen4.png") 
          h3.text-center Ancho especial
          p.text-small Están elaborados a partir de 2,80 cm, en este grupo se encuentran la tapicería y la decoración.
          <br>

    <br> <br>
    .row.justify-content-center.mb-4.mt-4
      .col-3
        h3.mb-4 Orillos de tela
        p Son los bordes longitudinales de la tela, están tejidos con una apariencia diferente y densa, como consecuencia de tratamientos de humectación y secado, que sufren una vez han sido tejidas para su estabilización.
      .col-6
        img(src="@/assets/curso/temas/tema2/imagen21.png" )

    br
    .row.justify-content-center.mb-4.mt-4
      .col-8
        .tarjeta.color-acento-botones.borde-redondo
          .row.justify-content-around.align-items-center
            .col-2
              img.mt-4.mb-4.ps-5(src="@/assets/curso/temas/tema2/admiracion.png")
            .col-10
              p.p-3.mb-0 <strong>¿Cómo surgen?</strong>
              p.ps-3 Los agujeritos de los orillos son realizados por unas plaquetas de agujas situadas en los laterales de los hornos encargados de secar las telas y que hacen que estas se mantengan sujetas y estiradas en su ancho durante todo el proceso. Suelen perforar el tejido desde el revés hacia el derecho, por lo que, por regla general, las rebabas de las perforaciones en los orillos indican el <strong>derecho de la tela.</strong>

    br
    .row.justify-content-center.mt-4.mb-4
      .col-8
        h3 Tipos de orillos
        p El propósito del orillo es que la tela no se deshilache. Según el diseño o fabricante los orillos de la tela se dividen en:

    
    .row.justify-content-center.mt-4.mb-4
      .col-4
        <br> <br>
        h3 Tipos de corte
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Orillo metido")
            .col-md-12.mb-4.mb-md-0
              p.text-small Una aguja especial en forma de gancho impulsada por una leva, después de que esta se corta, la inserción del extremo del hilo retorna, formando así un borde fuerte. Este sistema es usado generalmente en las telas de peso ligero a medio.
          .row(numero="2" titulo="Orillo leno")
            .col-md-12.mb-4.mb-md-0
              p.text-small Estos orillos se obtienen uniendo la trama con fuertes hilos adicionales y eliminando mediante corte los extremos de la trama que sobresalen. Este sistema es usado generalmente en las telas de peso pesado.  
          .row(numero="3" titulo="Orillo de puntada cadeneta")
            .col-md-12.mb-4.mb-md-0
              p.text-small Este tipo de orillo se produce mayoritariamente en un mecanismo de tejido de punto, se realiza principalmente en una máquina de tejer por medio de agujas. 
          .row(numero="4" titulo="Orillos fusionados")
            .col-md-12.mb-4.mb-md-0
              p.text-small Se obtiene presionando unos elementos mecánicos calientes en el borde de la tela, este método se puede aplicar en textiles de fibras sintéticas. 
          .row(numero="5" titulo="Orillos lisos")
            .col-md-12.mb-4.mb-md-0
              p.text-small Este tipo de orillo también llamado orillo de estampación es usado para controlar los colores básicos que tiene el dibujo, enumerándolos en el orden de estampación, además añade la marca del fabricante. 
          .row(numero="6" titulo="Orillos de cinta")
            .col-md-12.mb-4.mb-md-0
              p.text-small Este tipo de orillo es utilizado por los fabricantes de textiles clásicos como paños, también tejen sus nombres en el orillo para que sean identificados fácilmente en las sastrerías a medida. 
      .col-4
        img.p-3.mt-4(src="@/assets/curso/temas/tema2/imagen22.png", alt='telas')

    Separador    
    .row.mb-4
      .titulo-segundo.color-primario
        h2 2.3  Proceso de extendido

    .row.justify-content-center.mt-4.mb-4
      .col-4
        .tarjeta--boton.p-4(style="background-color: white")
          h3 ¿Qué es el extendido?
          p.text-small El tendido o extendido consiste en ubicar la tela sobre una superficie plana (mesa de corte), ya sea una capa de tela o varias según la orden de producción; se extiende la tela considerando las características del textil, se prepara y selecciona los materiales e instrumentos necesarios para la ejecución de la tarea; el extendido se puede realizar de dos formas:
          ul.lista-ul--color.fa-ul.color-primario
            li 
              i.fas.fa-plus
              | Con carro extendedor (manual y automático)
            li
              i.fas.fa-plus
              | Manual
      .col-3
        .tarjeta--boton.p-4(style="background-color: #FFF5D3")
          .row.justify-content-center.mb-3
            .col-7
              img(src="@/assets/curso/temas/tema2/tarjeta5/imagen1.png") 
          h3.text-center Con carro extendedor
          p.text-small.text-center Extendedora automática, extendedora de codo.
          <br>
      .col-3
        .tarjeta--boton.p-4(style="background-color: #FFF5D3")
          .row.justify-content-center.mb-3
            .col-7
              img(src="@/assets/curso/temas/tema2/tarjeta5/imagen2.png") 
          h3.text-center Manual
          p.text-small.text-center Extendedora de carro o coche.
          <br> <br>

    .row.justify-content-center.align-items-center.mt-4.mb-4
      h3.mt-4.mb-4.text-center Herramientas
      .row.justify-content-center.align-items-center
        .col-9
          img(src="@/assets/curso/temas/tema2/imagen23.png" alt="La imagen muestra tres herramientas utilizadas en la confección textil: pesas, pinzas y agujas o alfileres para sujeción textil. Estas herramientas son esenciales para asegurar y manipular las piezas de tela durante el proceso de corte y ensamblaje. ") 

    <br>
    .row.justify-content-center.align-items-center.mt-4.mb-4
      .col-3
        img.p-3(src="@/assets/curso/temas/tema2/imagen24.svg") 
      .col-3
        h3.mt-4.mb-4 Extendido manual
        p En el extendido manual se sitúa la pieza de textil en un extremo de la mesa, mientras dos operarios efectúan el estirado de la tela (pueden también utilizar un carro de extendido) hasta el largo previamente establecido.

    .row.justify-content-center.align-items-center.mt-4.mb-4
      h3.mt-4.mb-4.text-center Recomendaciones:

    .row.justify-content-center.mt-4.mb-4
      .col-4
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Alineación")
            .col-md-12.mb-4.mb-md-0
              p.text-small Se recomienda que el textil se encuentre completamente alineado al orillo, de ser posible alinear los dos orillos.
          .row(numero="2" titulo="Tensión")
            .col-md-12.mb-4.mb-md-0
              p.text-small En lo posible evitar la tensión en la tela, ya que después del corte las piezas pueden quedar reducidas (pequeñas con relación al tamaño real del molde).  
          .row(numero="3" titulo="Arrugas")
            .col-md-12.mb-4.mb-md-0
              p.text-small Evitar que la tela se encuentre arrugada en el tendido para que no se formen burbujas de aire, que ocasionan distorsiones en el corte. 
          .row(numero="4" titulo="Consumo")
            .col-md-12.mb-4.mb-md-0
              p.text-small Cortar solamente lo necesario para evitar más consumo de tela, controlando el desperdicio de acuerdo con la acomodación de los moldes. 
      .col-4
        img.p-3.mt-4(src="@/assets/curso/temas/tema2/imagen25.svg")

    .row.justify-content-center.align-items-center.mt-4.mb-4
      .col-4
        img.p-3(src="@/assets/curso/temas/tema2/imagen26.svg") 
      .col-4
        h3.mt-4.mb-4 Preparación del textil
        p Algunos textiles se pueden encoger o aumentar después de ser sometidos al lavado o planchado, por tal motivo, se sugiere que antes de realizar cualquier proceso de extendido y corte, el textil sea sometido a lo siguiente:
        ul.lista-ul--color.fa-ul.color-primario
          li 
            i.fas.fa-plus
            | Pruebas de % de elongación o reducción
          li
            i.fas.fa-plus
            | Pruebas de fusionado
          li
            i.fas.fa-plus
            | Pruebas de fusionado
          li
            i.fas.fa-plus
            | Lavado 
          li
            i.fas.fa-plus
            | Planchado
          li
            i.fas.fa-plus
            | Identificación de defectos textiles

    .row.mt-4.mb-4
      h3.mb-4 Disposición de la tela sobre la mesa
      p Extienda el textil sobre la mesa y defina el tipo de extendido de acuerdo con los patrones que desea trabajar: 

    .row.borde-redondo.mt-4.mb-4(style="background-color: #F8F5FF")
      SlyderB.mb-5.mt-5(:datos="datosSlyder")

    .row.mt-4.mb-4
      h3.mb-4.mt-4 Extendido industrial
      p El proceso de extendido industrial se realiza a través del software especializado (CAD, sistemas de diseño asistido por computador: Optitex, Lectra, Audaces). Este proceso se realiza según las especificaciones de la orden de corte o ficha técnica. Los extendidos utilizados en la industria son:

    AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--white")
      .row.borde-redondo-tmorada(titulo="Extendido cara arriba")
        .col-md-4.mb-4.mb-md-0
          p.p-5 La capa de tela se extiende según el largo del trazo, es importante determinar cuál es el derecho de la tela, ya que esta debe quedar mirando hacia arriba con respecto a la mesa. Se extiende la capa desde el inicio del trazo hasta el final del largo del trazo y se procede a cortar; nuevamente se desplaza la siguiente capa desde el inicio y se repite el proceso el número de veces que requiera las capas.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema2/tarjeta7/imagen1.svg")
      .row.borde-redondo-tmorada(titulo="Extendido al lomo o doblez de tela")
        .col-md-4.mb-4.mb-md-0
          p.p-5 Se realiza cuando la tela se dobla a la mitad de su ancho, se une orillo con orillo formando un doblez de tela en un extremo, conocido como lomo. Al doblar la tela queda derecho con derecho, lo que se denomina careado o cara a cara. Este tipo de extendido se utiliza para cortar prototipos, es utilizado por modistas o sastres.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema2/tarjeta7/imagen2.svg")
      .row.borde-redondo-tmorada(titulo="Extendido cara a cara")
        .col-md-4.mb-4.mb-md-0
          p.p-5 La capa de tela se extiende según el largo del trazo, es importante determinar cuál es el derecho de la tela, ya que la primera capa debe quedar con el derecho hacia arriba con respecto a la mesa. Se extiende la capa desde el inicio del trazo hasta el final del largo del trazo y se procede a cortar.
          p.ps-5 Se repite el proceso con la siguiente capa, pero teniendo en cuenta que esta debe quedar con el derecho de tela hacia abajo, quedando cada a cara con la primera capa. Las siguientes capas deben quedar en pares, derecho con derecho de la tela.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema2/tarjeta7/imagen3.svg")
      .row.borde-redondo-tmorada(titulo="Extendido zigzag")
        .col-md-4.mb-4.mb-md-0
          p.p-5 El proceso es igual al extendido cara a cara, la diferencia es que no se cortan los extremos. Una vez llegado al extremo dobla sobre sí mismo para hacer el recorrido en sentido contrario. De esta forma las capas de tela deben quedar pares cara con cara y revés con revés.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema2/tarjeta7/imagen4.svg")
      .row.borde-redondo-tmorada(titulo="Extendido escalonado o espiga")
        .col-md-4.mb-4.mb-md-0
          p.p-5 Es un extendido cara arriba en el que los largos de las capas de tela no son iguales. Las capas más largas se colocan debajo y las más cortas se colocan arriba formando un escalón, este tipo de extendido se emplea para ajustar en un solo trazo diferentes cantidades en relación con tallas y colores de prendas a cortar.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema2/tarjeta7/imagen5.svg")

    Separador    
    .row.mb-4.mt-4
      .titulo-segundo.color-primario
        h2 2.4  Tipos de trazo
    
    .row.mb-4.mt-4
      h3.text-center Tipos de trazo según requerimientos de patronaje:

    .row.justify-content-center.mt-4.mb-4
      .col-3
        .tarjeta.color-acento-botones.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta8/imagen1.png")
          p.text-center <strong>Requerimientos desde patronaje</strong>
      .col-3
        .tarjeta.color-primario.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta8/imagen2.png")
          p.text-center.color-white <strong>Tendido y marcación</strong>
      .col-3
        .tarjeta.color-acento-botones.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta8/imagen3.png")
          p.text-center <strong>Características del material</strong>
    
    <br> <br>
    .row.justify-content-center.mb-4.mt-4
      .col-5
        h3 Señalización
        p Para tener claro los requerimientos desde el área de patronaje es importante identificar y conocer la respectiva señalización de patrones:
        .row
          .col-6
            ul.lista-ul--color.fa-ul.color-primario
              li 
                i.fas.fa-plus
                | Hilo de tela
              li
                i.fas.fa-plus
                | Referencia o diseño
              li
                i.fas.fa-plus
                | Nombre de la pieza
              li
                i.fas.fa-plus
                | Número de veces a cortar
          .col-6
            ul.lista-ul--color.fa-ul.color-primario
              li 
                i.fas.fa-plus
                | Tipo de material
              li
                i.fas.fa-plus
                | Número de pieza en el tendido
              li
                i.fas.fa-plus
                | Piquetes 
              li
                i.fas.fa-plus
                | Plantilla
      .col-3
        img.p-3(src="@/assets/curso/temas/tema2/imagen27.svg")

    <br> <br>
    .row.mb-4.mt-4
      h3.text-center Señalización – Hilos de tela
      p.text-center Para tener claro los requerimientos desde el área de patronaje es importante identificar y conocer la respectiva señalización de patrones:

    .row.justify-content-center.mt-4.mb-4
      .col-3
        .tarjeta.color-primario.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta9/imagen1.png")
          p.text-center <strong>Urdimbre</strong>
      .col-3
        .tarjeta.color-acento-botones.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta9/imagen2.png")
          p.text-center.color-white <strong>Trama</strong>
      .col-3
        .tarjeta.color-primario.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta9/imagen3.png")
          p.text-center <strong>Sesgo o bies</strong>
      p.mb-4.mt-4.text-center Hilo de tela una cabeza hacia arriba, hilo de tela una cabeza hacia abajo, hilo de tela una cabeza doble.


    .row.justify-content-center.mt-4.mb-4(style="background-color: #FFFAE9")
      .col-3.mt-5
        h3 Trazo bidireccional, vello en ambos sentidos
        p Este trazo/marcado se realiza cuando el hilo de tela tiene la cabeza doble; se pueden colocar los patrones en dos sentidos de dirección. El material textil que se utilice no debe tener restricción con respecto a sus características. Hilo de tela una cabeza doble. 
      .col-5.mb-5.mt-5
        img(src="@/assets/curso/temas/tema2/imagen28.png", alt="La imagen muestra cómo posicionar patrones de una prenda en la tela, destacando la orientación del hilo de tela. Se observan tres piezas del patrón con flechas rojas que indican la dirección del hilo. Las instrucciones resaltan la necesidad de colocar el hilo de la tela de una camisa hacia arriba o hacia abajo según corresponda, asegurando que todas las piezas se corten correctamente alineadas con el hilo para mantener la coherencia en el diseño final de la prenda.")

    .row.justify-content-center.mt-4.mb-4
      .col-7
        h3.text-center.mt-5.mb-4 Bidireccional, vello en ambos sentidos
        img(src="@/assets/curso/temas/tema2/imagen29.png", alt="La imagen muestra la disposición de patrones en la tela, destacando la orientación correcta respecto al borde cortado y el orillo. En ambos ejemplos, las piezas del patrón están alineadas con flechas rojas que indican la dirección del hilo. A la izquierda, las piezas están colocadas cerca del orillo y el borde cortado, mientras que a la derecha, las piezas están alineadas con el orillo y el borde cortado de la tela, asegurando que las piezas se corten correctamente siguiendo la dirección del hilo para una confección precisa.")
    br
    .row.justify-content-center.mt-4(style="background-color: #E8DDFF")
      .col-4
        h3.mt-5 Trazo direccional, vello en un solo sentido
        p Este trazo/marcado se realiza cuando el hilo de tela tiene la cabeza sea hacia arriba o hacia abajo; se deben colocar los patrones en un sentido de dirección. El procedimiento de marcado tendrá por resultado un producto con la más elevada calidad. Este tipo de trazo se usa para materiales que tienen restricción con respecto a sus características en cuanto a brillo, cambio de color al tacto, estampados, dirección de pelo/vello, entre otros.
        p Hilo de tela una cabeza hacia arriba - Hilo de tela una cabeza hacia abajo
      .col-3
        img.mt-5.mb-5(src="@/assets/curso/temas/tema2/imagen30.png", alt="La imagen muestra dos piezas de un patrón de prenda, destacando la orientación del hilo de la tela. Una pieza tiene la flecha del hilo apuntando hacia arriba, indicando “hilo de tela una cabeza hacia arriba”, y la otra pieza tiene la flecha del hilo apuntando hacia abajo, indicando “hilo de tela una cabeza hacia abajo”. Estas instrucciones aseguran que las piezas del patrón se coloquen correctamente en la tela para mantener la consistencia del diseño y la estructura de la prenda.")

    .row.justify-content-center.mt-4.mb-4
      .col-7
        h3.text-center.mt-5.mb-4 Direccional - vello en un solo sentido
        img(src="@/assets/curso/temas/tema2/imagen31.png", alt="La imagen muestra la colocación de patrones en la tela, destacando la dirección del hilo. A la izquierda, las piezas del patrón están alineadas con flechas rojas que apuntan hacia el orillo de la tela, marcadas como “fold” (dobladillo) y “selvage edge” (orillo). A la derecha, las piezas del patrón también están alineadas con flechas que indican la dirección del hilo y se colocan cerca del orillo y el borde cortado de la tela. Estas guías aseguran que las piezas se corten correctamente para mantener la estructura y el diseño adecuado de la prenda.")
    br

    .row.justify-content-center.mt-4.mb-4(style="background-color: #FFFAE9")
      .col-4.mt-5
        h3 Señalización
        ul.lista-ul--color.fa-ul.color-primario
          li 
            i.fas.fa-plus
            | <strong>Referencia o diseño:</strong> ref:20201208
          li
            i.fas.fa-plus
            | <strong>Nombre de la pieza:</strong> delantero o frente
          li
            i.fas.fa-plus
            | <strong>Número de veces a cortar o marcadas:</strong> x 3 veces
          li
            i.fas.fa-plus
            | <strong>Tipo de material:</strong> x 1 v material base   x 1 v material forro  x 1 v material entretela
          li
            i.fas.fa-plus
            | <strong>Número de pieza en el tendido:</strong> 1/2
      .col-2.mb-2.mt-5.mb-4
        img(src="@/assets/curso/temas/tema2/imagen32.png", alt="La imagen muestra una pieza de patrón de una prenda, específicamente una camisa sin mangas, con una flecha roja que indica la dirección del hilo de tela desde arriba hacia abajo. Esto asegura que la pieza del patrón se alinee correctamente con el hilo de la tela durante el corte para mantener la integridad y el ajuste del diseño final de la prenda.")

    Separador    
    .row.mb-4.mt-4
      .titulo-segundo.color-primario
        h2 2.5  Tendido marcación y corte
      h3.mt-4.mb-4 Introducción
      p El tendido y marcación son una parte clave para el proceso de corte, este procedimiento requiere de precisión y técnica. Una vez identificados los requerimientos desde el área de patronaje se procede a realizar el tendido y marcación, para ello es importante seguir los siguientes pasos:
      img.mb-4.mt-4(src="@/assets/curso/temas/tema2/imagen33.png")
      h3.mt-4.mb-4 Ancho útil
      p Es importante identificar el ancho útil del material textil antes de empezar a desarrollar el trazo; se sugiere lo siguiente:
      img.mb-4.mt-4(src="@/assets/curso/temas/tema2/imagen34.png")
      p.mb-4.mt-4.text-center El ancho útil se halla restando al ancho total de la tela, el orillo.
    .row.justify-content-center
      .col-7
        img(src="@/assets/curso/temas/tema2/imagen35.png")
    Separador 

    .row.mb-4.mt-4
      h3 Ubicar patrones
      p Una vez identificado, analizado y alistado:
    
    .row.justify-content-center
      .col-9
        img(src="@/assets/curso/temas/tema2/imagen36.png")

    .row.justify-content-center.mt-4.mb-4
      p.text-center Se procede a hacer el trazo o marcación del molde o patrón en el textil.
      .col-7
        img.mt-4(src="@/assets/curso/temas/tema2/imagen37.png")
    
    .row.mt-4.mb-4
      h3 ¿Cómo transferir patrones?

    .row.mt-4.mb-4.justify-content-center
      .col-9
        img(src="@/assets/curso/temas/tema2/imagen38.png")

    .row.mt-4.mb-4.justify-content-center
      .col-4
        img(src="@/assets/curso/temas/tema2/imagen39.png")
    
    Separador 
    .row.mt-4.mb-4
      h3 Tipos de marcación 
      p Para transferir patrones al textil existen dos formas que son las más implementadas.

    SlyderF(columnas="col-lg-6 col-xl-4")
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta10/imagen1.png")
        p.text-center <strong>Tiza de cal</strong>
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta10/imagen2.png")
        p.text-center <strong>Jabón regular</strong>
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta10/imagen3.png")
        p.text-center <strong>Lapiz tela</strong>
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta10/imagen4.png")
        p.text-center <strong>Marcador tela</strong>
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta10/imagen5.png")
        p.text-center <strong>Rodaja</strong>
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta10/imagen6.png")
        p.text-center <strong>Papel onix o calco</strong>
    
    .row.justify-content-center.align-items-center.mb-4.mt-4
      .col-3
        p Es el método más utilizado por los sastres para marcaciones especiales sobre el textil; este método tiene puntos con hebras de hilo que sirven de guía, sin llegar a manchar el textil. Esta es una puntada suelta en bucle como una indicación de dónde coser finalmente.
      .col-3
        img(src="@/assets/curso/temas/tema2/imagen40.svg")
    
    br
    .row.align-items-center.justify-content-center.mt-4.mb-4
      .col-7
        h3.mt-4.mb-4 Tipos de marcación, alfileres
        p Fijar patrones con alfileres. Los alfileres vienen en una variedad de tamaños. Si la tela es gruesa use alfileres grandes y largos, si la tela es delgada y delicada como la seda utilice alfileres pequeños y cortos para evitar dañarla.
        .cajon.color-primario 
          p.p-5 <strong> Inserte los alfileres cada 3 cm al rededor del patrón y en puntos claves, evite coger mucha cantidad del textil para evitar los bucles y malformaciones a la hora de pinar, es recomendable ubicar los alfileres de forma diagonal.</strong>
      .col-3.p-3
        img(src="@/assets/curso/temas/tema2/imagen41.svg")

    .row.justify-content-center.mb-4.mt-4
      .col-6
        .tarjeta.color-acento-botones.borde-redondo
          .row.justify-content-around.align-items-center
            .col-3
              img.mt-4.mb-4.ps-5(src="@/assets/curso/temas/tema2/admiracion.png")
            .col-9
              p.p-3.mb-0 <strong>Pinar</strong>
              p.ps-3 Insertar alfileres en el textil para asegurar el molde.

    <br> <br>
    .row.justify-content-center.mt-4.mb-4
      .col-3
        p <strong>Lo que no se debe hacer</strong>
        ul.lista-ul--color.fa-ul.color-primario.ps-1
          li 
            i.fas.fa-plus
            | Asegurar con cinta
          li
            i.fas.fa-plus
            | No fijar los patrones
          li
            i.fas.fa-plus
            | No cortar el margen del patrón de forma inadecuada
          li
            i.fas.fa-plus
            | Marcar con tiza de forma inadecuada
      .col-3
        img(src="@/assets/curso/temas/tema2/imagen42.svg")

    Separador 
    .row.mb-4.mt-4
      h3 Proceso de corte

    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema2/imagen43.svg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Luego de realizar y seguir cada uno de los pasos para una adecuada calidad del proceso, se continúa con el corte del textil de acuerdo con la marcación. Para ello, es importante conocer las herramientas fundamentales para este proceso y elegir las adecuadas, lo cual garantiza un mejor trabajo.
    
    .row.mb-4.mt-4
      p <strong>Herramientas</strong>

    SlyderF(columnas="col-lg-6 col-xl-4")
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta11/imagen1.png")
        p.text-center <strong>Tijeras castellana</strong>
        p.text-small Tienen los dos orificios para los dedos del mismo tamaño, suelen tener un tamaño medio y son bastante ligeras, se recomiendan para textiles de peso liviano.
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta11/imagen2.png")
        p.text-center <strong>Tijeras sastre</strong>
        p.text-small Uno de los lados de la hoja no sobresale a su mango, permitiendo de esta manera apoyar las tijeras en la mesa a la hora de cortar la tela; tienen un tamaño y peso mayor. Se recomiendan para textiles de peso mediano a pesado.
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta11/imagen3.png")
        p.text-center <strong>Tijeras zigzag</strong>
        p.text-small Poseen dientes en las hojas, lo que crea un patrón de corte en zig zag. La función principal de este tipo de tijeras es la de evitar que se deshilache el textil después del corte.
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta11/imagen4.png")
        p.text-center <strong>Cortadores térmicos</strong>
        p.text-small Estos cortadores se emplean para el corte de acrílico y textiles. Una vez cortada la tela queda sellada y no se deshilacha.
      .tarjeta.color-acento-contenido.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src="@/assets/curso/temas/tema2/tarjeta11/imagen5.png")
        p.text-center <strong>Cúter rotatorio</strong>
        p.text-small Se caracteriza por ser el mejor cortador para telas, lonas, láminas plásticas, hule, vinilos y otros materiales textiles tejidos o no tejidos (fieltro). Su mango facilita el manejo, perfección y agilidad a la hora de cortar, se puede apoyar con reglas y otros elementos para una mejor precisión del corte.

    <br> <br>
    .row.justify-content-center.mt-4.mb-4
      .col-3
        p <strong>Tips de corte</strong>
        br
        ul.lista-ul--color.fa-ul.color-primario
          li 
            i.fas.fa-plus
            | Con una mano sostenga la tela y con la otra realice el corte 
          li
            i.fas.fa-plus
            | Realice cortadas amplias
          li
            i.fas.fa-plus
            | El tendido no se mueve, lo que se mueve son las tijeras, la mano y el operario a medida que se va cortando.
          li
            i.fas.fa-plus
            | En cada piquete, hacer un pequeño corte de máximo 3 mm de profundidad.
      .col-3
        img(src="@/assets/curso/temas/tema2/imagen44.svg")

    Separador    
    .row.mb-4.mt-4
      .titulo-segundo.color-primario
        h2 2.6  Características del material
      h3.text-center.mt-4.mb-4 Tipos de trazo

    .row.justify-content-center.mt-4.mb-4
      .col-3
        .tarjeta.color-primario.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta12/imagen1.png")
          p.text-center <strong>Requerimientos desde patronaje</strong>
      .col-3
        .tarjeta.color-acento-botones.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta12/imagen2.png")
          p.text-center.color-white <strong>Tendido y marcación</strong>
      .col-3
        .tarjeta.color-primario.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta12/imagen3.png")
          p.text-center <strong>Características del material</strong>
    
    .row.mb-4.mt-4
      p.mt-4.mb-4 <strong>Tipos de trazo</strong>
      p.mb-0 El reconocimiento de las características del material textil a trabajar es sumamente importante para asegurar una calidad óptima en la prenda al cortar y ensamblar. Antes de cada proceso de tendido, marcación y corte se deben verificar dichas características.
    
    .row.justify-content-center.mb-4-mt-4
      .col-7
        img.p-4(src="@/assets/curso/temas/tema2/imagen45.png")

    <br> <br>
    .row.justify-content-center.mb-4-mt-4
      .col-3
        p <strong>¿Qué es la textura nap (velvet, pelusa, fleece)?</strong>
        p Nap es la textura de los textiles que van en una dirección particular. Esta propiedad de la prenda es fundamental para garantizar la calidad de la misma. En algunos textiles se logra evidenciar el nap a simple vista como velvet, fleece, piel sintética, denim cepillado, franela, gamuza sintética, sarga, elástica, tela de felpa, etc.
      .col-3
        img.p-4(src="@/assets/curso/temas/tema2/imagen46.svg")

    .row.justify-content-center.mb-4.mt-4
      .col-8
        .tarjeta.color-acento-botones.borde-redondo
          .row.justify-content-around.align-items-center
            .col-2
              img.mt-4.mb-4.ps-5(src="@/assets/curso/temas/tema2/admiracion.png")
            .col-10
              p.ps-3.mb-0 <strong>¿Por qué es importante el nap?</strong>
              p.ps-3.mb-0 El nap es muy importante para determinar cómo se establece el patrón en el textil, en este caso se trabaja siempre un trazo direccional. Se debe tener en cuenta lo siguiente:

    .row.justify-content-center-aling-items-center
      .col-2
      .col-4
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/uno.svg' alt='AvatarTop')
          .tarjeta.cajonmorado.borde-redondo
            .text-dark.p-4
              p.text-center(style="color: white") <strong>Acabados de la prenda</strong>
              p.text-center(style="color: white") Si no se tiene en cuenta el nap al momento de cortar la prenda, la prenda terminaría con brillos diferentes en cada pieza, necesitan un color y una textura uniforme en toda la pieza.
      .col-4
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema2/dos.svg' alt='AvatarTop')
          .tarjeta.cajonmorado.borde-redondo
            .text-dark.p-4
              p.text-center(style="color: white") <strong>Determinar el consumo del textil</strong>
              p.text-center(style="color: white") Se debe determinar el consumo de material que requiere la prenda para garantizar que todo el textil sea suficiente para el corte, lo cual es una clara desventaja, ya que se desperdicia mucha tela al seguir un trazo direccional.
      .col-2  

    <br> <br>
    .row.justify-content-center.mb-4-mt-4
      .col-3
        p <strong>¿Cómo identificar el nap?</strong>
        p Al pasar las manos suavemente por el textil para sentir el nap/pelusa
        ul.lista-ul--color.fa-ul.color-primario
          li 
            i.fas.fa-plus
            | La sensación más suave es la dirección con nap/pelusa
          li
            i.fas.fa-plus
            | La sensación más áspera es la dirección contraria al nap/pelusa
          li
            i.fas.fa-plus
            | El brillo de la tela es diferente cuando se ve desde diferentes direcciones
      .col-3
        img(src="@/assets/curso/temas/tema2/imagen48.svg")

    .row.mb-4-mt-4
      p <strong>Trazo o marcado</strong>
      p Se recomienda que cuando se utilice este tipo de textiles con nap, el proceso de transferir los moldes al textil se trabaje preferiblemente en un tendido abierto, sujetado con alfileres. Para marcar pinzas o elementos clave se recomienda los hilvanes o tailor tacks.
      .row.justify-content-center
        .col-7
          img(src="@/assets/curso/temas/tema2/imagen49.svg")

    <br> <br>
    .row.justify-content-center.mb-4-mt-4
      .col-3
        p <strong>Piel sintética</strong>
        p La piel sintética también cuenta con nap/siesta que es mucho más sencilla para identificar la dirección del vello. En este caso se debe trabajar:
        ul.lista-ul--color.fa-ul.color-primario
          li 
            i.fas.fa-plus
            | Trazo direccional
          li
            i.fas.fa-plus
            | Tendido abierto
          li
            i.fas.fa-plus
            | Marcación por el revés con tiza
        p Algunas tienen el vello más largo que otras, por eso es importante realizar un trazo, marcado y corte de forma adecuada.
      .col-3
        img.mt-5(src="@/assets/curso/temas/tema2/imagen50.svg")

      .row.mt-4.mb-4
        p <strong>Tips de corte, piel sintética</strong>
        p Cortar en el sentido del nap/vello. Realice cortadas pequeñas, preferible con la punta de la tijeras. Una vez cortado se sugiere eliminar el exceso de vello/pelo por el margen de costura, teniendo en cuenta la dirección del pelo se recomienda confeccionarlo en esa misma dirección.
        .row.justify-content-center
          .col-6
            img.mt-5(src="@/assets/curso/temas/tema2/imagen51.svg")

    <br> <br>
    .row.justify-content-center.mb-4-mt-4
      .col-4
        p <strong>Textiles estampados</strong>
        p Los textiles estampados también se deben trabajar con un trazo direccional, ya que de esto depende la dirección del estampado que se desee en la prenda terminada. Esto significa que todas las piezas deben cortarse en la misma dirección para que el estampado quede acorde al diseño.
      .col-4
        img(src="@/assets/curso/temas/tema2/imagen52.svg" alt="La imagen muestra el proceso de colocar patrones sobre la tela para el corte. En la parte superior derecha, se ve una tela extendida con varias piezas del patrón colocadas, alineadas con el hilo y el orillo de la tela. En la parte inferior izquierda, se muestran dos piezas del patrón, con una marcada como “centro frente”, indicando la alineación central en la tela. Estas imágenes enfatizan la importancia de alinear correctamente los patrones con el hilo y el orillo de la tela para garantizar precisión en el corte y la confección de la prenda.")

    .row.align-items-center.justify-content-center.mt-4
      .col-3.p-3
        img(src="@/assets/curso/temas/tema2/imagen53.svg")
      .col-7
        p <strong>Textiles de cuadros</strong>
        p La continuidad de las líneas y el dibujo/cuadros en las prendas producen un efecto agradable a la vista.
        .cajon.color-primario 
          p.p-5 <strong> Hacer coincidir cada una de las líneas, cuadros o elementos del dibujo del textil requiere precisión; sin embargo, esto se utiliza en prendas de muy altos estándares de calidad, ya que el corte se debe hacer preferiblemente individual. </strong>

    <br> <br>
    .row.justify-content-center.mb-4-mt-4
      .col-5
        p <strong>Tendido y corte</strong>
        p Para los textiles de cuadros se recomienda trabajarlos de la siguiente manera:
        ul.lista-ul--color.fa-ul.color-primario
          li 
            i.fas.fa-plus
            | Trabajar despiece sin costura
          li
            i.fas.fa-plus
            | Trazo direccional
          li
            i.fas.fa-plus
            | Tendido abierto cara arriba
          li
            i.fas.fa-plus
            | Marcación por el revés con tiza
          li
            i.fas.fa-plus
            | Fijar los patrones con alfileres
      .col-3
        img.mt-5(src="@/assets/curso/temas/tema2/imagen54.svg" alt="La imagen muestra dos diagramas de una chaqueta a cuadros, destacando diferentes partes y detalles de la prenda con números y círculos. Estos diagramas probablemente señalan características específicas de la chaqueta, como costuras, botones, bolsillos y otros elementos de diseño tanto en la vista frontal como en la vista posterior. La anotación numérica facilita la identificación y referencia a las distintas partes de la chaqueta para su análisis o confección. ")

    <br> <br>
    .row.justify-content-center.align-items-center.mb-4-mt-4
      p.text-center <strong>Tips de corte para cuadros</strong>

    .row.justify-content-center.mt-4.mb-4
      .col-3
        .tarjeta.color-acento-botones.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta13/imagen1.png")
          p.text-center <strong>Ubicar los patrones en el textil y alinear para que coincidan las líneas</strong>
      .col-3
        .tarjeta.color-primario.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta13/imagen2.png")
          p.text-center.color-white <strong>Trazar en los patrones las líneas</strong>
          <br> <br>
      .col-3
        .tarjeta.color-acento-botones.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta13/imagen3.png")
          p.text-center <strong>Realizar esto con cada una de las piezas de la prenda</strong>
          br
      .col-3
        .tarjeta.color-primario.borde-redondo.p-4
          img.p-4(src="@/assets/curso/temas/tema2/tarjeta13/imagen4.png")
          p.text-center.color-white <strong>Una vez ubicados se debe ir pintando y con la tiza ir agregando margen de costura</strong>

    <br>
    .row.mt-4.mb-4
      p <strong>Ejemplo de tipos de tendido con diferentes características del material</strong>
      p En el desarrollo de los contenidos se han identificado términos técnicos de la industria, los cuales se irán apropiando con mayor rigor en la práctica; la inmersión en la industria y el mercado permitirá afianzar cada vez más los conocimientos teóricos; sin embargo, con el fin de sintetizar de una manera más gráfica se hará la contextualización aplicada en diferentes tipos de materiales con una serie de moldes a escala que permitirán poner en práctica los conceptos explicados.

    .row.justify-content-center.mt-4.mb-4(data-aos="zoom-in-left")
      .col-8
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-pdf-2.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-9.mb-sm-0
                  p.mb-0 Archivo descargable - Anexos 10.6.1 ARCHIVO DESCARGABLE
                .col-sm-12.col-lg-3
                  a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                    span.text-sistm Descargar
                    i.fas.fa-file-download.text-sistm

    .row.justify-content-center.mt-4.mb-4(data-aos="zoom-in-left")
      .col-8
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-9.mb-sm-0
                  p.mb-0 Para una mejor comprensión del tema revisar el siguiente video de “ejemplo sobre tipos de tendido con diferentes características del material”.
                .col-sm-12.col-lg-3
                  a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm

    Separador    
    .row
      .titulo-segundo.color-primario
        h2 2.7  Terminología industrial de trazo y corte
    
    .row.align-items-center
      .col-7
        p <strong>Tiqueteado</strong>
        p Consiste en rotular cada una de las piezas cortadas, identificando el lote, nombre de la pieza, talla y un consecutivo para contribuir en el orden del sistema operacional.
        .cajon.color-primario 
          p.p-5 <strong> Se usa tiqueteadora con su papel adhesivo; es importante definir la ubicación en la pieza, se trabaja por el revés de la tela. </strong>
      .col-3.p-3
        img(src="@/assets/curso/temas/tema2/imagen55.svg")

    .row.justify-content-center.mt-4.mb-4(data-aos="zoom-in-left")
      .col-8
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-9.mb-sm-0
                  p.mb-0 Para una mejor comprensión del tema revisar el siguiente video.
                .col-sm-12.col-lg-3
                  a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm
                    
    .row.mb-4.mt-4
      h3.mb-4 Operaciones auxiliares de corte
      p Interviene personal auxiliar para apoyar el proceso. 

    AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--white")
      .row.borde-redondo-tmorada(titulo="Fusionado")
        .col-md-12.mb-4.mb-md-0
          p.p-5 Una vez se corta la tela y la entretela, para entretelar se utiliza una máquina fusionadora, que a través de presión y calor adhiere la entretela a la tela. Es importante el control de temperatura según el textil, ya que puede generar encogimiento. En el siguiente video puede apreciar la operación.
          .row.justify-content-around.align-items-center
            .col-8
              .tarjeta.color-primario.borde-redondo.p-4.mb-5
                .row.justify-content-around.align-items-center
                  .col-sm-12.col-lg-2.d-none.d-lg-block
                    img(src="@/assets/template/icono-video.svg")
                  .col-sm-12.col-lg-10
                    .row.justify-content-between.align-items-center
                      .col-sm-12.col-lg-9.mb-sm-0
                        p.mb-0 Para una mejor comprensión del tema revisar el siguiente video.
                      .col-sm-12.col-lg-3
                        a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                          span.text-sistm Ir al sitio
                          i.fas.fa-video.text-sistm
      .row.borde-redondo-tmorada(titulo="Paqueteo")
        .col-md-12.mb-4.mb-md-0
          p.p-5 Consiste en separar por bloques las piezas cortadas, paqueteando la cantidad definida de todas las piezas que conforman la prenda, amarrando y conformando paquetes de 10 a 20 unidades; para así facilitar el control de producción y de calidad. Una vez se paquetee es importante el almacenamiento, utilizando la técnica de Kanban para entregarlas a ensamble.
      .row.borde-redondo-tmorada(titulo="Tecnología en corte")
        .col-md-12.mb-4.mb-md-0
          p.p-5 Consiste en separar por bloques las piezas cortadas, paqueteando la cantidad definida de todas las piezas que conforman la prenda, amarrando y conformando paquetes de 10 a 20 unidaLa tecnología en el área de corte inicia con el trazo asistido por computador a través de programas especializados, los cuales ahorran tiempo y espacio. Para el transporte de telas y paquetes cortados se usan bandas o carros, que son utilizados también para entregar los paquetes al área de ensamble.des; para así facilitar el control de producción y de calidad. Una vez se paquete es importante el almacenamiento, utilizando la técnica de Kanban para entregarlas a ensamble.
      .row.borde-redondo-tmorada(titulo="Software de corte")
        .col-md-12.mb-4.mb-md-0
          p.p-5 Los programas empleados en la industria textil como Audaces, Gerber, Optitex o Lectra cuentan con módulos especializados en trazo, que facilitan el corte de las prendas, siendo más precisos, optimizando los tiempos y disminuyendo el desperdicio de materia prima. Además del computador y del programa se requiere el plotter para poder imprimir los trazos. En el caso de que el corte sea automático, el cabezal irá cortando sobre la tela sin previa impresión del trazo.

    .row.justify-content-center.mt-4.mb-4(data-aos="zoom-in-left")
      .col-8
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-9.mb-sm-0
                  p.mb-0 Para una mejor comprensión del tema revisar el siguiente video.
                .col-sm-12.col-lg-3
                  a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm
                  p 
                  a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm



</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
    datosSlyder: [
      {
        imagen: require('@/assets/curso/temas/tema2/tarjeta6/imagen1.svg'),
        leyendaImagen: 'Tendido abierto',
        //titulo:
        //'Never, never assume that what you have achieved is good enough',
        texto:
          'La imagen muestra cómo alinear y cortar patrones en la tela. A la izquierda, se ven patrones colocados sobre una tela, alineados con el recto hilo y el orillo de la tela para asegurar un corte preciso. A la derecha, se ilustra cómo una pieza del patrón debe estar alineada con el orillo de la tela para que salga completa y correctamente cortada. Las instrucciones enfatizan la importancia de seguir la dirección del recto hilo y el orillo para obtener un resultado adecuado. ',
        //imagen: require('@/assets/template/img-placeholder.svg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        imagen: require('@/assets/curso/temas/tema2/tarjeta6/imagen2.svg'),
        leyendaImagen: 'Tendido Cerrado',
        //titulo:
        //  'Never, never assume that what you have achieved is good enough',
        texto:
          'La imagen muestra cómo alinear y cortar patrones en la tela. A la izquierda, se ven patrones colocados sobre una tela, alineados con el recto hilo y el orillo de la tela para asegurar un corte preciso. A la derecha, se ilustra cómo una pieza del patrón debe estar alineada con el orillo de la tela para que salga completa y correctamente cortada. Las instrucciones enfatizan la importancia de seguir la dirección del recto hilo y el orillo para obtener un resultado adecuado.',
        //imagen: require('@/assets/template/img-placeholder.svg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
    ],
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
