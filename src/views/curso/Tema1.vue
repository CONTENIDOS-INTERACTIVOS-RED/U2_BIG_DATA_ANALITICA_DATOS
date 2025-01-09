<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Tipos de analítica'")
  .container.tarjeta.tarjeta--blanca.px-4.pt-4.px-md-5.pt-md-5.pb-0.overflow-hidden
    .bg-color-2.mb-5(data-aos='flip-up')
      .row.justify-content-center.align-items-center
        .col-lg-auto.d-none.d-lg-block
          img(src='@/assets/curso/t1/1.png', alt='')
        .col-lg
          .p-4
            p.mb-0 La analítica de datos es un conjunto de acciones que permiten recolectar y aprovechar información para identificar tendencias y oportunidades. A continuación, se presenta una descripción detallada de la analítica descriptiva, combinando párrafos explicativos, características principales y un cuadro resumen.
    #t_1_1.titulo-segundo(data-aos='flip-up')
      h2 #[span 1.1] Analítica descriptiva
    p.mb-5(data-aos='flip-up') La analítica descriptiva es el punto de partida en el análisis de datos. Su propósito es sintetizar y visualizar información histórica para comprender qué ocurrió y por qué, estableciendo una base sólida para decisiones estratégicas y futuras proyecciones. Este enfoque analiza eventos pasados mediante la identificación de patrones, tendencias y relaciones, transformando datos complejos en información clara y accionable.

    h2.mb-3(data-aos='flip-up') Características principales de la analítica descriptiva
    p.mb-5(data-aos='flip-up') La analítica descriptiva es una herramienta esencial para comprender y resumir eventos pasados mediante el análisis de datos históricos:
    .bg-full-width.bg-color-3.mb-5(data-aos='flip-up')
      .p-4.p-md-5
        SlyderA(tipo='b').bg-white
          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5  Descripción de eventos pasados
              p Permite resumir e interpretar datos históricos. Por ejemplo, al analizar el comportamiento de ventas mensuales para identificar picos en temporadas específicas como Navidad.
            .col-lg-5.d-none.d-lg-block
                img(src='@/assets/curso/t1/2.png', alt='')

          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5  Enfoque en patrones
              p Analiza distribuciones, tendencias y correlaciones entre variables. Ejemplo: detectar el impacto de promociones en ventas, mediante gráficos interactivos.
            .col-lg-5.d-none.d-lg-block
                img(src='@/assets/curso/t1/3.png', alt='')

          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5  Base para otros análisis
              p Sirve como entrada para analítica predictiva y prescriptiva. Por ejemplo, utilizar ventas históricas para ajustar inventarios o proyectar la demanda futura.
            .col-lg-5.d-none.d-lg-block
                img(src='@/assets/curso/t1/4.png', alt='')

          

    h2.mb-5(data-aos='flip-up') Técnicas empleadas
    .row.justify-content-center.mb-5(data-aos='flip-up')
      .col-sm-12.col-lg-4.d-none.d-lg-block
        img(src='@/assets/curso/t1/5.png')
      .col-sm-12.col-lg-8
          p.mb-5 Las herramientas y métodos aplicados en la analítica descriptiva permiten organizar y presentar datos de forma comprensible, facilitando la toma de decisiones.
          h2.mb-3  a. Visualización de datos
          p.mb-5 Representa información numérica y tabulación en gráficos interactivos y dashboards. Herramientas como Power BI, Tableau y bibliotecas de Python, como Matplotlib, transforman datos complejos en elementos visuales, fáciles de interpretar.
          .p-4.bg-color-2
            p.mb-0 #[b Ejemplo:] un minorista utiliza Power BI para visualizar las ventas por sucursal en tiempo real, identificando áreas de alto rendimiento y posibles problemas logísticos.

    .bg-full-width.bg-fondo-3.mb-5(data-aos='flip-up')
      .px-4.px-md-5.pb-md-3
        h2.mb-3 b. Estadística descriptiva
        p.mb-5 Resume datos utilizando medidas como:
        .row.justify-content-center.align-items-stretch.mb-0
          .col-sm-12.col-lg-4.mb-4
            .custom-image-card-2.h-100.text-center
              .custom-image-card__text.p-4
                .row.align-items-center.justify-content-center.mb-3
                  .col-lg-auto.d-none.d-lg-block
                    img(src='@/assets/curso/t1/6.svg', style='max-width: 90px').mx-auto
                h5.mb-2.text-center Tendencia central
                p.mb-0  Promedio, mediana moda.
          .col-sm-12.col-lg-4.mb-4
            .custom-image-card-2.h-100.text-center
              .custom-image-card__text.p-4
                .row.align-items-center.justify-content-center.mb-3
                  .col-lg-auto.d-none.d-lg-block
                    img(src='@/assets/curso/t1/7.svg', style='max-width: 90px').mx-auto
                h5.mb-2.text-center Dispresión
                p.mb-0  Desviación estándar y rango.
                p.mb-0  Estas métricas permiten evaluar ingresos promedios y su variabilidad entre departamentos.
          .col-sm-12.col-lg-4.mb-4
            .custom-image-card-2.h-100.text-center
              .custom-image-card__text.p-4
                .row.align-items-center.justify-content-center.mb-3
                  .col-lg-auto.d-none.d-lg-block
                    img(src='@/assets/curso/t1/8.svg', style='max-width: 90px').mx-auto
                h5.mb-2.text-center Visualización adicional
                p.mb-0 Histogramas y diagramas de caja, complementan el análisis.


    h2.mb-3(data-aos='flip-up') c. Segmentación de datos
    p.mb-4(data-aos='flip-up') Divide la información en categorías o grupos relevantes, mediante algoritmos como K-Means.
    .bg-color-1.mb-5(data-aos='flip-up')
      .row.justify-content-center.align-items-center
        .col-lg-auto.d-none.d-lg-block
          img(src='@/assets/curso/t1/9.png', alt='')
        .col-lg
          .p-4
            p.mb-0 #[b Ejemplo:] una empresa segmenta a sus clientes, según frecuencia y monto de compra, para diseñar campañas de marketing, personalizadas.
    .row.justify-content-center.mb-5(data-aos='flip-up')
      .col-sm-12.col-lg-8
          .titulo-figura.mb-2.d-d-flex
            p.mb-0 #[b Tabla 1.] Herramientas y métodos
          .tabla-a.color-primario.mb-0
            table
              thead
                tr
                  th.w-25 Técnica
                  th Métodos comunes
                  th Ejemplo de uso práctico
              tbody
                tr
                  td.fw-bold Visualización de datos
                  td Power BI, Tableau, Matplotlib.
                  td Dashboards para monitorear métricas claves como ingresos y comportamiento del cliente.
                tr
                  td.fw-bold Estadística descriptiva
                  td Medidas de tendencia central y dispersión.
                  td Determinar promedio de ingresos mensuales y variabilidad de gastos en departamentos.
                tr
                  td.fw-bold Segmentación de datos
                  td Agrupación por atributos, algoritmos como K-Means.
                  td Crear estrategias personalizadas para diferentes segmentos de clientes, según su comportamiento.

    p.mb-5(data-aos='flip-up') La analítica descriptiva organiza y simplifica datos históricos, transformándolos en insights prácticos que fundamentan decisiones estratégicas. Su combinación de técnicas como visualización de datos, estadística descriptiva y segmentación, permite a las organizaciones identificar patrones, optimizar recursos y sentar las bases para análisis predictivos y prescriptivos, adaptándose a las necesidades de cada sector.

    #t_1_2.titulo-segundo(data-aos='flip-up')
      h2 #[span 1.2] Análisis detallado de la analítica descriptiva
    .bg-color-4.mb-5(data-aos='flip-up')
      .row.justify-content-center.align-items-center
        .col-lg
          .p-4
            p.mb-0 La analítica descriptiva es una herramienta esencial para las organizaciones, al proporcionar una visión clara y estructurada del comportamiento pasado mediante el análisis de datos históricos. Este enfoque facilita la toma de decisiones informadas, destacando patrones y relaciones que pueden optimizar los procesos operativos y estratégicos. A continuación, se presenta un análisis detallado, combinado con ejemplos, aplicaciones y limitaciones.
        .col-lg-auto.d-none.d-lg-block
          img(src='@/assets/curso/t1/10.png', alt='')
    .bg-full-width.bg-fondo-1.mb-4(data-aos='flip-up')
      .px-4.px-md-5.pb-md-3
        h2.mb-5 Ejemplo práctico
        p.mb-4 Una cadena minorista analiza las tendencias de ventas del último año, utilizando datos desglosados por producto y ubicación, obtenidos de su sistema de punto de venta. Con herramientas como Tableau, se diseñan dashboards interactivos que incluyen informes claves sobre productos más vendidos, comparativas regionales y evolución de ventas.
        .row.justify-content-center.align-items-stretch.mb-0
          .col-sm-12.col-lg-4.mb-0
            .custom-image-card-2.h-100.text-center
              .custom-image-card__text.p-4
                .row.align-items-center.justify-content-center.mb-3
                  .col-lg-auto.d-none.d-lg-block
                    img(src='@/assets/curso/t1/11.svg', style='max-width: 90px').mx-auto
                p.mb-0  Identificación de picos estacionales, como aumentos en ventas navideñas.
          .col-sm-12.col-lg-4.mb-0
            .custom-image-card-2.h-100.text-center
              .custom-image-card__text.p-4
                .row.align-items-center.justify-content-center.mb-3
                  .col-lg-auto.d-none.d-lg-block
                    img(src='@/assets/curso/t1/12.svg', style='max-width: 90px').mx-auto
                p.mb-0  Optimización de inventarios para garantizar disponibilidad en los momentos claves.
          .col-sm-12.col-lg-4.mb-0
            .custom-image-card-2.h-100.text-center
              .custom-image-card__text.p-4
                .row.align-items-center.justify-content-center.mb-3
                  .col-lg-auto.d-none.d-lg-block
                    img(src='@/assets/curso/t1/13.svg', style='max-width: 90px').mx-auto
                p.mb-0 Creación de estrategias especificas para aumentar las ventas en regiones menos dinámicas.

    p.mb-5(data-aos='flip-up') Este enfoque mejora la asignación de recursos y maximiza la capacidad de respuesta al mercado.
    h2.mb-4(data-aos='flip-up') Aplicación a la minería de datos
    .row.justify-content-center.mb-5(data-aos='flip-up')
      .col-sm-12.col-lg-8
          p.mb-3 La minería de datos complementa la analítica descriptiva, al descubrir patrones y relaciones ocultas en grandes volúmenes de información. Un ejemplo destacado es el #[b algoritmo Apriori], utilizado para generar reglas de asociación efectivas. El proceso del algoritmo Apriori:
          .row.justify-content-center.align-items-center.mb-0
            .col-lg-12
              .p-4.bg-color-5
                ul.lista-ul--color.mb-0
                  li.d-flex
                    i.fas.fa-circle.icon-list
                    span #[b Definición de parámetros iniciales:] umbrales de soporte mínimo y confianza mínima, determinan la relevancia de las asociaciones.
                  li.d-flex
                    i.fas.fa-circle.icon-list
                    span #[b Búsqueda de elementos frecuentes:] se identifican combinaciones de elementos recurrentes en las transacciones.
                  li.d-flex
                    i.fas.fa-circle.icon-list
                    span #[b Generación de reglas de asociación:] ejemplo: "Si se compra pan, hay un 80 % de probabilidad, que también se compre leche".
                  li.d-flex.mb-0
                    i.fas.fa-circle.icon-list
                    span #[b Optimización:] eliminación de combinaciones no frecuentes, para reducir complejidad.
      .col-sm-12.col-lg-4.d-none.d-lg-block
        img(src='@/assets/curso/t1/14.svg')
    h2.mb-4(data-aos='flip-up') Aplicaciones prácticas
    p.mb-3(data-aos='flip-up') Las aplicaciones prácticas de la analítica, permiten optimizar procesos y tomar decisiones estratégicas en diversos campos.
    figure.mb-5(data-aos='flip-up')
      .video
         iframe(width="560" height="315" src="https://www.youtube.com/embed/zRek9UnW8-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video
    h2.mb-4(data-aos='flip-up') Ventajas de la analítica descriptiva
    p.mb-4(data-aos='flip-up') La analítica descriptiva ofrece ventajas significativas para las organizaciones, al proporcionar información clara y procesable.
    .bg-full-width.bg-color-3.mb-5(data-aos='flip-up')
      .p-4.p-md-5
        SlyderA(tipo='b').bg-white
          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Visualización clara
              p Presentación comprensible mediante gráficos y dashboards.
            .col-lg-5.d-none.d-lg-block
              img(src='@/assets/curso/t1/15.png', alt='')

          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Detección de áreas de mejora
              p Identificación de ineficiencias y oportunidades en procesos operativos.
            .col-lg-5.d-none.d-lg-block
              img(src='@/assets/curso/t1/16.png', alt='')

          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Reducción de incertidumbre
              p Apoyo en la planificación estratégica, basada en patrones observados.
            .col-lg-5.d-none.d-lg-block
              img(src='@/assets/curso/t1/17.png', alt='')

          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Optimización de recursos
              p Enfoque en áreas de alto impacto, para maximizar el retorno de la inversión.
            .col-lg-5.d-none.d-lg-block
              img(src='@/assets/curso/t1/18.png', alt='')



    h2.mb-4(data-aos='flip-up') Limitaciones de la analítica descriptiva
    p.mb-3(data-aos='flip-up') Aunque la analítica descriptiva es una herramienta valiosa para comprender datos históricos, presenta limitaciones que pueden impactar su utilidad.
    .row.justify-content-center.mb-5(data-aos='flip-up')
      .col-sm-12.col-lg-5.d-none.d-lg-block
        img(src='@/assets/curso/t1/19.png')
      .col-sm-12.col-lg-7
        AcordionA(tipo='b').color-acento-contenido
          div(titulo='Sin capacidad predictiva')
            p.mb-0 No anticipa eventos futuros ni identifica tendencias emergentes.
          div(titulo='Falta de recomendaciones específicas')
            p.mb-0 Requiere que el usuario interprete los resultados, para definir las acciones.
          div(titulo='Dependencia de la calidad de los datos')
            p.mb-0 Datos incompletos o inconsistentes, pueden llevar a conclusiones erróneas.
          div(titulo='Limitada profundidad causal')
            p.mb-0 No profundiza en las causas subyacentes de los fenómenos analizados.
    
    
    p.mb-3(data-aos='flip-up') La analítica descriptiva es el punto de partida para cualquier estrategia de análisis de datos. Su capacidad para organizar y sintetizar grandes volúmenes de información, en visualizaciones claras, la convierte en una herramienta imprescindible para la toma de decisiones. Sin embargo, sus limitaciones destacan la importancia de complementarla con enfoques predictivos y prescriptivos, para profundizar en las causas y proyecciones futuras.
    #t_1_3.titulo-segundo(data-aos='flip-up')
      h2 #[span 1.3] Analítica predictiva
    .p-4.bg-color-5.mb-5
      .row.align-items-center
        .col-lg
          p.mb-0 La analítica predictiva aplica modelos estadísticos avanzados y técnicas de #[i machine learning], para identificar patrones en los datos históricos, anticipando eventos futuros y proporcionando a las organizaciones, una ventaja competitiva al tomar decisiones estratégicas.
        .col-lg-auto.d-none.d-lg-block
          img(src='@/assets/curso/t1/20.svg', style='max-width: 90px').mx-auto


    h2.mb-3(data-aos='flip-up') Técnicas claves
    .p-4.bg-color-2.mb-5(data-aos='flip-up')
      p.mb-0 Las técnicas de analítica predictiva, permiten abordar problemas específicos, como la predicción de valores, clasificación de datos o análisis de relaciones complejas. A continuación, se presentan las más utilizadas, junto con ejemplos prácticos:
    h2.mb-3(data-aos='flip-up') Modelos de regresión
    p.mb-0(data-aos='flip-up') Estas herramientas exploran las relaciones entre variables para prever valores o probabilidades.
    .row.justify-content-center.mb-5(data-aos='flip-up')
      .col-sm-12.col-lg-6.mb-lg-0.mb-3
        .custom-image-card.h-100.br-15
          img.custom-image-card__image.d-none.d-lg-block(src='@/assets/curso/t1/21.png' alt='')
          .custom-image-card__text.p-4
            h4.mb-2.text-center Regresión lineal
            p.mb-1.text- Utilizada para percibir valores continuos, basándose en variables independientes.
            p.mb-0.text- Ejemplo práctico: estimar ingresos mensuales de una empresa, en función de su inversión publicitaria.  
      .col-sm-12.col-lg-6.mb-lg-0.mb-3
        .custom-image-card.h-100.br-15
          img.custom-image-card__image.d-none.d-lg-block(src='@/assets/curso/t1/22.png' alt='')
          .custom-image-card__text.p-4
            h4.mb-2.text-center Regresión logística
            p.mb-1.text- Indicada para percibir resultados binarios como "si/no".
            p.mb-0.text- Ejemplo práctico: determinar la probabilidad que un cliente cancele un servicio.

    h2.mb-3(data-aos='flip-up') Modelos de clasificación
    p.mb-5(data-aos='flip-up') Los modelos de clasificación asignan categorías a los datos, según patrones detectados.
    h2.mb-3(data-aos='flip-up') Técnicas de series temporales
    p.mb-5(data-aos='flip-up') Analizan datos cronológicos para identificar patrones, tendencias y estacionalidades.
    .bg-color-1.mb-5(data-aos='flip-up')
      .row.justify-content-center.align-items-center
        .col-lg-auto.d-none.d-lg-block
          img(src='@/assets/curso/t1/23.png', alt='')
        .col-lg
          .p-4
            p.mb-0 #[b Ejemplo práctico:] Prever la demanda de productos como abrigos en invierno, o helados en verano.
    h2.mb-3(data-aos='flip-up') Técnicas de #[i machine learning]
    p.mb-4(data-aos='flip-up') Las técnicas de #[i machine learning] son herramientas poderosas para el análisis y la predicción, en diversos contextos.
    .bg-full-width.bg-color-3.mb-5(data-aos='flip-up')
      .p-4.p-md-5
        SlyderA(tipo='b').bg-white
          
          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 K-Nearest Neighbors (KNN)
              p Clasifica o predice valores, según datos similares cercanos.
              p Ejemplo práctico: Identificar clientes con características similares para campañas específicas.
            .col-lg-5.d-none.d-lg-block
                img(src='@/assets/curso/t1/24.png', alt='')

          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Redes neuronales artificiales
              p Modelan relaciones complejas entre datos no lineales. 
              p Ejemplo práctico: Reconocimiento de imágenes en aplicaciones biométricas.
            .col-lg-5.d-none.d-lg-block
                img(src='@/assets/curso/t1/25.png', alt='')
    h2.mb-3(data-aos='flip-up') Ejemplo práctico: predicción de rotación de clientes
    p.mb-5(data-aos='flip-up') Una empresa desea anticipar la cancelación de contratos de clientes.
    .bg-full-width.bg-color-3.mb-5(data-aos='flip-up')
      .p-4.p-md-5
        SlyderA(tipo='b').bg-white
          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Preparación de datos
              p Recopilación de datos históricos sobre el comportamiento de los clientes. Limpieza y normalización para garantizar calidad y coherencia.
            .col-lg-5.d-none.d-lg-block
                img(src='@/assets/curso/t1/26.png', alt='')

          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Modelado
              p Aplicación de regresión logística para predecir probabilidades de abandono. Uso de Random Forest como validación para mejorar la precisión.
            .col-lg-5.d-none.d-lg-block
                img(src='@/assets/curso/t1/27.png', alt='')

          .row.align-items-center.p-4.p-md-5
            .col-sm-12.col-lg-7
              h5 Resultados y acciones
              p Identificación de clientes en riesgo. 
              p Ofrecimiento de descuentos personalizados y mejoras en el servicio, para aumentar su fidelidad.
            .col-lg-5.d-none.d-lg-block
                img(src='@/assets/curso/t1/28.png', alt='')
    .bg-full-width.bg-fondo-2.mb-5(data-aos='flip-up')
      .px-4.px-md-5.pb-md-3
        h2.mb-3 Segmentación previa con K-Means
        p.mb-5 El algoritmo K-Means agrupa a los clientes en categorías, como "clientes fieles" o "clientes en riesgo", según su comportamiento.

        h2.mb-3 Ventajas de la analítica predictiva
        p.mb-5 La analítica predictiva es una herramienta clave para potenciar la estrategia organizacional.
        .row.justify-content-center.mb-0
          .col-sm-12.col-lg-4.mb-lg-0.mb-3
            .custom-image-card.h-100.br-15
              .custom-image-card__text.p-4
                .row.align-items-center.justify-content-center.mb-3
                  .col-lg-auto.d-none.d-lg-block
                    img(src='@/assets/curso/t1/29.svg', style='max-width: 90px').mx-auto
                h4.mb-2.text-center Anticipación de eventos
                p.mb-0.text-center Permite prever comportamientos futuros con base en datos históricos.
          .col-sm-12.col-lg-4.mb-lg-0.mb-3
            .custom-image-card.h-100.br-15
              .custom-image-card__text.p-4
                .row.align-items-center.justify-content-center.mb-3
                  .col-lg-auto.d-none.d-lg-block
                    img(src='@/assets/curso/t1/30.svg', style='max-width: 90px').mx-auto
                h4.mb-2.text-center Optimización de recursos
                p.mb-0.text-center Focaliza esfuerzos en áreas claves, para maximizar el retorno de inversión.
          .col-sm-12.col-lg-4.mb-lg-0.mb-3
            .custom-image-card.h-100.br-15
              .custom-image-card__text.p-4
                .row.align-items-center.justify-content-center.mb-3
                  .col-lg-auto.d-none.d-lg-block
                    img(src='@/assets/curso/t1/31.svg', style='max-width: 90px').mx-auto
                h4.mb-2.text-center Toma de decisiones estratégicas
                p.mb-0.text-center Proporciona información basada en evidencia, para respaldar planes de acción.


    h4.mb-4(data-aos='flip-up') Las limitaciones de la analítica predictiva: 
    .row.justify-content-center.mb-5(data-aos='flip-up')
      .col-sm-12.col-lg-6.mb-lg-0.mb-3
        .custom-image-card.h-100.br-15
          .custom-image-card__text.p-4
            .row.align-items-center.justify-content-center.mb-3
              .col-lg-auto.d-none.d-lg-block
                img(src='@/assets/curso/t1/32.svg', style='max-width: 90px').mx-auto
            h4.mb-2.text-center Dependencia de calidad de los datos
            p.mb-0.text-center Dato incompletos o inconsistentes, reducen la precisión de los modelos.

      .col-sm-12.col-lg-6.mb-lg-0.mb-3
        .custom-image-card.h-100.br-15
          .custom-image-card__text.p-4
            .row.align-items-center.justify-content-center.mb-3
              .col-lg-auto.d-none.d-lg-block
                img(src='@/assets/curso/t1/33.svg', style='max-width: 90px').mx-auto
            h4.mb-2.text-center Requiere conocimientos avanzados
            p.mb-0.text-center Su implementación y análisis, exigen experiencia técnica y recursos especializados.

    p.mb-5(data-aos='flip-up') La analítica predictiva, transforma datos históricos en información valiosa para el futuro. Combinando técnicas como regresión, clasificación y segmentación, las empresas pueden optimizar decisiones estratégicas, mejorando su capacidad para anticiparse y adaptarse al mercado.
    .bg-full-width.bg-color-4.mb-5(data-aos='flip-up')
      .p-5
        .row.justify-content-center.align-items-center
          .col-lg-7
            h2.mb-4 Analítica prescriptiva: guía para optimizar decisiones y procesos.
            p.mb-4 Se invita a explorar los fundamentos de la analítica prescriptiva, una herramienta avanzada que transforma datos, en acciones estratégicas. Este enfoque no solo anticipa desafíos futuros, sino que también propone soluciones específicas, para maximizar los resultados.
            a.anexo.mb-4.bg-white.w-fit(:href='obtenerLink("/downloads/analitica_prescriptiva.pdf")' target='_blank')
              .anexo__icono(:style='{"background-color": "#FCDFDB"}')
                img(src='@/assets/template/icono-pdf.svg')
              .anexo__texto
                p <strong>Anexo. </strong> Analítica prescriptiva: guía para optimizar decisiones y procesos.
          .col-lg-5.d-none.d-lg-block
            img(src='@/assets/curso/t1/34.png', alt='')

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2 MATERIAL COMPLEMENTARIO
        .row.material-complem
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.
            //- Referencia con enlace 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/book.svg' :style='{"max-width":"16px"}')
              a(href='https://elibro.net/es/lc/elibrocom/titulos/228973' target='_blank' rel='noopener noreferrer') Alarcón García, R. E. & Bravo Jaico, J. L. (Dir.). (2021). Sistema analítico basado en un modelo predictivo de procesamiento de datos en la Big Data en la Educación Superior. D - Universidad Señor de Sipán.
            
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style='{"max-width":"16px"}')
              a(href='https://www.redalyc.org/articulo.oa?id=344251476001' target='_blank' rel='noopener noreferrer') Hernández-Leal, E. J., Duque-Méndez, N. D. & Moreno-Cadavid, J. (2017). Big Data: una exploración de investigaciones, tecnologías y casos de aplicación. TecnoLógicas, 20(39), pp. 15-38.
            
            
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style='{"max-width":"16px"}')
              a(href='https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwi_16CtjaqKAxXKpVoFHWcfEH0YABAGGgJ2dQ&co=1&ase=2&gclid=CjwKCAiAmfq6BhAsEiwAX1jsZyV-GsicmWvyZ4UDt0h6kE8iknIy8JqB1vGMoGKx2ZM3m9wsm1P5pRoCF34QAvD_BwE&ohost=www.google.com&cid=CAESVuD2oLinDIE1KIUkwa71fD4ZE0krJpRhP8OYJsNgLvkJe9cWI5GXYjq8Cht0RTWRGmlwITfTSOIwcaJwD44mc1CHcQpZyPdqQCMrn71AHg4C0KLizV_V&sig=AOD64_1wjiJ-YKlimXyF-eXgT9USMwltkA&q&nis=4&adurl&ved=2ahUKEwiStZutjaqKAxVNTjABHf-CL3YQ0Qx6BAgNEAE' target='_blank' rel='noopener noreferrer') Unisys. (s.f.). Data Analytics Solutions.
            
            
            //- Referencia de youtube 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style='{"max-width":"16px"}')
              a(href='https://www.youtube.com/playlist?list=PLIOfVkvrHKVQFde9HMXKPB6UKacvVJq2t' target='_blank' rel='noopener noreferrer') Data_Pathfinder. (2024). Creación de un dashboard completo: gestión de datos, medidas y diseño visual [video]. YouTube.
            
            
          .col-12.col-md-6.col-lg-3.offset-lg-1.d-none.d-lg-block
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.tabs-content
  background-color: $color-sistema-h
.img-infografica
  background-color: $color-adicional-1
</style>
