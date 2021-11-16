<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido(data-aos='flip-up')
      .titulo-principal__numero
        span 6
      h1 Normativa de productos

    .row.mb-5.align-items-center.justify-content-center
      .col-lg-8.slideInLeft
        .cajon-b.color-primario.p-4.mb-4
          p.mb-0  La norma jurídica de protección del derecho a la estabilidad e indemnidad o situación de los clientes, sin perjuicio de los otros que les reconozcan leyes especiales, se establece en la Constitución Política de 1991 y el Estatuto del Consumidor. Acorde con el artículo 78 de la Constitución Política de 1991, serán responsables conforme con la ley, quienes en la producción y en la venta de bienes y servicios, atenten contra la salud, la estabilidad y el correcto aprovisionamiento a clientes y usuarios finales.
        .cajon.color-acento-contenido.p-4
          p.mb-0  Por su lado, la Ley 1480 de 2011 tiene como propósito general, entre otros, defender, impulsar y asegurar la positiva protección del derecho que tiene el consumidor a su estabilidad e indemnidad, en otros términos, a que los productos que usa en la satisfacción de sus necesidades no le ocasionen mal en situaciones típicas de implementación, así como a recibir defensa frente a contra las secuelas dañinas para la salud, la vida o la totalidad que dichos le constituyan.

      .col-lg-4
        figure
          img.nW.centered(src='@/assets/curso/t6-i1.jpg' alt='imagen decorativa')
      
    p.mb-5  En los términos del propio Estatuto, todo productor debería afirmar la idoneidad y estabilidad de los bienes y servicios que ofrezca o ponga en el mercado, obligación que se consagra en doble vía si se tiene presente que, paralelamente, el consumidor tiene el deber de instruirse en interacción a las indicaciones que suministre el productor o abastecedor relacionadas con el conveniente uso o consumo de los bienes y servicios, su conservación e instalación; además, se prevé la obligación solidaria y temporal para el productor y el abastecedor de contestar a título de garantía por la conformidad del producto con las condiciones de estabilidad legalmente exigibles o las ofrecidas.

    .row.mb-5.justify-content-center
      .col-lg-10
        .bloque-texto-a.color-acento-contenido.p-4.p-md-5.mb-5.customBC(data-aos='flip-left')
          .row.m-0.align-items-center.justify-content-between
            .col-lg-4.mb-4.mb-lg-0
              figure
                img.nW.centered(src='@/assets/curso/t6-i.jpg' alt='imagen decorativa') 
            .col-lg-8
              .bloque-texto-a__texto.p-4
                p.mb-0  En referencia a la seguridad de los productos son distintas las actividades y elecciones que puede adoptar la Superintendencia de Industria y Comercio, y aunque la responsabilidad por perjuicios por producto defectuoso es de entendimiento de la jurisdicción ordinaria, ello no se opone a la aplicación de medidas tendientes a la defensa de los clientes, pues esta actuación es bien distinta a la reservada para el juez en la tasación de daños y perjuicios.
      
    p.mb-5  Para conocer toda la información sobre el sector de tránsito de mercancías es importante conocer el Decreto 1079 de 2015: 
    .row.mb-5.justify-content-center
      .col-lg-10
        .tarjeta.color-gradient.p-3.mb-5(data-aos='flip-up')
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img.nW.centered(src="@/assets/curso/t6-ic1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Decreto 1079 de 2015 - Ministerio de transporte. Decreto Único Reglamentario del Sector Transporte.
                  p.text-small Se invita a consultar el Decreto 1079 de 2015 expedido por el Ministerio de Transporte, en donde se establece como único y reglamentario del sector transporte.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download


























</template>

<script>
export default {
  name: 'Tema6',
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
