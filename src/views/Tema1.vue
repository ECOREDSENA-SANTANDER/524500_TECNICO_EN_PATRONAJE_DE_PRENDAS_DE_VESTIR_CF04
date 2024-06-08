<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Trazado de patrones (<em>software</em> de patronaje)
      
    .row.justify-content-center.align-items-center.mt-4.mb-4
      .col-7
        p Para el manejo e implementación del software de patronaje es necesario tener como referente el desarrollo y elaboración de básicos, de acuerdo con la metodología del manual de patronaje SENA y demás teorías estudiadas hasta el momento.
        .cajon.color-primario 
          p.p-5 <strong> Para el trazo de patrones se referenciará únicamente la línea femenina; sin embargo, cabe resaltar que las herramientas del programa y manejo de interfaz aplican para cualquier línea; tenga en cuenta que el desarrollo del trabajo manual es la base para la apropiación de un proceso digital. </strong>
      .col-3.p-3
        img(src="@/assets/curso/introduccion/imagen2.svg", alt="Interfaz software")

    Separador
    .row.mb-4
      .titulo-segundo.color-primario
        h2 1.1  Personalizar área de trabajo - <em>Optitex</em>

    .row.mb-4
      h3 Reconocimiento interfaz de Optitex
      p Reconocimiento interfaz de Optitex:
    
    .row.justify-content-center.mb-4
      .col-3.mb-5.mb-sm-0
        ol.lista-ol--cuadro.lista-ol--separador
          li 
            .lista-ol--cuadro__vineta
              span 1
            | Barra de título
          li 
            .lista-ol--cuadro__vineta
              span 2
            | Barra de menú
          li 
            .lista-ol--cuadro__vineta
              span 3
            | Barra de herramientas
          li 
            .lista-ol--cuadro__vineta
              span 4
            | Ventana de piezas
          li 
            .lista-ol--cuadro__vineta
              span 5
            | Ventana de herramientas
          li 
            .lista-ol--cuadro__vineta
              span 6
            | Área de trabajo
      .col-7
        img(src="@/assets/curso/temas/tema1/imagen1.svg", alt="La imagen hace una descripción del paso a paso de la herramienta Optitex para poder hacer los trazos de cada prenda, allí se enumeran las barras y ventanas que se necesitan en cada fase.")

    .row.mb-4
      h3 Despejar el área de trabajo y activar herramientas

    .tarjeta.tarjeta--azul.p-4.mb-4.borde-redondo(style="background-color: #F8F5FF")
      SlyderA(tipo="b")
        .row.justify-content-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            p.p-4 1. En la barra de menú <strong>vista</strong> seleccione la opción <strong>caja de herramientas</strong> y active la ventana de <strong>herramientas</strong>, ubicada al lado izquierdo de la pantalla.
            p.p-4 2. Otra manera de visualizar las herramientas es <strong>situar el cursor debajo de la barra de menú</strong>, y con clic derecho observar las que están disponibles.
            p.p-4 De igual manera, se pueden activar las herramientas que se necesitan y dejar inactivas las que no se estén utilizando en el momento.
          .col-md-6
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta1/imagen1.svg", alt='La imagen muestra la interfaz de un programa de diseño de patrones con un menú desplegable abierto. El menú está resaltado con un óvalo negro y ofrece varias opciones como “General”, “Modelo”, “Almacenamiento”, “Bibliotecas”, “Reglas de piezas”, “Vista 3D”, y “Simulación 3D”, entre otras. A la izquierda, se encuentra el panel de herramientas con categorías como “Herramientas de Piezas”, “Herramientas Generales”, “Puntos y Piquetes”, y “Capturar Puntos y Piquetes”. El área central muestra una regla horizontal en la parte superior del área de trabajo.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-4 <strong>Ubique el cursor en cada herramienta, con un clic se desactivan.</strong>
            br
            p.p-4 Como se puede observar en la gráfica las herramientas no están disponibles; de esta manera se puede despejar el área de trabajo y activarlas nuevamente cuando sea necesario.
          .col-md-8
            img(src="@/assets/curso/temas/tema1/tarjeta1/imagen2.svg", alt='La imagen muestra la interfaz de un programa de diseño de patrones con un menú desplegable abierto. El menú está resaltado con un óvalo negro y ofrece varias opciones como “General”, “Modelo”, “Almacenamiento”, “Bibliotecas”, “Reglas de piezas”, “Vista 3D”, y “Simulación 3D”, entre otras. A la izquierda, se encuentra el panel de herramientas con categorías como “Herramientas de Piezas”, “Herramientas Generales”, “Puntos y Piquetes”, y “Capturar Puntos y Piquetes”. El área central muestra una regla horizontal en la parte superior del área de trabajo.')

    br
    .row.mt-4.mb-4
      h3 Configurar área de trabajo

    .tarjeta.tarjeta--gris.p-4.borde-redondo(style="background-color: #F8F5FF")
      LineaTiempoC.color-acento-botones(text-small)
        .row(titulo="1")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 En la barra de menú de herramientas seleccione la opción preferencias, aparece la siguiente ventana.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta2/imagen1.svg", alt='La imagen muestra una captura de pantalla de un programa de diseño de patrones con el menú “Herramientas” desplegado. En el menú, se destacan las opciones “Costura”, “Escalado”, “Aflojar”, “Pliegues”, “Editar Segmento”, “Líneas guías”, “Configuración temas…”, “Personalizar…”, “Resetear layout área trabajo…”, y “Preferencias…”. La opción “Herramientas” y “Preferencias…” están resaltadas con círculos naranjas. A la izquierda, se ve el panel de “Propiedades” con detalles de una pieza, como el nombre, cantidad y código.')
        .row(titulo="2")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 En esa ventana se puede configurar:
            ol.lista-ol--cuadro.ps-5.mb-0
              li 
                .lista-ol--cuadro__vineta
                  span 1
                | Colores
              li 
                .lista-ol--cuadro__vineta
                  span 2
                | Activar o desactivar relleno de la pieza
              li 
                .lista-ol--cuadro__vineta
                  span 3
                | Activar ventanas de diálogo de las herramientas
              li 
                .lista-ol--cuadro__vineta
                  span 4
                | Unidades de trabajo (unidades de medida)
              li 
                .lista-ol--cuadro__vineta
                  span 5
                | Atributos de herramientas
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta2/imagen2.svg", alt='La imagen muestra la ventana de “Preferencias” de un programa de diseño de patrones. A la izquierda, se encuentran varias categorías como “Principal”, “Interno y Texto”, “Piquete”, “Plot y corta”, “Guardar”, “Fuente”, “Colores” y “Configuración”, con subcategorías como “General”, “Pieza”, “Comando”, “Material”, “Puntada” y “Calidad”. En el panel derecho, bajo “Área de trabajo”, se pueden configurar opciones como el fondo, el color de línea guía, la rejilla, las rayas y el color de las reglas. Bajo “Pieza”, se pueden ajustar el color de relleno, el color de la pieza seleccionada, el color para contorno seleccionado, y varios otros colores específicos relacionados con el diseño de las piezas. La sección “Preferencias” está resaltada con un círculo amarillo.')
        .row(titulo="3")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 Al estar en la opción preferencias, diríjase a la carpeta principal y seleccione unidad. 
            p.ps-5.mb-0 Esta ventana permite seleccionar la unidad de medida con la que desea trabajar.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta2/imagen3.svg", alt='La imagen muestra la ventana de “Preferencias” del programa de diseño de patrones, específicamente en la sección “Principal” bajo “Unidades de trabajo”. A la izquierda, se ven varias categorías de configuración, incluyendo “Pieza”, “Interno y Texto”, “Piquete”, “Plot y corta”, “Guardar”, “Fuente”, “Colores”, “Configurar importación” y “Configurar exportación”. A la derecha, en el panel principal, se puede seleccionar la unidad de medida entre opciones como milímetros, centímetros, metros, pulgadas, pies y yardas. Ambas secciones están resaltadas con óvalos negros.')
        .row(titulo="4")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 Seleccione la carpeta colores, opción configuración.
            p.ps-5 Activar o desactivar el relleno de las piezas: 
            ol.lista-ol--cuadro.ps-5
              li 
                .lista-ol--cuadro__vineta
                  span 1
                | Todas las piezas del archivo
              li 
                .lista-ol--cuadro__vineta
                  span 2
                | Ninguna pieza
              li 
                .lista-ol--cuadro__vineta
                  span 3
                | Solo la pieza seleccionada. También se puede seleccionar el método de relleno, que puede ser: por material, pieza y calidad
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta2/imagen4.svg", alt='La imagen muestra la configuración de “Rellena pieza” en las “Preferencias” del programa de diseño de patrones. En la sección “Colores”, se puede activar o desactivar el relleno de piezas, aplicándolo a todas las piezas, ninguna, la pieza seleccionada o el set del modelo activo. También se puede elegir el método de relleno por material, pieza o calidad.')
        .row(titulo="5")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 Ahora, seleccione la carpeta colores, opción generales. Ahí se puede modificar el área de trabajo:
            ol.lista-ol--cuadro.ps-5
              li 
                .lista-ol--cuadro__vineta
                  span 1
                | Color del fondo
              li 
                .lista-ol--cuadro__vineta
                  span 2
                | Líneas guías
              li 
                .lista-ol--cuadro__vineta
                  span 3
                | Color de las reglas
            p.ps-5 En la pieza:
            ol.lista-ol--cuadro.ps-5
              li 
                .lista-ol--cuadro__vineta
                  span 1
                | Color del relleno de las piezas
              li 
                .lista-ol--cuadro__vineta
                  span 2
                | Color de la pieza seleccionada
              li 
                .lista-ol--cuadro__vineta
                  span 3
                | Color del contorno seleccionado
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta2/imagen5.svg", alt='La imagen muestra la ventana de “Preferencias” del programa de diseño de patrones, enfocada en la configuración de colores. En la categoría “Configuración” bajo “General”, se puede ajustar el color de diferentes elementos del área de trabajo y las piezas. Un menú desplegable permite seleccionar colores para el fondo, líneas guía, rejilla, rayas, y reglas del área de trabajo, así como colores específicos para el relleno de piezas, bordes y otros detalles. La sección “General” está resaltada con un círculo amarillo.')
    
    br
    .row.mt-4.mb-4
      h3 ¿Qué habilitar en la barra de menú vista?
       
    AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--white")
      .row.borde-redondo-tmorada(titulo="Opción ventana de piezas")
        .col-md-4.mb-4.mb-md-0
          p.p-5 En la barra de <strong>menú vista</strong> seleccione la opción <strong>ventana de piezas</strong>. En esta ventana se permite visualizar las piezas que se han creado en el archivo.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema1/tarjeta3/imagen4.svg", alt='La imagen muestra la interfaz del programa de diseño de patrones OptiTex PDS 10 Demo, con el menú “Vista” desplegado y la opción “Caja Herramientas” resaltada con un óvalo negro. A la izquierda, se observa la “Caja herramientas” con diversas opciones y herramientas de diseño. En el área central, hay un patrón de pieza de color amarillo, mostrando su diseño.')
      .row.borde-redondo-tmorada(titulo="Opción caja de herramientas")
        .col-md-4.mb-4.mb-md-0
          p.p-5 En la barra de <strong>menú vista</strong> habilite la opción <strong>caja de herramientas</strong>.
          p.ps-5 En esta ventana se encuentran todas las herramientas que están diseñadas para el proceso de actualización y transformación de las piezas que se encuentran en el área de trabajo. Las herramientas se encuentran divididas en grupos de acuerdo con su funcionalidad.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema1/tarjeta3/imagen1.svg", alt='La imagen muestra la interfaz del programa de diseño de patrones OptiTex PDS 10 Demo, con el menú “Vista” desplegado y la opción “Caja Herramientas” resaltada con un óvalo negro. A la izquierda, se observa la “Caja herramientas” con diversas opciones y herramientas de diseño. En el área central, hay un patrón de pieza de color amarillo, mostrando su diseño.')
      .row.borde-redondo-tmorada(titulo="Opción vista y selección")
        .col-md-4.mb-4.mb-md-0
          p.p-5 En la barra de <strong>menú vista</strong> habilite la opción <strong>vista y selección.</strong>
          p.ps-5 En esta ventana se habilita la información de la pieza, puntos o elementos internos que se quieran mostrar u ocultar en las piezas del archivo.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema1/tarjeta3/imagen2.svg", alt='La imagen muestra la interfaz del programa de diseño de patrones OptiTex PDS 10 Demo, con el menú “Vista” desplegado y la opción “Vista Selección” resaltada con un óvalo negro. A la izquierda, se ve el panel “Vista & Selección Atributos” que permite ajustar diversas propiedades y atributos de las piezas, como líneas guía, segmentos y tipos de puntada. En el área central, hay un patrón de pieza de color amarillo, mostrando su diseño y dimensiones.')
      .row.borde-redondo-tmorada(titulo="Más opciones para habilitar")
        .col-md-4.mb-4.mb-md-0
          p.p-5 En la barra del menú vista también se puede habilitar:
          ol.lista-ol--cuadro.ps-5
              li 
                .lista-ol--cuadro__vineta
                  span 1
                | Tabla de escalado
              li 
                .lista-ol--cuadro__vineta
                  span 2
                | Tabla de piezas
              li 
                .lista-ol--cuadro__vineta
                  span 3
                | Ventana de 3D
              li 
                .lista-ol--cuadro__vineta
                  span 4
                | Reglas
              li 
                .lista-ol--cuadro__vineta
                  span 5
                | Otras ventanas (calculadora)
              li 
                .lista-ol--cuadro__vineta
                  span 6
                | Habilitar colores por comandos
              li 
                .lista-ol--cuadro__vineta
                  span 7
                | Mostar líneas guías
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema1/tarjeta3/imagen3.svg", alt='Dama en un computador')

    <br> <br>
    Separador
    .row.mb-4
      .titulo-segundo.color-primario
        h2 1.2  Trazo de la falda - <em>Optitex</em>
    
    .row.mb-4.mt-4
      h3 ¿Cómo trazar la base de falda femenina?

    .tarjeta.tarjeta--gris.p-4.borde-redondo(style="background-color: #F8F5FF")
      LineaTiempoC.color-acento-botones(text-small)
        .row(titulo="1")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>1.</strong> Base de falda femenina talla 10. Para dar inicio haga clic derecho en el área de trabajo, dibuje un rectángulo, nombre la pieza como falda delantera:
            ul.lista-ul--color.fa-ul.color-primario.ps-1
              li 
                i.fas.fa-plus
                | <strong>Ancho:</strong> ¼ de contorno de cadera
              li
                i.fas.fa-plus
                | <strong>Largo:</strong> largo según talla (talla 10 = 60 cm)
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen1.svg", alt='La imagen muestra la ventana de creación de un rectángulo en un programa de diseño de patrones. A la izquierda, se ve un cuadro de diálogo titulado “Crear Rectángulo” donde se especifica el nombre de la pieza (“FALDA DEL”), su ancho (24) y su largo (60). A la derecha, se visualiza el rectángulo creado con las dimensiones especificadas, etiquetado como “FALDA DEL” en color azul claro.')
        .row(titulo="2")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>2.</strong> Tome <strong>herramienta punto</strong> para asignar sobre el rectángulo los puntos necesarios para darle forma a la falda. Sobre la línea vertical derecha marcar:
            ul.lista-ul--color.fa-ul.color-primario.ps-1
              li 
                i.fas.fa-plus
                | <strong>Altura de cadera:</strong> según talla (talla 10 = 18 cm)
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen2.svg", alt='La imagen muestra la ventana de creación de un rectángulo en un programa de diseño de patrones. A la izquierda, se ve un cuadro de diálogo titulado “Crear Rectángulo” donde se especifica el nombre de la pieza (“FALDA DELANTERO”), su ancho (24) y su largo (60). A la derecha, se visualiza el rectángulo creado con las dimensiones especificadas, etiquetado como “FALDA DELANTERO” en color azul claro. ')
        .row(titulo="3")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>3.</strong> 3. Sobre la línea de cintura marque:
            ul.lista-ul--color.fa-ul.color-primario.ps-1
              li 
                i.fas.fa-plus
                | <strong>Cintura:</strong> ¼ de contorno de cintura + pinza
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen3.svg", alt='La imagen muestra una interfaz de software con una ventana emergente titulada “Atributos de Punto”. En esta ventana se pueden definir varios parámetros de un punto, como su tipo, nombre, posición (X, Y), distancia, ángulo y opciones de movimiento sobre el contorno. También se presentan valores absolutos y proporcionales para la ubicación del punto.')
        .row(titulo="4")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>4.</strong> Clic derecho, herramienta <strong>selección</strong>; señale punto ángulo superior derecho de rectángulo y cambie atributos, asigne atributo de curva.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen4.svg", alt='La imagen muestra una captura de pantalla de una interfaz de software de diseño. A la izquierda, se visualiza un objeto azul etiquetado como “FALDA DELANTERA Base”. En el centro, aparece un menú desplegable titulado “Seleccionar Herramienta” con varias opciones. A la derecha, se encuentra un panel de propiedades con opciones para un punto seleccionado, y al lado, una ventana que muestra una vista del objeto azul.')
        .row(titulo="5")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>5.</strong> Tome herramienta <strong>mover</strong> punto (tecla rápida M), modele curva de cadera.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen5.svg", alt='La imagen muestra una ventana de software de diseño con un cuadro de diálogo titulado “Mover Punto.” En este cuadro se presentan opciones para mover un punto en un gráfico mediante coordenadas y ángulos específicos. Los campos de entrada muestran valores numéricos: -1.97, 7.92, -7.67 y -104.4. Hay opciones para aceptar o cancelar la acción. A la derecha, se ve una parte de un gráfico con una forma azul claro y una curva verde conectada a puntos de control en rosa, junto a una regla en la parte superior.')
        .row(titulo="6")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>6.</strong> Tome herramienta <strong>mover punto</strong>, para modificar el punto de cintura costado, subir 1 cm por costado. Marque en el eje Y 1 cm positivo y en el eje X 0.Tome herramienta <strong>mover</strong> punto (tecla rápida M), modele curva de cadera.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen6.svg", alt='La imagen describe una ventana de software de diseño, probablemente un programa de CAD o similar. En el cuadro de diálogo titulado “Mover Punto,” se presentan opciones para mover un punto en un gráfico. Se pueden ajustar las coordenadas y ángulos, y hay botones para aceptar o cancelar la acción. A la derecha del cuadro de diálogo, se observa una parte de un gráfico con una forma en azul claro y puntos de control en rosa.')
        .row(titulo="7")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>7.</strong> Para marcar la curva de cintura traiga una línea guía, ubique un punto en cintura con atributo de <strong>curva</strong>. Tome la herramienta mover punto y modifique la línea de cintura sin sobrepasar la línea guía trazada.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen7.svg", alt='La imagen muestra una ventana de software de diseño con un cuadro de diálogo titulado “Atributos de Punto.” En este cuadro, se pueden ver varias opciones de configuración para un punto en un gráfico. Los tipos de punto incluyen “Curva” y “Escalado,” con casillas de verificación para cada uno. También hay opciones para mover el punto sobre el contorno, ajustar las coordenadas X e Y, la distancia y el ángulo. Los campos de entrada muestran valores para el punto previo y el punto siguiente, tanto en términos absolutos como proporcionales. En la parte inferior hay botones para “OK” y “Cancelar.” A la izquierda del cuadro de diálogo, se puede ver una parte del gráfico con una forma azul claro y puntos de control en rosa.')
        .row(titulo="8")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>8.</strong> Para marcar la pinza, en el grupo de herramientas de insertar tome la herramienta <strong>pinza - añadir y girar pinza.</strong>
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen8.svg", alt='La imagen muestra un menú desplegable en un software de diseño, específicamente en la pestaña “Insertar.” Las opciones del menú incluyen “Añadir y girar pinza,” “Agregar Aflojo,” y “Crear pinza por puntos pivotes,” entre otras.')
        .row(titulo="9")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>9.</strong> Para macar la pinza en relación con la separación de busto, tenga en cuenta la medida del primer lado de la pinza; marque en absoluto la medida del primer lado de pinza. Marque la medida de la amplitud de la pinza.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen9.svg", alt='La imagen muestra dos cuadros de diálogo de “Atributos de Punto” en un software de diseño. Cada cuadro permite configurar el tipo de punto (Curva o Escalado), las coordenadas X e Y, la distancia y el ángulo. También se pueden ver los valores absolutos y proporcionales del punto previo y del punto siguiente. Los cuadros tienen botones para “OK” y “Cancelar.” En el fondo se observa parte de un gráfico con una forma azul claro y puntos de control en rosa.')
        .row(titulo="10")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>10.</strong> En la pestaña <strong>propiedades</strong> seleccione la opción <strong>profundidad</strong>, en este espacio asigne la medida de profundidad o largo de la pinza.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen10.svg", alt='La imagen muestra una sección de un software de diseño con el panel de “Propiedades” abierto a la izquierda. En este panel, se pueden ver atributos como “Profundidad” (9.5 cm), “Ancho” (2 cm), “Sobrepuesta” (CCW), entre otros. A la derecha, hay un gráfico con una forma azul claro y un objeto seleccionado, indicado por un contorno punteado y una figura geométrica con líneas guía.')
        .row(titulo="11")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>11.</strong> Para modificar los hilos de tela, en la caja de <strong>herramientas líneas de aplome</strong> escoja la herramienta <strong>hilo paralelo al tramo</strong>. Seleccione en sentido de las manecillas del reloj la <strong>línea de centro frente</strong>, para dejar el aplome paralelo al centro.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen11.svg", alt='La imagen muestra el panel “Caja herramientas” de un software de diseño de patrones a la izquierda, con varias opciones. A la derecha, hay dos piezas de patrón en azul claro etiquetadas como “FALDA DELANTERO Base” con puntos de control en rosa y líneas guía.')
        .row(titulo="12")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>12.</strong> Seleccione herramienta <strong>centrar aplome</strong>, para centrar el aplome o hilo de tela en relación con la pieza.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen12.svg", alt='La imagen muestra un software de diseño de patrones con el panel “Caja herramientas” a la izquierda y una pieza de patrón en azul claro a la derecha, etiquetada como “FALDA DEL Base.” Las opciones del panel incluyen “Centrar Aplome (Ctrl+I)” y “Girar por línea de hilo (Shift+P).”')
        .row(titulo="13")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>13.</strong> Al finalizar la parte delantera, dé clic derecho sobre la pieza y seleccione <strong>limpiar piezas</strong>. Reemplace el original, de esta manera se actualiza la pieza en la <strong>ventana - ventana de piezas.</strong>
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen13.svg", alt='La imagen muestra un software de diseño de patrones con el panel “Caja herramientas” a la izquierda y una pieza de patrón en azul claro a la derecha, etiquetada como “FALDA DEL Base.” Las opciones del panel incluyen “Centrar Aplome (Ctrl+I)” y “Girar por línea de hilo (Shift+P).”')
        .row(titulo="14")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>14.</strong> Para crear la parte posterior, dé <strong>clic derecho</strong> sobre el <strong>área de trabajo</strong>, seleccione la opción <strong>nueva pieza</strong>, posteriormente la opción <strong>crear un rectángulo</strong>. También puede acceder por la barra de menú.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen14.svg", alt='La imagen muestra dos menús desplegables en un software de diseño de patrones. El menú de la izquierda tiene la opción “Nueva pieza” con sub opciones para crear diferentes formas: “Crear Rectángulo,” “Crear Polígono,” “Crear Círculo,” “Crear Sector,” y “Crear Espiral.” El menú de la derecha también muestra opciones similares bajo la opción “Nueva pieza,” como “Crear Rectángulo,” “Crear Polígono,” “Crear Círculo,” “Crear Sector,” y “Crear Espiral.”')
        .row(titulo="15")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>15.</strong> En la ventana emergente asignar el nombre de la pieza como <strong>falda posterior</strong>.
            ul.lista-ul--color.fa-ul.color-primario.ps-1
              li 
                i.fas.fa-plus
                | <strong>Ancho:</strong> ¼ de contorno de cadera
              li 
                i.fas.fa-plus
                | <strong>Largo:</strong> largo según talla (talla 10 = 60 cm)
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen15.svg", alt='La imagen muestra un cuadro de diálogo del software de diseño de patrones titulado “Crear Rectángulo.” En el cuadro, se ingresa el nombre de la pieza como “FALDA POSTERIOR,” y se especifican las dimensiones: ancho de 24 y largo de 60. A la derecha, se ve la representación gráfica de la pieza de patrón en azul claro, etiquetada como “FALDA POSTERIOR Base.”')
        .row(titulo="16")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>16.</strong> Tomar herramienta <strong>punto sobre</strong> (tecla rápida O), para asignar sobre el rectángulo los puntos necesarios para darle forma a la falda.  Sobre la línea vertical derecha, marcar:
            ul.lista-ul--color.fa-ul.color-primario.ps-1
              li 
                i.fas.fa-plus
                | <strong>Altura de cadera:</strong> según talla (talla 10 = 18 cm)
            p.ps-5 Sobre la línea de cintura, marcar:
            ul.lista-ul--color.fa-ul.color-primario.ps-1
              li 
                i.fas.fa-plus
                | <strong>Cintura:</strong> ¼ de contorno de cintura + pinza
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen16.svg", alt='La imagen muestra dos cuadros de diálogo de “Atributos de Punto” en un software de diseño de patrones. Ambos cuadros permiten configurar el tipo de punto (Curva o Escalado), coordenadas X e Y, distancia y ángulo. También se muestran valores para el punto previo y el punto siguiente en términos absolutos y proporcionales. Los cuadros tienen botones para “OK” y “Cancelar.” En el fondo, se ve parte de las piezas de patrón en azul claro etiquetadas como “FALDA POSTERIOR.”')
        .row(titulo="17")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>17.</strong> Haga clic derecho en la herramienta <strong>selección</strong>; señale el punto ángulo superior derecho del rectángulo y cambie los atributos, asigne atributo de curva.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen17.svg", alt='La imagen muestra el panel “Propiedades” de un software de diseño de patrones a la izquierda, con opciones como “Escalado,” “Curva,” “Conectado,” “Nombre,” “Ángulo,” “Costura,” y “Punto alternativo de partida.” A la derecha, se ven dos piezas de patrón: una en negro etiquetada como “FALDA DELANTERO” y otra en azul claro etiquetada como “FALDA POSTERIOR Base.” Ambas piezas tienen puntos de control en rosa y líneas de guía.')
        .row(titulo="18")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>18.</strong> Tome herramienta <strong>mover punto</strong> (tecla rápida M); modele curva de cadera.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen18.svg", alt='La imagen muestra un cuadro de diálogo titulado “Mover Punto” en un software de diseño de patrones. El cuadro permite ajustar la posición de un punto utilizando coordenadas y ángulos específicos. Los campos de entrada muestran los valores: -1.64, 7.74, -7.56 y -102.2. Hay opciones para aceptar o cancelar la acción. A la derecha, se ve parte de una pieza de patrón en azul claro con puntos de control en rosa y una curva verde.')
        .row(titulo="19")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>19.</strong> Tome herramienta mover punto, para modificar el punto de cintura costado, subir 1 cm por costado. Marque en el eje de Y 1 cm positivo y en el eje X 0.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen19.svg", alt='La imagen muestra dos cuadros de diálogo titulados “Mover Punto” en un software de diseño de patrones. Ambos cuadros permiten ajustar la posición de un punto utilizando coordenadas y ángulos. Los valores en los campos de entrada del primer cuadro son: 0.13, 1.34, 1.33, y 95.5. En el segundo cuadro, los valores son: 0, 1, 1, y 90.0. Hay opciones para aceptar o cancelar la acción.')
        .row(titulo="20")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>20.</strong> Baje el punto de cintura centro atrás 1 cm. Marque en el eje de Y -1 cm y en el eje X 0. Para marcar la curva de cintura traiga una línea guía y ubique un punto en cintura con atributo de curva. Tome herramienta mover punto y modifique la línea de cintura sin sobrepasar la línea guía trazada.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen20.svg", alt='La imagen muestra un cuadro de diálogo titulado “Mover Punto” en un software de diseño de patrones. El cuadro permite ajustar la posición de un punto utilizando coordenadas y ángulos específicos. Los valores en los campos de entrada son: 0.03, 1, 1, y -88.5. Hay opciones para aceptar o cancelar la acción. A la derecha, se observa una parte de una pieza de patrón en azul claro con puntos de control en rosa y una línea verde.')
        .row(titulo="21")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>21.</strong> Para marcar la pinza, en el grupo de herramientas de insertar tome la herramienta <strong>pinza, opción añadir y girar pinza.</strong> Para marcar la pinza en relación con la separación de busto, se debe tener en cuenta la medida del primer lado de la pinza, marque en absoluto la medida del primer lado de la pinza; marque la medida de la amplitud de la pinza.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen21.svg", alt='La imagen muestra el menú desplegable “Añadir y girar pinza” en un software de diseño de patrones, con opciones como “Agregar Aflojo,” “Crear pinza por puntos pivotes,” y “Cortar pinza por arco.” A la derecha, se encuentra un cuadro de diálogo de “Atributos de Punto” con opciones para ajustar el tipo de punto (Curva o Escalado), las coordenadas X e Y, distancia y ángulo. Los valores mostrados en el cuadro son: Absoluto 2.75 y 1.95, Proporcional 0.833 y 0.167.')
        .row(titulo="22")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>22.</strong> En la pestaña <strong>propiedades, opción profundidad</strong>, asigne la medida de <strong>profundidad o largo de la pinza.</strong> 
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen22.svg", alt='La imagen muestra el menú desplegable “Añadir y girar pinza” en un software de diseño de patrones, con opciones como “Agregar Aflojo,” “Crear pinza por puntos pivotes,” y “Cortar pinza por arco.” A la derecha, se encuentra un cuadro de diálogo de “Atributos de Punto” con opciones para ajustar el tipo de punto (Curva o Escalado), las coordenadas X e Y, distancia y ángulo. Los valores mostrados en el cuadro son: Absoluto 2.75 y 1.95, Proporcional 0.833 y 0.167.')
        .row(titulo="23")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>23.</strong> Para modificar los hilos de tela, en la caja de <strong>herramientas, opción movimiento, mover pieza interna.</strong> Tome el hilo de tela de la pieza delantera y arrastrarlo hacia la pieza posterior. 
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta4/imagen23.svg", alt='La imagen muestra el panel “Caja herramientas” de un software de diseño de patrones, destacando la opción “Mover” con sub opciones como “Mover punto (M)” y “Mover línea (B).” A la derecha, se ven cuatro piezas de patrón en azul claro, etiquetadas como “FALDA POSTERIOR” con puntos de control en rosa y líneas de guía. Cada pieza muestra diferentes detalles de ajuste y configuración.')

    <br> <br>
    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-8.mb-sm-0
                  p.mb-0 Para una mejor comprensión revisar el siguiente video de “trazo de falda en Optitex”.
                .col-sm-12.col-lg-4
                  a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm
      .col-sm-12.col-lg-6
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-8.mb-sm-0
                  p.mb-0 También se recomienda revisar el siguiente “tutorial de patrón básico de falda”.
                .col-sm-12.col-lg-4
                  a.boton.color-boton(href="https://www.youtube.com/embed/Ds5CtwVbaag" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm

    Separador
    .row.mb-4.mt-4
      .titulo-segundo.color-primario
        h2 1.3 Trazo de la base superior femenina -<em>Optitex</em>
    h3.mb-4.mt-4 ¿Cómo trazar la base superior femenina?
    p <strong>Parte posterior talla 10</strong>

    AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--white")
      .row.borde-redondo-tmorada(titulo="Paso 1")
        .col-md-4.mb-4.mb-md-0
          p.p-5 Inicie creando un archivo nuevo, sobre el archivo cree un rectángulo con las siguientes medidas:
          ul.lista-ul--color.fa-ul.color-primario.ps-1
              li 
                i.fas.fa-plus
                | <strong>Largo:</strong> medida de talle posterior: 42,5 cm
              li
                i.fas.fa-plus
                | <strong>Ancho:</strong> ¼ de busto, 23 cm
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema1/tarjeta5/imagen1.svg", alt='La imagen muestra un patrón de costura con varias medidas y etiquetas. En el lado izquierdo, se observa una línea vertical con una etiqueta en el centro. A la derecha, se presenta un esquema con medidas específicas: “Medida de Hombro,” “Medida de Escote,” “Caída de Hombro,” y “Medida Centro Atrás.” También se indican instrucciones para ajustar el patrón, como “Mitad de la distancia A-D” y “Bajar Punto B 2 cms.” Las letras A, B, C, D, E, F, y H marcan puntos clave en el patrón.')
      .row.borde-redondo-tmorada(titulo="Paso 2")
        .col-md-4.mb-4.mb-md-0
          p.p-5 Haga doble clic sobre el <strong>ángulo del escote</strong> y cambie el atributo del punto, <strong>desmarcando escalado y señalando curva.</strong>
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema1/tarjeta5/imagen2.svg", alt='La imagen muestra un cuadro de diálogo titulado “Atributos de Punto” en un software de diseño de patrones. Las opciones permiten seleccionar el tipo de punto, con casillas de verificación para “Escalado” y “Curva,” siendo “Curva” la opción seleccionada. Se puede ajustar el “Ángulo del punto” (con el valor 180) y el “Nombre del punto.” Hay botones para “Aplicar,” “Cancelar,” y “Costura.”')
      .row.borde-redondo-tmorada(titulo="Paso 3")
        .col-md-4.mb-4.mb-md-0
          p.p-5 Los ángulos del hombro y continuación de la sisa se suprimen. El patrón queda como lo señala la imagen.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema1/tarjeta5/imagen3.svg", alt='La imagen muestra tres piezas de patrón de costura alineadas horizontalmente. Cada pieza tiene una línea central vertical y varias líneas horizontales y curvas en la parte superior que indican diferentes medidas y ajustes. Las piezas parecen representar diferentes etapas de modificación de un mismo patrón.')
      .row.borde-redondo-tmorada(titulo="Paso 4")
        .col-md-4.mb-4.mb-md-0
          p.p-5 Con la herramienta <strong>medir</strong> se señala el segmento del hombro en el sentido de las manecillas del reloj. Haga clic en el botón <strong>editar largo del segmento</strong>; este a su vez abre la ventana largo del segmento.
          p.ps-5 En la ventana editar largo del segmento, escribir 12 cm para el largo y escoja la opción <strong>primer horizontal</strong>. Esta opción se selecciona porque el punto correspondiente al ángulo del hombro sisa es el que debe moverse al realizar el cambio de medida, y elija primer horizontal porque es el punto inicial.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema1/tarjeta5/imagen4.svg", alt='La imagen muestra un patrón de costura a la izquierda con una línea central vertical y varias líneas de control en los bordes. A la derecha, hay dos cuadros de diálogo. El primero es la “Ventana de medidas,” que incluye opciones para editar la longitud del segmento, con el botón “Editar largo del segmento” resaltado. El segundo cuadro de diálogo, titulado “Largo del segmento,” permite ajustar la longitud de un segmento específico, con opciones para aceptar, cancelar y copiar/pegar. Elementos como “Nuevo,” “Punto vertical,” y “Uso horizontal” están resaltados.')
      .row.borde-redondo-tmorada(titulo="Paso 5")
        .col-md-4.mb-4.mb-md-0
          p.p-5 Ubique el punto mitad de sisa (mitad de la distancia entre el escote y altura de sisa), y marque también sobre la línea donde formará la curva de sisa.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema1/tarjeta5/imagen5.svg", alt='La imagen muestra un patrón de costura con una línea central vertical. Una flecha horizontal señala dos puntos en el patrón, con el texto “Medimos la distancia entre estos puntos para deducir la medida de mitad de ancho espalda.” Esta instrucción indica cómo determinar la medida de la mitad del ancho de la espalda utilizando los puntos indicados.')
      .row.borde-redondo-tmorada(titulo="Paso 6")
        .col-md-4.mb-4.mb-md-0
          p.p-5 Mida  la distancia señalada en la gráfica y a esta réstele el valor de la mitad del ancho de espalda para saber cuánto debe <strong>mover el punto</strong> de la sisa, con el fin de darle la forma a la misma; con la herramienta mover punto, mueva en X el valor que se debe restar para darle la medida de ancho de espalda, y en Y debe quedar 0.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema1/tarjeta5/imagen6.svg", alt='La imagen muestra un patrón de costura con una línea central vertical y una nueva línea en verde en la parte superior izquierda del patrón. Debajo del patrón, hay un cuadro de diálogo titulado “Mover Punto,” que permite ajustar la posición de un punto utilizando coordenadas específicas. Los valores en los campos de entrada son: 3.2 y 3.2 para las coordenadas, y 0° para el ángulo. Hay opciones para aceptar o cancelar la acción.')
      .row.borde-redondo-tmorada(titulo="Paso 7")
        .col-md-4.mb-4.mb-md-0
          p.p-5 <strong>Dele la forma</strong> a la sisa siguiendo las indicaciones de las imágenes.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema1/tarjeta5/imagen7.svg", alt='La imagen muestra tres etapas en la modificación de un patrón de costura. Primero, se ve el patrón original. Luego, se añade una línea verde curva al patrón, utilizando un cuadro de diálogo titulado “Crear arco” con campos para el número de puntos y el radio. Finalmente, el patrón modificado muestra la curva aplicada, indicando que el punto seleccionado tiene atributos tanto de escalado como de curva, según el texto que dice: “Doble clic sobre este punto y además de atributo de escalado, le damos también de curva.”')
      .row.borde-redondo-tmorada(titulo="Paso 8")
        .col-md-4.mb-4.mb-md-0
          p.p-5 Con la herramienta mover punto entalle la medida de cintura correspondiente a la talla. Fije un punto con atributo de escalado a 9 cm, que corresponde a la medida de la mitad de separación del busto. Según el método de patronaje utilizado, el costado posterior es igual a la medida A-B más 1 cm. Se edita el largo del segmento de costado, siguiendo las indicaciones de la imagen.
        .col-md-8
          img.p-5(src="@/assets/curso/temas/tema1/tarjeta5/imagen8.svg", alt='La imagen muestra dos patrones de costura y dos cuadros de diálogo. El primer patrón está etiquetado con puntos A y B, indicando que “A ponemos punto a mitad de separación de hombro”. El segundo patrón refleja una modificación con una curva añadida. Los cuadros de diálogo muestran la “Ventana de medidas” con opciones para editar la longitud del segmento y el cuadro “Largo del segmento” con opciones para ajustar la longitud y posición del segmento, resaltando “Largo” y “Primera posición”.')

    <br> <br>
    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-8.mb-sm-0
                  p.mb-0 Para una mejor comprensión revisar el siguiente video de “trazado de corpiño básico”.
                .col-sm-12.col-lg-4
                  a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm
    
    .row.mt-4.mb-4
      h3 ¿Cómo trazar la pinza?

    .tarjeta.tarjeta--azul.p-4.mb-4.borde-redondo(style="background-color: #F8F5FF")
      SlyderA(tipo="b")
        .row.justify-content-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            p.p-4 <strong>1.</strong> Tome la herramienta pinza y reparta a cada lado del punto señalado, mitad de la amplitud de la pinza, para este caso, 1,5 a cada lado del punto. Traiga una línea guía a la altura de la sisa hasta donde llega la profundidad de sisa para marcar hasta ahí el largo de esta. Se marca la pinza, llevando la misma hasta la línea de altura de la sisa y en la última ventana <strong>atributos de pinza</strong> se activa la opción <strong>sobrepuesta</strong>.
          .col-md-6
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta6/imagen1.png", alt='La imagen muestra un programa de diseño de patrones de costura. En la parte superior, se ve una ventana de atributos de pieza con opciones para seleccionar, desfilar y cambiar medidas de la pieza. La opción “Subgrupo” está destacada con un círculo rojo. En la parte inferior, hay dos diagramas de patrones de una prenda. El diagrama de la izquierda muestra una línea verde, que parece indicar una modificación en el patrón original. El diagrama de la derecha muestra el mismo patrón con líneas punteadas azules, indicando las líneas de costura y cortes.')
        .row.justify-content-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            p.p-4 <strong>2.</strong> La pinza debe llegar al punto de intersección entre altura y separación de busto. Para ello utilice la herramienta pinza, señale el punto del vértice de la <strong>pinza</strong>, arrastre y seleccione el punto de intersección entre las líneas guías, haga clic y el vértice de la pinza se traslada al punto señalado.
          .col-md-6
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta6/imagen2.png", alt='La imagen muestra dos diagramas de patrones de costura. Ambos diagramas están enfocados en una misma sección de los patrones, que está resaltada con un círculo rojo. La sección resaltada parece indicar un ajuste o una modificación específica en la línea de costura central. El patrón de la izquierda y el de la derecha son similares, pero el detalle en el círculo rojo puede señalar un punto de ajuste clave en el diseño del patrón, probablemente relacionado con la colocación de la pinza o un punto de intersección de líneas importantes.')
        .row.justify-content-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            p.p-4 <strong>3.</strong> Para terminar el patrón, haga clic en la herramienta <strong>reemplazar original</strong> (grupo de herramientas generales), de esta manera en la <strong>barra de piezas</strong> quedan guardados los cambios que se hicieron al rectángulo desde el inicio. Para guardar el archivo, diríjase a la barra de <strong>menú archivo</strong>, opción <strong>guardar como</strong>, proceder a darle un nombre al archivo, este queda con <strong>extensión dsn</strong>.
          .col-md-6
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta6/imagen3.png", alt='La imagen muestra dos diagramas de patrones de costura para el cuerpo de una prenda. El diagrama de la izquierda presenta un patrón básico con líneas punteadas que indican la ubicación de una pinza en la cintura, y el contorno del patrón está delineado con líneas sólidas negras. El diagrama de la derecha muestra el mismo patrón pero con el área sombreada en azul, destacando la pieza completa. Ambas imágenes tienen las mismas líneas punteadas y sólidas para indicar las características del patrón, siendo la principal diferencia el sombreado azul en el diagrama derecho.')

    h3.mb-5.mt-5 Parte delantera talla 10

    .tarjeta.tarjeta--gris.p-4.borde-redondo(style="background-color: #F8F5FF")
      LineaTiempoC.color-acento-botones(text-small)
        .row(titulo="1")
          .col-md-5.mb-4.mb-md-0
            p.ps-5.mb-4 <strong>1.</strong> Se parte de un rectángulo, cuyas dimensiones son:
            ul.lista-ul--color.fa-ul.color-primario.ps-1
              li 
                i.fas.fa-plus
                | <strong>Largo del rectángulo=</strong> medida de talle delantero
              li
                i.fas.fa-plus
                | <strong>Ancho=</strong> ¼ de la medida de contorno de busto
            p.ps-5.mt-5.mb-5 Sobre el rectángulo se ubican los puntos de:
            ul.lista-ul--color.fa-ul.color-primario.ps-1
              li 
                i.fas.fa-plus
                | <strong>Centro frente (punto A)</strong>
              li
                i.fas.fa-plus
                | <strong>½ de la medida de talle (punto B).  Este punto se ubica utilizando la ventana de punto proporcional 0,5.</strong>
              li
                i.fas.fa-plus
                | <strong>El punto B corresponde a la altura de sisa.</strong>
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta7/imagen1.svg", alt='La imagen muestra cómo ubicar un punto en un patrón de costura usando un software de diseño. Se ve un rectángulo con dos puntos, Punto A y Punto B, conectados por una línea horizontal. A la derecha, una ventana de “Atributos de Punto” muestra configuraciones, destacando la opción “Proporcional” en 0.5. Esta configuración posiciona el punto de manera proporcional respecto a otros puntos en el patrón.')
        .row(titulo="2")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>2.</strong> Trace líneas guías sobre la caída y la medida de hombro. Eleve el ángulo superior derecho del rectángulo a la intersección de las líneas guías. Para ello, se utiliza la herramienta <strong>mover punto</strong>. Haga clic sobre el punto del ángulo superior izquierdo del rectángulo, cambiar el atributo de escalado a curva y modele la curva de escote con la herramienta <strong>mover punto</strong>.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta7/imagen2.svg", alt='La imagen muestra el diseño de un patrón de costura enfocado en la medida del escote y del hombro. A la izquierda, se indican las medidas del escote y del hombro con flechas rojas en la parte superior del rectángulo, junto con una flecha adicional que señala la “Caída de Hombro”. A la derecha, se muestra el patrón ajustado con una línea curva que representa la caída del hombro, y líneas punteadas azules que indican las guías para las medidas del escote y el hombro. Este diagrama explican cómo tomar y aplicar estas medidas en el patrón de una prenda.')
        .row(titulo="3")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>3.</strong> Trace la curva de escote utilizando la herramienta <strong>punto en contorno</strong>. Suprima los puntos de la imagen anterior para definir la línea de hombro y línea de sisa. Se puede tomar como referencia las <strong>líneas guías</strong>.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta7/imagen3.svg", alt='La imagen muestra un patrón de costura con líneas y puntos que indican las medidas y ajustes para el escote y el hombro. Las líneas punteadas azules representan guías de referencia para estas medidas. La línea curva en la parte superior izquierda indica el escote, mientras que las líneas inclinadas y rectas a la derecha muestran la caída y la posición del hombro. Este patrón visualiza cómo aplicar las medidas del escote y el hombro en el diseño de una prenda.')
        .row(titulo="4")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>4.</strong> Seleccione la línea de hombro en <strong>sentido de las manecillas del reloj</strong>. Haga clic en el botón <strong>editar largo del segmento</strong>; en esta ventana se escribe <strong>el valor a editar</strong> que para la talla 10 corresponde a 12 cm, también seleccione la opción <strong>última horizontal</strong>, según la posición de la gráfica. Al escoger esta opción se debe tener en cuenta que el punto a mover para ajustar la medida debe ser el <strong>punto hombro-sisa.</strong>
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta7/imagen4.svg", alt='La imagen muestra un software de diseño de patrones de costura, enfocado en la configuración del largo de un segmento. En la parte superior izquierda, hay una ventana titulada “Largo del segmento” donde se introduce la medida de 12 en el campo “Largo”, resaltada en un círculo rojo. Abajo, otra ventana titulada “Editar largo del segmento” también tiene el campo “Largo” con el valor 12.05, igualmente resaltado. A la derecha, el patrón de costura visualiza las modificaciones aplicadas, con líneas y guías punteadas azules que ayudan a ajustar y verificar las dimensiones del segmento en el diseño de la prenda.')
        .row(titulo="5")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>5.</strong> Para editar la medida de hombro utilice la herramienta <strong>medida</strong>.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta7/imagen5.svg", alt='La imagen muestra una barra de herramientas del software de diseño de patrones de costura, específicamente la sección llamada “Pieza”. Entre los íconos disponibles, uno está resaltado con un círculo rojo, aunque parece estar deshabilitado (en gris). Los íconos incluyen herramientas para manipular y ajustar piezas del patrón, como medir, cortar, y seleccionar diferentes tipos de prendas.')
        .row(titulo="6")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>6.</strong> Ubique el punto de <strong>altura de pecho</strong>. Para ello, se utiliza la herramienta <strong>punto en contorno</strong> y la <strong>opción proporcional 0,5</strong>. Seleccione el atributo de escalado. La ubicación de este punto se marca también sobre la línea de sisa.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta7/imagen6.svg", alt='La imagen muestra una ventana de “Atributos de Punto” del software de diseño de patrones de costura junto a un patrón de prenda. En la ventana, se pueden configurar los atributos del punto, como el tipo de punto (Curva o Escalado), coordenadas X e Y, distancia, ángulo, y la opción de mover sobre el contorno. También se destacan los valores de posición absoluta y proporcional del punto. A la derecha, el patrón muestra el punto ajustado en el diseño de la prenda, con líneas y puntos que indican las medidas y ajustes específicos.')
        .row(titulo="7")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>7.</strong> Con la herramienta <strong>mover punto</strong>; corra el punto a la distancia que resulte de la resta de la medida que dio entre los dos puntos y la medida de mitad de ancho de pecho, según la talla que se esté trazando.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta7/imagen7.svg", alt='La imagen muestra dos diagramas de patrones de costura. En el diagrama superior, se indican dos puntos específicos con círculos rojos, entre los cuales se mide la distancia utilizando la herramienta “Medida”. El texto entre los puntos dice: “Medimos la distancia entre estos puntos, con la herramienta ‘Medida’”. En el diagrama inferior, se muestra un patrón de prenda con las medidas y ajustes aplicados, reflejando la modificación basada en la distancia medida entre los dos puntos en el diagrama superior.')
        .row(titulo="8")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>8.</strong> Trace la curva de la sisa e identifique el punto de vértice de pinza.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta7/imagen8.svg", alt='La imagen muestra un patrón de costura con instrucciones para trazar la curva de la sisa y ubicar el punto de separación del busto. En la parte superior, se indica “Trazar la curva de sisa con ayuda de líneas guías”, utilizando líneas punteadas azules como referencia. En la parte inferior, una flecha roja señala “Ubicar el punto de separación de busto”, marcando su posición en el patrón.')
        .row(titulo="9")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>9.</strong> Para editar el largo de medida de costado seleccione los puntos en el <strong>sentido de las manecillas del reloj</strong>. De acuerdo con la figura se debe editar el último punto en forma diagonal. La medida de costado del patrón delantero <strong>debe ser igual al costado del posterior.</strong>
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta7/imagen9.svg", alt='La imagen muestra una ventana de “Largo del segmento” del software de diseño de patrones de costura. A la izquierda, la “Ventana de medidas” muestra detalles como la distancia, ángulo, y largo del segmento seleccionado, con un valor base de 22.25. En el centro, se ve el patrón de una prenda con líneas que indican las medidas ajustadas. A la derecha, otra ventana de “Largo del segmento” muestra un valor de 18.25 y opciones para extender el segmento en dirección vertical, horizontal o diagonal. Estas ventanas permiten ajustar y medir segmentos específicos del patrón.')
        .row(titulo="10")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>10.</strong> El patrón debe quedar según la ilustración.
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta7/imagen10.svg", alt='La imagen muestra una ventana emergente de un software de diseño de patrones de costura. La ventana emergente está titulada “ventana piezas” y ofrece opciones para editar una pieza del patrón. El menú desplegable muestra las opciones “Editar”, “Pieza”, y “Borrar”. Bajo la opción “Pieza”, se pueden elegir las subopciones “Reemplazar Original”, “Remover Actual” y “Crear como nueva”. En el fondo, se observa parte de un patrón de costura y una regla de medición, lo que sugiere que el usuario está trabajando en ajustar o modificar el diseño del patrón.')
        .row(titulo="11")
          .col-md-5.mb-4.mb-md-0
            p.ps-5 <strong>11.</strong> Corregir el sentido de hilo de la tela con la herramienta <strong>hilo paralelo al tramo.</strong> Centre y aplome con la herramienta <strong>nueva línea base.</strong> Por último, actualizar los cambios en la ventana de piezas, con la opción <strong>reemplazar original.</strong>
          .col-md-7
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta7/imagen11.svg", alt='La imagen muestra un patrón de costura para la parte delantera de una prenda, como una camisa o blusa. Incluye las líneas de contorno para los bordes, puntos de referencia importantes (marcados en rosa y negro), y líneas de construcción para guiar el corte y la costura. La “Base Delantero” es una línea vertical utilizada como referencia. Las curvas en la parte superior representan el escote y la sisa, esenciales para el ajuste de la prenda. El patrón guía el corte y ensamblaje de la tela para asegurar un ajuste correcto y la forma deseada.')

    <br> <br>
    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-8.mb-sm-0
                  br
                  p.mb-0 A continuación, le invito a revisar el siguiente video sobre el” trazo de la base superior femenina”.
                  br
                .col-sm-12.col-lg-4
                  a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm
      .col-sm-12.col-lg-6
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-8.mb-sm-0
                  p.mb-0 También se recomienda revisar el siguiente video para una mejor compresión sobre cómo “crear, modificar y trasladar los diferentes estilos de pinza en Optitex”.
                .col-sm-12.col-lg-4
                  a.boton.color-boton(href="https://www.youtube.com/embed/Ds5CtwVbaag" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm

    <br>
    Separador
    .row.mb-4
      .titulo-segundo.color-primario
        h2 1.4  Traslados de pinza - <em>Optitex</em>

    .tarjeta.tarjeta--azul.p-4.mb-4.borde-redondo(style="background-color: #F8F5FF")
      SlyderA(tipo="b")
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>1.</strong> Para dar inicio se parte de la base superior delantera, trace una línea guía hasta la línea de cintura o largo de talle delantero.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen1.svg", alt='La imagen muestra dos patrones de costura para la parte delantera y trasera de una prenda, como una camisa o blusa. El patrón de la izquierda, marcado como “Base SUPERIOR FRENTE”, corresponde a la parte delantera, mientras que el de la derecha, “Base SUPERIOR ESPALDA”, corresponde a la parte trasera. Ambos patrones incluyen puntos de referencia en rosa que indican lugares clave para la construcción de la prenda. Las líneas de contorno definen los bordes de cada pieza, incluyendo el escote, la sisa, el costado y el dobladillo. Las flechas indican la dirección de la base y sirven como guía para la alineación y corte de la tela.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>2.</strong> Traiga  una línea guía de la regla vertical y llévela hasta el ángulo <strong>cintura costado.</strong> Con la herramienta <strong>mover punto</strong> lleve el ángulo cintura costado a la intersección de las dos líneas guías.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen2.svg", alt='La imagen muestra dos patrones de costura para la parte delantera de una prenda, etiquetados como “Base SUPERIOR FRENTE”. Ambos patrones son azules y tienen puntos de referencia en rosa para la construcción. Las líneas de contorno definen los bordes de la pieza, y las flechas indican la dirección de la base para guiar el corte de la tela.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>3.</strong> Valide que la línea de cintura esté <strong>totalmente recta</strong> sobre la línea de talle delantero, y verifique con la <strong>tecla F8</strong> qué medida tiene la cintura.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen3.svg", alt='La imagen muestra dos patrones de costura: uno para la parte delantera (izquierda) y otro para la parte trasera (derecha) de una prenda. El patrón delantero está marcado como “Base SUPERIOR FRENTE” y está coloreado en azul, mientras que el trasero está marcado como “Base SUPERIOR ESPALDA”. Ambos patrones incluyen puntos de referencia en rosa y medidas específicas en cada punto, indicando las distancias entre los diferentes puntos clave del patrón. Las flechas indican la dirección de la base para guiar el corte de la tela.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.ps-5.mt-4 <strong>4.</strong> En la línea de cintura se identifica un punto con atributo de escalado a 9 cm, este punto determina la medida de separación del busto. <strong>Medida de cintura:</strong>
            ul.lista-ul--color.fa-ul.color-primario.ps-1
              li 
                i.fas.fa-plus
                | <strong>Cintura:</strong> ¼ contorno de cintura + pinza
            p.ps-5 Al tomar como punto de partida los 9 cm, marque un punto a 12 cm para que quede exactamente la medida ¼ contorno de cintura, 17 cm + 4 cm de pinza, para un total de 21 cm. Con la herramienta <strong>puntos sobre</strong> (tecla rápida O) a partir de los 9 cm ubicar un punto a 12 cm o el restante para la medida de cintura.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen4.svg", alt='La imagen muestra una ventana de configuración de atributos de punto en un software de diseño de patrones de costura, junto a un patrón para la parte delantera de una prenda etiquetado como “Base SUPERIOR FRENTE”. En la ventana de configuración, se pueden ajustar las coordenadas (X e Y), la distancia, el ángulo, y si el punto es una curva o escalado. También se muestra la posición relativa y absoluta del punto en relación con otros puntos del patrón.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>5.</strong> Dé clic derecho, escoja la herramienta <strong>selección</strong>, señale el punto del costado y suprimir. Para verificar nuevamente las medidas oprimir la <strong>tecla F8</strong>.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen5.svg", alt='La imagen muestra tres vistas de patrones de costura en un software de diseño. En la vista izquierda, se muestra el patrón de la parte delantera de una prenda etiquetado como “Base SUPERIOR FRENTE”. En el centro, hay un menú contextual del software con opciones como “Seleccionar Herramienta”, “Líneas guía”, “Nueva pieza”, “Insertar”, “Herramientas”, “Segmento”, “Zoom”, y “Deshacer Agregar un punto”. En la vista derecha, se muestra el mismo patrón delantero con medidas específicas entre puntos clave. Los patrones están en azul y tienen puntos de referencia en rosa, con líneas de contorno que definen los bordes y flechas que indican la dirección de la base.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>6.</strong> Si la medida de los costados de la pieza del frente y del posterior no coinciden, trace una pinza correctiva de talle. Con la herramienta <strong>punto sobre</strong>, ubicar un punto a 5 cm por debajo de la altura de la sisa.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen6.svg", alt='La imagen muestra una ventana de configuración de atributos de punto en un software de diseño de patrones de costura, junto a un patrón para la parte delantera de una prenda etiquetado como “Base SUPERIOR FRENTE”. La ventana permite ajustar las coordenadas X e Y, la distancia, y el ángulo de un punto específico en el patrón. También se puede seleccionar si el punto es una curva o escalado, y moverlo sobre el contorno. Además, se muestran las posiciones absoluta y proporcional del punto en relación con otros puntos del patrón.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>7.</strong> Marque una línea guía, exactamente al <strong>punto</strong> de los 5 cm. Con la herramienta punto, fijar ese mismo punto sobre la línea centro frente. Marque una línea guía vertical para identificar el <strong>vértice de pinza.</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen7.svg", alt='La imagen muestra dos versiones del patrón de costura para la parte delantera de una prenda, etiquetados como “Base SUPERIOR FRENTE”. Ambos patrones son azules y tienen puntos de referencia en rosa. Las líneas de contorno definen los bordes de cada pieza, y las flechas indican la dirección de la base. La diferencia entre los dos patrones es que el de la derecha tiene una línea adicional horizontal y vertical, posiblemente para ajustes o modificaciones específicas del diseño.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>8.</strong> Para verificar el largo de los costados oprima la <strong>tecla F8</strong>. Para validar el largo del costado delantero tome la medida con la herramienta <strong>medir</strong>, del grupo de herramientas de pieza, o sume los dos segmentos que aparecen.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen8.svg", alt='La imagen muestra dos patrones de costura, uno delantero y otro trasero, ambos etiquetados como “Base SUPERIOR FRENTE” y “Base SUPERIOR ESPALDA”. Cada patrón está en azul con puntos de referencia en rosa y medidas entre puntos clave. También se ve una herramienta de medición del software de diseño, que permite ajustar ángulos y longitudes de los segmentos del patrón.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>9.</strong> Para poder deducir la <strong>medida de la pinza</strong>, en el grupo de herramientas <strong>vista</strong>, opción <strong>otras herramientas</strong>, seleccione <strong>calculadora.</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen9.svg", alt='La imagen muestra una interfaz de software de diseño de patrones de costura con un menú desplegable que ofrece varias opciones como calcular, mostrar líneas guía y otras herramientas. A la derecha, se ve una calculadora. Estos elementos indican la integración de herramientas de medición y cálculo dentro del software para ajustar y diseñar los patrones de costura.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>10.</strong> Después de tener clara la medida de la pinza, <strong>marque pinza</strong>. Tome la herramienta <strong>pinza</strong>, opción <strong>insertar pinza</strong>, desde el punto de los 5 cm de altura de busto, dar la medida correspondiente a la amplitud de la pinza, marque la <strong>profundidad o el largo</strong> de pinza, hasta la intersección de las líneas guías, correspondiente al vértice de pinza o altura de busto.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen10.svg", alt='La imagen muestra dos capturas de pantalla de un software de diseño de patrones. La izquierda presenta una ventana para ajustar atributos de punto (coordenadas, distancia y ángulo), mientras que la derecha muestra el patrón delantero de una prenda, etiquetado como “Base SUPERIOR FRENTE”, con un punto ajustado.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>11.</strong> Con la pinza correctiva de talle se realizarán todos los traslados de pinza. Para crear la pinza de entalle o ajuste por cintura, primero <strong>elimine líneas guías y limpie el área de trabajo</strong>. Tome la herramienta pinza, opción <strong>insertar pinza</strong> y asigne la medida para el primer y segundo lado de pinza. La pinza de entalle debe quedar entre 2 a 3 cm por debajo de la pinza de recuperación de talle.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen11.svg", alt='La imagen muestra tres capturas de pantalla de un software de diseño de patrones de costura. La primera captura presenta una ventana de configuración de atributos de punto, permitiendo ajustar coordenadas, distancia, y ángulo de un punto. La segunda captura muestra el patrón delantero de una prenda con un punto ajustado y líneas adicionales. La tercera captura también muestra el patrón delantero con modificaciones en las líneas de construcción.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>12.</strong> Para realizar el traslado de pinza se sugiere que mueva el hilo de tela, con el fin de no interferir con el traslado seleccione la herramienta <strong>mover interno</strong> (tecla rápida I).
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen12.svg", alt='La imagen muestra tres capturas de pantalla de un software de diseño de patrones de costura. La primera captura presenta la “Caja de herramientas” con varias opciones para mover puntos y piezas, resaltando “Mover Interno (I)”. La segunda y tercera capturas muestran el patrón delantero de una prenda, etiquetado como “Base SUPERIOR FRENTE”, con líneas y puntos ajustados utilizando las herramientas seleccionadas.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>13.</strong> Como ya se identifican las pinzas y para poder actualizarlas pulse <strong>clic derecho, opción limpiar pieza, actualizar pieza. Eliminar o suprimir la pieza posterior.</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen13.svg", alt='La imagen muestra tres capturas de pantalla de un software de diseño de patrones de costura. La primera captura presenta la “Caja de herramientas” con varias opciones para mover puntos y piezas, resaltando “Mover Interno (I)”. La segunda y tercera capturas muestran el patrón delantero de una prenda, etiquetado como “Base SUPERIOR FRENTE”, con líneas y puntos ajustados utilizando las herramientas seleccionadas. La primera captura presenta la “Caja de herramientas” con varias opciones para mover puntos y piezas, resaltando “Mover Interno (I)”. La segunda y tercera capturas muestran el patrón delantero de una prenda, etiquetado como “Base SUPERIOR FRENTE”, con líneas y puntos ajustados utilizando las herramientas seleccionadas.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>14.</strong> Para poder realizar los diferentes tipos de traslados de pinza copie la pieza actual del delantero. Para copiar la pieza, en la ventana pieza dé clic <strong>derecho en pieza - crear como nueva</strong>. Cree las copias que considere necesarias de acuerdo con la cantidad de traslados de pinza que se vayan a realizar.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen14.svg", alt='La imagen muestra una captura de pantalla de un software de diseño de patrones de costura con una ventana emergente de opciones para editar piezas. La opción seleccionada es “Crear copia nueva”. En el fondo, hay varios patrones delanteros de una prenda etiquetados como “Base SUPERIOR FRENTE”, uno de ellos en azul y los demás en blanco. Cada patrón tiene líneas y puntos de referencia ajustados.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>15.</strong> Para empezar los traslados de pinza inicie con un traslado de hombro, tome <strong>herramienta pinza</strong>, opción <strong>añadir y girar pinza</strong>. Al acercarse al vértice de pinza, de la pinza correctiva de talle se identifica un cambio de color, señalando qué se puede modificar o trasladar.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen15.svg", alt='La imagen muestra un menú del software de diseño de patrones con la opción “Añadir y girar pinza” seleccionada. A la derecha, un patrón delantero de una prenda (“Base SUPERIOR FRENTE”) tiene una pinza añadida y ajustada.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>16.</strong> En el sentido de las manecillas del reloj se traslada la pinza hacia el hombro para que la pinza quede en toda la mitad de la medida o el largo de hombro; en la ventana de diálogo <strong>casilla proporcional</strong> asigne 0.5. Al validar la medida se identifica que el recorrido del patrón se torna de un color diferente desde un punto hacia el otro, esto quiere decir que ya está lista la pieza para realizar el traslado.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen16.svg", alt='La imagen muestra dos capturas de pantalla de un software de diseño de patrones de costura. A la izquierda, se ve una ventana de configuración de atributos de punto con opciones para ajustar coordenadas, distancia y ángulo. A la derecha, se muestra un patrón delantero de prenda etiquetado como “Base SUPERIOR FRENTE” con ajustes visibles en las líneas de construcción y una pinza añadida.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>17.</strong> Haga clic sobre cualquier punto de la pieza, automáticamente la pinza se ancla y al cerrar o mover la pieza se identifica el traslado de la pinza hacia el lado deseado.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen17.svg", alt='La imagen muestra dos patrones delanteros de una prenda etiquetados como “Base SUPERIOR FRENTE”. A la izquierda, el patrón tiene líneas verdes adicionales que indican ajustes o añadidos, como una pinza. A la derecha, el patrón muestra más modificaciones con una pinza añadida y un área destacada con un recuadro punteado, indicando un ajuste específico.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>18.</strong> De esa manera se deben hacer los traslados de pinza a cada una de las partes del cuerpo.
            ol.lista-ol--cuadro.ps-5
                li 
                  .lista-ol--cuadro__vineta
                    span 1
                  | Traslado al hombro
                li 
                  .lista-ol--cuadro__vineta
                    span 2
                  | Traslado a la sisa
                li 
                  .lista-ol--cuadro__vineta
                    span 3
                  | Traslado al costado
                li 
                  .lista-ol--cuadro__vineta
                    span 4
                  | Traslado a la pinza de entalle
                li 
                  .lista-ol--cuadro__vineta
                    span 5
                  | Traslado al centro frente
                li 
                  .lista-ol--cuadro__vineta
                    span 6
                  | Traslado al escote
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta8/imagen18.svg", alt='La imagen muestra cinco patrones de la parte delantera de una prenda etiquetada como “Base SUPERIOR FRENTE”. Cada patrón tiene variaciones en las líneas de construcción y las pinzas, indicando diferentes ajustes y modificaciones. Los puntos de referencia en rosa y las líneas de construcción muestran cómo se pueden alterar los patrones para adaptar la prenda.')

    <br> <br>
    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-8.mb-sm-0
                  p.mb-0 Para una mejor comprensión del tema le invito a revisar el siguiente video sobre “traslados de pinzas”.
                .col-sm-12.col-lg-4
                  a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm
      .col-sm-12.col-lg-6
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-8.mb-sm-0
                  p.mb-0 También se recomienda visualizar el siguiente video donde se muestra cómo “aplicar y manipular pinzas en Optitex”.
                .col-sm-12.col-lg-4
                  a.boton.color-boton(href="https://www.youtube.com/embed/Ds5CtwVbaag" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm
    
    Separador    
    .row.mb-4
      .titulo-segundo.color-primario
        h2 1.5  Cortes base superior femenina - <em>Optitex</em>

    .tarjeta.tarjeta--gris.p-4.borde-redondo(style="background-color: #F8F5FF")
      LineaTiempoC.color-acento-botones(text-small)
        .row(titulo="1")
          .col-md-4.mb-4.mb-md-0
            p.ps-5.mb-4 <strong>1.</strong> Tomar herramienta <strong>pinza</strong>, opción <strong>añadir y girar pinza</strong>. Encontrará las pinzas en el punto central del busto.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen1.svg", alt='La imagen muestra tres capturas de pantalla de un software de diseño de patrones de costura. A la izquierda, se ve un menú desplegable con la opción “Añadir y girar pinza” seleccionada. En el centro y a la derecha, se muestran patrones delanteros de una prenda, etiquetados como “Base SUPERIOR FRENTE”, con pinzas añadidas y ajustadas, representadas por líneas de construcción y puntos de referencia en el área del busto.')
        .row(titulo="2")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>2.</strong> Grupo de herramientas <strong>piezas</strong>, opción <strong>cortar a pieza</strong>. El cursor cambia a una estrella y tijeras, la estrella debe coincidir sobre el punto que se quiere cortar.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen2.svg", alt='La imagen muestra una captura de pantalla de un software de diseño de patrones de costura, enfocada en la herramienta “Pieza”. El menú desplegable ofrece dos opciones: “Cortar a pieza” y “Cortar a pieza a lo largo de un interno”. La opción “Cortar a pieza” está seleccionada. Esta herramienta permite ajustar y modificar las piezas del patrón dentro del software.')
        .row(titulo="3")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>3.</strong> Inicie por el punto de hombro hacia centro frente, haga clic en el <strong>vértice de pinza</strong>, y luego dé clic en el botón <strong>aceptar</strong> de la ventana emergente.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen3.svg", alt='La imagen muestra dos capturas de pantalla de un software de diseño de patrones de costura. En la captura de la izquierda, se ve un patrón delantero de prenda etiquetado como “Base SUPERIOR FRENTE” con líneas de construcción y puntos de referencia. A la derecha, se muestra la ventana “Mover Puntos”, que permite ajustar la posición de un punto específico en el patrón, con opciones para mover desde un punto, un segmento, o una ventana definida, y para ajustar las coordenadas y ángulos del punto seleccionado.')
        .row(titulo="4")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>4.</strong> Seguir cortando hasta el punto de cintura centro frente, al finalizar el corte se habilita una ventana emergente para asignar margen de costura, en este caso se está trabajando sin margen de costura, así que presione el <strong>botón cancelar.</strong>
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen4.svg", alt='La imagen muestra dos capturas de pantalla de un software de diseño de patrones de costura. A la izquierda, se ve un patrón delantero de prenda etiquetado como “Base SUPERIOR FRENTE” con líneas de construcción y puntos de referencia. A la derecha, se muestra la ventana “Atributos de Costura”, que permite definir el inicio y fin de las costuras, las costuras de esquina, y ajustar el ancho de costura. También incluye opciones para conservar escalado y aplicar configuraciones específicas a las costuras del patrón.')
        .row(titulo="5")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>5.</strong> Al generar el corte se crea un hilo de tela diferente, es decir, quedan hilos de tela independientes por pieza. Al seleccionar la pieza y al arrastrar se identifica la división o el corte.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen5.svg", alt='La imagen muestra dos patrones de costura para la parte delantera de una prenda, etiquetados como “Base SUPERIOR FRENTE”. Cada patrón presenta variaciones en las líneas de construcción y puntos de referencia, indicando diferentes ajustes y modificaciones. Los patrones están en azul con puntos de referencia en rosa, y las líneas de construcción muestran cómo se pueden alterar los patrones para adaptar la prenda.')
        .row(titulo="6")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>6.</strong> Para eliminar los excedentes de pinza del corte siguiente se debe tomar la herramienta <strong>cortar a pieza</strong> (tecla rápida C), fijar punto desde el hombro hacia sisa, hasta punto de vértice de pinza, <strong>cancelar ventana emergente y separar pieza.</strong>
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen6.svg", alt='La imagen muestra tres capturas de pantalla de un software de diseño de patrones de costura. A la izquierda, se ve el menú de la herramienta “Pieza” con la opción “Cortar a pieza” seleccionada. En el centro, se muestra un patrón delantero de una prenda etiquetado como “Base SUPERIOR FRENTE” con líneas de construcción adicionales que indican un corte. A la derecha, el patrón cortado en dos piezas separadas, reflejando el ajuste realizado.')
        .row(titulo="7")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>7.</strong> Tome nuevamente herramienta cortar <strong>pieza</strong> (tecla rápida C), y finalizar el corte desde vértice de pinza hasta cintura.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen7.svg", alt='La imagen muestra dos capturas de pantalla de un software de diseño de patrones de costura. A la izquierda, se ve un patrón delantero de prenda etiquetado como “Base SUPERIOR FRENTE” cortado en dos partes. A la derecha, el patrón se ha dividido en tres piezas separadas: la parte superior, una pieza intermedia, y una pieza pequeña adicional, todas etiquetadas y ajustadas según las líneas de construcción y puntos de referencia.')
        .row(titulo="8")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>8.</strong> Separe la pieza hasta obtener piezas entre frente, pieza acostado y sobrantes de pinza. Para eliminar los sobrantes de las pinzas haga <strong>clic sobre la pieza</strong> para identificar el nombre o la pieza en la <strong>ventana de piezas</strong>. Luego de identificar la pieza en la ventana de piezas dé clic sobre la ventana, opción <strong>editar - borrar pieza desde modelo.</strong>
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen8.svg", alt='La imagen muestra dos capturas de pantalla de un software de diseño de patrones de costura. En la captura de la izquierda, se ve la ventana “Ventana piezas” con varias piezas de patrones, destacando la “Base SUPERIOR FRENTE” que se ha dividido en varias partes. En la captura de la derecha, un menú contextual muestra opciones para editar, cortar, copiar y borrar piezas, con la opción “Borrar Pieza desde modelo” resaltada. Las piezas del patrón se muestran separadas y etiquetadas, listas para ser ajustadas o eliminadas según sea necesario.')
        .row(titulo="9")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>9.</strong> Repita el ejercicio hasta eliminar todos los sobrantes y dejar únicamente las piezas correspondientes al corte. Con el fin de suavizar las puntas generadas en cada uno de los cortes, lo primero que debe hacer es limpiar la pieza, para ello, <strong>haga clic sobre el corte</strong>, una vez se seleccione indica que quedó el segmento de la pinza anterior, oprimir la tecla <strong>suprimir</strong> para eliminar dicho segmento.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen9.svg", alt='La imagen muestra tres capturas de pantalla de un software de diseño de patrones de costura. En la primera captura, se ve la ventana “Ventana piezas” con varias piezas de patrones, destacando la “Base SUPERIOR FRENTE” que se ha dividido en varias partes. En la segunda captura, se muestra un patrón delantero de prenda con una pinza añadida y líneas de construcción adicionales, representado como varias piezas etiquetadas. En la tercera captura, las piezas del patrón se muestran separadas y etiquetadas, destacando la “Base SUPERIOR FRENTE” dividida en tres partes, listas para ser ajustadas o ensambladas.')
        .row(titulo="10")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>10.</strong> Repita el ejercicio hasta que no se identifiquen segmentos externos a cada una de las piezas. Al tener la pieza completamente limpia de cualquier segmento, dé clic sobre el punto de vértice o de intersección de pinza y en la pestaña <strong>propiedades</strong>, opción <strong>principal</strong>, habilite el <strong>atributo curva.</strong>
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen10.svg", alt='La imagen muestra una interfaz de software de diseño de patrones de costura. En la parte superior, hay una barra con iconos de diferentes piezas de patrones. En el centro, se visualizan dos piezas de patrón: una recta y otra curva, con líneas y puntos de ajuste. A la izquierda, hay un panel de propiedades con opciones seleccionables como “Punto”, “Escalada”, “Curva”, entre otras.')
        .row(titulo="11")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>11.</strong> Al asignar el <strong>atributo de curva</strong> se modifica toda la pieza.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen11.svg", alt='La imagen muestra una interfaz de software de diseño de patrones de costura. En la parte superior, hay una barra con iconos de diferentes piezas de patrón etiquetadas como “Base Sup”. En el centro, se visualizan dos piezas de patrón: una recta y otra curva (coloreada en azul), con líneas y puntos de ajuste. A la izquierda, hay un panel de propiedades con opciones como “Principal”, “Escalado”, “Curva”, “Conectado”, y otras. ')
        .row(titulo="12")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>12.</strong> Para evitar modificar todo el trayecto se sugiere agregar punto en ambas direcciones y colocar la medida del trayecto dependiendo del volumen del busto o copa, sin seleccionar ningún atributo.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen12.svg", alt='La imagen muestra dos capturas de pantalla de una interfaz de software de diseño de patrones de costura. En ambas capturas, se ven dos piezas de patrón: una recta y otra curva (coloreada en azul). Cada captura tiene una ventana emergente titulada “Atributos de Punto”, donde se pueden ajustar valores como la distancia y el ángulo. Ambas ventanas tienen opciones para “Cerrar”, “Mostrar valor constante”, y campos para ingresar detalles específicos de los puntos.')
        .row(titulo="13")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>13.</strong> Al seleccionar el <strong>punto de vértice pinza</strong> y pasar atributo de curva se identifica cómo se suaviza el vértice. Seleccionar herramienta <strong>mover punto y suavizar</strong> como se haría de manera manual.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen13.svg", alt='La imagen muestra dos partes de una interfaz de software de diseño de patrones de costura. La parte izquierda muestra la interfaz completa con dos piezas de patrón, una recta y otra curva (coloreada en azul), y un panel de propiedades con opciones como “Principal”, “Escalado”, “Curva”, entre otras. La parte derecha muestra una ampliación de la pieza curva en azul, detallando los puntos y líneas de ajuste.')
        .row(titulo="14")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>14.</strong> 
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen14.svg", alt='La imagen muestra dos partes de una interfaz de software de diseño de patrones de costura. La parte izquierda muestra la interfaz completa con dos piezas de patrón, una recta y otra curva (coloreada en azul), y un panel de propiedades con opciones como “Principal”, “Escalado”, “Curva”, entre otras. La parte derecha muestra una ampliación de la pieza curva en azul, detallando los puntos y líneas de ajuste.')
        .row(titulo="15")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>15.</strong> Repita el mismo ejercicio en cada una de las bases con traslado de pinza para convertir a cortes, recuerde que los nombres comerciales de los cortes varían según la región o el país donde se trabaje, siempre remítase a la parte funcional o técnica de lo que se está trabajando.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta9/imagen15.svg", alt='La imagen muestra cuatro piezas de patrón de costura en una interfaz de software de diseño. Las piezas están etiquetadas como “Blusa CF”, “Blusa Espalda DEL”, “Blusa Espalda”, y “Blusa Espalda Fruncida” (esta última coloreada en azul). Todas las piezas tienen líneas y puntos de ajuste visibles, organizados de manera que parecen partes de un patrón para una blusa.')

    <br> <br>
    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-8.mb-sm-0
                  p.mb-0 Para una mejor comprensión del tema revisar el siguiente video sobre “cortes de base superior femenina”.
                .col-sm-12.col-lg-4
                  a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm

    Separador    
    .row.mb-4
      .titulo-segundo.color-primario
        h2 1.6  Blusa hasta la cadera - <em>Optitex</em>

    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema1/imagen2.svg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Para dar inicio al trazo de la blusa hasta cadera (página número 39 del manual) se trabajará con la base trazada anteriormente, con traslado de pinza por costado y pinza de ajuste. Este ejercicio brinda el contexto general para trabajar cualquier tipo de interpretación o modificación de prendas superiores.

    .tarjeta.tarjeta--azul.p-4.mb-4.borde-redondo(style="background-color: #F8F5FF")
      SlyderA(tipo="b")
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>1.</strong> Para modificar el largo de la prenda, en este caso hasta la altura de cadera; diríjase a <strong>caja de herramientas</strong>, opción <strong>movimiento paralelo.</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen1.svg", alt='La imagen muestra dos vistas de una interfaz de software de diseño de patrones de costura. En la parte izquierda, se ve una pieza de patrón titulada “Base Sup FRENTE” (coloreada en azul) con líneas y puntos de ajuste, y un panel de herramientas a la izquierda con opciones como “Mover punto”, “Movimiento paralelo”, y “Cortar/Borrar”. A la derecha, se muestra una ampliación de la misma pieza de patrón con más detalle en las líneas y puntos de ajuste.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>2.</strong> Seleccionar la línea de cintura en sentido de las manecillas del reloj. Cuando el cursor cambia de forma se puede alargar arrastrando el mouse.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen2.svg", alt='La imagen muestra tres vistas de una pieza de patrón titulada “Base Sup FRENTE” (coloreada en azul) en una interfaz de software de diseño de patrones de costura. Las tres vistas presentan la misma pieza, pero con diferentes líneas y puntos de ajuste, mostrando variaciones en los detalles de costura y ajustes. Cada vista incluye líneas punteadas y sólidas que indican diferentes secciones y posibles ajustes de la pieza del patrón.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>3.</strong> En la ventana emergente <strong>movimiento paralelo del tramo</strong>, marque el largo deseado, teniendo en cuenta el eje X y el eje Y, posteriormente haga clic en el botón <strong>aceptar.</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen3.svg", alt='La imagen muestra dos partes de una interfaz de software de diseño de patrones de costura. A la izquierda, se ve una ventana emergente titulada “Movimiento paralelo del tramo”, donde se pueden ingresar valores numéricos y direcciones para ajustar el movimiento de los puntos del patrón. A la derecha, se muestra una pieza de patrón titulada “Base Sup FRENTE” (coloreada en azul) con líneas y puntos de ajuste, indicando las modificaciones realizadas.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>4.</strong> Al modificar el largo se identifica la variación en la pinza, es decir, se ve la pinza anclada al largo. Para eliminar la pinza dé <strong>clic derecho</strong> en la <strong>herramienta selección</strong>, seleccione el trayecto o la pinza y suprimir, de igual manera, se debe suprimir todos y cada uno de los puntos de la pinza.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen4.svg", alt='La imagen muestra tres vistas de una pieza de patrón titulada “Base Sup FRENTE” (coloreada en azul) en una interfaz de software de diseño de patrones de costura. En la vista izquierda, se muestra un menú desplegable con opciones como “Seleccionar Herramienta”, “Líneas guía”, “Nueva pieza”, “Herramientas”, “Segmento”, y “Zoom”. Las vistas central y derecha muestran la misma pieza de patrón con diferentes detalles de líneas y puntos de ajuste, indicando posibles modificaciones en la costura.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>5.</strong> En este punto ya se tiene la blusa con el largo deseado, es necesario darle la forma de cada uno de los puntos del cuerpo. Para marcar el punto de cintura tome la herramienta puntos sobre y fijar un punto con atributo de <strong>escalado</strong>, por costado con la medida de altura de cadera. Para verificar las medidas oprimir la <strong>tecla F8.</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen5.svg", alt='La imagen muestra dos partes de una interfaz de software de diseño de patrones de costura. A la izquierda, se ve una ventana emergente titulada “Atributos de Punto” con opciones para ajustar el tipo de punto, su número, y sus coordenadas (X e Y), además de opciones de movimiento y escalado. A la derecha, se muestra una pieza de patrón titulada “Base Sup FRENTE” (coloreada en azul) con líneas y puntos de ajuste, incluyendo medidas y coordenadas numéricas para varios puntos del patrón.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>6.</strong> Verifique el recorrido de la línea de cadera con la herramienta <strong>medir.</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen6.svg", alt='La imagen muestra una interfaz de software de diseño de patrones de costura. A la izquierda, se ve una ventana emergente titulada “Ventana de medidas” con campos para ajustar la distancia, ángulo, y largo de un segmento, además de opciones para editar el largo del segmento. A la derecha, se muestra una pieza de patrón titulada “Base Sup FRENTE” (coloreada en azul) con líneas y puntos de ajuste. La ventana de medidas parece estar utilizada para modificar y precisar las dimensiones de la pieza del patrón.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>7.</strong> Aumente la medida de 1/4 del contorno de cadera más pinza según el manual, en editar segmento en la ventana de <strong>medidas</strong>, asignar medida, y presione el botón <strong>aceptar</strong>.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen7.svg", alt='La imagen muestra dos capturas de una interfaz de software de diseño de patrones de costura. Ambas capturas presentan la “Ventana de medidas” con campos para ajustar la distancia (Dist), ángulo (Angulo) y largo (Largo) de un segmento. En ambas ventanas, se están modificando los valores del largo del segmento para la talla “Base”. A la derecha, se observa una pieza de patrón titulada “Base Sup FRENTE” (coloreada en azul) con líneas y puntos de ajuste. Las ventanas de medidas permiten modificar y precisar las dimensiones de esta pieza del patrón.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>8.</strong> Para marcar la pinza en segmento interno se debe marcar una línea guía en cintura. Con la herramienta <strong>puntos sobre</strong>, fije en el segmento de centro frente, un punto, en el punto de talle o cintura.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen8.svg", alt='La imagen muestra dos vistas de una interfaz de software de diseño de patrones de costura, ambas con la pieza de patrón titulada “Base Sup FRENTE” (coloreada en azul). A la izquierda, se observa una ventana emergente titulada “Atributos de Punto” que permite ajustar las coordenadas X e Y, la distancia, y el ángulo de un punto específico en el patrón, además de opciones para mover el punto sobre el contorno y escalado. A la derecha, se ve la misma pieza de patrón sin la ventana emergente, mostrando las líneas y puntos de ajuste.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>9.</strong> En el grupo de herramientas <strong>insertar</strong> identifique la herramienta <strong>botón</strong>, y dé clic en <strong>crear botón</strong>. Para marcar el punto de pinza se debe tener en cuenta el primer y segundo lado de pinza, el análisis se hace tomando como referencia el ancho de pinza y la separación de busto.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen9.svg", alt='La imagen muestra una interfaz de software de diseño de patrones de costura. Incluye una barra de herramientas con la opción “Crear Botón”, una ventana emergente para ajustar las coordenadas y la posición del botón, y una pieza de patrón “Base Sup FRENTE” con un botón agregado en el patrón.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>10.</strong> Crear cada uno de los puntos de pinza con la herramienta <strong>botón</strong>, con el fin de poder marcar el ancho de la pinza.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen10.svg", alt='La imagen muestra una interfaz de software de diseño de patrones de costura. A la izquierda, se ve una barra de herramientas con opciones de edición, y una pieza de patrón coloreada en azul con un símbolo de botón agregado. A la derecha, se muestra una pieza de patrón titulada “Base Sup FRENTE” con varios símbolos de botón agregados en diferentes puntos del patrón.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>11.</strong> Para marcar el largo de la pinza por la línea de cadera utilizar la herramienta <strong>punto.</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen11.svg", alt='La imagen muestra una interfaz de software de diseño de patrones de costura con dos ventanas emergentes tituladas “Atributos de Punto”. Estas ventanas permiten ajustar las coordenadas, distancia, ángulo y proporciones de los puntos en el patrón. En el fondo, se observan dos piezas de patrón coloreadas en azul con varios símbolos de botón agregados y líneas de ajuste visibles.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>12.</strong> Se debe identificar cada uno de los vértices de pinza, teniendo en cuenta que no se puede encontrar el vértice de pinza por costado y el vértice de pinza de ajuste.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen12.svg", alt='La imagen muestra dos patrones de costura para la parte delantera de una prenda. Ambos patrones tienen marcados los mismos puntos de referencia y líneas guía, pero el patrón de la izquierda incluye marcas adicionales para la colocación de pinzas, mientras que el patrón de la derecha tiene una marca para un ojal.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>13.</strong> Para marcar o dibujar la pinza, en la herramienta <strong>dibujar</strong>, opción <strong>borrador</strong> se puede ir marcando cada uno de los puntos o vértices señalados.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen13.svg", alt='La nueva imagen muestra dos patrones de costura adicionales para la parte delantera de una prenda. El patrón de la izquierda tiene una línea verde que parece indicar una nueva línea de corte o costura. El patrón de la derecha tiene un diseño con una pinza central que se extiende desde la parte inferior hasta el centro del patrón, además de una marca para un ojal cerca de la parte superior.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.ps-5.mb-4 <strong>14.</strong> Para trazar la parte posterior de la blusa hasta la cadera se parte desde el básico posterior. Trace una línea guía en el punto de cintura costado, en este caso debe tener en cuenta los desniveles de cintura, es decir, el largo de la prenda se dará desde el punto de costado cintura, mientras que la pinza se marcará desde el punto de cintura centro atrás.
            p.ps-5 Para alinear los puntos de cintura, en el grupo de herramientas de <strong>contorno</strong> seleccione <strong>alinear puntos</strong> (tecla rápida G), seleccione los puntos de cintura que se quieren alinear; siempre se debe marcar en el sentido de las manecillas del reloj.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen14.svg", alt='La imagen muestra dos patrones de costura para la parte trasera de una prenda. Ambos patrones tienen marcas de referencia con medidas numéricas en puntos clave. El patrón de la izquierda incluye una línea vertical que puede indicar una costura o pliegue. El patrón de la derecha, que es una versión más pequeña del primero, también tiene una línea vertical similar. Ambos patrones indican que son para la “Base Sub ESPALDA” y muestran opciones de alineación en el software de diseño.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>15.</strong> En la ventana emergente seleccione <strong>alinear al último punto</strong>. En este caso debe seleccionar <strong>alinear todos los puntos.</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen15.svg", alt='La imagen describe una acción que es: en la ventana emergente, seleccione “Alinear al último punto”. En esta ocasión, debe seleccionar “Alinear todos los puntos”.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>16.</strong> En la caja de herramientas escoja <strong>movimiento paralelo</strong>, seleccione desde el punto de centro atrás hacia costado, en el sentido de las manecillas del reloj; extender hacia abajo, asignando la medida de altura de cadera, teniendo en cuenta el eje X y el eje Y.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen16.svg", alt='En la imagen se describe como en la caja de herramientas, se selecciona la opción de movimiento paralelo. Luego, marque desde el punto central trasero hacia el costado, en sentido de las manecillas del reloj. Extienda hacia abajo, asignando la medida de la altura de la cadera, considerando los ejes X e Y.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>17.</strong> En este punto ya se tiene la blusa con el largo deseado, es necesario darle la forma de cada uno de los puntos del cuerpo. Para marcar el punto de cintura tome la herramienta <strong>puntos sobre</strong> y fije un punto con el atributo de <strong>escalado</strong>, por costado con la medida de altura de cadera. Para verificar las medidas oprimir la <strong>tecla F8.</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen17.svg", alt='La imagen muestra tres piezas de un patrón de costura, cada una correspondiente a una parte del cuerpo, probablemente para una prenda superior (como una blusa o chaqueta). Cada pieza tiene medidas específicas y puntos de referencia marcados, que ayudan en la confección y ensamblaje de la prenda.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>18.</strong> Verificar el recorrido de la línea de cadera con la herramienta <strong>medir</strong>. Aumentar la medida de 1/4 del contorno de cadera más pinza según el manual; en editar segmento de la ventana de <strong>medidas</strong>, asignar medida, y posteriormente dé clic en el botón <strong>aceptar.</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen18.svg", alt='La imagen muestra dos ventanas de un software de diseño de patrones, donde se ajustan las dimensiones y divisiones de segmentos del patrón, y una pieza de patrón de costura con medidas y puntos de referencia para confección de una prenda.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>19.</strong> Para marcar la pinza en segmento interno se debe marcar una línea guía en cintura. Con la herramienta <strong>punto sobre</strong>, fije en el segmento de centro frente, un punto, en el punto de talle o cintura. En el grupo de herramientas <strong>insertar</strong> identifique la herramienta <strong>botón</strong>, haga clic en <strong>crear botón.</strong> Para marcar el punto de pinza se debe tener en cuenta el primer y segundo lado de pinza, el análisis se hace tomando como referencia el ancho de pinza y la separación del busto.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen19.svg", alt='La imagen explica la acción para marcar la pinza en el segmento interno, trace una línea guía en la cintura. Utilice la herramienta de punto sobre para fijar un punto en el segmento del centro frente, en el talle o cintura. En el grupo de herramientas de insertar, seleccione la herramienta botón y cree un botón. Para marcar el punto de pinza, considere los lados de la pinza y analice el ancho de la pinza y la separación del busto.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>20.</strong> Crear cada uno de los puntos de pinza con la herramienta <strong>botón</strong>, con el fin de poder marcar el ancho de la pinza. Para marcar el largo de la pinza por línea de cadera utilizar la herramienta <strong>punto sobre</strong>. Se debe identificar cada uno de los vértices de pinza, teniendo en cuenta que no se puede encontrar el vértice de pinza por costado y el vértice de pinza de ajuste. Para marcar o dibujar la pinza, en la herramienta <strong>dibujar</strong>, opción <strong>borrador</strong> se puede ir marcando cada uno de los puntos o vértices señalados.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen20.svg", alt='La imagen explica la acción para marcar la pinza en el segmento interno, trace una línea guía en la cintura. Utilice la herramienta de punto sobre para fijar un punto en el segmento del centro frente, en el talle o cintura. En el grupo de herramientas de insertar, seleccione la herramienta botón y cree un botón. Para marcar el punto de pinza, considere los lados de la pinza y analice el ancho de la pinza y la separación del busto.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>21.</strong> Ya en este punto se identifica parte delantera y parte posterior.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen21.svg", alt='La imagen muestra dos piezas de un patrón de costura para la parte delantera y trasera de una prenda. Ambas piezas tienen pinzas marcadas para ajustar el contorno del busto y la cintura, con puntos de referencia y líneas guía que facilitan el ensamblaje y la confección.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>22.</strong> Para trazar la pechera o el cruce de botonadura se deben eliminar todos los puntos del centro frente. En el grupo de herramientas <strong>editar</strong> escoja la herramienta <strong>extender en paralelo</strong> y seleccione la <strong>línea centro frente</strong> en el sentido de las manecillas del reloj; en la ventana emergente asigne la medida del cruce de botonadura.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen22.svg", alt='La imagen expone la forma como Para trazar la pechera o el cruce de botonadura, elimine todos los puntos del centro frente. En el grupo de herramientas de edición, seleccione la herramienta de extensión en paralelo y marque la línea del centro frente en el sentido de las manecillas del reloj. En la ventana emergente, asigne la medida del cruce de botonadura.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>23.</strong> Al realizar la extensión utilice la herramienta crear un <strong>contorno interno paralelo al tramo seleccionado</strong>, esta permite crear o extender el cruce de botonadura como se hace de manera manual sobre papel.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta10/imagen23.svg", alt='La imagen muestra la interfaz de un software de diseño de patrones, específicamente en la funcionalidad de crear una línea paralela a un segmento. En la primera ventana emergente, se configuran la distancia y los puntos de extensión de la nueva línea paralela. En la segunda ventana emergente, se pregunta si también se debe crear un punto sobre el contorno extendido. A la derecha, se visualiza una pieza de patrón con el centro frente y las pinzas marcadas.')

    <br> <br>
    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-8.mb-sm-0
                  p.mb-0 Para una mejor comprensión del tema revisar el siguiente video de “blusa hasta cadera delantero”. 
                .col-sm-12.col-lg-4
                  a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm
      .col-sm-12.col-lg-6
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-8.mb-sm-0
                  p.mb-0 Para una mejor comprensión del tema revisar el siguiente video de “blusa hasta cadera posterior”. 
                .col-sm-12.col-lg-4
                  a.boton.color-boton(href="https://www.youtube.com/embed/Ds5CtwVbaag" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm

    Separador    
    .row.mb-4
      .titulo-segundo.color-primario
        h2 1.7  Corte princesa y francés - <em>Optitex</em>

    .tarjeta.tarjeta--gris.p-4.borde-redondo(style="background-color: #F8F5FF")
      LineaTiempoC.color-acento-botones(text-small)
        .row(titulo="1")
          .col-md-4.mb-4.mb-md-0
            p.ps-5.mb-4 <strong>1.</strong> Antes de iniciar el corte princesa y el corte francés se hará el corte de almilla, trasladando la parte delantera hacia la parte posterior. A partir del punto cuello hombro y hombro sisa marque el recorrido de la almilla; una los dos puntos con la herramienta <strong>dibujar</strong>. Seleccionar la herramienta <strong>cortar</strong>, opción <strong>cortar a pieza a lo largo de un interno.</strong>
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen1.svg", alt='La imagen muestra tres capturas de pantalla de un software de diseño de patrones de costura. A la izquierda, se ve un menú desplegable con la opción “Añadir y girar pinza” seleccionada. En el centro y a la derecha, se muestran patrones delanteros de una prenda, etiquetados como “Base SUPERIOR FRENTE”, con pinzas añadidas y ajustadas, representadas por líneas de construcción y puntos de referencia en el área del busto.')
        .row(titulo="2")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>2.</strong> Dé clic y verifique que aparece un hilo de tela independiente sobre la pieza que se quiere cortar. De igual manera, se habilita la ventana emergente de costuras, si se desea se puede asignar el margen de costura o en este caso como se viene trabajando, no se asigna margen de costura.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen2.svg", alt='La imagen muestra una ventana de configuración del software de diseño de patrones, titulada “Símbolos de Costura”. Aquí se pueden definir los tipos de líneas de costura, el final de las costuras y las cintas de sesgo. A la derecha, se visualiza una pieza de patrón con ajustes en las pinzas y otros detalles. La ventana de configuración permite personalizar los símbolos y las líneas que se utilizarán en el diseño del patrón para una mayor precisión en la confección.')
        .row(titulo="3")
          .col-md-4.mb-4.mb-md-0
            p.ps-5.mb-4 <strong>3.</strong> Verificar que la pieza se puede trasladar o mover.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen3.svg", alt='La imagen ilustra la forma como se puede  verificar que la pieza se puede trasladar o mover, para facilitar el proceso')
        .row(titulo="4")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>4.</strong> Para poder unir la pieza al posterior se debe validar la medida de los escotes, diríjase al grupo de herramientas <strong>insertar</strong>, opción <strong>voltear pieza</strong> y seleccione <strong>volteo horizontal.</strong>
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen4.svg", alt='La imagen expone  la forma como puede  unir la pieza al posterior, primero valide la medida de los escotes. Luego, vaya al grupo de herramientas “Insertar”, seleccione la opción “Voltear pieza” y elija “Volteo horizontal”.')
        .row(titulo="5")
          .col-md-4.mb-4.mb-md-0
            p.ps-5.mb-4 <strong>5.</strong> Para que coincida hombro con hombro diríjase al grupo de herramientas <strong>insertar</strong>, opción <strong>voltear pieza</strong> y seleccione <strong>volteo vertical.</strong>
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen5.svg", alt='La imagen expone la forma para alinear los hombros, vaya al grupo de herramientas “Insertar”, seleccione la opción “Voltear pieza” y elija “Volteo vertical”.')
        .row(titulo="6")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>6.</strong> Para unir las piezas diríjase a la <strong>herramienta piezas</strong>, opción <strong>recorrido</strong>. Haga clic en la pieza que se cortó el delantero y la parte posterior, y haga clic sobre la línea de hombro para unir la pieza.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen6.svg", alt='La imagen expone la forma como debe unir las piezas, vaya a la herramienta “Piezas” y seleccione la opción “Recorrido”. Haga clic en la pieza cortada del delantero y en la parte posterior, luego haga clic en la línea del hombro para unirlas.')
        .row(titulo="7")
          .col-md-4.mb-4.mb-md-0
            p.ps-5.mb-4 <strong>7.</strong> Para fusionar las <strong>piezas</strong>, en el grupo de herramientas piezas seleccione <strong>unir piezas o unir partes.</strong>
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen7.svg", alt='La imagen explica como se debe  unir las piezas, dirígete a la herramienta “Unir piezas”, selecciona la opción “Recorrido”, haz clic en la pieza cortada del delantero y en la parte posterior, y luego haz clic en la línea del hombro. En la ventana emergente “Unir piezas”, configura las opciones necesarias y haz clic en “OK”.')
        .row(titulo="8")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>8.</strong> Luego de fusionadas las piezas si no se identifican curvas suaves en cada unión suavice los puntos; tome la herramienta <strong>selección</strong>, haga clic sobre el punto y asigne atributo <strong>curva</strong>. Con la herramienta <strong>mover punto</strong> deslice el mouse hasta suavizar la curva. De igual manera, suavice el punto de hombro escote.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen8.svg", alt='La imagen describe como una vez fusionadas las piezas, si no se observan curvas suaves en cada unión, suavice los puntos. Utilice la herramienta de selección, haga clic sobre el punto y asigne el atributo de curva. Luego, con la herramienta de mover puntos, deslice el mouse hasta suavizar la curva. Repita el proceso para suavizar el punto en el hombro y el escote.')
        .row(titulo="9")
          .col-md-4.mb-4.mb-md-0
            p.ps-5.mb-4 <strong>9.</strong> Ya en este punto se identifica la corrección de las uniones en cada uno de los puntos de hombro. Si el hilo de tela que se identifica en la pieza no corresponde al hilo de tela del trazo o corte proceda a modificarlo con la opción <strong>mover interno</strong> (tecla rápida I). Arrastre o mueva el hilo de tela de la pieza delantera, haciendo intersección sobre el hilo de la tela posterior, haga clic sobre este; se observa que el hilo de tela se modifica quedando paralelo al centro atrás.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen9.svg", alt='Para suavizar las uniones, use la herramienta de selección para hacer clic en los puntos de las curvas y asigne el atributo de curva. Luego, con la herramienta de mover puntos, deslice el mouse hasta suavizar las curvas en las uniones y el punto del hombro y escote.')
        .row(titulo="10")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>10.</strong> Lo ideal es mover los hilos de tela en tal punto que no interfieran con los cortes que se van a trabajar. Para realizar los cortes, en el grupo de herramientas <strong>pieza</strong> seleccione <strong>cortar</strong>, opción <strong>cortar pieza.</strong> Haga clic sobre el punto de hombro, y en la ventana emergente, en la opción <strong>proporcional</strong>, asignar 0.5 para que quede en la mitad.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen10.svg", alt='Para suavizar las uniones, use la herramienta de selección para hacer clic en los puntos de las curvas y asigne el atributo de curva. Luego, con la herramienta de mover puntos, deslice el mouse hasta suavizar las curvas en las uniones, incluyendo el punto del hombro y escote.')
        .row(titulo="11")
          .col-md-4.mb-4.mb-md-0
            p.ps-5.mb-4 <strong>11.</strong> Vaya al vértice de pinza, posteriormente al primer lado de pinza por cintura, y finalice en el primer lado de pinza por largo total. En la ventana emergente de <strong>costura</strong> haga clic en el botón <strong>cancelar</strong>, identifique el traslado o movimiento del corte.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen11.svg", alt='Para suavizar las uniones, use la herramienta de selección para hacer clic en los puntos de las curvas y asigne el atributo de curva. Luego, con la herramienta de mover puntos, deslice el mouse hasta suavizar las curvas en las uniones, incluyendo el punto del hombro y escote.')
        .row(titulo="12")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>12.</strong> Repita el ejercicio hasta generar el corte de costado. Identifique cada una de las piezas, centro, frente, costado y pinza.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen12.svg", alt='La imagen describe como suavizar las uniones, para ello utilice la herramienta de selección para hacer clic en los puntos de las curvas y asigne el atributo de curva. Luego, con la herramienta de mover puntos, deslice el mouse hasta suavizar las curvas en las uniones, incluyendo los puntos en los hombros y escotes.')
        .row(titulo="13")
          .col-md-4.mb-4.mb-md-0
            p.ps-5.mb-4 <strong>13.</strong> En la pieza de costado identifique la pinza de recuperación de talle, para cerrar la pinza, en el menú herramientas, opción <strong>escalado</strong>, seleccione <strong>cerrar pinza</strong>. En la ventana emergente <strong>fijar pinza</strong> seleccione <strong>intermedia entre primer y segundo segmento de pinza.</strong>
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen13.svg", alt='La imagen describe la forma para fijar las piezas, vaya a la herramienta “Piezas”, seleccione “Copiar pieza” y configure las opciones necesarias en la ventana emergente. Asegúrese de elegir la acción adecuada y haga clic en “OK” para aplicar los cambios.')
        .row(titulo="14")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>14.</strong> Suavice los vértices de pinza en cada uno de los cortes.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen14.svg", alt='La imagen muestra dos patrones de costura para una prenda de vestir, probablemente una blusa o una camisa. Cada patrón está coloreado en azul claro y tiene líneas y puntos que indican las líneas de corte y costura. La pieza de la izquierda parece ser la parte delantera del patrón, y la pieza de la derecha, la parte trasera. Ambos patrones tienen flechas y textos que posiblemente indican instrucciones de ensamblaje o alineación')
        .row(titulo="15")
          .col-md-4.mb-4.mb-md-0
            p.ps-5.mb-4 <strong>15.</strong> Repita los mismos pasos en la parte posterior para generar el corte princesa en la espalda.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen15.svg", alt='La imagen muestra cuatro patrones de costura para una prenda, con etiquetas y flechas que indican instrucciones de ensamblaje. La cuarta pieza está coloreada en azul claro.')
        .row(titulo="16")
          .col-md-4.mb-4.mb-md-0
            p.ps-5 <strong>16.</strong> Para generar el corte francés en cualquiera de las dos piezas repita los pasos anteriores, partiendo desde sisa, que es donde sale el corte francés.
          .col-md-8
            img.p-2(src="@/assets/curso/temas/tema1/tarjeta11/imagen16.svg", alt='La imagen muestra dos patrones de costura, uno de los cuales está coloreado en azul claro. Las piezas tienen etiquetas y flechas que indican instrucciones de ensamblaje.')

    <br> <br>
    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-8.mb-sm-0
                  p.mb-0 Para una mejor comprensión del tema revisar el siguiente video de “corte princesa y francés”. 
                .col-sm-12.col-lg-4
                  a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm

    Separador    
    .row.mb-4
      .titulo-segundo.color-primario
        h2 1.8  Modelos de faldas - <em>Optitex</em>

    .tarjeta.tarjeta--azul.p-4.mb-4.borde-redondo(style="background-color: #F8F5FF")
      SlyderA(tipo="b")
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>1.</strong> Para el trazo de tres modelos de falda: falda media campana (página 36), falda con vuelo (página 37) y falda sirena revise en el <strong>manual de patronaje SENA (página 34).</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen1.svg", alt='La imagen muestra una captura de pantalla de un software de diseño de patrones de costura. En la parte superior hay un menú desplegable con opciones relacionadas con pliegues y pinzas. Debajo del menú, se muestra un patrón de costura coloreado en azul claro, con una flecha y etiquetas que indican instrucciones de ensamblaje.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>2.</strong> Se trabajará la falda de dos pinzas para generar el vuelo hacia el ruedo, cree el primer traslado, tome la herramienta <strong>pinza</strong>, opción <strong>añadir y girar pinza.</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen2.svg", alt='La imagen muestra tres patrones de costura, todos coloreados en azul claro y etiquetados con instrucciones y flechas para el ensamblaje. Además, hay una ventana emergente de “Atributos de Punto” que parece ser parte del software de diseño de patrones, mostrando opciones para ajustar los detalles de las costuras y las pinzas.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>3.</strong> Acérquese con el puntero al vértice de pinza, una vez cambie de color dé clic para seleccionarla y <strong>arrastre</strong> hasta el ruedo, en el recuadro <strong>atributos de punto</strong> proporcione la ubicación deseada del punto al cual se requiera trasladar la pinza.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen3.svg", alt='La imagen muestra tres patrones de costura, todos coloreados en azul claro y con etiquetas y flechas que indican instrucciones de ensamblaje. El primer patrón tiene líneas de pinzas en la parte superior. El segundo patrón incluye una línea verde adicional que podría representar una modificación o ajuste. El tercer patrón muestra una línea discontinua y una línea verde que indica un posible cambio en el diseño o la posición de alguna parte del patrón.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>4.</strong> Lleve el puntero a cualquier parte del costado de la falda, haga clic, gire, haga clic y traslade la pinza.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen4.svg", alt='La imagen muestra cinco patrones de costura, todos coloreados en azul claro y con etiquetas y flechas que indican instrucciones de ensamblaje. Algunos patrones tienen líneas discontinuas y verdes que indican modificaciones o ajustes en el diseño. En la parte superior central, hay una ventana emergente de “Atributos de Punto” que forma parte del software de diseño, mostrando opciones para ajustar los detalles de las costuras y las pinzas.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>5.</strong> Se realiza el mismo procedimiento trasladando la otra pinza, una vez cambie de color el vértice de pinza, haga clic para seleccionar y arrastre hasta el ruedo dando clic sobre este, en el recuadro <strong>atributos de punto</strong> indique la <strong>ubicación deseada</strong>, haga clic en cualquier parte del costado, gire, haga clic y traslade pinza.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen5.svg", alt='La imagen muestra cuatro patrones de costura, todos coloreados en azul claro, con etiquetas y flechas que indican instrucciones de ensamblaje. Algunos patrones tienen líneas discontinuas, probablemente para indicar ajustes o pliegues. A la izquierda de la imagen, hay un menú desplegable del software de diseño con varias opciones de herramientas para trabajar con los patrones.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>6.</strong> Haga clic derecho en la herramienta <strong>selección</strong>, elija la pinza a eliminar y suprima cada una de las líneas para limpiar la pieza.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen6.svg", alt='La imagen muestra dos patrones de costura, ambos coloreados en azul claro y con líneas y puntos que indican detalles de ensamblaje. El patrón de la izquierda tiene una flecha y una línea que podría representar una dirección del grano o una pinza. El patrón de la derecha parece ser una vista ampliada de una sección de un patrón, mostrando más detalles en los puntos de ajuste o costura.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>7.</strong> Para suavizar los puntos que se generaron por los traslados de pinza seleccione los puntos en el sentido de las manecillas del reloj, haga clic en el último punto.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen7.svg", alt='La imagen muestra tres paneles de propiedades del software de diseño de patrones, todos titulados “Propiedades”. Cada panel tiene varias opciones ajustables como “Escalado”, “Curva”, “Conectado”, “Nombre”, “Ángulo”, “Costura” y “Punto alternativo de partida”. Las casillas de verificación permiten al usuario seleccionar o deseleccionar estas opciones para ajustar las características del patrón.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>8.</strong> En la pestaña propiedades se identifica que los puntos tienen atributo de <strong>escalado</strong>, desmárquelo y señale de <strong>curva.</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen8.svg", alt='La imagen muestra cuatro patrones de costura, todos coloreados en azul claro y con líneas y puntos que indican detalles de ensamblaje. Tres de los patrones parecen ser secciones ampliadas, mostrando más detalles en los puntos de ajuste o costura. Uno de los patrones (izquierda) tiene una línea que podría representar una dirección del grano o una pinza. Los otros patrones muestran curvas y puntos de referencia para el ensamblaje.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>9.</strong> Haga clic en los puntos que no se requieren, y luego suprimir.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen9.svg", alt='La imagen muestra dos patrones de costura coloreados en azul claro. El patrón de la izquierda tiene una flecha y líneas que indican instrucciones de ensamblaje, probablemente para la dirección del grano o una pinza. El patrón de la derecha parece ser una sección más grande, también con una flecha similar. Ambas piezas tienen líneas punteadas en la parte inferior que podrían indicar un borde o una línea de corte adicional.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>10.</strong> Con ayuda de una línea guía ubique el ruedo de la falda centro frente y verifique que la curva no sobrepase la línea escuadrada.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen10.svg", alt='La imagen muestra varios patrones de costura, todos coloreados en azul claro y con líneas y puntos que indican detalles de ensamblaje. Hay un panel de “Propiedades” en el centro que permite ajustar características como “Escalado”, “Curva” y “Conectado”. Los patrones incluyen flechas y líneas que indican la dirección del grano o las pinzas, y algunos tienen líneas punteadas que podrían representar bordes o líneas de corte adicionales.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>11.</strong> Haga clic en los puntos de la cintura en sentido de las manecillas del reloj, en la pestaña <strong>propiedades</strong> quite el atributo de <strong>escalado</strong> y asigne el atributo de <strong>curva</strong>, suprima uno de los dos puntos y verifique que la línea guía de la curva no sobrepase la línea escuadrada.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen11.svg", alt='La imagen muestra varios patrones de costura, algunos coloreados en azul claro y otros sin color, con etiquetas y flechas que indican instrucciones de ensamblaje. En la parte superior hay una ventana del software titulada “Ventana piezas” que muestra una vista de las diferentes piezas de una falda. Los patrones incluyen líneas y flechas que indican la dirección del grano y posibles pinzas o pliegues, con líneas punteadas que podrían representar bordes o líneas de corte adicionales.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>12.</strong> Seleccione en la ventana piezas otra falda; para ajustar el hilo de tela seleccione la herramienta <strong>copiar o mover interno</strong>, arrastre al otro hilo de tela y haga clic.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen12.svg", alt='La imagen muestra una captura de pantalla de un software de diseño de patrones. A la izquierda, hay un menú desplegable con varias opciones relacionadas con la manipulación de líneas y piezas. En la parte superior, una ventana titulada “Ventana piezas” muestra diferentes piezas de una falda. Abajo, se ve parte de un patrón de costura coloreado en azul claro con líneas y flechas que indican instrucciones de ensamblaje. Las opciones del menú permiten al usuario trabajar con las líneas y ajustar detalles del patrón.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>13.</strong> Haga clic derecho sobre la falda previamente modificada, escoja la opción <strong>limpiar pieza</strong>, posteriormente seleccione <strong>actualizar original</strong>, suprima cada una de las líneas para limpiar la mesa de trabajo. Marque línea guía.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen13.svg", alt='La imagen muestra dos patrones de costura coloreados en azul claro, con flechas y líneas que indican instrucciones de ensamblaje. Entre los dos patrones, hay una ventana emergente titulada “Atributos de Punto”. Esta ventana permite ajustar diversos parámetros del punto, como el tipo de punto (curva o escalado), la posición (X, Y), distancia, ángulo y los puntos previos y siguientes. La ventana también incluye opciones para mover el punto sobre el contorno y definir si es proporcional o absoluto.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>14.</strong> Tome la herramienta <strong>construir pieza</strong>, haga clic sobre la pieza a seleccionar, haga clic para separar la pieza que se desea ampliar o modificar.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen14.svg", alt='La imagen muestra tres patrones de costura. El primer patrón a la izquierda está dividido en dos colores: la parte superior en azul claro y la parte inferior en verde, con flechas y líneas que indican instrucciones de ensamblaje. En la parte superior izquierda de la imagen, hay un menú desplegable con opciones como “Definir pieza”, “Definir Tamaño”, “Definir piezas”, “Construir zonas piezas”, y “Definir zonas piezas”. Los otros dos patrones también están coloreados en azul claro, con líneas y flechas similares que indican detalles del ensamblaje.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>15.</strong> Seleccione en el sentido de las manecillas del reloj dónde se va a dar el vuelo de la pieza. Seleccione en el grupo de herramientas <strong>aflojar</strong>, opción <strong>abrir múltiples flojos</strong> e indique el número de flojos que se quiere trabajar, los flojos corresponden al número de cortes para dar amplitud.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen15.svg", alt='La imagen muestra una captura de pantalla de un software de diseño de patrones. En la parte superior izquierda, hay un menú desplegable con opciones relacionadas con “Ajustar”, incluyendo “Insert Ajuste”, “Abrir Múltiples Ajustes” y “Cerrar Ajuste”. En la parte inferior derecha, hay una ventana emergente titulada “Abrir Pliegues múltiples” que permite al usuario configurar el número de pliegues, el ancho, la posición de los primeros y últimos puntos, y el ángulo de los pliegues.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>16.</strong> En la ventana emergente, en la sección <strong>anchos</strong>, defina el rango que se quiere trabajar, <strong>desde el inicio hasta el final</strong> de las amplitudes.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen16.svg", alt='La imagen describe  la ventana emergente, en la sección de anchos, donde se define el rango que se desea trabajar, desde el inicio hasta el final de las amplitudes. ')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>17.</strong> Para suavizar la curva tome los puntos en el sentido de las manecillas del reloj, quite el atributo de <strong>escalado</strong> y asigne atributo de <strong>curva.</strong>
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen17.svg", alt='La imagen expone  la forma como se puede  suavizar la curva, en donde debe seleccionar los puntos en el sentido de las manecillas del reloj, eliminar el atributo de escalado y asignar el atributo de curva.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>18.</strong> Repetir el ejercicio para generar más vuelos, las alturas y anchos se pueden modificar.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen18.svg", alt='La imagen muestra un software de diseño de patrones de falda. En el centro, hay dos patrones: uno rectangular a la izquierda y dos patrones curvados a la derecha, con el último patrón a la derecha resaltado en azul. En la parte superior, hay íconos de diferentes tipos de patrones de falda.')
        .row.justify-content-center.my-lg-4
          .col-md-4.mb-4.mb-md-0
            p.p-5 <strong>19.</strong> Para dividir la parte superior de la falda y hacer que coincida con el corte o con el vuelo marque la línea guía a la altura de la separación.
          .col-md-8
            img.p-3(src="@/assets/curso/temas/tema1/tarjeta12/imagen18.svg", alt='La imagen muestra una interfaz de software de diseño de patrones de costura. En ella, se presentan tres patrones de falda, cada uno en una etapa diferente de edición, con áreas sombreadas en verde y azul para resaltar secciones específicas. En la esquina inferior izquierda, hay un menú desplegable con varias opciones, como “Delinear tramos”, “Delinear pieza” y “Construir zonas piezas”, entre otras.')

    <br> <br>
    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6
        .tarjeta.color-primario.borde-redondo.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-8.mb-sm-0
                  p.mb-0 Para una mejor comprensión del tema le invito a revisar el video “modelos de faldas en Optitex”.
                .col-sm-12.col-lg-4
                  a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-video.text-sistm

    Separador
    .row.mb-4
      .titulo-segundo.color-primario
        h2 2.2  Introducción a trazo y corte




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
