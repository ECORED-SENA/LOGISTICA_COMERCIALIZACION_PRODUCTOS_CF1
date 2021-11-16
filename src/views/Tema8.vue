<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido(data-aos='flip-up')
      .titulo-principal__numero
        span 8
      h1 Ciclo de pedido
    .row.mb-5
      .col-lg-5
        figure
          img.nW.centered(src='@/assets/curso/t8-i1.jpg' alt='imagen decorativa')
      .col-lg-7
        p.mb-4  Los elementos y recursos del servicio al cliente tienen la posibilidad de mantener el control del manejo de la logística, se identifica dentro del criterio de tiempo del ciclo del pedido (o del servicio). 
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta color-gradientTransp")
          .row(titulo="Ciclo del pedido")
            .col-md-12.mb-4.mb-md-0
              p Puede definirse como el tiempo transcurrido entre el instante en que se levanta un pedido de comprador, una orden de compra o una solicitud de servicio y el instante en que el producto o servicio es recibido por el comprador. 
          
          .row(titulo="Periodo del pedido")
            .col-md-12.mb-4.mb-md-0
              p Tiene todos los eventos involucrados que dan forma al tiempo total solicitado para que un comprador reciba un pedido de los elementos que conforman un periodo normal del pedido de un producto. 

          .row(titulo="Recursos particulares del tiempo de periodo del pedido")
            .col-md-12.mb-4.mb-md-0
              p Son la época de transmisión, de procesamiento del pedido, del ensamblado del pedido, la disponibilidad del inventario, la producción y entrega. Dichos recursos se controlan directa o indirectamente por medio de la elección y el diseño de métodos de transmisión de demandas, políticas de inventario-almacenamiento, métodos de procesamiento de demandas, métodos de transporte y métodos de programación. 



    p.mb-5  La siguiente infografía presenta el tiempo total del ciclo del pedido.
        
    figure(data-aos='flip-left').mb-5
      img.nW.centered(src='@/assets/curso/t8-ic1.svg' alt='imagen decorativa')
    
    br
    br
    .row.mb-5
      .col-lg-7
        p.mb-4  El período de transmisión del pedido puede estar formado por diversos recursos de tiempo, dependiendo del método usado para comunicar las demandas:
        ol.lista-ol--cuadro.lista-ol--separador.mb-4
          li 
            .lista-ol--cuadro__vineta
              span
                i.fas.fa-chevron-right
            p.mb-0  Un sistema de comunicación electrónico y por vendedor, tendrá una época de transmisión de pedido formado por la era en la que el vendedor y la oficina de ventas retienen el pedido previo a transmitirlo, y por la era que el pedido esté en el canal de transmisión.   
          li 
            .lista-ol--cuadro__vineta
              span
                i.fas.fa-chevron-right
            p.mb-0 Un pedido preparado por el comprador más una transmisión electrónica tendrá una época de transmisión total equivalente a una llamada telefónica, fax, mensaje electrónico de datos o utilización de una página web.        
        p.mb-5   A veces podría ser fundamental integrar, en la era del periodo del pedido, la época que le toma al comprador colmar un pedido o la era en medio de las visitas de los vendedores.

      .col-lg-5
        figure(data-aos='flip-left')
          img.nW.centered(src='@/assets/curso/t8-ic3.jpg' alt='imagen decorativa')


















</template>

<script>
export default {
  name: 'Tema8',
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
