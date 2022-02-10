<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 La composición digital 
    .row.mb-5.justify-content-center
      .col-lg-8
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/1.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 La composición digital o composición de efectos visuales, es el proceso con el que se manipulan y combinan distintos elementos mediante técnicas digitales, para crear una sola imagen que funcione como una pieza homogénea y conforme a la visión artística del director.
    p.mb-5 Algunas generalidades importantes para tener en cuenta, sobre la composición digital, son:
    SlyderB.mb-5(:datos="datosSlyder")
    .contenedor_amarillo.bg--4-claro.p-5.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-6.mb-3
          .titulo-segundo.color-primario
            h3 ¿Qué es la Composición Digital para VFX? 
          p.mb-3 Amplíe el concepto y utilidad de la composición digital, visualizando el vídeo que aquí se propone. Tome nota de los aspectos más relevantes.
        .col-lg-4
          a(href="https://www.youtube.com/watch?v=o-Xjedov3y8&ab_channel=U-tad" target="_blank")
            img(src="@/assets/curso/7.jpg")
    #t_1_1.titulo-segundo.color-secundario
      h2 1.1 Tipos de composición 
    .contenedor-fondo.p-5
      .row.justify-content-center
        .col-lg-10: img(src='@/assets/curso/8.png').mb-5.mt-5
        p.text-center Gerald Millerson, autor de varios libros y publicaciones referentes a la producción y realización en televisión, distingue tres tipos de composición: 
    .row.mb-5
      .col-lg-4.mb-3
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/curso/9.jpg' alt='AvatarTop' style='width:400px')
          .tarjetas-up_card.bg--2-claro.p-4
            .title.d-flex.align-items-center.mb-4
              span.c--4
                i.fas.fa-caret-up.fa-2x.color-primario.me-3
                i.fas.fa-caret-down.fa-2x.color-primario.me-3
              h4.mb-0 Composición por diseño
            p Se da cuando la composición se crea desde cero, añadiendo y organizando los objetos y elementos de la escena donde y como se quiera, lo que favorece la creatividad, dando libertad a la composición.
      .col-lg-4.mb-3
        .tarjetas-up
          img(src='@/assets/curso/10.jpg' alt='AvatarTop' style='width:400px')
          .tarjetas-up_card.bg--2-claro.p-4
            .title.d-flex.align-items-center.mb-4
              span.c--4
                i.fas.fa-caret-up.fa-2x.color-primario.me-3
                i.fas.fa-caret-down.fa-2x.color-primario.me-3
              h4.mb-0 Composición por disposición
            p En esta tipología los elementos se disponen en el plano buscando un efecto intencionado como por ejemplo equilibrar el peso visual de la imagen o superponer primer término y fondo para generar dramatismo, diversión o persuasión.
      .col-lg-4.mb-3
        .tarjetas-up
          img(src='@/assets/curso/11.jpg' alt='AvatarTop' style='width:400px')
          .tarjetas-up_card.bg--2-claro.p-4
            .title.d-flex.align-items-center.mb-4
              span.c--4
                i.fas.fa-caret-up.fa-2x.color-primario.me-3
                i.fas.fa-caret-down.fa-2x.color-primario.me-3
              h4.mb-0 Composición por selección
            p Ocurre cuando la escena viene previamente configurada y sólo encajan las opciones derivadas de la colocación de la cámara para construir un efecto comunicativo determinado.
    .row.mb-5.justify-content-center
      .col-lg-8
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/12.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 En cuanto a la posición de la cámara, esta determina el <b>“punto de vista”</b> de la toma y la perspectiva, razón por la que es uno de los elementos más valiosos en toda composición. El resultado de una composición u otra depende del punto desde donde se enfoque.
    p.mb-5 Utilizar ángulos y enfoques distintos producen efectos llamativos y originales porque la mayoría de las tomas se realizan a nivel del ojo. <b>Por ejemplo</b>, desde un punto de vista bajo, los objetos cercanos se agrandan; los horizontes más bajos desplazan el centro de atención hacia el cielo; los horizontes más altos, desplazan el horizonte hacia la tierra (Armenteros, 2011).
      br
      br
      | Otros elementos que determinan el diseño final y que tienen relación con la colocación de la cámara son:
    .row.mb-5.justify-content-center
      .col-lg-9
        LineaTiempoD.color-primario
          div.row(numero="1" titulo="Distancia focal").p-4.align-items-center
            .col-lg-8
              p La distancia focal, según el objetivo y el encuadre elegido, ayuda a identificar profundidad de campo a través del gran angular y facilita la incorporación de muchos elementos. 
            .col-lg-4
              .rounded-2
                img(src='@/assets/curso/13.jpg' style='border-radius: 25px')
          div.row(numero="2" titulo="Encuadre").p-4.align-items-center
            .col-lg-8
              p El encuadre por su parte, incluye o excluye partes de la escena, controla las formas y líneas y va dirigiendo la mirada del espectador y creando el ritmo visual. La composición se ve limitada a la selección del encuadre, por lo que el efecto de un encuadre, u otro, es definitivo.
            .col-lg-4
              .rounded-2
                img(src='@/assets/curso/14.jpg' style='border-radius: 25px')
          div.row(numero="3" titulo="Layout y composición").p-4.align-items-center
            .col-lg-8
              p <i>Loyout</i> y composición como un storytelling; una composición coherente ayuda a seguir la trama y a entender con claridad lo que sucede en pantalla ya que conduce la mirada hacia un inequívoco “centro de interés”, por más diversidad de elementos que haya en escena.
            .col-lg-4
              .rounded-2
                img(src='@/assets/curso/15.jpg' style='border-radius: 25px')
          div.row(numero="4" titulo="Estilo narrativo").p-4.align-items-center
            .col-lg-8
              p Crear una composición, es tomar una decisión sobre el estilo narrativo del proyecto, por lo que los otros factores que determinan el encuadre: valor de plano, movimiento de cámara, iluminación, temperatura de color, personajes y los todos los elementos necesarios para la escena, deben responder a ese estilo.
            .col-lg-4
              .rounded-2
                img(src='@/assets/curso/16.jpg' style='border-radius: 25px')
    #t_1_2.titulo-segundo.color-secundario
      h2 1.2 Reglas de la composición digital
    .row.mb-5.justify-content-center
      .col-lg-8
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/17.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Existe un conjunto de principios provenientes de disciplinas artísticas, como el dibujo, la pintura, la fotografía y el diseño, que sirven de guía en el momento de diseñar un dibujo, una fotografía, una pintura, etc. 
    p.mb-5 De muchas de estas reglas se nutre la composición para las imágenes en movimiento, como las que se generan a través de la animación digital que, aunque incluyen una perspectiva técnica, pretenden ayudar a construir el mensaje a través de la creación de la narrativa visual del producto.
      br
      br
      |Aunque existen decenas de reglas, algunas de las más usadas son las siguientes:
    .bg-video.p-4.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-10
          figure
            .video
              iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    .contenedor_amarillo.bg--4-claro.p-5.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-6.mb-3
          .titulo-segundo.color-primario
            h3 Conozca más sobre la aplicación de estas reglase en cine y video y estudie algunos ejemplos, visualizando los vídeos que aquí se proponen. Explore cada uno de ellos y procure llevar registro, en su libreta personal de apuntes, de los aspectos más relevantes que encuentre:
          a(href="https://www.youtube.com/watch?v=t5MPOqnt60U" target="_blank")
            .bg--1-claro.display-block.rounded-2.p-2.c--1.d-flex.w-100.mb-2.hover
              img(src='@/assets/curso/18.svg' style='width: 25px').me-2
              p.mb-0.fw-bold.d-flex.align-items-center.justify-content-center Reglas de Composición Cinematográficas.
          a(href="https://www.youtube.com/watch?v=I7sS54EIEAg&ab_channel=LucianoAvilasobrecineyseries" target="_blank")
            .bg--1-claro.display-block.rounded-2.p-2.c--1.d-flex.w-100.mb-2.hover
              img(src='@/assets/curso/18.svg' style='width: 25px').me-2
              p.mb-0.fw-bold.d-flex.align-items-center.justify-content-center Técnicas y principios de composición fotográfica en cine y series.
          a(href="https://www.youtube.com/watch?v=I7sS54EIEAg&ab_channel=LucianoAvilasobrecineyseries" target="_blank")
            .bg--1-claro.display-block.rounded-2.p-2.c--1.d-flex.w-100.mb-2.hover
              img(src='@/assets/curso/18.svg' style='width: 25px').me-2
              p.mb-0.fw-bold.d-flex.align-items-center.justify-content-center MEJORA TUS FOTOS Y VIDEOS con este simple TRUCO (composición).
          a(href="https://www.youtube.com/watch?v=I7sS54EIEAg&ab_channel=LucianoAvilasobrecineyseries" target="_blank")
            .bg--1-claro.display-block.rounded-2.p-2.c--1.d-flex.w-100.mb-2.hover
              img(src='@/assets/curso/18.svg' style='width: 25px').me-2
              p.mb-0.fw-bold.d-flex.align-items-center.justify-content-center Mr. Robot: Encuadres que rompen las reglas de composición (Análisis).
          a(href="https://www.youtube.com/watch?v=zkxLh4op_oo&t=255s" target="_blank")
            .bg--1-claro.display-block.rounded-2.p-2.c--1.d-flex.w-100.mb-2.hover
              img(src='@/assets/curso/18.svg' style='width: 25px').me-2
              p.mb-0.fw-bold.d-flex.align-items-center.justify-content-center How To Break The Rules Of Composition.
        .col-lg-4
          img(src="@/assets/curso/19.svg")
    #t_1_3.titulo-segundo.color-secundario
      h2 1.3 Técnicas de composición 
    .row.mb-5.justify-content-center
      .col-lg-8
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/20.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Los avances tecnológicos actuales permiten crear universos cada vez más fantásticos, hacer cosas imposibles con personajes inimaginables y solucionar, también, secuencias difíciles del cine y la televisión, a través de técnicas y herramientas antes impensables. Estas técnicas se circunscriben en el área de la composición digital donde la creatividad, podría decirse, ya no tiene límites.
    p.mb-5 Sabiendo esto, a continuación, se explican algunas de las técnicas de composición más utilizadas en efectos visuales (VFX):
    .row.mb-3
      .col-lg-6.mb-3
        .tarjeta.bg--1-claro.p-4.pointer.d-flex.align-items-center.h-100.position-relative(@click="modal1 = true" @mouseover="mostrarIndicador = false")
          .indicador--click(v-if="mostrarIndicador")
          img(src="@/assets/curso/21.svg" style="width:155px").me-2
          .textos
            h5 Planar Tracking (2.5D) 
            p.mb-0 Se utiliza para separar elementos y personajes del fondo original, cuando no se ha usado chromas.
        ModalA(:abrir-modal.sync="modal1")
          .row.p-5
            .col-lg-8: img(src='@/assets/curso/31.jpg' style='border-radius:25px')
            .col-lg-4
              h5 Planar Tracking (2.5D) 
              p Esta información permite determinar el movimiento de un objeto fijo en una escena, de un elemento que se mueve, o revelar la trayectoria de la propia cámara respecto de ese escenario.
                br
                br
                |De esta forma se puede usar esa información para estabilizar un plano, insertar elementos CGI o cambiar el escenario por un matte painting. Se puede realizar el seguimiento de un punto (Traslación)  o de 2 o más puntos (Traslación, rotación y escala).
      .col-lg-6.mb-3
        .tarjeta.bg--1-claro.p-4.pointer.d-flex.align-items-center.h-100(@click="modal2 = true")
          img(src="@/assets/curso/22.svg" style="width:155px").me-2
          .textos
            h5 Rotoscopia
            p.mb-0 Consiste en marcar objetos mediante el reconocimiento de uno o varios píxeles y hacerles seguimiento para calcular su trayectoria durante un plano, con el objetivo de que otros elementos digitales sigan dicho movimiento. 
        ModalA(:abrir-modal.sync="modal2")
          .row.p-5
            .col-lg-8: img(src='@/assets/curso/32.jpg' style='border-radius:25px')
            .col-lg-4
              h5 Rotoscopia
              p También permite eliminar elementos cualquier elemento no deseado en el plano  (cuerdas, micrófonos, y cualquier objeto que no deben aparecer en el metraje). La <b><i>Rotoscopia</i></b> crea máscaras recortadas de forma manual, fotograma a fotograma, haciendo un trazo sobre algún objeto de la capa superior para usarla como una máscara encima de otra.
    .row.mb-3
      .col-lg-6.mb-3
        .tarjeta.bg--1-claro.p-4.pointer.d-flex.align-items-center.h-100(@click="modal3 = true")
          img(src="@/assets/curso/23.svg" style="width:155px").me-2
          .textos
            h5 Chroma key
            p.mb-0  También conocido como Keying, permite que, mediante manipulación del color, se puedan superponer personajes en escenarios diferentes, ya sea un fondo real o creado digitalmente. 
        ModalA(:abrir-modal.sync="modal3")
          .row.p-5
            .col-lg-8: img(src='@/assets/curso/33.jpg' style='border-radius:25px')
            .col-lg-4
              h5.fst-italic Chroma key
              p Consiste en filmar un personaje u objeto frente a un fondo de color especifico, por lo general verde o azul, para luego aislarlo y recortarlo perfectamente, extraerlo y superponerlo sobre un fondo o escenario diferente, que puede ser real o creado digitalmente.
      .col-lg-6.mb-3
        .tarjeta.bg--1-claro.p-4.pointer.d-flex.align-items-center.h-100(@click="modal4 = true")
          img(src="@/assets/curso/24.svg" style="width:155px").me-2
          .textos
            h5 Paint & Prep / Borrados & Parches
            p.mb-0 Esta técnica usa herramientas de relleno para borrar elementos que sobran en el plano. 
        ModalA(:abrir-modal.sync="modal4")
          .row.p-5
            .col-lg-8: img(src='@/assets/curso/34.jpg' style='border-radius:25px')
            .col-lg-4
              h5 Paint & Prep | Borrados & Parches
              p Se refiere al trabajo previo de limpiar y preparar el plano para el compositor. Tanto Nuke y After Effects cuentan con la función de relleno que permite el borrado automático de elementos no deseados en un video.
    .row.mb-3
      .col-lg-6.mb-3
        .tarjeta.bg--1-claro.p-4.pointer.d-flex.align-items-center.h-100(@click="modal5 = true")
          img(src="@/assets/curso/25.svg" style="width:155px").me-2
          .textos
            h5 Corrección de color
            p.mb-0  Mediante la modificación de determinados colores se corrigen problemas de exposición, parámetros de la luz, el aspecto (look), se ecualiza o unifican los niveles de diferentes planos (etalonaje), etc.
        ModalA(:abrir-modal.sync="modal5")
          .row.p-5
            .col-lg-8: img(src='@/assets/curso/35.jpg' style='border-radius:25px')
            .col-lg-4
              h5 Corrección de color
              p La corrección de color es quizá el elemento mas importante en el proceso de la composición audiovisual, porque modificando los colores, cambia la intención en una secuencia. El color, la luz, las siluetas, ayudan a transmitir las emociones; de ahí la importancia de manipular la curva emocional en una película.
                br
                br
                |En este enlace se encuentra un artículo en el que se muestran cómo marcan el estado de ánimo en unas 50 películas.
              a.anexo.mb-4.mb-lg-0(href="https://digitalsynopsis.com/design/cinema-palettes-famous-movie-colors/." target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  p <b>Enlace web.</b> https://digitalsynopsis.com/design/cinema-palettes-famous-movie-colors/. 
      .col-lg-6.mb-3
        .tarjeta.bg--1-claro.p-4.pointer.d-flex.align-items-center.h-100(@click="modal6 = true")
          img(src="@/assets/curso/26.svg" style="width:155px").me-2
          .textos
            h5 Camera projection
            p.mb-0 El tracking 3D extrae información tridimensional del desplazamiento y la rotación de la cámara en la escena, y el movimiento de un objeto en la escena. 
        ModalA(:abrir-modal.sync="modal6")
          .row.p-5
            .col-lg-8: img(src='@/assets/curso/36.jpg' style='border-radius:25px')
            .col-lg-4
              h5 <i>Camera projection</i>
              p El resultado son muchos puntos que sirven para crear imágenes 3D muy precisas, a partir de una grabación bidimensional. Esta información se reutiliza sobre el mismo plano, creando y colocando nuevos assets o personajes.
    .row.mb-3
      .col-lg-6.mb-3
        .tarjeta.bg--1-claro.p-4.pointer.d-flex.align-items-center.h-100(@click="modal7 = true")
          img(src="@/assets/curso/27.svg" style="width:155px").me-2
          .textos
            h5 Matchmoving y rotomation
            p.mb-0 Permite insertar elementos en un video previamente grabado y situarlos  en  su posición, escala, orientación y movimiento correctos, en relación con los elementos que aparecen en el plano. .  
        ModalA(:abrir-modal.sync="modal7")
          .row.p-5
            .col-lg-8: img(src='@/assets/curso/37.jpg' style='border-radius:25px')
            .col-lg-4
              h5 <i>Matchmoving y rotomation</i>
              p Esta técnica rastrea el movimiento de la cámara real a partir de lo que sucede en la grabación y obtiene información de las coordenadas de movimiento de la cámara para trasladar esa información a una cámara virtual.
      .col-lg-6.mb-3
        .tarjeta.bg--1-claro.p-4.pointer.d-flex.align-items-center.h-100(@click="modal8 = true")
          img(src="@/assets/curso/28.svg" style="width:155px").me-2
          .textos
            h5 Digital Matte Painting
            p.mb-0 Se trata de técnicas 2D y 3D que combinan habilidades de composición fotográfica, producción 3D y pintura digital, para el diseño y creación de cualquier tipo de fondo, entorno o escenario digital.
        ModalA(:abrir-modal.sync="modal8")
          .row.p-5
            .col-lg-8: img(src='@/assets/curso/38.jpg' style='border-radius:25px')
            .col-lg-4
              h5 <i>Digital Matte Painting</i>
              p El digital matte painting hace posible la construcción de mundos imaginarios que parecen realistas y que, en la vida real, serían muy costosos o imposibles de filmar.
    .row.mb-5
      .col-lg-6.mb-3
        .tarjeta.bg--1-claro.p-4.pointer.d-flex.align-items-center.h-100(@click="modal9 = true")
          img(src="@/assets/curso/29.svg" style="width:155px").me-2
          .textos
            h5 Deep Compositing
            p.mb-0  Permite que de una imagen 2D se pueda extraer información tridimensional y trabajar a diferentes profundidades
        ModalA(:abrir-modal.sync="modal9")
          .row.p-5
            .col-lg-8: img(src='@/assets/curso/39.jpg' style='border-radius:25px')
            .col-lg-4
              h5 <i>Deep Compositing</i>
              p Cada píxel visto en pantalla contiene información adicional al color, como profundidad, color de otros objetos que se encuentren detrás, etc. (Varios Píxeles de diferentes profundidades en uno solo).
      .col-lg-6.mb-3
        .tarjeta.bg--1-claro.p-4.pointer.d-flex.align-items-center.h-100(@click="modal10 = true")
          img(src="@/assets/curso/30.svg" style="width:155px").me-2
          .textos
            h5 Composición multipase
            p.mb-0 Consiste en crear una imagen a partir de varias imágenes (o canales) extraídas durante el proceso de render 3D. Cada una de ellas tiene información sobre el color, materiales, sombreado, luces, reflejos, profundidad (Z-Depth) etc.
        ModalA(:abrir-modal.sync="modal10")
          .row.p-5
            .col-lg-8: img(src='@/assets/curso/40.jpg' style='border-radius:25px')
            .col-lg-4
              h5 <i>Composición multipase</i>
              p Cuando se junta toda esta información, se obtiene el aspecto final del modelo CGI. Teniendo los canales por separado se puede manipular, si fuera necesario, cada uno de estos pases individualmente y así conseguir una integración mucho más fotorrealista o más artística. 
                br
                br
                | En el video que se propone explore breves explicaciones, con ejemplos reales, de la manera como se aplican las distintas técnicas en el <i><b>software</b></i> Nuke: 
              a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=SxDTwFLq7Fk" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  p Webinar: Técnicas de Composición Digital 
    #t_1_4.titulo-segundo.color-secundario
      h2 1.4 Software de composición 
    .row.mb-5.justify-content-center
      .col-lg-8
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/41.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Actualmente, la mayoría de los softwares que se usan en la industria audiovisual combinan, en menor o mayor medida, herramientas de todas las fases de la postproducción. Esto quiere decir que, un software especializado en edición de vídeo como Adobe Premiere, incluye opciones como el chroma o la rotoscopia que, normalmente, están disponibles en la composición digital, pero también movimiento de títulos u otros objetos que pertenecen a la animación.
    .bg-carrousel.d-flex.justify-content-center.align-items-center.mb-4(@mouseover="mostrarIndicador = false")
      .indicador--hover(v-if="mostrarIndicador")
      h2.h1.text-center.text-white Sabías que...
      .bg-carrousel_content.px-5.py-5.justify-content-center.d-flex.align-items-center
        .text-center.w-75
          p.fw-bold.mb-0 Igualmente, existen softwares enfocados en la composición digital como After Effects o Hitfilm Pro, que tienen sus propias herramientas de edición de video.
    .bg-carrousel2.d-flex.justify-content-center.align-items-center.mb-5(@mouseover="mostrarIndicador = false")
      .indicador--hover(v-if="mostrarIndicador")
      h2.h1.text-center.text-white Sabías que...
      .bg-carrousel2_content.px-5.py-5.justify-content-center.d-flex.align-items-center
        .text-center.w-75
          p.fw-bold.mb-0 Esta información es importante en el momento de elegir las herramientas con las que se finalizarán los proyectos en postproducción. Es necesario plantearse qué se va a hacer y qué tipo de editor es el más apropiado.
    p.mb-5 Para las tareas de composición digital existen softwares de composición especializados de dos tipos: software que se basa en la composición multicapa y software que se basa en la composición por nodos. 
      br
      br
      |Ambos tipos de composición pueden definirse de la siguiente manera:
    .row.mb-5.justify-content-center
      .col-lg-10
        .tarjeta.tarjeta--gris.p-4
          PasosB.color-primario
            .row(titulo="").px-4
              .col-md-5
                figure
                  img(src='@/assets/curso/44.jpg', alt='Texto que describa la imagen' style='border-radius: 30px')
              .col-md-7.mb-4.mb-md-0
                h4.fst-italic Nuke
                p Uno de los mejores softwares de composición digital para FX que se utiliza para la postproducción de cine y televisión. Es un programa  potente usado grandes producciones cinematográficas; está disponible para Microsoft Windows, Mac OS X y Linux.
            .row(titulo="").px-4
              .col-md-5
                figure
                  img(src='@/assets/curso/45.jpg', alt='Texto que describa la imagen' style='border-radius: 30px')
              .col-md-7.mb-4.mb-md-0
                h4.fst-italic Adobe After Effects 
                p Programa versátil que crea y anima; también es un software líder de efectos visuales y otras disciplinas. Perfecto para realizar VFX, Motion Graphics, Composición digital, animación 2D y 3D, programar expresiones, crear vídeos de RV, entre otras.
            .row(titulo="").px-4
              .col-md-5
                figure
                  img(src='@/assets/curso/46.jpg', alt='Texto que describa la imagen' style='border-radius: 30px')
              .col-md-7.mb-4.mb-md-0
                h4.fst-italic Blackmagic Fusion
                p Sirve para composición digital y postproducción; es el programa más avanzado para especialistas en VFX y 3D ya que permite realizar animación, realidad virtual y contenidos 3D. Su interfaz es muy intuitiva y está basada en nodos.
            .row(titulo="").px-4
              .col-md-5
                figure
                  img(src='@/assets/curso/47.jpg', alt='Texto que describa la imagen' style='border-radius: 30px')
              .col-md-7.mb-4.mb-md-0
                h4.fst-italic Natron 
                p Poderoso compositor digital de código abierto que puede manejar 2D / 2.5D. Es el programa más flexible para el sector de los efectos visuales y de la animación profesional; compatible con Open Efects;  trabaja con un sistema de nodos y cuenta con decenas de plugins libres.
            .row(titulo="").px-4
              .col-md-5
                figure
                  img(src='@/assets/curso/48.jpg', alt='Texto que describa la imagen' style='border-radius: 30px')
              .col-md-7.mb-4.mb-md-0
                h4.fst-italic OpenColorIO
                p Permite gestionar de manera efectiva el color en las películas de efectos visuales y canales por computador. Desde su nacimiento, está basado en aplicaciones comerciales como Katana, Mari, Nuke, Silhouette FX. Se ha usado en películas como SpiderMan 2 (2004), Surf’s Up (2007), Cloudy with a Chance of Meatballs (2009), Alicia en el País de las Maravillas (2010), entre otras.
            .row(titulo="").px-4
              .col-md-5
                figure
                  img(src='@/assets/curso/49.jpg', alt='Texto que describa la imagen' style='border-radius: 30px')
              .col-md-7.mb-4.mb-md-0
                h4.fst-italic DaVinciResolve
                p Edición, etalonaje, efectos visuales y postproducción de audio con calidad profesional. Es el software de composición más potente en corrección de color de la industria VFX.
            .row(titulo="").px-4
              .col-md-5
                figure
                  img(src='@/assets/curso/50.jpg', alt='Texto que describa la imagen' style='border-radius: 30px')
              .col-md-7.mb-4.mb-md-0
                h4.fst-italic Clarisse iFX
                p Conjunto de herramientas CG totalmente interactivo para crear escenarios 3D, desarrollar looks, iluminar, renderizar y componer. Fue diseñado para agilizar el flujo de trabajo de artistas y permitirles trabajar e interactuar constantemente en su imagen final, con efectos completos y en tiempo real. 
    p.mb-5 De igual manera, es importante saber que algunos de los programas más utilizados para las labores de composición digital son:        
    SlyderB.mb-5(:datos="datosSlyder2")
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    mostrarIndicador: true,
    modal1: false,
    modal2: false,
    modal3: false,
    modal4: false,
    modal5: false,
    modal6: false,
    modal7: false,
    modal8: false,
    modal9: false,
    modal10: false,
    datosSlyder: [
      {
        titulo: 'Efectos visuales VFX',
        texto:
          'La composición digital, es parte del universo de los efectos visuales (VFX); se refiere a la manera como en un mismo plano o escena se combinan, modifican o eliminan múltiples y diversos elementos de distinto origen o medio como la iluminación, animación, color, movimiento, personajes, elementos atmosféricos, partículas, texturas o cualquier pieza que salga de la imaginación del director.',
        imagen: require('@/assets/curso/2.jpg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Efectos integrados al renderizado',
        texto:
          'Los efectos, mediante el uso de capas o nodos superpuestos, se integran en el proceso de renderizado para, finalmente, dar la ilusión de que todas pertenecen a una misma imagen, produciendo un plano final de cine, televisión, publicidad, realidad virtual, etc.',
        imagen: require('@/assets/curso/3.jpg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Capas y combinaciones de capas',
        texto:
          'Para la composición se necesita una imagen de fondo, una imagen en primer plano y una máscara, que indicará cuáles elementos serán visibles y cuáles no. Cada elemento puede tratarse de manera independiente del resto, y modificarse en cuanto a forma, color o iluminación; también puede mezclarse con otros, hasta lograr complejas combinaciones de capas, incrementando posibilidades creativas de composición. ',
        imagen: require('@/assets/curso/4.jpg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Producción de planos',
        texto:
          'La composición digital también interviene la producción de planos que no necesitan integrar elementos, sino llevar a cabo acciones de borrado de elementos, como eliminar un micrófono o un cable que se queda visible en el plano, retoque de los actores, extraer cromas, eliminar puntos de referencia (tracks), etc.',
        imagen: require('@/assets/curso/5.jpg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Proceso cinematográfico',
        texto:
          'Finalmente, la composición es, también, el proceso cinematográfico con el que se pueden recrear escenas muy complejas o imposibles de realizar en una misma secuencia de rodaje.',
        imagen: require('@/assets/curso/6.jpg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
    ],
    datosSlyder2: [
      {
        titulo: 'Composición multicapa',
        texto:
          'Se basa en la distribución de diversos elementos en capas; cada elemento es una capa. Estos programas se suelen organizar en tres partes: La línea de tiempos donde se distribuyen las capas, el visor donde se ve la composición y los paneles de propiedades para modificar los elementos. El orden de las capas es fundamental: la capa que esté por encima en la línea de tiempo, será la que estará delante en el visor. ',
        imagen: require('@/assets/curso/51.jpg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Composición por nodos',
        texto:
          'La distribución de los elementos del programa es parecida; existe un visor y una panel de propiedades, pero la línea de tiempos con nodos difiere bastante de la de las capas. Cada elemento y cada efecto que se aplica es un nodo. La idea es componer basándose en un diagrama estilo de árbol, donde cada elemento se va situando con la lógica piramidal. ',
        imagen: require('@/assets/curso/52.jpg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'En la composición por nodos, tenga presente',
        texto:
          'Cada nodo tiene uno o varios inputs (información que entra) y uno o varios outputs (información que sale). Y así, mediante el procedimiento de entrada/salida se va construyendo el árbol distribuyendo los elementos. En este sentido, la información se ordena de manera muy visual y esquemática, ya que un árbol de nodos se parece mucho a un diagrama de flujo de trabajo.',
        imagen: require('@/assets/curso/53.jpg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
    ], // variables de vue
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

<style lang="sass">
.slyder__btn
  &:hover
    background-color: $color-acento-contenido
  background-color: $color-secundario
  i
    color: $color-primario
.contenedor-fondo
  background-image: url('../assets/curso/bg-1.png')
  background-repeat: no-repeat
  background-size: cover
  background-position: center
.tarjetas-up

  overflow: hidden
  border-radius: 10px
  position: relative
  &_card
    transition: bottom .3s ease-in-out
    position: absolute
    border-radius: 10px
    width: 100%
    height: 100%
    left: 0
    bottom: -80%
    i:last-child
      display: none
  &:hover
    .tarjetas-up_card
      bottom: -40%
    i:first-child
      display: none
    i:last-child
      display: block
.linea-tiempo-d__item--selected .linea-tiempo-d__item__content__title, .linea-tiempo-d__item__content__slot
  background-color: #f8e8d5


.linea-tiempo-d__item__number.tarjeta.tarjeta--gris
  background-color: $color-primario
  span
    color: white
.pointer
  transition: background-color .3s ease-in-out
  &:hover
    cursor: pointer
    background-color: #ffda66 !important
.modal-a__content
  background-image: url('../assets/curso/bg-3.svg')
  background-repeat: no-repeat
  background-size: cover
  background-position: center
.pasos-b.color-primario .pasos-b__header__item--active .pasos-b__header__item__dot
  border-spacing: 20px
  outline-offset: -8px
  outline: 4px white solid
  span
    color: #fff
.bg-carrousel
  position: relative
  background-image: url('../assets/curso/SQ.svg')
  background-repeat: no-repeat
  background-size: cover
  background-position: center
  width: 100%
  min-height: 207px
  overflow: hidden
  &:hover
    .bg-carrousel_content
      left: 0
  &_content
    width: 100%
    background-color: #ffe799
    transition: left .3s ease-in-out
    position: absolute
    height: 100%
    left: 150%
.bg-carrousel2
  position: relative
  background-image: url('../assets/curso/IM.svg')
  background-repeat: no-repeat
  background-size: cover
  background-position: center
  width: 100%
  min-height: 207px
  overflow: hidden
  &:hover
    .bg-carrousel2_content
      left: 0
  &_content
    width: 100%
    background-color: #ffe799
    transition: left .3s ease-in-out
    position: absolute
    height: 100%
    left: 150%
</style>
