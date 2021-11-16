<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido(data-aos='flip-up')
      .titulo-principal__numero
        span 4
      h1 Indicadores de logística - KPI (Key Performance Indicators)


    .row.mb-5
      .col-lg-7.slideInLeft
        p.mb-3  Los KPI o indicadores de gestión, <i>Key Performance Indicators</i> por sus siglas en inglés, no es una tarea fácil como se podría pensar, debido al hecho de que hay tantas variaciones diferentes de la definición de un KPI disponibles en la literatura escrita sobre este tema. Generalmente se encuentra un enfoque más concreto, más bien operativo, de los diferentes conceptos; los KPI deberían ser herramientas prácticas más que discursivas. 
        p.mb-4  Aquí se retoma lo escrito por Kelvin, 
        .bloque-texto-d.color-secundario.p-4.mb-4
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left
            h3.text-regular lo que no se puede definir no se puede medir, lo que no se puede medir no se pueden mejorar, lo que no se puede mejorar se puede deteriorar
            i.fas.fa-quote-right
          .bloque-texto-d__autor 
            .h5.mb-0 - Lord, 2008

        p  De acuerdo con lo anterior, un KPI es una medida que evalúa cómo una empresa ejecuta su visión estratégica. Este término se refiere a cómo una estrategia interactiva, se integra en la estrategia de la empresa en su conjunto, por ello es importante que todos los implicados en ella estén de acuerdo en lo que representa la estrategia y cómo se interpretan.

      .col-lg-5.slideInRight
        figure
          img.nW.centered(src='@/assets/curso/t4-i1.svg' alt='imagen decorativa')

    .row.mb-5.justify-content-center
      .col-lg-10
        //-- Auqui viene el bloque para descarga

    p.mb-5  Un KPI, o un grupo de KPI (ya que un KPI raramente existe por sí solo), forma un tipo de lenguaje que puede ser utilizado, en el caso de que la estrategia de la empresa no sea la misma y no solo para medir la eficacia de los proyectos, sino también para indicar sus posibilidades de éxito. Un KPI es una característica fundamental y sin un acuerdo sobre su significado, se convertiría en una fuente de caos en lugar de ser una fuente de acción a seguir.

    .row.mb-5.justify-content-center
      .col-lg-12(data-aos='flip-up')
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/t4-i2.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4.shadow-box
            p.mb-0 Los esfuerzos que se invierten en cualquier proyecto de KPI representan la base de las mediciones utilizadas para analizar el rendimiento de cualquier actividad dentro de la empresa. Los KPI solo son relevantes si pueden mostrar el camino hacia el éxito, un camino con muchas acciones diferentes con el objetivo de intentar mejorar un esfuerzo sostenido de optimización. Es necesario, entonces, destacar el hecho de que hay un límite en la forma en que cada uno de los puntos de optimización puede mejorar. También se han visto los efectos de la anulación donde el aumento de la eficacia de una acción concreta parecía producirse solo a favor de otra acción.
    
    p.mb-5  Entre los indicadores más utilizados se deben tener en cuenta: el costo de transporte, costo por envío de acuerdo con su naturaleza, costo de almacenamiento, entregas a tiempo y los pedidos devueltos. Atendiendo a lo anterior, se pueden reconocer los elementos de un indicador de gestión a continuación: 

    .row.mb-5.justify-content-center  
      .col-lg-6
        figure(data-aos='flip-left')
          img.nW.centered(src='@/assets/curso/t4-i3.jpg' alt='imagen decorativa')
      .col-lg-4(data-aos='slide-right')
        ol.lista-ol--cuadro.lista-ol--separador
          li 
            .lista-ol--cuadro__vineta
              span
                i.fas.fa-chevron-right
            | Índice.     
          li 
            .lista-ol--cuadro__vineta
              span
                i.fas.fa-chevron-right
            | Alcance.
          li 
            .lista-ol--cuadro__vineta
              span
                i.fas.fa-chevron-right
            | Meta.                 
          li 
            .lista-ol--cuadro__vineta
              span
                i.fas.fa-chevron-right
            | Responsable.
          li 
            .lista-ol--cuadro__vineta
              span
                i.fas.fa-chevron-right
            | Forma de cálculo.
          li 
            .lista-ol--cuadro__vineta
              span
                i.fas.fa-chevron-right
            | Unidad.
          li 
            .lista-ol--cuadro__vineta
              span
                i.fas.fa-chevron-right
            | Periodicidad.







</template>

<script>
export default {
  name: 'Tema4',
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
