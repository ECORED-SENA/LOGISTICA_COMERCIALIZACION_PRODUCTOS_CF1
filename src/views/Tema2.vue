<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.bg-foot
    .titulo-principal.color-acento-contenido(data-aos='flip-up')
      .titulo-principal__numero
        span 2
      h1 Ficha técnica de mercancías

    .row.mb-5
      .col-lg-7.slideInLeft
        .cajon-b.color-primario.p-3.mb-4
          p.mb-0  La ficha técnica es un documento en forma de sumario que contiene la descripción de las características técnicas de un objeto, material, producto o bien de manera detallada. Los contenidos varían dependiendo del producto, servicio o entidad descrita, pero en general contiene datos como el nombre, características físicas, el modo de uso o elaboración, propiedades distintivas, métodos de ensayo y especificaciones técnicas.
        p.mb-3  La preparación de la ficha técnica posibilita adecuar los productos mediante la estandarización de los productos, de esta forma se describe la calidad requerida por el comprador, además posibilita a este conocer la información técnica del producto o los productos que está adquiriendo y, así mismo, ofrecer cumplimiento a las exigencias que la ley exige en la normatividad presente; lo anterior posibilita evitar inconvenientes económicos y facilitar la verificación de calidad de producto.
      .col-lg-5.slideInRight
        figure
          img(src='@/assets/curso/t2-i1.jpg' alt='')

    .row.mb-5.justify-content-center
      .col-lg-8
        .cajon.color-secundario.p-3
          .row
            .col-lg-6   
            .col-lg-6  




















</template>

<script>
export default {
  name: 'Tema2',
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
