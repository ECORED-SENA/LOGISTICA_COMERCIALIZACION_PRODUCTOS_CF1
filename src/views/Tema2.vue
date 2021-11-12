<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.bg-foot
    .titulo-principal.color-acento-contenido(data-aos='flip-up')
      .titulo-principal__numero
        span 2
      h1 Ficha técnica de mercancías

    .row.mb-5
      .col-lg-8.slideInLeft
        .cajon-b.color-primario.p-4.mb-4
          p.mb-0.text-bold  La ficha técnica es un documento en forma de sumario que contiene la descripción de las características técnicas de un objeto, material, producto o bien de manera detallada. Los contenidos varían dependiendo del producto, servicio o entidad descrita, pero en general contiene datos como el nombre, características físicas, el modo de uso o elaboración, propiedades distintivas, métodos de ensayo y especificaciones técnicas.
        p.mb-3  La preparación de la ficha técnica posibilita adecuar los productos mediante la estandarización de los productos, de esta forma se describe la calidad requerida por el comprador, además posibilita a este conocer la información técnica del producto o los productos que está adquiriendo y, así mismo, ofrecer cumplimiento a las exigencias que la ley exige en la normatividad presente; lo anterior posibilita evitar inconvenientes económicos y facilitar la verificación de calidad de producto.
      .col-lg-4.slideInRight
        figure
          img(src='@/assets/curso/t2-i1.jpg' alt='')

    .row.mb-5.justify-content-center
      .col-lg-10
        .cajon.color-acento-contenido.p-4
          .row
            .col-lg-6
              p.mb-3.p-4.text-bold  La ficha técnica de un producto es la carta de presentación de la compañía y contiene propiedades físicas y químicas relevantes y correctas que ayudan al conveniente conocimiento y uso del producto, además le da prueba que se está cumpliendo con los estándares de calidad del producto.
            .col-lg-6
              .tabla-b.color-secundario.mb-5.shadow-box
                table
                  thead
                    tr
                      th Nombre producto
                      th Pimentón molido
                  tbody
                    tr
                      td Nombre producto
                      td.b-left Pimentón molido
                    tr
                      td Nro. producto: 
                      td.b-left 32.589
                    tr
                      td Origen:
                      td.b-left España
                    tr
                      td Importador:
                      td.b-left Vilta S.A.
                    tr
                      td Peso neto:
                      td.b-left 87 grs.
                    tr
                      td Peso bruto:
                      td.b-left 152 grs.
                    tr
                      td Fecha envasado:
                      td.b-left Febrero 2018
                    tr
                      td Fecha vencimiento:
                      td.b-left Marzo 2020
                    tr
                      td Lote N°:
                      td.b-left 2036589














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
