<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido(data-aos='flip-up')
      .titulo-principal__numero
        span 7
      h1 Herramientas de comunicación

    .row.mb-5.align-items-center.justify-content-center
      .col-lg-8.slideInLeft
        .cajon-b.color-primario.p-4.mb-4
          p.mb-0.text-bold  Hoy por hoy, el mercado tecnológico alrededor de la gestión de almacenes y las operaciones de <i>picking</i>, específicamente, es variado y se orienta a ofrecer respuestas a las necesidades concretas de las organizaciones de los más variados sectores y con los más diversos productos. 
        p.mb-3  Si bien se debería tener en cuenta que hay diversas herramientas que pretenden apresurar, optimizar y hacer eficientes los procesos de <i>picking</i> de cada compañía, cabe subrayar que no existe un sistema mundial ni fórmula mágica, debido a que cada caso se debería examinar de manera personalizada. De poco sirven los instrumentos si no se cuenta con un sistema de administración que coordine los movimientos de manera idónea.        
      .col-lg-4.slideInRight
        figure
          img.nW.centered(src='@/assets/curso/t7-i1.jpg' alt='imagen decorativa')
    

    p.mb-5  La tendencia mundial en logística como en otras zonas muestra hacia la automatización de los procesos, el <i>picking</i> no es la exclusión. En esta línea, se resaltan tres tecnologías en especial: 
    .neg-margin-x.bg-curved.mb-4
      .row.mb-5.justify-content-center
        .col-xs-6.col-md-6.col-xl-3.mb-4.mb-xl-0
          .tarjeta-numerada.color-secundario.p-5.h-100(data-aos='flip-left')
            .tarjeta-numerada__numero
              .h2 1
            .h3.text-center Terminales de radiofrecuencia.
        .col-xs-6.col-md-6.col-xl-3.mb-4.mb-xl-0.h-100(data-aos='flip-left')
          .tarjeta-numerada.color-acento-contenido.p-5
            .tarjeta-numerada__numero
              .h2 2
            .h3.text-center Sistemas de reconocimiento de voz.

        .col-xs-6.col-md-6.col-xl-3.mb-4.mb-xl-0(data-aos='flip-left')
          .tarjeta-numerada.color-primario.p-5
            .tarjeta-numerada__numero
              .h2 3
            .h3.text-center Lectores manuales de código de barras.

    p.mb-5  Todas ellas tienen sus ventajas y sus desventajas; y cada una constituye la solución correcta para un definido caso y entorno operacional, sin perjuicio de que logren aplicarse.
    p.mb-5  Por otro lado, las evidentes diferencias y diversas propiedades de cada tecnología, involucran que, anterior a ser implementadas, se deba realizar una evaluación de ciertos componentes, como, por ejemplo: la productividad de <i>picking</i> en superficies de alta densidad; independencia en la utilización de las manos a causa de los operadores, capacidad para hallar las posiciones, la función de proporcionar información o el decrecimiento de los errores de “pickeo”. Es frente a estos y otros límites que las tecnologías empiezan a marcar sus diferencias y utilidades concretas.

    .row.mb-5.justify-content-center
      .col-sm-6.col-lg-4.mb-4.mb-lg-0
        .tarjeta.color-acento-contenido.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/t7-ic1.svg', alt='imagen decorativa')
          h3.text-center Código de barras

      .col-sm-6.col-lg-4.mb-4.mb-lg-0
        .tarjeta.color-secundario.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/t7-ic2.svg', alt='imagen decorativa')
          h3.text-center Terminales de radiofrecuencia

      .col-sm-6.col-lg-4.mb-4.mb-lg-0
        .tarjeta.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/t7-ic3.svg', alt='imagen decorativa')
          h3.text-center Sistema de reconocimiento de voz


























</template>

<script>
export default {
  name: 'Tema7',
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
