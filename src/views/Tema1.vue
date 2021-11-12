<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos='flip-up')
      .titulo-principal__numero
        span 1
      h1 Conceptos de logística y mercancías
    .row.mb-5
      .col-lg-7
        .cajon-b.color-primario.p-3.mb-4
          p.mb-0  A lo largo de años, la funcionalidad logística fue considerada como una actividad rutinaria, meramente operativa y elemental para hacer llegar los productos a partir de los centros de producción a los de uso o consumo. A partir de esta visión, la funcionalidad logística en la organización era contemplada solo como un centro generador de costes sin capacidad de diferenciación (Ballou, 2004). 
        p.mb-3  En el campo académico, su análisis se realizaba a partir del punto de vista industrial o técnica, en busca de modelos que permitieran optimizar espacios, planear distribuciones y minimizar costes. La globalización de la economía y la consiguiente apertura de nuevos mercados distanciados geográficamente fueron cambiando la percepción de la funcionalidad logística hacia novedosas magnitudes, en las que la funcionalidad logística permitía ciertas ventajas competitivas fundamentadas en la reducción de los tiempos de entrega o en la mejora de costes.
        p.mb-3  Sin embargo, a pesar de estas ventajas, la funcionalidad logística seguía siendo una actividad menor en la administración empresarial. En la década de 1960 la administración logística, siguiendo los postulados de marketing, consigue una orientación hacia el comprador que se materializa en dar un servicio logístico ajustado a las necesidades y requisitos de este, y que posibilite su satisfacción. A partir de allí, la funcionalidad logística comienza a ser tratada como una actividad de carácter estratégico capaz de crear ventajas competitivas que diferencian a la organización de la competencia. A continuación, se relacionan aspectos importantes sobre el proceso de logística.
      .col-lg-5
        figure
          img(src='@/assets/curso/t1-i1.jpg' alt='')

    

    #t_1_1.titulo-segundo.color-secundario
      h2 1.1. Medios de transporte







    Separador
    br
    br
    #t_1_2.titulo-segundo.color-secundario
      h2 1.2. Simbología de manejo de carga


















    //- El componente "Muestras" tiene las aplicaciones de todos los componentes de la base
    //- se encuentra en src/components/Muestras.vue
    //- Una vez el componente "Muestras" no se necesite 
    //- Se debe borrar el "import Muestras from '../components/Muestras'" y en "components" en "<script"
    //- esto evitará que se compile en la carpeta final de distribución
    Muestras
  
</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
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
