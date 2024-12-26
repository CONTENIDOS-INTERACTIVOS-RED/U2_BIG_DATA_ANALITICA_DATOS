<template lang="pug">
  .curso-main-container.introduccion
    BannerInterno(subTitulo="Introducción")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      p.mb-5(data-aos="fade-up") La analítica de datos, es fundamental para transformar grandes volúmenes de información en conocimiento útil que permita a las organizaciones tomar decisiones informadas. Desde el análisis descriptivo, que sintetiza datos históricos para identificar patrones y tendencias, hasta el predictivo, que anticipa eventos futuros mediante modelos avanzados, cada enfoque contribuye a optimizar estrategias y procesos claves. Estas técnicas ayudan a comprender el pasado y proyectar escenarios futuros, permitiendo a las organizaciones adaptarse mejor a los cambios del entorno.
      .row.justify-content-center.mb-5(data-aos="fade-up")
        .col-sm-12.col-lg-4.d-none.d-lg-block
          img(src="@/assets/curso/intro/1.png", alt="")
        .col-sm-12.col-lg-8
          .bg-color-1.px-5.py-4
            p.mb-0 Además, la minería de datos amplía las posibilidades al trabajar con datos estructurados y no estructurados, ofreciendo un análisis integral que combina métricas cuantitativas y percepciones cualitativas. Con el apoyo de herramientas tecnológicas como Power BI, Tableau o Apache Spark, es posible extraer insights accionables de información compleja, mejorando la eficiencia operativa y la capacidad de respuesta, frente a desafíos específicos. 

</template>

<script>
import BannerInterno from '../components/plantilla/BannerInterno'

export default {
  name: 'Introduccion',
  components: {
    BannerInterno,
  },
  data: () => ({
    globalData: global,
  }),
}
</script>

<style lang="sass"></style>
