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
          p.mb-0  Los principales aspectos para la clasificación de mercancías se basan en su estado de físico, para establecer las diferentes características de durabilidad o caducidad de la mercancía, lo que influye de forma importante en su conservación y mantenimiento, además se puede establecer su nivel de peligrosidad, su nivel de rotación y la funcionalidad que practica dentro del flujo logístico, así mismo, la interacción entre el peso y el volumen de la carga a guardar (forma, tamaño, densidad).        
      .col-lg-4
        figure
          img.centered(src='@/assets/curso/t5-i1.jpg' alt='imagen decorativa')


    

    #t_5_1.titulo-segundo.color-secundario
      h2 5.1 Manipulación de mercancías 
    p.mb-5  La manipulación de carga engloba cada una de las operaciones de desempeño de la mercancía en almacenes, plataformas y terminales de transporte.

    .row.mb-5.justify-content-center
      .col-lg-8
        .cajon.color-acento-contenido.p-4
          p.mb-0  Para la manipulación de mercancías se aplica, además del trabajo manual que se necesita en ciertos instantes, maquinaria diversa que agiliza y permite las tareas tanto en las cargas/descargas, como en el almacenaje y movimientos interiores. 

    p.mb-5  A continuación, se podrán conocer las herramientas para manipulación de carga:

    .neg-margin-x.bg-sliders.py-0
      .tarjeta.p-4.mb-5.r-0
        SlyderA(tipo="a")
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0.p-5
              .h4 Grúas
              p Dependiendo de su implementación, de las propiedades de la mercancía, del volumen a manejar y del precio de inversión las hay de diferentes tipos como puente, cigüeña, martillo, móviles, de cuchara.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i2.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0.p-5
              .h4 Transpaleta manual
              p Son carretillas de uñas dobles que sirven para desplazar mercancías en distancias cortas y que no sean bastante pesadas, usadas usualmente en almacenes y para  carga/descarga en el centro de camiones, en especial una vez que no hay muelles.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i3.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0.p-5
              .h4 Transpaleta eléctrica
              p Igual a la anterior, sin embargo, el operario va comúnmente sobre ella, se mueve eléctricamente, sirven para pesos más grandes y aceptan uñas más largas para cargar dos paletas paralelamente, además se usan comúnmente en la preparación de pedidos, una vez que se deben recorrer gigantes distancias.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i4.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0.p-5
              .h4 Carretillas
              p Sirven para desplazar paletas y contenedores, varían de manera enorme de peso y elevación, logrando desplazar hasta contenedores cargados.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i5.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0.p-5
              .h4 Equipos de manipulación de contenedores
              p Son enormes carretillas de uñas, (grúas-puente), <i>straddle carriers</i> (torres móviles), <i>spreaders</i> (bastidores), que conforman el parque elemental de las terminales de contenedores.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i6.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0.p-5
              .h4 Mangueras de impulsión/succión
              p Accionadas neumáticamente (graneles sólidos) o hidráulicamente (graneles líquidos) se usan para carga/descarga de minerales ligeros, cereales, petróleo, productos químicos y alimenticios.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i7.png', alt='imagen decorativa')

          .row.align-items-center
            .col-md-8.mb-4.mb-md-0.p-5
              .h4 Cintas de carga
              p Para funcionamiento de minerales y cereales con libertad de su densidad, principalmente elaboradas en neopreno.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i8.png', alt='imagen decorativa')

          .row.align-items-center
            .col-md-8.mb-4.mb-md-0.p-5
              .h4 Plataformas (<i>Roll-trailers</i>) 
              p Plataformas bajas, dotadas de ruedas utilizadas en los puertos de carga y descarga a bordo de buques de transbordo, ofrecen ahorro en tiempos lo que favorece la operación.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i9.png', alt='imagen decorativa')


    Separador
    br
    br
    #t_5_2.titulo-segundo.color-secundario
      h2 5.2 Tipos de almacenamiento   
    p.mb-3(data-aos='slide-up')  Los tipos de almacenamiento que pertenecen a una compañía son de una pluralidad casi infinita, dado los diseños personalizados que siguen las necesidades especializadas. Por lo opuesto, un centro de repartición sirve para saciar el extenso rango de necesidades de las compañías. Por ello, una vez que se comparan con almacenamiento especializado son más estandarizados en la configuración del espacio y en la utilización del equipo para múltiples fines. 
    p.mb-5(data-aos='slide-up')  Los almacenes de los centros de distribución tienen la posibilidad de clasificarse en un número reducido de equipos.

    .row.mb-5.justify-content-center
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/t5-cf1.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.text-center
              br
              .h3 Almacenes de productos o mercancías
              p.mb-4 Dichos almacenes limitan sus servicios a guardar y manejar ciertas mercancías, como madera, algodón, tabaco, grano y otros productos que se deterioran de forma sencilla.
              br

      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/t5-cf2.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.text-center
              br
              .h3 Almacenes de volúmenes gigantes
              p.mb-4 Ciertos almacenes ofrecen guardar y manejar productos de gran volumen (a granel), como productos químicos líquidos, aceite, sales para autopistas y almíbares. Además, mezclan productos y separan embarques consolidados como parte de su servicio.
              br

      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/t5-cf3.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.text-center
              br
              .h3 Almacenes de temperatura controlada
              p.mb-0 Hay almacenes que controlan el ambiente del almacenamiento, así, tanto la temperatura como la humedad tienen la posibilidad de regularse. Los bienes perecederos, como frutas, vegetales y comidas congeladas, así como ciertos productos químicos y medicamentos, necesitan de esta clase de almacenamiento.
      .clearfix.mb-3
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/t5-cf4.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.text-center
              br
              .h3 Almacenes de bienes domésticos
              p.mb-0 Guardar y manejar artículos y menaje del hogar son la especialidad de estos almacenes. Aun cuando los productores de muebles tienen la posibilidad de utilizar dichos almacenes, los usuarios primordiales son las compañías de mudanzas de bienes domésticos.
              br

      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/t5-cf5.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.text-center
              br
              .h3 Almacenes de mercancía general
              p.mb-0 Dichos almacenes, el tipo más común, manejan un extenso rango de mercancías. Comúnmente, la mercancía no necesita las instalaciones especiales de los casos anteriores.
              br




</template>

<script>
export default {
  name: 'Tema5',
  data: () => ({
    mostrarIndicador: true,
    indicadorImagenZoom: true,
    indicadorTarjetaFlip: true,
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
