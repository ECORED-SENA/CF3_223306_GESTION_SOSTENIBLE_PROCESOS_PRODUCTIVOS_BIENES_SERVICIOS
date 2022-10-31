<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .bg_grad-01
      .row.mb-5.justify-content-center
        .col-8.col-lg-4.mb-3.mb-lg-0(data-aos="fade-right")
          figura.d-flex.justify-content-center
            img.img350(src='@/assets/curso/intro/img1.svg' alt='Texto que describa la imagen') 
        .col-12.col-lg-8.d-flex.align-items-end(data-aos="fade-left")
          div
            p A través de la historia, el ser humano ha dependido de la naturaleza para su supervivencia y gracias a su razonamiento e inteligencia se ha adaptado al entorno aprendiendo a sembrar, cosechar y mantener sus cultivos a largo plazo con desarrollo científico y tecnológico. Sin embargo, el hombre no ha cuidado del todo a la naturaleza y sus ecosistemas y se ha encargado de destruirla debido al impacto producido por el mal manejo de los recursos.
            p.mb-0 Es por esto, que el desarrollo de estos contenidos estará enfocado en la importancia de los ecosistemas, cómo es la relación del hombre con la naturaleza, cuál es el metabolismo de la economía colombiana, cuáles son los modelos económicos, qué es la economía circular, normatividad, incentivos y casos de éxito. 
    
    p Por otro lado, se trabajará el concepto de bioeconomía y los sistemas sostenibles, con el objetivo de impulsar estas estrategias en las empresas y diferentes instituciones de orden nacional e internacional. Conocerán, además, los indicadores de uso de los recursos naturales, cómo calcular la demanda de agua y energía y la importancia de la responsabilidad social empresarial. 

    p.mb-5 Como punto inicial, lo invitamos a ver el siguiente video de bienvenida y desarrollo de este componente formativo:

    figure(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/N2wSqwPfMHM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)





    

    
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
