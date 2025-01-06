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


    .bg-full-width.border-top.actividad.ctn-actividad
      .p-4.p-md-5
        #Actividad                
          <Actividad :cuestionario='cuestionario'/>

</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    cuestionario: {
      tema: '--',
      titulo: 'Ponte a prueba',
      introduccion:
        'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
      barajarPreguntas: true,
      preguntas: [
        {
          id: 1,
          texto:
            '¿Qué técnica de analítica permite comprender eventos pasados para la toma decisiones?',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Analítica predictiva',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Analítica descriptiva',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Minería de datos',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Machine Learning',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Correcto! La analítica descriptiva es la técnica que nos permite comprender eventos pasados.',
          mensaje_incorrecto: 'No es correcto. Intenta nuevamente.',
        },
        {
          id: 2,
          texto: '¿Cuál es una ventaja clave de la analítica descriptiva?',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Anticipar eventos futuros',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Proporcionar un análisis visual claro de los datos',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Realizar simulaciones complejas',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Generar acciones óptimas',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Correcto! La analítica descriptiva proporciona un análisis visual claro de los datos.',
          mensaje_incorrecto: 'No es correcto. Revisa nuevamente el material.',
        },
        {
          id: 3,
          texto:
            '¿Qué tipo de datos se almacenan en un formato predefinido como tablas?',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'No estructurados',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Estructurados',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Semiestructurados',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Heterogéneos',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Correcto! Los datos estructurados son aquellos que se almacenan en formatos predefinidos como tablas.',
          mensaje_incorrecto: 'No es correcto. Intenta nuevamente.',
        },
        {
          id: 4,
          texto:
            '¿Qué algoritmo de minería de datos es utilizado para identificar patrones frecuentes?',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Apriori',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'K-Means',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Random Forest',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Regresión lineal',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Correcto! El algoritmo Apriori es utilizado para identificar patrones frecuentes en los datos.',
          mensaje_incorrecto: 'No es correcto. Revisa nuevamente el material.',
        },
        {
          id: 5,
          texto:
            '¿Cuál de las siguientes herramientas es ideal para analizar datos no estructurados?',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'SQL',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'HDFS',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Power BI',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'MySQL',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Correcto! HDFS es una herramienta ideal para el análisis de datos no estructurados.',
          mensaje_incorrecto: 'No es correcto. Intenta nuevamente.',
        },
      ],
      mensaje_final_aprobado: '¡Felicidades! Has superado la prueba con éxito.',
      mensaje_final_reprobado:
        'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
    },
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
