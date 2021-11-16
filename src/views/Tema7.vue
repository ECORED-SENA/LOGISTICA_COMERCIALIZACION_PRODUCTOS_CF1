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
          p.mb-0  Hoy por hoy, el mercado tecnológico alrededor de la gestión de almacenes y las operaciones de picking, específicamente, es variado y se orienta a ofrecer respuestas a las necesidades concretas de las organizaciones de los más varios sectores y con los más diversos productos. 
        p.mb-3  Si bien se debería tener en cuenta que hay diversas herramientas que pretenden apresurar, optimizar y hacer eficientes los procesos de picking de cada compañía, cabe subrayar que no existe un sistema mundial ni fórmula mágica, debido a que cada caso se debería examinar de manera personalizada. De poco sirven los instrumentos si no se cuenta con un sistema de administración que coordine los movimientos de manera idónea.        
      .col-lg-4.slideInRight
        figure
          img.nW.centered(src='@/assets/curso/t7-i1.jpg' alt='imagen decorativa')
    

































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
