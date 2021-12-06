<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido(data-aos='flip-up')
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p.mb-3  La evolución de los métodos de gestión en las organizaciones ha hecho que muchas empresas opten por concentrar sus esfuerzos en las actividades principales del negocio y corresponde a los proveedores suministrar a las empresas productos y servicios complementarios. Sin embargo, se establece una relación de dependencia entre la empresa, cliente y sus proveedores que empiezan a actuar como parte de la propia empresa.
    p.mb-5  En el siguiente recurso educativo, se podrán conocer las intencionalidades que tiene este componente.


    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/R_8v8GBrklw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
     





</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
