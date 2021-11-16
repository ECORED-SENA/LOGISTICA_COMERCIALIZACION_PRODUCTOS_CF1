<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos='flip-up')
      .titulo-principal__numero
        span 1
      h1 Conceptos de logística y mercancías
    .row.mb-5.slideInUp
      .col-lg-7
        .cajon-b.color-primario.p-3.mb-4
          p.mb-0  A lo largo de años, la funcionalidad logística fue considerada como una actividad rutinaria, meramente operativa y elemental para hacer llegar los productos a partir de los centros de producción a los de uso o consumo. A partir de esta visión, la funcionalidad logística en la organización era contemplada solo como un centro generador de costes sin capacidad de diferenciación (Ballou, 2004). 
        p.mb-3  En el campo académico, su análisis se realizaba a partir del punto de vista industrial o técnica, en busca de modelos que permitieran optimizar espacios, planear distribuciones y minimizar costes. La globalización de la economía y la consiguiente apertura de nuevos mercados distanciados geográficamente fueron cambiando la percepción de la funcionalidad logística hacia novedosas magnitudes, en las que la funcionalidad logística permitía ciertas ventajas competitivas fundamentadas en la reducción de los tiempos de entrega o en la mejora de costes.
        p.mb-3  Sin embargo, a pesar de estas ventajas, la funcionalidad logística seguía siendo una actividad menor en la administración empresarial. En la década de 1960 la administración logística, siguiendo los postulados de marketing, consigue una orientación hacia el comprador que se materializa en dar un servicio logístico ajustado a las necesidades y requisitos de este, y que posibilite su satisfacción. A partir de allí, la funcionalidad logística comienza a ser tratada como una actividad de carácter estratégico capaz de crear ventajas competitivas que diferencian a la organización de la competencia. A continuación, se relacionan aspectos importantes sobre el proceso de logística.
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

            .tarjeta.color-secundario.p-3.shadow-box(x="14%" y="27%" numero="1")
              .h5.mb-2 Medios de transporte
                ul.lista-ul
    
    
    p.mb-5  En la logística se asocian varios recursos innovadores que mediante una combinación eficiente ofrecen al cliente un nivel elevado de calidad y confiabilidad buscando soluciones y de esta forma incrementan la competitividad y sostenimiento de la empresa. La experiencia y la competencia permiten encontrar soluciones acordes a cada necesidad. 
    .row.mb-5.justify-content-center
      .col-lg-12
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/t1-i2.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4.shadow-box
            p.mb-0.text-bold El término mercancía se define como cualquier bien o producto que se puede comercializar. Hay una extensa varievdad de objetos y materiales considerados como mercancías, que son transportados nacional e internacionalmente, con fines comerciales; por lo cual se debieron clasificar para que los transportistas logren realizar entregas con éxito. El cuidado en el funcionamiento de las cargas es demasiado fundamental en la logística, conforme el trato que reciba la misma, debido a que podría provocar una variación del producto para el cliente. De esta forma, las cargas tienen que clasificarse de acuerdo con el tipo o estado físico de la mercancía, para asegurar su adecuado transporte y entrega. 

    p.mb-5 Los productos y mercancías, de acuerdo con su tipo, se clasifican de la siguiente forma: 

    .neg-margin-x.bg-sliders.py-0.mb-5
      .tarjeta.p-4.mb-5.r-0
        SlyderA(tipo="a")
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0
              .h4 Carga general:
              p Se trata de los productos transportados en pequeñas unidades independientes. Ejemplo: cajas, frascos y botellas.
            .col-md-4
              figure
                img(src='@/assets/curso/t1-s0.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0
              .h4 Carga suelta:
              p Compuesta por productos sueltos por unidades de tamaño, manipulados y transportados como unidades separadas. Ejemplo: llantas, madera y cilindros.
            .col-md-4
              figure
                img(src='@/assets/curso/t1-s1.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0
              .h4 Carga paletizada:
              p Compuesta por una cantidad de productos agrupados sobre una estiba para ser almacenada y transportada en una operación más sencilla. 
            .col-md-4
              figure
                img(src='@/assets/curso/t1-s3.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0
              .h4 Carga contenedorizada:
              p Es el tipo de carga que utiliza el contenedor, como unidad de transporte, que permite el traslado seguro e inviolable de la mercancía. 
            .col-md-4
              figure
                img(src='@/assets/curso/t1-s4.png', alt='imagen decorativa')

    p.mb-5  Teniendo en cuenta el tipo de mercancía, los productos y mercancías, también se clasifican de acuerdo con su naturaleza:
    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-primario.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/t1-p1.png', alt='icono decorativo')
        .h2.text-center Carga peligrosa
        p Son los productos o sustancias que, al ser transportados, representan un riesgo para la salud, el medio ambiente, entre otros. Las mercancías peligrosas se la clasifican por el peligro que estas tienen, por la posibilidad de contaminar, su estructura y/o su nivel de peligrosidad. Para la diferenciación de estas mercancías, hay etiquetas en el transporte que identifican los peligros que estas pueden provocar. 


      .col-md.tarjeta.color-acento-botones.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/t1-p2.png', alt='icono decorativo')
          
        .h2.text-center Carga perecedera
        p Son los productos que, expuestos a diversas temperaturas del medio ambiente, pueden deteriorarse después de un tiempo determinado; trátese de alimentos o productos sanitarios que deban seguir un control y unos parámetros técnicos dentro de la cadena de frío, etc. Dentro de los productos perecederos se encuentran las frutas y las verduras, la carne y sus derivados, los pescados y los mariscos, los productos lácteos y las flores, entre otros. Se destacan entre los   productos perecederos las verduras, frutas, carnes, pescados y lácteos entre otros.

      .col-md.tarjeta.color-acento-contenido.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/t1-p3.png', alt='icono decorativo')
        .h2.text-center Carga frágil
        p Son todas aquellas mercancías que, por sus condiciones de elaboración, deben tener un cuidado especial en su transporte, pues se pueden averiar por manipulación inadecuada. En este grupo se identifican los elementos de cristal, esculturas,  productos de precisión, entre otros.


    #t_1_1.titulo-segundo.color-secundario
      h2 1.1. Medios de transporte
    p.mb-5  Cada tipo de mercancía debe acomodarse a una clase de transporte que sea compatible con su naturaleza, medidas físicas o sus características y las precauciones para su movilización. El concepto medio de transporte comprende el conjunto de técnicas de transporte y dispositivos que se usan en el traslado de productos o mercancías de un lugar a otro, incluida la manera a pie. Los medios de transportes usados para la distribución de productos son el avión, el camión, el tren y el buque. A continuación, se conocerán algunos medios:
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row(titulo="Ciclo del pedido")
        .col-md-8.mb-4.mb-md-0
          p Puede definirse como el tiempo transcurrido entre el instante en que se levanta un pedido de comprador, una orden de compra o una solicitud de servicio y el instante en que el producto o servicio es recibido por el comprador. 
        .col-md-4
          figure
            img.nW(src='@/assets/curso/t1-a1.png', alt='icono decorativo')

      .row(titulo="Tipos de aviones")
        .col-md-8.mb-4.mb-md-0
          p El tipo de aeronave usado para transporte de carga es el 
            span.text-bold-text-color avión carguero, 
            | dedicado al transportar todo tipo de mercancías contenerizadas o carga general y correspondencia. <br>Otro tipo de aeronave es el avión cisterna, que es acondicionado para transporte de gráneles líquidos. A partir del año 1919 se efectuó el primer vuelo comercial con mercancías, y la demanda del uso de aeronaves para el transporte de carga no ha dejado de crecer. Esta demanda propició el uso de contenedores aéreos y la necesidad de compatibilizar el transporte de pasajeros con la carga aérea sin olvidar que hoy en día encontramos aviones exclusivos para la carga de mercancías. 
        .col-md-4
          figure
            img.nW(src='@/assets/curso/t1-a2.png', alt='icono decorativo')

      .row(titulo="Camión")
        .col-md-8.mb-4.mb-md-0
          p.mb-3  Medio sobre el que se sustenta el transporte de carretera es el camión, transporte compuesto por la unidad tractora y la caja que arrastra, llamada semirremolque. El camión podría ser duro, sin que se logren dividir ambos recursos y por lo que la carga reposa sobre el chasis o el articulado.
          p.mb-3  El remolque compuesto por una plataforma sin sistema de tracción propia, es arrastrado por una unidad tractora en la que se ensambla y reposa parcialmente, transfiriendo una sección mayoritaria de su masa y carga. No tiene eje delantero y puede contar con 1, 2 o 3 ejes traseros.
          //-- Aqui viene la info de tipos de camiones
          
        .col-md-4
          figure
            img.nW(src='@/assets/curso/t1-a3.png', alt='icono decorativo')


      .row(titulo="Tren")
        .col-md-8.mb-4.mb-md-0
          p.mb-3  Medio de transporte especializado con vagones sellados, sillas y vagones planos con contenedores. Principalmente cargan mercancías a granel como carbón, granos, además los hay como planchones para cargar contenedores, por una vía férrea.
          p.mb-3  La máquina o unidad tractora que arrastra los vagones puede consumir energía eléctrica o  combustible para producir la fuerza esencial para la tracción.
          
        .col-md-4
          figure
            img.nW(src='@/assets/curso/t1-a2.png', alt='icono decorativo')





    Separador
    br
    br
    #t_1_2.titulo-segundo.color-secundario
      h2 1.2. Simbología de manejo de carga


















    //- El componente "Muestras" tiene las aplicaciones de todos los componentes de la base
    //- se encuentra en src/components/Muestras.vue
    //- Una vez el componente "Muestras" no se necesite 
    //- Se debe borrar el "import Muestras from '../components/Muestras'" y en "components" en "<script"
    //- esto evitará que se compile en la carpeta final de distribución
    Muestras
  
</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
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
