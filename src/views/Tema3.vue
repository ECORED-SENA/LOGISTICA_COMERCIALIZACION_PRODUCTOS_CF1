<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido(data-aos='flip-up')
      .titulo-principal__numero
        span 3
      h1 Selección de mercancías
    .row.mb-5.align-items-center.justify-content-center
      .col-lg-8.slideInLeft
        .cajon-b.color-primario.p-4.mb-4
          p.mb-0  <b>En cualquier centro de distribución la fase de preparación de pedidos es una de las más relevantes.</b> En esta se asegura que el producto sea el conveniente y que su preparación y embalaje sean los adecuados para llegar en perfectas condiciones a su destino final. Por consiguiente, si la fase de preparación de demandas en pedidos no es eficiente, la productividad de la organización y la vivencia del comprador tienen la posibilidad de verse afectadas.        
      .col-lg-4
        figure
          img.centered(src='@/assets/curso/t3-i1.png' alt='imagen decorativa')
    
    .row.mb-5.justify-content-center
      .col-lg-10.slideInRight
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/t3-i2.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4.shadow-box
            p.mb-0 Para seleccionar la mercancía de manera adecuada, es necesario responder a la siguiente pregunta ¿cómo se relacionan el <i>picking</i> y el <i>packing</i>? Aunque son dos procesos diferentes, ellos son complementarios, ya que el <i>picking</i> prepara el pedido antes de ser empacado y después, el <i>packing</i> se encarga del embalaje del producto.






    #t_3_1.titulo-segundo.color-secundario
      h2 3.1 Solicitud de pedidos y despacho
    p.mb-5  Crear una <i>picking list</i> es la mejor forma de optimizar la preparación de pedidos. Las actividades manuales de preparación de pedidos en el centro de distribución son principalmente trabajos de clasificación y ordenación por destinos de acuerdo con la solicitud del cliente. Las actividades consisten en: levantar, mover, recoger, poner, embalaje y otros trabajos típicos. El proceso de <i>picking</i> manual para comparar las actividades físicas y actividades cognitivas, se trata de un paso que es fácil, sin embargo, requiere de atención y concentración; habilidades cognitivas incluidas.
    .neg-margin-x.bg-curved.mb-0
      .row.justify-content-center
        .col-lg-7
          PasosA.color-secundario.mb-5(tipo="n")
            .row
              .col-md-12.mb-4.mb-md-0
                p En el primer paso, <b>los preparadores toman la lista de pedidos y la leen</b>, al mismo tiempo que cuentan la cantidad de artículos. 
            .row
              .col-md-12.mb-4.mb-md-0
                p A continuación, <b>comienzan a moverse con el carro para colocar en él los artículos</b>, mientras buscan el lugar de recogida.                 
            .row
              .col-md-12.mb-4.mb-md-0
                p Después de encontrar la ubicación de <i>picking</i>, <b>se dirigen al lugar y recogen los artículos de la estantería de almacenamiento</b>, identificando aquellos que van a ser clasificados, y a la vez contando el número de artículos.                 
        .col-lg-4
          figure
            img.nW(src='@/assets/curso/t3-i4.png' alt='imagen decorativa')

    .neg-margin-x.bg-curved2.mb-5.py-0
      .row.justify-content-center
        .col-lg-7
          ImagenInfografica.color-secundario.mb-5
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/t3-info1.svg', alt='Despacho de mercancias')

            .tarjeta.color-secundario.p-3.shadow-box(x="14%" y="27%" numero="1")
              .h5.mb-2 Medios de transporte
              ul.lista-ul
                li
                  i.fas.fa-check
                  p.mb-0 Simbología de la carga
                li
                  i.fas.fa-check
                  p.mb-0 Ficha técnica

            .tarjeta.color-secundario.p-3.shadow-box(x="49%" y="6%" numero="2")
              .h5.mb-2 Especificaciones de la mercancía
              ul.lista-ul
                li
                  i.fas.fa-check
                  p.mb-0 Tipo
                li
                  i.fas.fa-check
                  p.mb-0 Naturaleza
                li
                  i.fas.fa-check
                  p.mb-0 Característica

            .tarjeta.color-secundario.p-3.shadow-box(x="49%" y="80%" numero="4")
              .h5.mb-2 Herramientas de comunicación
              ul.lista-ul
                li
                  i.fas.fa-check
                  p.mb-0 Terminales de radiofrecuencia
                li
                  i.fas.fa-check
                  p.mb-0 Código de barras
                li
                  i.fas.fa-check
                  p.mb-0 Sistemas de voz    

            .tarjeta.color-secundario.p-3.shadow-box(x="14%" y="63%" numero="5")
              .h5.mb-2 Normativa de producto
              ul.lista-ul
                li
                  i.fas.fa-check
                  p.mb-0 Familia de producto
                li
                  i.fas.fa-check
                  p.mb-0 Procedimiento
            .tarjeta.color-secundario.p-3.shadow-box(x="85.5%" y="63%" numero="3")
              .h5.mb-2 Procesos de recibo y despacho
              ul.lista-ul
                li
                  i.fas.fa-check
                  p.mb-0 <i>Picking</i>
                li
                  i.fas.fa-check
                  p.mb-0 <i>Packing</i>
    
    .row.mb-5.justify-content-center
      .col-lg-8
        .cajon.color-acento-contenido.p-4
          p.mb-0  Las actividades de desplazamiento y recogida continúan hasta que se acumulan todos los productos de la lista de pedidos. Aunque se realice el mismo pedido, el rendimiento del <i>picking</i> puede variar en función de las actividades de cognición del preparador; muchos errores de preparación de pedidos se producen al contar o identificar los artículos. 


    p.mb-5  Es necesario tener presente que el <i>picking</i>, involucra cuatro etapas; estas son:

    .row.mb-5.justify-content-center
      .col-lg-10
        PasosA.color-primario.mb-5(tipo="n")
          .row
            .col-md-9.mb-4.mb-md-0
              h4 Preparación
              ul.lista-ul
                li
                  i.fas.fa-angle-right
                  p.mb-0 Recolección de datos y entrega de documentos y órdenes clasificadas.
                li
                  i.fas.fa-angle-right
                  p.mb-0 Preparación de equipos requeridos.            
            .col-md-3
              figure
                img(src='@/assets/curso/t3-ic1.svg', alt='Imagen decorativa')

          .row
            .col-md-3.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/t3-ic2.svg', alt='Imagen decorativa')
            .col-md-9.text-left
              .h4 Recorrido
              ul.lista-ul
                li
                  i.fas.fa-angle-right
                  p.mb-0 Desde la zona de operaciones hasta el punto donde se ubica el producto.
                li
                  i.fas.fa-angle-right
                  p.mb-0 Desde el punto de ubicación al siguiente y así sucesivamente.
                li
                  i.fas.fa-angle-right
                  p.mb-0 Regreso a la zona de operaciones. Se utiliza el concepto de secuenciación para garantizar el tiempo óptimo para este proceso.
          .row
            .col-md-9.mb-4.mb-md-0
              h4 Extracción
              ul.lista-ul
                li
                  i.fas.fa-angle-right
                  p.mb-0 También llamado retiro, es la actividad de  posicionarse donde se encuentra el producto a piso o en altura, hacer su extracción, recuento de producto y devolución sobrante si es el caso.
         
            .col-md-3
              figure
                img(src='@/assets/curso/t3-ic3.svg', alt='Imagen decorativa')

          .row
            .col-md-3.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/t3-ic4.svg', alt='Imagen decorativa')
            .col-md-9.text-left
              .h4 Verificación del pedido preparado
              ul.lista-ul
                li
                  i.fas.fa-angle-right
                  p.mb-0 Control, embalaje, acondicionado en cajas, precintado, pesaje y etiquetado.
                li
                  i.fas.fa-angle-right
                  p.mb-0 Traslado a zona de expedición y clasificación por transportistas en destino.
                li
                  i.fas.fa-angle-right
                  p.mb-0 Elaboración del <i>packing list</i> del transportista.


    .row.mb-5.justify-content-center
      .col-lg-8
        .cajon.color-acento-contenido.p-4
          p.mb-0  <b>El segundo tiempo del recorrido denominado alistamiento o <i>picking</i>, es el más crítico.</b> Después sigue en orden de complejidad el de verificación, sin embargo, si se cuenta con la tecnología adecuada estos tiempos tienden a reducirse de manera significativa, optimizando el proceso.

    p.mb-5  El despacho de mercancías es una fase de la logística cuyo propósito es que el producto salga de almacén y sea entregado a su destino final, a tiempo y en excelentes condiciones. En esta parte las principales tareas son: 

    .neg-margin-x.bg-curved.mb-0
      .row.justify-content-center.align-items-center
        .col-lg-7
          PasosA.color-secundario.mb-5(tipo="n")
            .row
              .col-md-12.mb-4.mb-md-0
                p <b>Asegurar</b> una óptima administración de mercancías previamente del despacho.
            .row
              .col-md-12.mb-4.mb-md-0
                p <b>Planificar</b> las entregas a hacer a lo largo del día.               
            .row
              .col-md-12.mb-4.mb-md-0
                p <b>Comprobar</b> que cada producto y su documentación permanecen en orden.        
            .row
              .col-md-12.mb-4.mb-md-0
                p <b>Cargar</b> la mercancía en el transporte adecuado.
            .row
              .col-md-12.mb-4.mb-md-0
                p <b>Monitorear</b> el desarrollo del transporte logístico.  
        
        .col-lg-4
          figure
            img.nW(src='@/assets/curso/t3-i5.png' alt='imagen decorativa')
    p.mb-5  A lo largo del despacho de mercancías hay probables errores que pueden impedir que se concrete la entrega al comprador, de aquí el valor de conocer cuáles son para evitarlos en la práctica. Al no monitorear las cambiantes externas a lo largo del despacho de mercancías, como resultado, se tendrá que:
    .row.mb-5
      .col-lg-6
        figure
          img(src='@/assets/curso/t3-i6.svg' alt='imagen decorativa')
      .col-lg-6
        ol.lista-ol--cuadro.lista-ol--separador
          li 
            .lista-ol--cuadro__vineta
              span
                i.fas.fa-chevron-right
            | Realmacenar la carga.
          li 
            .lista-ol--cuadro__vineta
              span
                i.fas.fa-chevron-right
            | Reprocesar el despacho de mercancías.
          li 
            .lista-ol--cuadro__vineta
              span
                i.fas.fa-chevron-right
            | Reenviar las peticiones.

    p.mb-5  Lo anterior genera precios extras por entregas fallidas y una mala fama del servicio de entrega; por ello el objetivo es reducir el volumen de falla de servicio al comprador y aumentar la confianza del mismo a lo largo del despacho de mercancías.   




    .row.mb-5.justify-content-center
      .col-lg-8
        .cajon.color-acento-contenido.p-4
          p.mb-0  Una compañía que no hace seguimiento a sus transportistas a lo largo del despacho de mercancías desconoce cómo se desenvuelve el transporte, las rutas logísticas y los procesos de entrega. Por esta razón, las empresas tienen que minimizar al mínimo sus errores de logística, y para lograrlo necesitan adoptar tecnologías para la administración de entregas y despacho de mercancías, así se logra optimizar todos los procesos en la última milla.


    Separador
    br
    br
    #t_3_2.titulo-segundo.color-secundario
      h2 3.2 Sellos de seguridad  
    
    .row.mb-5.align-items-center.justify-content-center
      .col-lg-8.slideInLeft
        .cajon-b.color-primario.p-4.mb-4
          p.mb-0  Los sellos de seguridad para transporte son una pieza de alta tecnología, indispensable para el negocio mundial. Dichos sellos son una pieza desarrollada de metal y plástico, diseñado para cerrar el ingreso de un contenedor con productos o bienes; a diferencia de, ejemplificando, un candado, un sello de seguridad podría ser roto y no solamente podría ser roto, sino que se necesita que se abra para consumar su funcionalidad. En otras palabras, el sello únicamente sugiere en qué momento debería ser abierto por una persona autorizada. Por esa razón los sellos fueron creados con el fin de dejar prueba de todo intento de apertura no autorizado.       
        p.mb-3  Esta característica de los sellos para transporte se complementa con su foliado impreso. Los sellos de estabilidad reciben un folio impreso en láser o <i>hot-stamping</i>. Este folio en números continuos y códigos de barras es primordial. Al poner sellos continuos en contenedores de productos, cajas de tráileres y otros recipientes de productos, se garantiza un orden logístico de empaquetado, de esta forma la compañía de transporte puede estar segura de que los objetos que guardó permanecen incólumes al abrir el sello. Al conservar un orden numérico, se garantiza que ningún contenedor falta; esto no únicamente incrementa la estabilidad, sino que ayuda a tener un óptimo orden de transporte.
      .col-lg-4
        figure
          img.nW.centered(src='@/assets/curso/t3-i7.png' alt='imagen decorativa')

    p.mb-5  Entre los principales sellos de seguridad se encuentran:
    .row.mb-5.justify-content-center.custom-table-cards
      .col-md-6.col-lg-4.tarjeta--tabla.justify-content-center
        .h2.text-center Alta seguridad
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/t3-c1.png' alt='AvatarTop')
        
      .col-md-6.col-lg-4.tarjeta--tabla
        .h2.text-center Sellos de plástico
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/t3-c2.png' alt='AvatarTop')
        br
        
      .col-md-6.col-lg-4.tarjeta--tabla
        .h2.text-center Sellos metálicos         
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/t3-c3.png' alt='AvatarTop')

      .col-md-6.col-lg-4.tarjeta--tabla
        .h2.text-center Sellos de cable
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/t3-c4.png' alt='AvatarTop')

      .col-md-6.col-lg-4.tarjeta--tabla
        .h2.text-center Etiqueta de seguridad       
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/t3-c5.png' alt='AvatarTop')


</template>

<script>
export default {
  name: 'Tema3',
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
