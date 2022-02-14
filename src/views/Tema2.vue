<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Edición de audio y vídeo
    .row.mb-5
      .col-lg-7
        p El montaje o también conocido como edición, es el proceso mediante el cual se determina la duración y cortes de cada uno de los planos, de la misma manera se realiza la sincronización de sonidos para otorgar mayor sentido al audiovisual.
          br
          br
          |Este es uno de los elementos más importantes ya que contribuye a la organización y el ritmo del filme, los cuales determinarán en gran medida la experiencia y efectos generados en los espectadores. Dentro del proceso, se juega con la tendencia del espectador a relacionar imágenes para construir significado. (Fernández y Martínez, 1999).
          br
          br
          |Desde el lenguaje audiovisual reconocemos el concepto de ritmo como la sensación dinámica dada por el flujo de movimiento, sonoro y visual en los diferentes planos, así como también por efectos de montaje. Es así como se puede crear tensión o relajación a partir de la forma en cómo se articulan los diferentes elementos. Se habla de que un plano cinematográfico posee un ritmo interno y otro externo, que también puede entenderse como montaje interno y montaje externo.
      .col-lg-5: img(src='@/assets/curso/54.jpg')
    #t_2_1.titulo-segundo.color-secundario
      h2 2.1 Edición de video
    .contenedor-fondo.p-5.mb-3
      .row.justify-content-center
        .col-lg-8: img(src='@/assets/curso/55.png').mb-5.mt-5
        p.w-75.mb-5 Es el proceso mediante el cual se crea un producto audiovisual a partir de la selección y unión de fragmentos de vídeo y audio en la línea del tiempo, que fueron obtenidos previamente a través de un soporte digital como cámara o programa.
          br
          br
          |Anteriormente, se hablaba de dos formas de edición: analógica y digital, pero, en la actualidad, la edición analógica está casi descontinuada y es, la edición digital, con la que se trabaja en todos los entornos en los que son necesarios los productos audiovisuales.
    p.mb-5 Por tales motivos, se debe tener en cuenta estas generalidades:
    ImagenInfografica.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/56.jpg', alt='Texto que describa la imagen')

      .tarjeta.bg-white.p-3(x="10%" y="18%" numero="")
        p La parte final de la edición es la posproducción de imagen y audio.
      .tarjeta.bg-white.p-3(x="68%" y="50%" numero="")
        p La edición suele ser un proceso dispendioso que, habitualmente, había venido requiriendo de dos profesionales: quien define el concepto y quien utiliza el programa.
      .tarjeta.bg-white.p-3(x="25%" y="60%" numero="")
        p En la postproducción de imagen se elaboran los efectos especiales, sobreimpresión de textos o animaciones y, en el audio, las locuciones, efectos o bandas sonoras.
      .tarjeta.bg-white.p-3(x="90%" y="70%" numero="")
        p Los cambios en el mercado y las competencias profesionales, hoy día, han simplificado los procesos y un mismo profesional, con el apoyo de la tecnología, debe estar en capacidad de elaborar un producto audiovisual de principio a fin.
    h3 Narrativa audiovisual
    .row.mb-5.justify-content-center
      .col-lg-8
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/57.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Las imágenes en movimiento, asumen el espacio en dos dimensiones y componen la realidad mediante encuadres o planos fijos y puntos de vista o ángulos de visión. Las imágenes en movimiento tienen además la propiedad de trabajar con la dimensión del tiempo.
    p.mb-5 Los elementos narrativos de un producto audiovisual son:
    .row.mb-5.justify-content-center
      .col-lg-10
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bg-ac")
          .row(titulo="El fotograma").px-5.justify-content-center.align-items-center
            .col-md-4.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/58.svg', alt='Texto que describa la imagen')
            .col-md-8
              p Unidad mínima en la que se divide una captura de imagen en movimiento. Es una imagen fija que, al sucederse con otras, produce una imagen en movimiento. Es equivalente a una fotografía.
          .row(titulo="La secuencia").px-5.justify-content-center.align-items-center
            .col-md-4.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/59.svg', alt='Texto que describa la imagen')
            .col-md-8
              p Manera de narrar completamente una acción. Aunque la acción sucede en diferentes lugares y momentos, se mantiene una línea argumental. Su duración depende de su importancia dentro del guion. La secuencia se compone de escenas y estas, a su vez, de planos. 
          .row(titulo="Planos").px-5.justify-content-center.align-items-center
            .col-md-4.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/60.svg', alt='Texto que describa la imagen')
            .col-md-8
              p <b>Existe un tipo de plano adaptado a la secuencia:</b> el plano secuencia es un plano fijo o en movimiento que no tiene cortes y dura lo mismo que la secuencia que está capturando.
          .row(titulo="La escena").px-5.justify-content-center.align-items-center
            .col-md-4.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/61.svg', alt='Texto que describa la imagen')
            .col-md-8
              p Se encarga de mostrar una acción que transcurre en un mismo tiempo y lugar. El paso de una escena a otra se da a través de cortes, que pueden ser secos, si se pasa de una imagen a otra diferente; fundidos a negro, cuando se oscurece la imagen hasta el negro o, fundido encadenado, cuando se superpone paulatinamente a la siguiente escena. La escena se compone de tomas.
          .row(titulo="La toma").px-5.justify-content-center.align-items-center
            .col-md-4.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/62.svg', alt='Texto que describa la imagen')
            .col-md-8
              p Es la grabación obtenida de una acción o escena. Es habitual hacer varias tomas de una misma escena utilizando diferentes ángulos de visión o puntos de vista.
          .row(titulo="Los planos en movimiento").px-5.justify-content-center.align-items-center
            .col-md-4.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/63.svg', alt='Texto que describa la imagen')
            .col-md-8
              p Surgen cuando la cámara hace un seguimiento del espacio y del movimiento de los personajes. Estos planos son, entre otros: travelling, panorámica y plano grúa.
    p.mb-5 Algunos tipos de plano, según tamaño, funciones, características de movimiento e imagen, son:
    .tarjetas-up.mb-5
      .tarjetas-up__content.p-4.d-flex.align-items-center(@mouseover="mostrarIndicador = false")
        .indicador--hover(v-if="mostrarIndicador")
        .tarjetas-up__content__image: img(src='@/assets/curso/64.jpg')
        .text-center
          p.fw-bold Travelling
          p Plano que describe la cámara al acompañar al personaje o elemento durante su desplazamiento de un lugar a otro.
      .tarjetas-up__content.p-4.d-flex.align-items-center
        .tarjetas-up__content__image: img(src='@/assets/curso/65.jpg')
        .text-center
          p.fw-bold Panorámica
          p Plano que se obtiene al realizar un movimiento de cámara de derecha a izquierda para dar una visión general del espacio.
      .tarjetas-up__content.p-4.d-flex.align-items-center
        .tarjetas-up__content__image: img(src='@/assets/curso/66.jpg')
        .text-center
          p.fw-bold Plano grúa
          p Plano que se capta al colocar la cámara sobre una grúa elevada para tomar la imagen cenital, desde lo alto y en todas las direcciones.
      .tarjetas-up__content.p-4.d-flex.align-items-center
        .tarjetas-up__content__image: img(src='@/assets/curso/67.jpg')
        .text-center
          p.fw-bold Plano general
          p Ubica al espectador en el espacio donde sucede la acción y su objetivo es describir el entorno.
      .tarjetas-up__content.p-4.d-flex.align-items-center
        .tarjetas-up__content__image: img(src='@/assets/curso/68.jpg')
        .text-center
          p.fw-bold Plano de detalle
          p Se usa para destacar elementos específicos que se consideren fundamentales para la acción que quiere presentarse.
      .tarjetas-up__content.p-4.d-flex.align-items-center
        .tarjetas-up__content__image: img(src='@/assets/curso/69.jpg')
        .text-center
          p.fw-bold Plano entero
          p Está estrechamente relacionado con el plano general, la diferencia radica en que el centro de acción lo producen los personajes no el decorado.
      .tarjetas-up__content.p-4.d-flex.align-items-center
        .tarjetas-up__content__image: img(src='@/assets/curso/70.jpg')
        .text-center
          p.fw-bold Plano americano
          p “Nació a partir de la necesidad del western, que en el plano medio tenía que incluir la pistola del cowboy. Este plano comprende, entonces, desde la pistola colgada debajo de la cintura hasta la cabeza entera del personaje”. 
      .tarjetas-up__content.p-4.d-flex.align-items-center
        .tarjetas-up__content__image: img(src='@/assets/curso/71.jpg')
        .text-center
          p.fw-bold Plano medio
          p Este plano presenta desde la cintura hasta la cabeza del personaje.
      .tarjetas-up__content.p-4.d-flex.align-items-center
        .tarjetas-up__content__image: img(src='@/assets/curso/72.jpg')
        .text-center
          p.fw-bold Primer plano 
          p Es el más expresivo, del cual se ha dicho es el reflejo del alma.
      .tarjetas-up__content.p-4.d-flex.align-items-center
        .tarjetas-up__content__image: img(src='@/assets/curso/73.jpg')
        .text-center
          p.fw-bold Primerísimo <br> primer plano
          p Este plano supone un acercamiento muy acentuado al rostro del personaje, va de debajo de los labios hasta las cejas.
    p.mb-5 Tenga en cuenta las siguientes características aplicadas a los planos; mediante ellas se busca alcanzar el objetivo o intención de cada plano:
    .row.mb-5
      .col-lg-6: img(src='@/assets/curso/74.jpg')
      .col-lg-6
        h3 Ritmo
        p Está al servicio de la narrativa y depende directamente de la sensación que se quiere transmitir. Dentro de un audiovisual se puede tener tanto un ritmo dinámico, como un ritmo suave. Como su nombre lo indica, el ritmo dinámico se caracteriza por mayor cambio de planos de corta duración (MS, CU) lo cual crea una sensación de acción y movimiento. En contraste, el ritmo suave suele tener planos de mayor duración y potencia la lectura de las expresiones y pensamientos de los personajes. La clave estará entonces, en lograr un equilibrio entre estos dos tipos de ritmo (Marquès, 1995).
          br
          br
          |El ritmo está condicionado entonces por el ritmo interno del plano, dado por las acciones que en este se suceden, así como también por el encuadre, la variación de centros de interés, el movimiento de la cámara o del zoom, y la combinación con los planos anteriores y posteriores (Fernández & Martínez, 1999).
        a.anexo.mb-4.mb-lg-0.bg--4-claro(href="https://www.youtube.com/watch?v=YwJaz7tXq1Y&ab_channel=DiegoValenzuela" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto.bg
            p <b>Enlace web.</b> Ritmo narrativo: ¿qué es y por qué es tan importante?
    .row.mb-5
      .col-lg-6
        h3 Elipsis y transiciones
        p Este elemento se equipará a los signos de puntuación en la escritura. La elipsis es la omisión del tiempo muerto con el objetivo de mostrar solo aquellas acciones relevantes, significativas y atractivas, por cualquier forma de transición. Se puede pasar de hoy a mañana, al próximo siglo o a los próximos milenios (Fernández & Martínez, 1999). Es la herramienta narrativa que ayuda a pasar de una secuencia a otra para avanzar en la historia en tiempo y espacio (CÁMARA, 2006). Una elipsis se realiza mediante el uso de transiciones variadas, cada una con su propio valor expresivo: corte, fundido encadenado y fundido a negro.
      .col-lg-6: img(src='@/assets/curso/75.jpg')
    h3 Herramientas técnicas para la edición de vídeo.
    p.mb-5 Al momento de iniciar la edición, es necesario contar con dos herramientas básicas para procesar el material “en bruto”; es decir, todo el material grabado por el dispositivo. Se trata del guion de montaje y el programa de edición. El guion técnico es el mismo documento que se utilizó en la etapa de grabación, pero que en la edición se constituye como un documento clave que consigna el orden en que se insertarán todos los elementos de la narrativa audiovisual.
    .row.mb-5.justify-content-center
      .col-lg-8
        .cajon.color-acento-botones.bg--4-claro.p-4.mb-4
          p.mb-0 El guion técnico define cómo se une una escena con otra, los tipos de plano que contiene cada escena, las transiciones entre las escenas y las secuencias definidas. Además de las imágenes, consigna los sonidos de cada escena y otro tipo de elementos gráficos como títulos o imágenes insertadas que contribuyan a dar sentido.
    p.mb-5 En cuanto a los programas de edición, existe una amplia variedad de software con los cuales llevar a cabo el montaje de las imágenes de video. Los softwares más populares actualmente son los siguientes:
    .row.mb-5.justify-content-center
      .col-lg-9
        LineaTiempoD.color-primario
          div.row(numero="1" titulo="Final Cut Pro (Mac):").p-4.align-items-center
            .col-lg-8
              p Se establecen las posiciones y movimientos de cámara acorde a lo definido en el guión técnico y en el storyboard, de igual manera se dispone de la ubicación en el espacio de los elementos de la escena y los personajes.
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/76.svg' style='border-radius: 25px')
          div.row(numero="2" titulo="Adobe Premiere Pro (Windows y Mac): ").p-4.align-items-center
            .col-lg-8
              p es una de las mejores alternativas profesionales para sacar el máximo rendimiento a la edición de vídeo. Pertenece a la familia de productos de Adobe Creative Suite. 
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/77.svg' style='border-radius: 25px')
          div.row(numero="3" titulo="Adobe After Effects (Windows y Mac): ").p-4.align-items-center
            .col-lg-8
              p es un complemento para Adobe Premiere Pro que, aunque requiere de un nivel algo avanzado, permite crear animaciones, gráficos 3D con movimiento y efectos para incluir en los vídeos dando un toque muy profesional.
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/78.svg' style='border-radius: 25px')
          div.row(numero="4" titulo="Avid Media Composer (Windows y Mac): ").p-4.align-items-center
            .col-lg-8
              p a pesar de no ser tan popular en los estudios de posproducción profesional de cine y televisión es muy usado por su dinámico flujo de trabajo. 
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/79.svg' style='border-radius: 25px')
          div.row(numero="5" titulo="Pinnacle Studio (Windows): ").p-4.align-items-center
            .col-lg-8
              p es un <i>software</i> muy intuitivo y fácil de manejar.
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/80.svg' style='border-radius: 25px')
          div.row(numero="6" titulo="Sony Vegas Pro (Windows): ").p-4.align-items-center
            .col-lg-8
              p potente <i>software</i> con una estética que sigue la línea de Sony. También tiene una versión llamada <i>Movie Studio</i> para usuarios no tan avanzados.
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/81.svg' style='border-radius: 25px')
          div.row(numero="7" titulo="Corel VideoStudio (Windows): ").p-4.align-items-center
            .col-lg-8
              p una opción más a tener en cuenta entre los programas avanzados. Recientemente ha añadido la opción de capturar en vídeo la pantalla del ordenador, ideal para tutoriales.
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/82.svg' style='border-radius: 25px')
    .contenedor-fondo.p-5.mb-4
      .row.justify-content-center
        .col-lg-8: img(src='@/assets/curso/83.png').mb-5.mt-5
        p.w-75.mb-5 Hace referencia a la posibilidad de manipular diferentes elementos sonoros, involucrando en el proceso un terminal computarizado y software específico, con el fin de integrar o generar sonidos nuevos o que se adapten a una necesidad específica.
          br
          br
          |Un sonido digital suele tener asociados una serie de condiciones y parámetros característicos entre los que se puede destacar: la tendencia a ser dinámicos, su capacidad de interactividad, su condición ubicua, su naturaleza versátil.
    p.mb-5 En la producción audiovisual, se hace necesario:
    SlyderD.mb-5(:datos="datosSlyder")
    .contenedor_amarillo.bg--4-claro.p-5.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-6.mb-3
          .titulo-segundo.color-primario
            h3 Construcción del diseño de sonido 
          p.mb-3 Conozca, más y mejor, el proceso de construcción del diseño de sonido para audiovisuales. Para ello, visualice el video que aquí se propone:
        .col-lg-4
          a(href="https://www.youtube.com/watch?app=desktop&v=CkiPtW8IZT0" target="_blank")
            img(src="@/assets/curso/88.jpg")
    p.mb-5 Ahora bien, el proceso de edición se compone de las siguientes tareas:
    .row.mb-5
      .col-lg-4.mb-3
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/curso/89.jpg' alt='AvatarTop' style='width:400px')
          .tarjetas-up_card.p-4
            .title.d-flex.align-items-center
              h4.mb-5 1. Arreglos
            p Se revisa todo el material que se ha grabado, se evalúa lo que funciona y lo que no: cortar secciones de una pista que desordenan la mezcla, mover una sección a una nueva parte de la canción, eliminar secciones por completo si no agregan valor, etc.
            a.boton.color-acento-botones.indicador__container.text-system(@click="modal1 = true")
              span.fw-bold Ver mas 
              .indicador--click(v-if="mostrarIndicador")
            ModalA(:abrir-modal.sync="modal1")
              p.fw-bold 1. Arreglos
              ul.lista-ul--color.vr
                li 
                  i.fas.fa-circle
                  p  <b>Acompañamiento: </b> se comparan las tomas duplicadas de cada pista y se selecciona la mejor. También se pueden seleccionar las mejores partes de cada toma y combinarlas en una nueva sección.
                li
                  i.fas.fa-circle
                  p <b>Reducción de ruido: </b>tiene como objetivo eliminar en la mayor medida posible los sonidos no deseados que puedan existir de fondo en una grabación (voces de fondo, pasos, respiraciones o simplemente el ruido ambiente).

                li
                  i.fas.fa-circle
                  p <b>Edición de tempo: </b>corrigen las notas fuera de ritmo utilizando el método “cortar y pegar», que funciona bien en instrumentos de percusión o el método de «estiramiento de tiempo», que funciona bien en casi todos los instrumentos.

                li
                  i.fas.fa-circle
                  p <b>Edición de tono: </b>  permite cambiar cualquier nota y “colocarla” en un nuevo tono, utilizando Auto-Tune o cualquier software similar. Normalmente se usa en voces, pero también funciona bien en la mayoría de los instrumentos melódicos.
              
      .col-lg-4.mb-3
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/curso/90.jpg' alt='AvatarTop' style='width:400px')
          .tarjetas-up_card.p-4
            .title.d-flex.align-items-center
              h4.mb-5 2. Proceso de Mezcla
            p Se encarga de fusionar, en una unidad cohesionada, los distintos sonidos depurados. Es una función con varias tareas fundamentales, que todos los técnicos en sonido deberán saber llevar a cabo durante la etapa del proceso de postproducción.
            a.boton.color-acento-botones.indicador__container.text-system(@click="modal2 = true")
              span.fw-bold Ver mas 
              .indicador--click(v-if="mostrarIndicador")
            ModalA(:abrir-modal.sync="modal2")
              h4.mb-5 2. Proceso de Mezcla
              ul.lista-ul--color.vr
                li 
                  i.fas.fa-circle
                  p  <b>Balance: </b> a través de esta tarea se busca que ningún instrumento suene demasiado alto o suave en relación con los demás.
                li 
                  i.fas.fa-circle
                  p  <b>Panorámica: </b>aquí se le da a cada instrumento su propio espacio en la imagen estéreo, al igual que cada músico tiene su propio espacio en el escenario.

                li 
                  i.fas.fa-circle
                  p  <b>Ecualización: </b>es la encargada de crear un espacio único en el espectro de frecuencias para cada instrumento, de modo que no haya dos sonidos que compitan por la misma banda de frecuencias.

                li 
                  i.fas.fa-circle
                  p  <b>Compresión: </b>nivela el rango dinámico de un instrumento para que cada nota se escuche con claridad y la mezcla suene más fuerte en su conjunto.
                li 
                  i.fas.fa-circle
                  p  <b>Reverberación: </b>  crea un espacio tridimensional para la mezcla, agrega una sensación de profundidad y unifica los instrumentos bajo el sonido de una habitación.
                li 
                  i.fas.fa-circle
                  p  <b>Automatización: </b> permite cambiar la configuración en diferentes puntos de la canción, para darle a la mezcla una sensación de movimiento.
      .col-lg-4.mb-3
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/curso/91.jpg' alt='AvatarTop' style='width:400px')
          .tarjetas-up_card.p-4
            .title.d-flex.align-items-center
              h4.mb-5 3. Masterización
            p Una vez que se ha realizado todas estas tareas y la mezcla está finalizada, es momento de pasar a la última etapa, es decir al proceso de masterización que consiste en potenciar la mezcla y dejarla en un solo archivo estéreo.
            a.boton.color-acento-botones.indicador__container.text-system(@click="modal3 = true")
              span.fw-bold Ver mas 
              .indicador--click(v-if="mostrarIndicador")
            ModalA(:abrir-modal.sync="modal3")
              h4.mb-5 3. Masterización
              ul.lista-ul--color.vr
                li 
                  i.fas.fa-circle
                  p  <b>Dato curioso: </b> suele afirmarse que la primera de todas las masterizaciones de la historia, ocurrió el laboratorio del conocido <i>Thomas Edison</i> de quien, se presume, debió producir el primer cilindro listo para ser usado en el fonógrafo; esto, para lograr la reproducción de un sonido grabado, previamente, a través del mismo artefacto.
    h3 Maqueta de sonido
    .row.mb-5.align-items-center
      .col-lg-6
        p La maqueta de sonido es la exploración inicial del ensamble sonoro necesario para el audiovisual; en este punto, se explora con música y otros sonidos, en su mayoría preexistentes, para determinar en la práctica qué cosas pueden funcionar y qué cosas no; permitiendo establecer los tiempos exactos de cada acción porque hay sonidos como los correspondientes a los diálogos que son necesarios para determinar aspectos de la animación.
          br
          br
          |Aunque, inicialmente, se trata de una maqueta para determinar con exactitud qué aspectos sonoros deben ser diseñados y producidos, desde este punto es importante tener en cuenta (cuatro) 4 aspectos fundamentales que deben estar presentes en el diseño sonoro de cualquier producción, los cuales se listan y describen a continuación:
      .col-lg-6: img(src='@/assets/curso/92.jpg')
    .tabla-a.color-primario.mb-5 
      table
        thead
          tr.bg-white
            th Dialogos
            th Efectos
            th.fst-italic Foley
            th Música
        tbody
          tr.vertical-align-initial
            td
              p Son una parte importante de todo el diseño sonoro de una producción pues como se mencionó anteriormente, estos definen diversos aspectos de la animación como el timing o los acentos en el <i>acting</i> del personaje.
            td 
              p En este aspecto podemos encontrar 2 grandes categorías, el sonido ambiente y los efectos especiales:
                br
                br
                <b>1. Sonido ambiente o efectos de ambiente.</b>
                br
                br
                | También conocido como room tone, corresponde a todos aquellos sonidos que nos permiten identificar un espacio; es decir el sonido característico de un lugar cuando se encuentra en “silencio”, por ejemplo, el sonido de los pájaros cantando en el bosque.
                br
                br
                <b>2. Efectos especiales</b>
                br
                br
                | Son sonidos específicos que sirven para resaltar determinadas situaciones y que son necesarios recrear ya en un estudio diseñado para ello o en un espacio natural, no tienen correspondencia estricta con lo que se está mostrando.
        
            td 
              p Es la reconstrucción o creación en estudio de sonidos en sincronía con la imagen real, es una forma de crear efectos especiales, pero principalmente sirve para resaltar o acentuar los sonidos que acompañan una acción y para ello se hace uso de gran variedad de elementos en un ambiente controlado.
            td
              p En este aspecto encontramos también dos grandes categorías: la música diegética y la música extra diegética o incidental:
                br
                br
                <b>1. Música diegética</b>
                br
                br
                | Diégesis es una palabra derivada del griego y según la RAE hace referencia al desarrollo narrativo de los hechos.
                br
                br
                <b>2. Música extra diegética o incidental</b>
                br
                br
                | En su definición más sencilla se trata de música de acompañamiento; es decir, se encarga de originar una atmósfera para el desarrollo de la acción.
    h3 Masterización
    .row.mb-5.justify-content-center
      .col-lg-8
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/1.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 La masterización en el audio es el último paso para poner en equilibrio todos los elementos que en ella se combinan. De allí parten todas las copias de dicho audio finalizadas para diferentes formatos o plataformas, como también da consistencia y uniformidad entre las diferentes pistas que componen el producto, dotándolo de claridad y coherencia.
    p.mb-5 La premisa principal es que masterizar dota de características al audio, para que suene de la mejor manera posible en cualquier plataforma; si las pistas del audio no estuviesen masterizadas, incurrirán en no tener correlación y básicamente parecería que no pertenecieran a un mismo proyecto.
      br
      br
      |Algunas técnicas de masterización para mejorar el audio son:
    .row.mb-5
      .col-lg-4
        .tarjeta.tarjetas-a.p-5.h-100
          .iconos.mb-4
            img(src='@/assets/curso/94.svg' style='width: 120px')
            img(src='@/assets/curso/95.svg' style='width: 120px')
          h5 Maximización de la sonoridad:
          p se consigue a través de una mayor compresión y limitación. De esta forma el nivel promedio de señal en el tiempo es lo más alto posible, sin sacrificar demasiado el rango dinámico.
      .col-lg-4
        .tarjeta.tarjetas-a.p-5.h-100
          .iconos.mb-4
            img(src='@/assets/curso/94.svg' style='width: 120px')
            img(src='@/assets/curso/95.svg' style='width: 120px')
          h5 Balance de frecuencias
          p se realiza a través de EQ adicionales y un proceso conocido como compresión multibanda, que puede comprimir bandas de frecuencia individuales por separado del resto del espectro.
      .col-lg-4
        .tarjeta.tarjetas-a.p-5.h-100
          .iconos.mb-4
            img(src='@/assets/curso/94.svg' style='width: 120px')
            img(src='@/assets/curso/95.svg' style='width: 120px')
          h5 Ampliación estéreo: 
          p se alcanza con un complemento especial diseñado para agregar una sensación adicional de «ancho» a las frecuencias más altas en su mezcla.
    .bg-carrousel2.d-flex.justify-content-center.align-items-center.mb-5(@mouseover="mostrarIndicador = false")
      .indicador--hover(v-if="mostrarIndicador")
      h2.h1.text-center.text-white Importante
      .bg-carrousel2_content.px-5.py-5.justify-content-center.d-flex.align-items-center
        .text-center.w-75
          p.fw-bold.mb-0 Una vez que todo suena como se espera, la pista se convierte a su frecuencia de muestreo o profundidad de bits adecuada. Terminadas estas etapas se finaliza todo el proceso de postproducción de audio para ensamblar con el video.
    h3 Formatos de sonido
    .row.mb-5.justify-content-center
      .col-lg-8
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/96.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Los formatos de sonido son decodificadores que transmiten la señal junto al video. Los formatos de sonido, podrían definirse como contenedores de audio o grabaciones.
    p.mb-5 Los formatos de sonido más usados por la industria de los videojuegos son:
    TabsA.color-primario.mb-5
      .tarjeta.bg--2-claro.p-4(titulo="Dolby Digital")
        h4 Dolby Digital
        p Es el más utilizado a lo largo de la historia, gracias a que presenta mayor compatibilidad con un gran número de equipos, aunque se puede sufrir cierta pérdida en la calidad, al comprimir el sonido. En los últimos años, ha venido trabajando con otros formatos Dolby digital plus, Dolby Digital TRUE HD, y Dolby ATOMS, que evitan comprimir el audio, conservando la fidelidad de los sonidos.
      .tarjeta.bg--2-claro.p-4(titulo="Digital Sourround (DTS)")
        h4 Digital Sourround (DTS)
        p Es la competencia directa de Dolby Digital, se caracteriza por conservar un sonido fuerte y nítido, aunque al comprimirse también se presenta una pérdida en la calidad, pero menor que la presentada por Dolby Digital y, al igual que esta, ha venido trabajando en su formato DTS – HD sin compresión con el fin de conservar la alta definición del sonido.
      .tarjeta.bg--2-claro.p-4(titulo="Otros Formatos")
        h4 Otros Formatos
        p Adicionalmente, se utilizan otros formatos de archivo sin compresión en la programación de videojuegos como el <b>WAV</b> y <b>AIFF</b>; que son similares, aunque tienen ciertas diferencias de encapsulado. Mientras que el formato de archivo con compresión más utilizado en la programación de videojuegos es el <b>MP3</b>; y aunque el <b>AAC</b> de <b>Apple</b> y el <b>WMA</b> de Microsoft ofrecen versiones mejoradas al <b>MP3</b>, en el mundo de la programación para videojuegos no se suelen usar, debido a su falta de compatibilidad.
    h3 Software para la edición de sonido
    .row.mb-5.justify-content-center
      .col-lg-8
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/97.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Cualquier software de sonido, que reúna características de calidad, funcionalidad y pertinencia, será para los productores, desarrolladores y creativos en general, una herramienta esencial. Además del After Effects, el cual gracias a su versatilidad incluye también el tratamiento de audio, existen otros softwares de alta aceptación en el mercado y en las organizaciones.
    p.mb-5 Siendo así, los softwares para edición de sonido, algunos de pago y otros gratuitos, son:
    .row.mb-5.justify-content-center
      .col-lg-9
        LineaTiempoD.color-primario
          div.row(numero="1" titulo="Adobe Audition").p-4.align-items-center
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/98.svg' style='border-radius: 25px')
            .col-lg-8
              p Se establecen las posiciones y movimientos de cámara acorde a lo definido en el guión técnico y en el storyboard, de igual manera se dispone de la ubicación en el espacio de los elementos de la escena y los personajes.
          div.row(numero="2" titulo="Logic Pro X").p-4.align-items-center
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/99.svg' style='border-radius: 25px')
            .col-lg-8
              p Producto Apple que sólo está disponible para macOS. Es un DAW <i>(Digital Audio Workstation)</i> con funciones básicas y avanzadas. Una de sus funciones más particulares es el Smart Tempo, que consiste en sincronizar diferentes pistas de un proyecto automáticamente.
          div.row(numero="3" titulo="Ableton Live 10").p-4.align-items-center
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/100.svg' style='border-radius: 25px')
            .col-lg-8
              p Se presume como el mejor programa para tocar música en vivo con gran cantidad de funciones: admite pistas ilimitadas de audio y MIDI, 256 canales de entrada y 256 canales de salida mono. Equipado con 70 GB de sonidos pregrabados, 15 instrumentos de software y 46 efectos de audio. Su éxito se debe a su capacidad para crear y tocar música en vivo. Tiene una vista de sesión para añadir pistas MIDI y clips de audio para mezclarlos en tiempo real.
          div.row(numero="4" titulo="Pro Tools").p-4.align-items-center
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/101.svg' style='border-radius: 25px')
            .col-lg-8
              p Potente software para editar música: creado para grabar, mezclar y masterizar la mejor calidad de audio posible. Muy utilizado por los profesionales de la industria musical o cinematográfica para sesiones largas ya que soporta casi todas los formatos: .aac, MP3, S1, SD2, M4a y más.
          div.row(numero="5" titulo="FL Studio").p-4.align-items-center
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/102.svg' style='border-radius: 25px')
            .col-lg-8
              p Este DAW viene equipado con más de 80 plugins listos para usar y es muy popular en el género del Hip-Hop. También tiene una función única llamada Piano Roll, que permite modificar las notas de los samples con total inmediatez. 
          div.row(numero="6" titulo="Audacity").p-4.align-items-center
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/103.svg' style='border-radius: 25px')
            .col-lg-8
              p Considerado el mejor programa de código abierto para editar audio. Es muy útil para crear playlists y cuenta con un editor multitrack de audio. Graba y edita audio e, incluso, añade efectos. Es el rey de los programas de edición de audio gratuitos para Windows. 
          div.row(numero="7" titulo="Ocenaudio").p-4.align-items-center
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/104.svg' style='border-radius: 25px')
            .col-lg-8
              p Tiene una interfaz de usuario sencilla y permite copiar y pegar, además de añadir efectos y filtros.
          div.row(numero="8" titulo="GarageBand").p-4.align-items-center
            .col-lg-3
              .rounded-2
                img(src='@/assets/curso/105.svg' style='border-radius: 25px')
            .col-lg-8
              p Programa gratuito para grabar música en Mac. Viene preinstalado en todos los dispositivos de Apple y permite grabar música. Como curiosidad, el beat de la canción "Umbrella" fue creado usando un loop de GarageBand.Con esta canción, Rihanna ganó un Grammy y alcanzó el #1 en el ranking de Billboard Hot 100. GarageBand ofrece tantas posibilidades y es tan completo que muchos artistas amateurs ven más conveniente producir su música con él que pagar por un estudio de grabación tradicional. 
    .contenedor_amarillo.bg--4-claro.p-5.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-6.mb-3
          .titulo-segundo.color-primario
            h3 Para finalizar este contenido, se le recomienda visitar los siguientes enlaces para ampliar su conocimiento y apropiación sobre softwares para edición de sonido: 
          a(href="https://www.crehana.com/pe/blog/video/mejores-programas-edicion-audio/#grg-band" target="_blank")
            .bg--1-claro2.display-block.rounded-2.p-2.d-flex.w-100.mb-2.hover
              img(src='@/assets/curso/18.svg' style='width: 25px').me-2
              p.mb-0.fw-bold.d-flex.align-items-center.justify-content-center Edición de audio
          a(href="https://www.youtube.com/watch?v=uN5rYk9dYek" target="_blank")
            .bg--1-claro2.display-block.rounded-2.p-2.d-flex.w-100.mb-2.hover
              img(src='@/assets/curso/18.svg' style='width: 25px').me-2
              p.mb-0.fw-bold.d-flex.align-items-center.justify-content-center Audio After effects
        .col-lg-4
          img(src="@/assets/curso/19.svg")



</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    modal1: false,
    modal2: false,
    modal3: false,
    mostrarIndicador: true,
    datosSlyder: [
      {
        titulo: 'El diseño de sonido',
        texto:
          'El diseño de sonido, que consiste en la creación de todo el ambiente sonoro para un medio audiovisual, ya sea cine, tv, web-streaming, etc.',
        imagen: require('@/assets/curso/84.jpg'),
      },
      {
        titulo: 'Interacción entre audio y video',
        texto:
          'Junto a los elementos visuales, una de las áreas más importantes es la interacción entre audio y video, que tiene por fin que el espectador logre involucrarse por completo en la situación y/o experiencia que se quiere proporcionar.',
        imagen: require('@/assets/curso/85.jpg'),
      },
      {
        titulo: 'Diseño sonoro',
        texto:
          'En el diseño sonoro se tienen en cuenta cuatro aspectos principales: diálogo, efectos, música y ambiente; estos son conocidos, técnicamente, como planos sonoros y aportan realismo a la imagen.',
        imagen: require('@/assets/curso/86.jpg'),
      },
      {
        titulo: 'Edición de sonido y mezcla',
        texto:
          'El diseño sonoro trabaja con la edición de sonido y la mezcla. Con el paso del tiempo, las tareas de un editor y un mezclador se han ido fusionando y existe una zona en la que ambas labores se mezclan.',
        imagen: require('@/assets/curso/87.jpg'),
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

<style lang="sass">
.contenedor-fondo
  background-image: url('../assets/curso/bg-2.png')
  background-repeat: no-repeat
  background-size: cover
  background-position: center
.bg-ac
  background-color: #fdf7ef


.tarjetas-up
  justify-content: center
  display: flex
  flex-wrap: wrap
  &__content
    position: relative
    overflow: hidden
    width: 295px
    height: 295px
    margin: 5px
    border-radius: 10px
    background-color: #F6DCDB
    &:hover
      .tarjetas-up__content__image
        top: 0
    &__image
      position: absolute
      width: 100%
      height: 100%
      left: 0
      top: -100%
      transition: top 0.3s ease-in-out
.linea-tiempo-d__item--selected .linea-tiempo-d__item__content__title, .linea-tiempo-d__item__content__slot
  background-color: #f8e8d5
.linea-tiempo-d__item__number.tarjeta.tarjeta--gris
  background-color: $color-primario
  span
    color: white


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
    bottom: -85%
    background-color: rgba(255,255 ,255 ,0.9)
      transition: opacity .3s ease-in-out
  &:hover
    .tarjetas-up_card
      bottom: -35%
.vr
  i
    color: #D44F4A !important

.modal-a__content
  background-image: url('../assets/curso/bg-3.svg')
  background-repeat: no-repeat
  background-size: cover
  background-position: center


.vertical-align-initial
  tr,td
    vertical-align: initial !important

.tarjetas-a
  background-color: #F6DCDB
  transition: background-color .3s ease-in-out
  img:first-child
    display: block
  img:last-child
    display: none
  &:hover
    img:first-child
      display: none
    img:last-child
      display: block
    background-color: #E59592

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
.tabs-a.color-primario .tabs-a__tab__selected
  color: white !important
.tabs-a__tab
  background-color: #F4DCC0
</style>
