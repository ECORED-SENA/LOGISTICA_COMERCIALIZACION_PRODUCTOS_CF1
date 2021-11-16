<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido(data-aos='flip-up')
      .titulo-principal__numero
        span 5
      h1 Clasificación de mercancías

    .row.mb-5.align-items-center.justify-content-center
      .col-lg-8.slideInLeft
        .cajon-b.color-primario.p-4.mb-4
          p.mb-0  <b>En cualquier centro de distribución la fase de preparación de pedidos es una de las más relevantes.</b> En esta se asegura que el producto sea el conveniente y que su preparación y embalaje sean los adecuados para llegar en perfectas condiciones a su destino final. Por consiguiente, si la fase de preparación de demandas en pedidos no es eficiente, la productividad de la organización y la vivencia del comprador tienen la posibilidad de verse afectadas.        
      .col-lg-4
        figure
          //--img.nW.centered(src='@/assets/curso/t5-i1.jpg' alt='imagen decorativa')


    

    #t_5_1.titulo-segundo.color-secundario
      h2 5.1. Manipulación de mercancías 








    Separador
    br
    br
    #t_5_2.titulo-segundo.color-secundario
      h2 5.2. Tipos de almacenamiento   




</template>

<script>
export default {
  name: 'Tema5',
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
