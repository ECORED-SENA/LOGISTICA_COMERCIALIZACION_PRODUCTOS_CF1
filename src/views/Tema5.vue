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
          p.mb-0  Los principales aspectos para la clasificación de mercancías se basan en el estado de físico de las mercancías, para establecer las diferentes características de durabilidad o caducidad de la mercancía, lo que influye de forma importante en su conservación y mantenimiento, además se puede establecer su nivel de peligrosidad, su nivel de rotación y la funcionalidad que practica dentro del flujo logístico, así mismo, la interacción entre el peso y el volumen de la carga a guardar (forma, tamaño, densidad).        
      .col-lg-4
        figure
          img.nW.centered(src='@/assets/curso/t5-i1.jpg' alt='imagen decorativa')


    

    #t_5_1.titulo-segundo.color-secundario
      h2 5.1. Manipulación de mercancías 
    p.mb-5  La manipulación de carga engloba cada una de las operaciones de desempeño de la mercancía en almacenes, plataformas y terminales de transporte.

    .row.mb-5.justify-content-center
      .col-lg-8
        .cajon.color-acento-contenido.p-4
          p.mb-0  Para la manipulación de mercancías se aplica, además del trabajo manual que se necesita en ciertos instantes, maquinaria diversa que agiliza y permite las tareas tanto en las cargas/descargas, como en el almacenaje y movimientos interiores. 

    p.mb-5  A continuación, se podrán conocer las herramientas para manipulación de carga:

    .neg-margin-x.tarjeta--lila.py-0
      .tarjeta.p-4.mb-5.r-0
        SlyderA(tipo="b")
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0
              .h4 Grúas
              p Dependiendo su implementación, de las propiedades de la mercancía, del volumen a manejar y del precio de inversión las hay diferentes tipos como puente, cigüeña, martillo, móviles, de cuchara.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i2.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0
              .h4 Transpaleta manual
              p Son carretillas de uñas dobles que sirven para desplazar mercancías en distancias cortas y que no sean bastante pesadas, usadas usualmente en almacenes y para  carga/descarga en el centro de camiones, en especial una vez que no hay muelles.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i3.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0
              .h4 Transpaleta eléctrico
              p Igual a la anterior, sin embargo, el operario va comúnmente sobre ella, se mueve eléctricamente, sirven para pesos más grandes y aceptan uñas más largas para cargar dos paletas paralelamente, además se usan comúnmente en la preparación de pedidos una vez que se debe recorrer gigantes distancias.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i4.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0
              .h4 Carretillas
              p Sirven para desplazar paletas y contenedores, varían de manera enorme de peso y elevación, logrando desplazar hasta contenedores cargados.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i5.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0
              .h4 Equipos de manipulación de contenedores
              p Son enormes carretillas de uñas, (grúas-puente), Straddle carriers (torres móviles), Spreaders (bastidores), que conforman el parque elemental de las terminales de contenedores.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i6.png', alt='imagen decorativa')
          .row.align-items-center
            .col-md-8.mb-4.mb-md-0
              .h4 Mangueras de impulsión/succión
              p Accionadas neumáticamente (graneles sólidos) o hidráulicamente (graneles líquidos) se usan para carga/descarga de minerales ligeros, cereales, petróleo, productos químicos y alimenticios.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i7.png', alt='imagen decorativa')

          .row.align-items-center
            .col-md-8.mb-4.mb-md-0
              .h4 Cintas de carga
              p Para funcionamiento de minerales y cereales con libertad de su densidad, principalmente elaboradas en neopreno.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i8.png', alt='imagen decorativa')

          .row.align-items-center
            .col-md-8.mb-4.mb-md-0
              .h4 Plataformas (Roll-trailers) 
              p Plataformas bajas, dotadas de ruedas utilizadas en los puertos de carga y descarga a bordo de buques de transbordo, ofrecen ahorro en tiempos lo que favorece la operación.
            .col-md-4
              figure
                img(src='@/assets/curso/t5-i9.png', alt='imagen decorativa')


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
