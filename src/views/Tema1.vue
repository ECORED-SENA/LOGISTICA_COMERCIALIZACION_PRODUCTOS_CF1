<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.bg-foot
    .titulo-principal.color-acento-contenido(data-aos='flip-up')
      .titulo-principal__numero
        span 1
      h1 Conceptos de logística y mercancías
    .row.mb-5.slideInUp
      .col-lg-7
        .cajon-b.color-primario.p-3.mb-4
          p.mb-0  A lo largo de años, la funcionalidad logística fue considerada como una actividad rutinaria, meramente operativa y elemental para hacer llegar los productos a partir de los centros de producción a los de uso o consumo. A partir de esta visión, la funcionalidad logística en la organización era contemplada solo como un centro generador de costes sin capacidad de diferenciación (Ballou, 2004). 
        p.mb-3  En el campo académico, su análisis se realizaba a partir del punto de vista industrial o técnica, en busca de modelos que permitieran optimizar espacios, planear distribuciones y minimizar costes. La globalización de la economía y la consiguiente apertura de nuevos mercados distanciados geográficamente fueron cambiando la percepción de la funcionalidad logística hacia novedosas magnitudes, en las que la funcionalidad logística permitía ciertas ventajas competitivas fundamentadas en la reducción de los tiempos de entrega o en la mejora de costes.
        p.mb-3  Sin embargo, a pesar de estas ventajas, la funcionalidad logística seguía siendo una actividad menor en la administración empresarial. En la década de 1960 la administración logística, siguiendo los postulados de <i>marketing</i>, consigue una orientación hacia el comprador que se materializa en dar un servicio logístico ajustado a las necesidades y requisitos de este, y que posibilite su satisfacción. A partir de allí, la funcionalidad logística comienza a ser tratada como una actividad de carácter estratégico capaz de crear ventajas competitivas que diferencian a la organización de la competencia. A continuación, se relacionan aspectos importantes sobre el proceso de logística.
      .col-lg-5.slideInLeft
        figure
          img(src='@/assets/curso/t1-i1.jpg' alt='')

    .neg-margin-x.bg-sliders2.mb-5
      .row.mb-5.justify-content-center
        .col-lg-7
          ImagenInfografica.color-secundario.mb-5
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/t1-im1.svg', alt='Despacho de mercancias')

            .tarjeta.color-secundario.p-3.shadow-box(x="49%" y="18%" numero="")
              .h5.mb-2 Proceso:
              p.mb-0  Grupo de secuencia de actividades repetidas.
            .tarjeta.color-secundario.p-3.shadow-box(x="78%" y="33%" numero="")
              .h5.mb-2 Planeación:
              p.mb-0  Requiere de estrategias.
            .tarjeta.color-secundario.p-3.shadow-box(x="86%" y="65%" numero="")
              .h5.mb-2 Instrumentación:
              p.mb-0  Por ejecutarse después de la planeación.
            .tarjeta.color-secundario.p-3.shadow-box(x="64%" y="90%" numero="")
              .h5.mb-2 Control:
              p.mb-0  Evaluar, supervisar, mejorar y retroalimentar.              
            .tarjeta.color-secundario.p-3.shadow-box(x="33%" y="93%" numero="")
              .h5.mb-2 Flujo y almacén:
              p.mb-0  Distribución física.  
            .tarjeta.color-secundario.p-3.shadow-box(x="13%" y="65%" numero="")
              .h5.mb-2 Flujo informativo:
              p.mb-0  Situación relativa de los transportadores.
            .tarjeta.color-secundario.p-3.shadow-box(x="20%" y="33%" numero="")
              .h5.mb-2 Cumple expectativas:
              p.mb-0 Esquema que el cliente pide y exige. 

    
    p.mb-5  En la logística se asocian varios recursos innovadores que mediante una combinación eficiente ofrecen al cliente un nivel elevado de calidad y confiabilidad buscando soluciones y de esta forma incrementan la competitividad y sostenimiento de la empresa. La experiencia y la competencia permiten encontrar soluciones acordes a cada necesidad. 
    .row.mb-5.justify-content-center
      .col-lg-12
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/t1-i2.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4.shadow-box
            p.mb-0.text-bold El término mercancía se define como cualquier bien o producto que se puede comercializar. Hay una extensa variedad de objetos y materiales considerados como mercancías, que son transportados nacional e internacionalmente, con fines comerciales; por lo cual se debieron clasificar para que los transportistas logren realizar entregas con éxito. El cuidado en el funcionamiento de las cargas es demasiado fundamental en la logística, conforme el trato que reciba la misma, debido a que podría provocar una variación del producto para el cliente. De esta forma, las cargas tienen que clasificarse de acuerdo con el tipo o estado físico de la mercancía, para asegurar su adecuado transporte y entrega. 

    p.mb-5 Los productos y mercancías, de acuerdo con su tipo, se clasifican de la siguiente forma: 

    .neg-margin-x.bg-sliders.py-0.mb-5
      .tarjeta.p-4.mb-5.r-0
        SlyderA(tipo="a")
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0.p-5
              .h4 Carga general:
              p Se trata de los productos transportados en pequeñas unidades independientes. Ejemplo: cajas, frascos y botellas.
            .col-md-4
              figure
                img(src='@/assets/curso/t1-s0.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0.p-5
              .h4 Carga suelta:
              p Compuesta por productos sueltos por unidades de tamaño, manipulados y transportados como unidades separadas. Ejemplo: llantas, madera y cilindros.
            .col-md-4
              figure
                img(src='@/assets/curso/t1-s1.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0.p-5
              .h4 Carga paletizada:
              p Compuesta por una cantidad de productos agrupados sobre una estiba para ser almacenada y transportada en una operación más sencilla. 
            .col-md-4
              figure
                img(src='@/assets/curso/t1-s3.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0.p-5
              .h4 Carga contenedorizada:
              p Es el tipo de carga que utiliza el contenedor, como unidad de transporte, que permite el traslado seguro e inviolable de la mercancía. 
            .col-md-4
              figure
                img(src='@/assets/curso/t1-s4.png', alt='imagen decorativa')
    br
    p.mb-5  Teniendo en cuenta el tipo de mercancía, los productos y mercancías, también se clasifican de acuerdo con su naturaleza:
    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-primario.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/t1-p1.png', alt='icono decorativo')
        .h2.text-center Carga peligrosa
        p Son los productos o sustancias que, al ser transportados, representan un riesgo para la salud, el medio ambiente, entre otros. Las mercancías peligrosas se clasifican por el peligro que estas tienen, por la posibilidad de contaminar, su estructura y/o su nivel de peligrosidad. Para la diferenciación de estas mercancías, hay etiquetas en el transporte que identifican los peligros que estas pueden provocar. 


      .col-md.tarjeta.color-acento-botones.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/t1-p2.png', alt='icono decorativo')
          
        .h2.text-center Carga perecedera
        p Son los productos que, expuestos a diversas temperaturas del medio ambiente, pueden deteriorarse después de un tiempo determinado; trátese de alimentos o productos sanitarios que deban seguir un control y unos parámetros técnicos dentro de la cadena de frío, etc. Dentro de los productos perecederos se encuentran las frutas y las verduras, la carne y sus derivados, los pescados y los mariscos, los productos lácteos y las flores, entre otros. Se destacan entre los   productos perecederos las verduras, frutas, carnes, pescados y lácteos, entre otros.

      .col-md.tarjeta.color-acento-contenido.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/t1-p3.png', alt='icono decorativo')
        .h2.text-center Carga frágil
        p Son todas aquellas mercancías que, por sus condiciones de elaboración, deben tener un cuidado especial en su transporte, pues se pueden averiar por manipulación inadecuada. En este grupo se identifican los elementos de cristal, esculturas,  productos de precisión, entre otros.


    #t_1_1.titulo-segundo.color-secundario
      h2 1.1 Medios de transporte
    p.mb-5  Cada tipo de mercancía debe acomodarse a una clase de transporte que sea compatible con su naturaleza, medidas físicas o sus características y las precauciones para su movilización. El concepto medio de transporte comprende el conjunto de técnicas de transporte y dispositivos que se usan en el traslado de productos o mercancías de un lugar a otro, incluida la manera a pie. Los medios de transportes usados para la distribución de productos son el avión, el camión, el tren y el buque. A continuación, se conocerán algunos medios:
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--lila")
      .row(titulo="Avión")
        .col-md-8.mb-4.mb-md-0
          p Medio de transporte capaz de moverse de forma autónoma en el espacio aéreo, con capacidad para el transporte de individuos, carga de mercancías y correo. Los aviones según su uso se ordenan en cargueros, de pasajeros y mixtos; y conforme con la soberanía de vuelo, en corta, media y extensa o larga. Por el número y tipo de su sistema de propulsión, pueden ser de hélice, con motor de pistón; de actitud, impulsados por la salida de gases a chorro; y de turbopropulsión, con motor de reacción provisto de una turbina de gas.
        .col-md-4
          figure
            img.nW(src='@/assets/curso/t1-a1.png', alt='icono decorativo')

      .row(titulo="Tipos de aviones")
        .col-md-8.mb-4.mb-md-0
          p El tipo de aeronave usado para transporte de carga es el 
            span.text-bold.text-color avión carguero, 
            | dedicado a transportar todo tipo de mercancías contenerizadas o carga general y correspondencia. <br>Otro tipo de aeronave es el avión <b>cisterna</b>, que es acondicionado para transporte de graneles líquidos. A partir del año 1919 se efectuó el primer vuelo comercial con mercancías y la demanda del uso de aeronaves para el transporte de carga no ha dejado de crecer. Esta demanda propició el uso de contenedores aéreos y la necesidad de compatibilizar el transporte de pasajeros con la carga aérea sin olvidar que hoy en día encontramos aviones exclusivos para la carga de mercancías. 
        .col-md-4
          figure
            img.nW(src='@/assets/curso/t1-a2.png', alt='icono decorativo')

      .row(titulo="Camión")
        .col-md-12.mb-4.mb-md-0
          p.mb-3  El medio sobre el que se sustenta el transporte de carretera es el camión, transporte compuesto por la unidad tractora y la caja que arrastra, llamada semirremolque. El camión podría ser duro, sin que se logren dividir ambos recursos y por lo que la carga reposa sobre el chasís o el articulado.
          p.mb-4  El remolque compuesto por una plataforma sin sistema de tracción propia, es arrastrado por una unidad tractora en la que se ensambla y reposa parcialmente, transfiriendo una sección mayoritaria de su masa y carga. No tiene eje delantero y puede contar con 1, 2 o 3 ejes traseros.
          .h5.mb-4 Tipos de camiones de carga en el transporte terrestre
          .row.mb-5
            .col-md-4.col-lg-4.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/t-a1.svg' alt='ejemplo de camion')
              .h6.text-center Rabon (1 eje)
            .col-md-4.col-lg-4.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/t-a2.svg' alt='ejemplo de camion')
              .h6.text-center Torton (2 ejes)
            .col-md-4.col-lg-4.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/tt.svg' alt='ejemplo de camion')
              .h6.text-center Caja cerrada de 53 pies
            .col-md-4.col-lg-4.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/t-a4-1.svg' alt='ejemplo de camion')
              .h6.text-center Caja cerrada de 48 pies
            .col-md-8.col-lg-8.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/t-a5.svg' alt='ejemplo de camion')
              .h6.text-center Full / Doble semirremolque
            .col-md-4.col-lg-4.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/t-a6.svg' alt='ejemplo de camion')
              .h6.text-center Caja refrigerada
            .col-md-4.col-lg-4.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/t-a7.svg' alt='ejemplo de camion')
              .h6.text-center Plataforma 45 pies
            .col-md-4.col-lg-4.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/t-a8.png' alt='ejemplo de camion')
              .h6.text-center Autotanque / Pipa

            .col-md-4.col-lg-4.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/t-a9.png' alt='ejemplo de camion')
              .h6.text-center Jaula a granel / Granelera

            .col-md-4.col-lg-4.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/t-a10.png' alt='ejemplo de camion')
              .h6.text-center Autotanque para asfalto / Granel

            .col-md-4.col-lg-4.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/t1-a11.png' alt='ejemplo de camion')
              .h6.text-center <i>Low boy</i> / Cama baja

            .col-md-4.col-lg-4.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/t-12.png' alt='ejemplo de camion')
              .h6.text-center Jaula ganadera
              
            .col-md-4.col-lg-4.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/t-a13.png' alt='ejemplo de camion')
              .h6.text-center Jaula enlonada / Cortina
            .col-md-4.col-lg-4.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/t-a14.png' alt='ejemplo de camion')
              .h6.text-center Tolva
            .col-md-4.col-lg-4.tarjeta--tabla.p-4
              .row.justify-content-center.mb-3
                .col-10
                  .objBox
                    img(src='@/assets/curso/t-a15.png' alt='ejemplo de camion')
              .h6.text-center Madrina / Porta vehículos
              


      .row(titulo="Tren")
        .col-md-8.mb-4.mb-md-0
          p.mb-3  Medio de transporte especializado con vagones sellados, sillas y vagones planos con contenedores. Principalmente cargan mercancías a granel como carbón, granos, además los hay como planchones para cargar contenedores, por una vía férrea.
          p.mb-3  La máquina o unidad tractora que arrastra los vagones puede consumir energía eléctrica o  combustible para producir la fuerza esencial para la tracción.
          
        .col-md-4
          figure
            img.nW(src='@/assets/curso/t1-a4.png', alt='icono decorativo')

      .row(titulo="Buque")
        .col-md-8.mb-4.mb-md-0
          p.mb-3  El modo marítimo usa el buque como medio de transporte en el segmento primordial de su cadena de transporte. El pacto MARPOL 73/78 lo define como toda clase de embarcación que opere en el medio marino, incluido los aliscafos, los aerodeslizadores, los sumergibles, las herramientas flotantes y las plataformas fijas o flotantes.
          p.mb-3  Los buques han alcanzado un grado de especialización que pueden adaptarse a las diferentes características de las cargas que haya que transportar. En el mercado marítimo internacional existen buques mercantes acondicionados para transportar todo tipo de mercancías, atendiendo a su naturaleza, el volumen de la carga, la distancia entre puerto de origen y el de destino.
          
        .col-md-4
          figure
            img.nW(src='@/assets/curso/t1-a5.png', alt='icono decorativo')

      .row(titulo="Buque carga general o buque multipropósito")
        .col-md-8.mb-4.mb-md-0
          p.mb-3  Buque habitualmente provisto de 2 cubiertas que, al igual que sus bodegas,  fueron adaptadas para la carga de contenedores. Pueden disponer de sistemas ro-ro, refrigeración, tanques y grúas para carga pesada. Los buques multipropósito pueden desplazar: graneles líquidos y secos, carga sobre automóviles, enormes piezas, palés, contenedores, carga general y carga perecedera.
          
        .col-md-4
          figure
            img.nW(src='@/assets/curso/t1-a6.png', alt='icono decorativo')

      .row(titulo="Buque granelero")
        .col-md-8.mb-4.mb-md-0
          p.mb-3  Buque construido con una única cubierta, con tanques en la parte superior y tanques laterales de tolva en los espacios de carga, para el transporte de graneles firmes y líquidos. La parte  de sus bodegas tiene forma de pirámide para aprovechar mejor el espacio. Regularmente permanecen dotados con grúas. Ciertos buques pueden atender alternativamente el transporte de líquidos o firmes, como los denominados «OBO».
          
        .col-md-4
          figure
            img.nW(src='@/assets/curso/t1-a7.png', alt='icono decorativo')
            
      .row(titulo="Buque de carga horizontal")
        .col-md-8.mb-4.mb-md-0
          p.mb-3  Buque elaborado para el transporte de mercancías sobre medios rodantes utilizados en el transporte terrestre, como plataformas, remolques o semirremolques, camiones, vagones, etc., que se ponen a bordo por sus propios medios o mediante carretillas elevadoras o grúas.
          
        .col-md-4
          figure
            img.nW(src='@/assets/curso/t1-a8.png', alt='icono decorativo')

    p.mb-5  Los medios de transporte tienen diversas características que deben ser tenidas en cuenta para garantizar que las mercancías lleguen a su destino teniendo en cuenta sus necesidades, por ejemplo:            
    .row.mb-5.justify-content-center
      .col-lg-4
        figure
          img.nW(src='@/assets/curso/t1-mn1.jpg', alt='icono decorativo')
      .col-lg-6
        .tarjeta-avatar-b.mb-2.align-items-center
          .tarjeta-avatar-b__img
            img.nW(src='@/assets/curso/t1-t1.svg' alt='AvatarTop')
          .tarjeta.tarjeta--azul
            .p-4
              .h3 La dimensión de la carga.

        .tarjeta-avatar-b.mb-2.align-items-center
          .tarjeta-avatar-b__img
            img.nW(src='@/assets/curso/t1-t2.svg' alt='AvatarTop')
          .tarjeta.tarjeta--azul
            .p-4
              .h3 La fuerza motriz del vehículo.
        .tarjeta-avatar-b.mb-2.align-items-center
          .tarjeta-avatar-b__img
            img.nW(src='@/assets/curso/t1-t3.svg' alt='AvatarTop')
          .tarjeta.tarjeta--azul
            .p-4
              .h3 La capacidad y protección de la carga.
        .tarjeta-avatar-b.mb-2.align-items-center
          .tarjeta-avatar-b__img
            img.nW(src='@/assets/curso/t1-t4.svg' alt='AvatarTop')
          .tarjeta.tarjeta--azul
            .p-4
              .h3 El bienestar y comodidad de la tripulación.
        .tarjeta-avatar-b.mb-2.align-items-center
          .tarjeta-avatar-b__img
            img.nW(src='@/assets/curso/t1-t5.svg' alt='AvatarTop')
          .tarjeta.tarjeta--azul
            .p-4
              .h3 La seguridad de las mercancías que transporta.


    Separador
    br
    br
    #t_1_2.titulo-segundo.color-secundario
      h2 1.2 Simbología de manejo de carga

    p.mb-5  Para hacer un adecuado transporte de mercancías, se necesita marcar correctamente el embalaje, ya que esta marcación dejará defender, trasladar, guardar y manipular apropiadamente una gigantesca proporción de empaques y embalajes.
    p.mb-5  Para el transporte de mercancía se conocen tres tipos de marcas:

    .tarjeta.tarjeta--azul.mb-5.p-4
      .row.mb-5.justify-content-center
        .col-lg-4
          ImagenInfografica.color-secundario.customDots
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/t1-box.svg', alt='Despacho de mercancias')

            .tarjeta.color-secundario.p-3.shadow-box(x="8%" y="45%" numero="1")
              .h5.mb-2 Marcas estándar o de expedición
              p.mb-0  Contienen datos acerca del importador, destino, dirección, número de referencia, número de unidades, etcétera.
            .tarjeta.color-secundario.p-3.shadow-box(x="40%" y="87%" numero="2")
              .h5.mb-2 Marcas de manipulación
              p.mb-0  Indican el funcionamiento y advertencias en el momento de manipular o desplazar la carga, en este caso se aplican símbolos pictóricos internacionalmente aceptados.
              
            .tarjeta.color-secundario.p-3.shadow-box(x="88%" y="80%" numero="3")
              .h5.mb-2 Marcas informativas
              p.mb-0  Señalan información adicional que nace en el empaque o embalaje como: territorio de origen, puerto de salida, puerto de ingreso, peso bruto, peso neto, dimensiones de las cajas, entre otros.
              

    p.mb-5 Del mismo modo, estos embalajes deben pasar acompañados de unos símbolos en particular para el marcado de carga a desplazar. Y su trascendencia radica en que así se resuelven los problemas de diferencias de idiomas o analfabetismo de estibadores y consignatarios. Además, hay normas de manipulación que deben estar escritas en las lenguas comúnmente usadas en el comercio mundial o en la lengua de la región de destino.
    
    .cajon.color-acento-contenido.p-5.mb-5
      .row
        .col-lg-5
          p La organización ISO ha desarrollado un lenguaje sencillo por medio de imágenes representadas en íconos que logran informar sobre el manejo, manipulación y gestión de las mercancías. Estas imágenes se definen como una instrucción rigurosa y determinante en el procedimiento de la carga en cada una de las latitudes de todo el planeta. Al final, ya que la mayor parte de posibles daños e incidencias sufridas en el embalaje a lo largo de su tiempo de repartición acostumbran a darse a lo largo de su manipulación y más justamente a lo largo del proceso de carga y descarga, es fundamental conocer su sentido y, a la vez, los recursos del embalaje.
        .col-lg-7
          figure
            img.nW.centered(src='@/assets/curso/t1-nn1.png', alt='icono decorativo')          

    p.mb-5 Para complementar el tema, es importante conocer la simbología de unidades de carga, la que se describe a continuación: 

    .row.mb-5.justify-content-center
      .col-lg-8
        .tabla-c
          table
            thead
              th.text-center.mw200 Símbolo
              th.text-center.b-left Instrucción
              th.mw200.text-center.b-left Significado
            tbody
              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic1.svg', alt='icono decorativo')    
                td.b-left  No usar carretilla elevadora
                td.b-left  La carga no se debe manipular con carretilla elevadora.
              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic2.svg', alt='icono decorativo')    
                td.b-left  Colocar mordazas aquí
                td.b-left  Colocar las abrazaderas en los lados que se indica para manipular la carga.
              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic3.svg', alt='icono decorativo')    
                td.b-left  No colocar mordazas aquí
                td.b-left  No colocar las abrazaderas en los lados que se indica al manipular el embalaje.
              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic4.svg', alt='icono decorativo')    
                td.b-left  Apilamiento limitado
                td.b-left  Indica el peso máximo posible sobre la unidad de carga.
              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic5.svg', alt='icono decorativo')    
                td.b-left  Apilamiento limitado por número
                td.b-left  Número máximo de embalajes iguales que se pueden apilar (n=número máx.).
              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic6.svg', alt='icono decorativo')    
                td.b-left  No apilar
                td.b-left  No se debe apilar ninguna otra carga encima.

              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic7.svg', alt='icono decorativo')    
                td.b-left  
                  p Eslingas aquí
                  figure
                    img.nW(src='@/assets/curso/t1-ic7-1.svg', alt='icono decorativo') 
                td.b-left  Indica dónde se deben emplazar las eslingas para elevar la carga.
                
              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic8.svg', alt='icono decorativo')    
                td.b-left  Límites de temperatura
                td.b-left  Límites de temperatura entre los que se debe conservar y manipular la carga.

              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic9.svg', alt='icono decorativo')    
                td.b-left  Frágil
                td.b-left  El contenido del embalaje es frágil y se debe manejar con precaución.

              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic10.svg', alt='icono decorativo')    
                td.b-left  No usar garfios
                td.b-left  No se pueden usar garfios en el manejo de la carga.
              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic11.svg', alt='icono decorativo')    
                td.b-left  Mantener vertical
                td.b-left  La unidad de carga se debe mantener en posición vertical.
              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic12.svg', alt='icono decorativo')    
                td.b-left  Proteger de la luz solar
                td.b-left  La carga no debe exponerse a la luz solar u otras fuentes de calor.

              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic13.svg', alt='icono decorativo')    
                td.b-left  Mantener a resguardo de la lluvia
                td.b-left  La carga debe mantenerse en un ambiente seco.

              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic14.svg', alt='icono decorativo')    
                td.b-left  Centro de gravedad
                td.b-left  Indica el centro de gravedad de la unidad de carga.

              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic15.svg', alt='icono decorativo')    
                td.b-left  No rodar ni inclinar
                td.b-left  La carga no se debe rodar ni inclinar o balancear.

              tr
                td 
                  figure
                    img.nW.centered(src='@/assets/curso/t1-ic16.svg', alt='icono decorativo')    
                td.b-left  No manipular con las horquetas/horquillas en esta cara
                td.b-left  Caras de la unidad de carga donde no se deben colocar las horquetas/horquillas de las carretillas manuales.



  
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
