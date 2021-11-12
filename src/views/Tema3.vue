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
          img.nW.centered(src='@/assets/curso/t3-i1.png' alt='imagen decorativa')
    
    .row.mb-5.justify-content-center
      .col-lg-10.slideInRight
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/t3-i2.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4.shadow-box
            p.mb-0.text-bold Para seleccionar la mercancía de manera adecuada, es necesario responder a la siguiente pregunta ¿cómo se relacionan el <i>picking</i> y el <i>packing</i>? Aunque son dos procesos diferentes, ellos son complementarios, ya que el <i>picking</i> prepara el pedido antes de ser empacado y después, el packing se encarga del embalaje del producto.






    #t_3_1.titulo-segundo.color-secundario
      h2 3.1. Solicitud de pedidos y despacho
    p.mb-5  Crear una <i>Picking List</i> es la mejor forma de optimizar la preparación de pedidos. Las actividades manuales de preparación de pedidos en el centro de distribución son principalmente trabajos de clasificación y ordenación por destinos de acuerdo con la solicitud del cliente. Las actividades consisten en: levantar, mover, recoger, poner, embalaje y otros trabajos típicos. El proceso de <i>picking manual</i> para comparar las actividades físicas y actividades cognitivas, se trata de un paso que es fácil, sin embargo, requiere de atención y concentración; habilidades cognitivas incluidas.
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
                p Después de encontrar la ubicación de picking, <b>se dirigen al lugar y recogen los artículos de la estantería de almacenamiento</b>, identificando aquellos que van a ser clasificados, y a la vez contando el número de artículos.                 


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

            .tarjeta.color-secundario.p-3.shadow-box(x="85.5%" y="27%" numero="2")
              .h5.mb-2 Indicadores de gestión
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

            .tarjeta.color-secundario.p-3.shadow-box(x="14%" y="63%" numero="3")
              .h5.mb-2 Normativa de producto
              ul.lista-ul
                li
                  i.fas.fa-check
                  p.mb-0 Familia de producto
                li
                  i.fas.fa-check
                  p.mb-0 Procedimiento
            .tarjeta.color-secundario.p-3.shadow-box(x="85.5%" y="63%" numero="4")
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
          p.mb-0  Las actividades de desplazamiento y recogida continúan hasta que se acumulan todos los productos de la lista de pedidos. Aunque se realice el mismo pedido, el rendimiento del picking puede variar en función de las actividades de cognición del preparador; muchos errores de preparación de pedidos se producen al contar o identificar los artículos. 


    p.mb-5.text-bold  Es necesario tener presente que el picking, involucra cuatro etapas; estas son:

    .row.mb-5.justify-content-center
      .col-lg-10
        PasosA.color-primario.mb-5(tipo="n")
          .row
            .col-md-9.mb-4.mb-md-0
              h4 Preparación
              ul.lista-ul
                li
                  i.fas.fa-check
                  p.mb-0 Recolección de datos y entrega de documentos y órdenes clasificadas.
                li
                  i.fas.fa-check
                  p.mb-0 Preparación de equipos requeridos.            
            .col-md-3
              figure
                img(src='@/assets/curso/t3-ic1.svg', alt='Imagen decorativa')

          .row
            .col-md-3.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/t3-ic2.svg', alt='Imagen decorativa')
            .col-md-9
              .h4 Recorrido
              ul.lista-ul
                li
                  i.fas.fa-check
                  p.mb-0 Desde la zona de operaciones hasta el punto donde se ubica el producto.
                li
                  i.fas.fa-check
                  p.mb-0 Desde el punto de ubicación al siguiente y así sucesivamente.
                li
                  i.fas.fa-check
                  p.mb-0 Regreso a la zona de operaciones., se utiliza el concepto de secuenciación para garantizar el tiempo óptimo para este proceso.








    Separador
    br
    br
    #t_3_2.titulo-segundo.color-secundario
      h2 3.2. Sellos de seguridad  




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
