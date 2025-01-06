<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Análisis de datos estructurados y no estructurados'")
  .container.tarjeta.tarjeta--blanca.px-4.pt-4.px-md-5.pt-md-5.pb-0.overflow-hidden
    p.mb-4(data-aos="fade-up") El análisis de datos, tanto estructurados como no estructurados, debe ser evaluado, según criterios claros que aseguren su efectividad, escalabilidad y precisión.
    p.mb-4.fw-bold(data-aos="fade-up") Los criterios para evaluar técnicas de análisis de datos, son: 
    .bg-full-width.mb-5(data-aos="fade-up")
      ImagenInfografica.color-secundario.mb-5
        template(v-slot:imagen)
          figure
            img(src='@/assets/curso/t3/1.svg')
        .tarjeta.color-adicional-1.p-4(x="18.5%" y="50%" numero="")
          p.mb-0.text-center Capacidad del modelo para producir resultados correctos y relevantes, medidos por métricas como tasa de error, exactitud y coeficientes de correlación.
        .tarjeta.color-adicional-1.p-4(x="50%" y="60%" numero="")
          p.mb-0.text-center Evaluación de tiempo y recursos necesarios para procesar datos, considerando memoria, capacidad de procesamiento y tiempos de ejecución.
        .tarjeta.color-adicional-1.p-4(x="81.5%" y="50%" numero="")
          p.mb-0.text-center Habilidad del modelo para mantener su rendimiento frente al aumento de datos, utilizando arquitecturas distribuidas o técnicas de optimización.
    h2.mb-3(data-aos="fade-up") Aplicaciones prácticas de los criterios
    p.mb-5(data-aos="fade-up") La implementación de sistemas tecnológicos avanzados, requiere priorizar atributos claves como la precisión, la eficiencia y la escalabilidad.
    TabsC.color-acento-contenido.mb-5(data-aos="fade-up")
      .py-4.py-md-5.bg-color-7.p-4(titulo="Precisión")
        .row
          .col-sm-12.col-lg-4.d-none.d-lg-block
            img(src='@/assets/curso/t3/2.png')
          .col-sm-12.col-lg-8
            h4 Precisión
            p.mb-0 Asegurar que las sugerencias en un sistema de recomendación de productos, reflejen las preferencias del usuario, basándose en su historial de compras.

      .py-4.py-md-5.bg-color-7.p-4(titulo="Eficiencia")
        .row
          .col-sm-12.col-lg-4.d-none.d-lg-block
            img(src='@/assets/curso/t3/3.png')
          .col-sm-12.col-lg-8
            h4 Eficiencia
            p.mb-0 Procesar datos de transacciones bancarias en tiempo real, para detectar fraudes sin demoras.
      .py-4.py-md-5.bg-color-7.p-4(titulo="Escalabilidad")
        .row
          .col-sm-12.col-lg-4.d-none.d-lg-block
            img(src='@/assets/curso/t3/4.png')
          .col-sm-12.col-lg-8
            h4 Escalabilidad
            p.mb-0 Manejar eficientemente millones de datos generados por usuarios nuevos, en una aplicación de streaming, sin disminuir la calidad del servicio.


    p.mb-5(data-aos="fade-up") Con estas técnicas, herramientas y criterios, la minería de datos permite a las organizaciones, transformar información compleja en decisiones estratégicas, optimizando recursos y resultados.
    .bg-full-width.bg-color-4.mb-5(data-aos="fade-up")
      .p-5
        .row.justify-content-center.align-items-center
          .col-lg-7
             h2.mb-4 Ejemplo práctico
             p.mb-4 Se invita a profundizar en un caso práctico que compara el análisis descriptivo y predictivo, destacando su implementación con herramientas como SQL y Apache Spark. Este ejemplo ofrece una visión detallada sobre cómo estas metodologías, permiten extraer información clave para la toma de decisiones estratégicas, adaptándose a diferentes necesidades organizacionales y niveles de complejidad. 
             a.anexo.mb-4.bg-white.w-fit(:href='obtenerLink("/downloads/ejemplo_practico.pdf")' target='_blank')
                .anexo__icono(:style='{"background-color": "#FCDFDB"}')
                  img(src='@/assets/template/icono-pdf.svg')
                .anexo__texto
                    p <strong>Anexo. </strong> Ejemplo práctico
          .col-lg-5.d-none.d-lg-block
             img(src='@/assets/curso/t3/5.png', alt='')




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
