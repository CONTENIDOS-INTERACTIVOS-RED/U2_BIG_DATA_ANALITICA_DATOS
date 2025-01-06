<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Técnicas básicas de minería de datos'")
  .container.tarjeta.tarjeta--blanca.px-4.pt-4.px-md-5.pt-md-5.pb-0.overflow-hidden
    .row.justify-content-center.mb-5(data-aos="fade-up")
      .col-sm-12.col-lg-8
        .bg-color-6.p-4
          p.my-2 La minería de datos emplea técnicas avanzadas para analizar grandes volúmenes de datos y transformarlos en información útil. Este proceso se fundamenta en la organización y el manejo de datos estructurados y no estructurados, así como en su integración para generar análisis más completos.
      .col-sm-12.col-lg-4.d-none.d-lg-block
        img(src='@/assets/curso/t2/1.png', alt='')

    #t_2_1.titulo-segundo(data-aos="fade-up")
      h2 #[span 2.1] Datos estructurados
    .row.justify-content-center.mb-5(data-aos="fade-up")
      .col-sm-12.col-lg-8
        p.mb-4 Los datos estructurados son aquellos organizados en un formato bien definido, como tablas en bases de datos relacionales, donde cada elemento se clasifica en campos predefinidos, con tipos específicos de datos (números, texto, fechas). Estos datos son ideales para su procesamiento y análisis, debido a su estructura rígida y su compatibilidad con herramientas estándar.
        .bg-color-5.p-5
          p.mb-4.fw-bold Ejemplo práctico
          p.mb-0 En una base de datos de ventas, cada fila representa una transacción, con columnas que indican el ID del producto, la fecha de la venta, el precio, la cantidad y el monto total. Esto permite identificar tendencias de compra, calcular ingresos totales por periodo o analizar el rendimiento de diferentes categorías de productos.
      .col-sm-12.col-lg-4.d-none.d-lg-block
        img(src='@/assets/curso/t2/2.png', alt='')

    h2.mb-3(data-aos="fade-up")  Herramientas utilizadas
    p.mb-5(data-aos="fade-up") El análisis de datos se apoya en diversas herramientas que potencian su eficiencia y alcance.
    .row.justify-content-center.mb-5(data-aos="fade-up")
      .col-sm-12.col-lg-6.mb-lg-0.mb-3
        .custom-image-card.h-100.br-15
          .custom-image-card__text.p-4
            .row.align-items-center.justify-content-center.mb-3
              .col-lg-auto.d-none.d-lg-block
                img(src='@/assets/curso/t2/3.svg', style='max-width: 90px').mx-auto
            h4.mb-2.text-center Gestores de bases de datos
            p.mb-0.text-center MySQL, PostgreSQL y SQL Server, que facilitan el almacenamiento y consulta de grandes volúmenes de datos.

      .col-sm-12.col-lg-6.mb-lg-0.mb-3
        .custom-image-card.h-100.br-15
          .custom-image-card__text.p-4
            .row.align-items-center.justify-content-center.mb-3
              .col-lg-auto.d-none.d-lg-block
                img(src='@/assets/curso/t2/4.svg', style='max-width: 90px').mx-auto
            h4.mb-2.text-center Lenguajes y bibliotecas
            p.mb-0.text-center Python, con herramientas como Pandas y NumPy para manipulación y análisis de datos tabulares.


    #t_2_2.titulo-segundo(data-aos="fade-up")
      h2 #[span 2.2] Datos no estructurados
    p.mb-4(data-aos="fade-up") Los datos no estructurados carecen de un formato predefinido, incluyendo texto libre, imágenes, videos, audios y publicaciones en redes sociales. Este tipo de datos es más complejo de procesar, pero contiene información valiosa que no puede ser capturada por métodos tradicionales.
    .bg-color-1.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.d-none.d-lg-block
          img(src='@/assets/curso/t2/5.png', alt='')
        .col-lg
          .p-4
            p.mb-0.fw-bold Ejemplo práctico
            p.mb-0 Un análisis de opiniones de usuarios en redes sociales, como comentarios en Twitter o Facebook, permite identificar percepciones positivas o negativas, sobre un producto o servicio.
    h2.mb-3(data-aos="fade-up") Herramientas utilizadas
    p.mb-5(data-aos="fade-up") El manejo y análisis de grandes volúmenes de datos, requieren herramientas especializadas que aseguren eficiencia y escalabilidad.
    .bg-full-width.bg-color-3.mb-5(data-aos="fade-up")
      .p-4.p-md-5
        SlyderA(tipo='b').bg-white
          .row.align-items-center.p-4.p-md-5.justify-content-center
            .col-sm-12.col-lg-7
              h5 Hadoop
              p A través de su sistema HDFS, almacena datos no estructurados en clústeres distribuidos, asegurando eficiencia y escalabilidad.
            .col-lg-4.d-none.d-lg-block
                img(src='@/assets/curso/t2/6.png', alt='Logo de Hadoop')

          .row.align-items-center.p-4.p-md-5.justify-content-center
            .col-sm-12.col-lg-7
              h5 Apache Spark
              p Procesa grandes volúmenes de datos en memoria, siendo especialmente útil para análisis en tiempo real.
            .col-lg-3.d-none.d-lg-block
                img(src='@/assets/curso/t2/7.png', alt='Logo de Apache Spark')

          .row.align-items-center.p-4.p-md-5.justify-content-center
            .col-sm-12.col-lg-7
              h5 Procesamiento de lenguaje natural (NLP)
              p Técnicas como análisis de sentimientos y extracción de temas recurrentes, en comentarios textuales.
            .col-lg-4.d-none.d-lg-block
                img(src='@/assets/curso/t2/8.png', alt='Imagen representativa de NLP')


    #t_2_3.titulo-segundo(data-aos="fade-up")
      h2 #[span 2.3]  Procesos integradores
    p.mb-5(data-aos="fade-up") La combinación de datos estructurados y no estructurados, es esencial para un análisis integral que abarque, tanto métricas cuantitativas como percepciones cualitativas.
    h2.mb-3(data-aos="fade-up") Uso combinado de datos estructurados y no estructurados
    p.mb-4(data-aos="fade-up") La integración permite correlacionar datos transaccionales, con información subjetiva de los clientes.
    .row.justify-content-center.mb-5(data-aos="fade-up")
      .col-sm-12.col-lg-4.d-none.d-lg-block
        img(src='@/assets/curso/t2/9.png', alt='')
      .col-sm-12.col-lg-8
        .bg-color-1.p-5
          .my-3
            p.mb-1.fw-bold Ejemplo práctico
            p.mb-0 Si las ventas de un producto muestran una caída, al analizar comentarios de clientes en redes sociales, pueden descubrirse quejas recurrentes sobre su calidad, lo que facilita la identificación del problema y la acción correctiva.
    h2.mb-3(data-aos="fade-up") Herramientas utilizadas
    p.mb-4(data-aos="fade-up") La gestión de datos se apoya en herramientas claves que facilitan su integración y análisis.
    .row.justify-content-center.mb-5
      .col-sm-12.col-lg-8
        LineaTiempoD.color-acento-contenido.large
          div(numero='1' titulo='ETL (Extract, Transform, Load)')  Estos procesos extraen datos de múltiples fuentes, los transforman en formatos compatibles y los cargan en sistemas centralizados. 
          div(numero='2' titulo='Visualización de datos') Plataformas como Tableau o Power Bi, permiten representar la información combinada en dashboards interactivos, que facilitan la interpretación y la toma de decisiones. 
      .col-sm-12.col-lg-4.d-none.d-lg-block
        img(src='@/assets/curso/t2/10.png')
          
    h2.mb-3(data-aos="fade-up") Ejemplo práctico del uso combinado
    .bg-color-2.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.d-none.d-lg-block
          img(src='@/assets/curso/t2/11.png', alt='')
        .col-lg
          .p-4
            p.mb-0 Un minorista cruza datos de ventas (estructurados) con comentarios de clientes (no estructurados). Las ventas incluyen columnas como fecha, producto y monto, mientras que los comentarios de clientes, provienen de redes sociales y encuestas. Este análisis revela una correlación entre una disminución en las ventas y menciones negativas en redes, sobre la calidad del producto, lo que permite a la empresa tomar medidas inmediatas.

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2 MATERIAL COMPLEMENTARIO
        .row.material-complem
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.
            //- Referencia con enlace 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/book.svg' :style='{"max-width":"16px"}')
              a(href='https://elibro.net/es/lc/elibrocom/titulos/217097' target='_blank' rel='noopener noreferrer') Rovira Samblancat, P. & Pascual Cid, V. (2021). Analítica Visual. Cómo explorar, analizar y comunicar datos. Anaya Multimedia.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style='{"max-width":"16px"}')
              a(href='https://www.redalyc.org/articulo.oa?id=291376231005' target='_blank' rel='noopener noreferrer') León García, O. A. (2023). Impacto de las capacidades de análisis de Big Data en la innovación empresarial. Ingeniería y Competitividad, 25(2).
            
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style='{"max-width":"16px"}')
              a(href='https://docs.rapidminer.com/9.9/studio/installation/' target='_blank' rel='noopener noreferrer') RapidMiner. (s.f.). RapidMiner Studio 9.9: Installation guide. 
            
            
            //- Referencia de youtube 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style='{"max-width":"16px"}')
              a(href='https://www.youtube.com/watch?v=u_BmGi4RxRQ' target='_blank' rel='noopener noreferrer') TED. (2012). How to get your ideas to spread | Seth Godin [video]. YouTube.
            
            
          .col-12.col-md-6.col-lg-3.offset-lg-1.d-none.d-lg-block
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema2',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
