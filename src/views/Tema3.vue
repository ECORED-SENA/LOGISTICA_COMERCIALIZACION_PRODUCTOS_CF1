<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido(data-aos='flip-up')
      .titulo-principal__numero
        span 3
      h1 Ficha técnica de mercancías
    .row.mb-5
      

    

    #t_3_1.titulo-segundo.color-secundario
      h2 3.1. Medios de transporte







    Separador
    br
    br
    #t_3_2.titulo-segundo.color-secundario
      h2 3.2. Simbología de manejo de carga   




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
