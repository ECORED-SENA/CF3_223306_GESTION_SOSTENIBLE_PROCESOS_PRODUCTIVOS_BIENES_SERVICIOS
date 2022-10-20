<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Cadena de valor
    
    .bg_grad-19
      .row.mb-5.justify-content-center
        .col-12.col-lg-6.d-flex.align-items-center
          p.mb-0 La cadena de valor es un modelo económico que describe todas las actividades necesarias para crear un producto o servicio. Para las organizaciones que fabrican mercancías, esta cadena incluye los pasos que llevan el producto desde la etapa de diseño hasta la etapa de entrega. Su objetivo es aumentar la eficiencia de la producción para ofrecer el mayor valor al menor costo posible. Este concepto fue introducido por Michael E. Porter en 1985 en su libro Ventaja Competitiva: Creación y sostenimiento de su desempeño superior. 
        .col-12.col-lg-4
          figure
            img(src='@/assets/curso/tema5/t5-1.png', alt='Texto que describa la imagen')
    
    p.mb-5 En el siguiente diagrama se observan las actividades que son básicas para la creación de un producto o servicio:

    .bg_grad-07
      .row.justify-content-center.mb-5
        .col-12.col-lg-8
          .titulo-sexto.color-acento-contenido
            h5 Figura 9
            span Cadena de valor
          figura
            img(src='@/assets/curso/tema5/t5-2.svg' alt='Texto que describa la imagen')
          figcaption.mt-5 Nota. Adaptado de Grupo Trevenque (2021). La cadena de valor: qué es y cómo hacerla.
    
    p.mb-5 La importancia de aplicar la cadena de valor son diversas razones, aunque se destacan los siguientes:

    .bg_grad-13
      .row.mb-5
        .col-12.col-lg-7.p-4.d-flex.align-items-center
          ul.fa-ul
            li.mb-2
              i.fa-li.fas.fa-check-circle.colr
              | Impulsar una mejora continua de los productos y servicios ofertados.
            li.mb-2
              i.fa-li.fas.fa-check-circle.colr
              | Optimizar de forma eficiente los procesos internos.
            li.mb-2
              i.fa-li.fas.fa-check-circle.colr
              | Incrementar la productividad de cada departamento.
            li.mb-2
              i.fa-li.fas.fa-check-circle.colr
              | Fomentar la reducción de los costes de actividad.
            li.mb-2
              i.fa-li.fas.fa-check-circle.colr
              | Identificar ventajas competitivas.
            li
              i.fa-li.fas.fa-check-circle.colr
              | Fidelizar clientes generando valor.
        .col-12.col-lg-4
          figura
            img(src='@/assets/curso/tema5/t5-3.svg' alt='Texto que describa la imagen')
    
    p.mb-5 En la cadena de valor se dan dos tipos de actividades: primarias y secundarias: 

    AcordionA.mb-5(tipo="a" clase-tarjeta="bgr_20")
      .row(titulo="Actividades primarias")
        .col-md-8.mb-4.mb-md-0.px-5.py-3
          p El propósito principal es agregar valor y diseñar una ventaja competitiva. Estas actividades se componen por cinco aspectos:
          ol.lista-ol--cuadro
            li 
              .lista-ol--cuadro__vineta
                span 1
              | Logística de entrada: las funciones son recibir, almacenar y gestionar el inventario.
            li 
              .lista-ol--cuadro__vineta
                span 2
              | Operaciones: consiste en los procesos que la empresa desarrollar para transformar las materias primas en productos finales.
            li 
              .lista-ol--cuadro__vineta
                span 3
              | Logística de salida: incluye todas las operaciones relacionadas a la distribución del producto terminado hacia los consumidores.
            li 
              .lista-ol--cuadro__vineta
                span 4
              | Marketing y ventas: está conformada por las estrategias pertinentes para mejorar la imagen y llegar de manera adecuada a los clientes, por medio de la publicidad, la promoción y la fijación de precios.
            li 
              .lista-ol--cuadro__vineta
                span 15              
              | Servicio: el último aspecto trata de los programas de mejora de la experiencia del cliente y del producto, a través de la atención al cliente, el mantenimiento, la reparación, la sustitución o el cambio de producto.
        .col-md-4
          figure
            img(src='@/assets/curso/tema5/t5-4.png', alt='Texto que describa la imagen')
      .row(titulo="Actividades secundarias ")
        .col-md-8.mb-4.mb-md-0.px-5.py-3
          p Su función principal es de incrementar la eficiencia de las actividades primarias. Están compuestas por:
          ol.lista-ol--cuadro
            li 
              .lista-ol--cuadro__vineta
                span 1
              | Adquisición: son todas las operaciones que la empresa lleva a cabo para adquirir las materias primas.
            li 
              .lista-ol--cuadro__vineta
                span 2
              | Desarrollo tecnológico: es la etapa comprendida por la investigación y desarrollo que abarca actividades como preparar técnicas y automatización en los procesos del producto. 
            li 
              .lista-ol--cuadro__vineta
                span 3
              | Gestión de recursos humanos: incluye la contratación y captación de colaboradores que realicen de manera eficiente la estrategia de la empresa. Adicionalmente, estos contribuirán al diseño, comercialización y venta del producto.
            li 
              .lista-ol--cuadro__vineta
                span 4
              | Infraestructura: son los sistemas y departamentos que lo conforman como contabilidad, finanzas, producción, control de calidad y demás.
        .col-md-4
          figure
            img(src='@/assets/curso/tema5/t5-5.png', alt='Texto que describa la imagen')
           

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
