# Caso de estudio Cyclistic

Análisis de datos orientado a comprender las diferencias de
comportamiento entre usuarios ocasionales y miembros anuales de
Cyclistic, con el objetivo de generar recomendaciones para aumentar las
membresías.

<p align="center">
  <img src="https://img.shields.io/badge/Google-Data_Analytics-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Data Analytics">
  <img src="https://img.shields.io/badge/Data_Analysis-Case_Study-009688?style=for-the-badge&logo=databricks&logoColor=white" alt="Case Study">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Status">
</p>

---

## Índice de Contenidos
- [Objetivo](#objetivo)
- [Metodología](#metodología)
- [Datos y Procesamiento](#datos-y-procesamiento)
- [Resultados y Recomendaciones](#resultados-y-recomendaciones)
- [Autor](#autor)

---

## Objetivo

Responder la pregunta de negocio:

> ¿Cómo utilizan de manera diferente las bicicletas de Cyclistic los
> miembros anuales y los usuarios ocasionales?

El proyecto busca transformar los patrones observados en los viajes en
acciones de marketing que puedan probarse y medirse.

## Metodología

El análisis sigue el ciclo de análisis de datos de Google:

-   Ask: definición del problema de negocio.
-   Prepare: revisión y consolidación de los datos de viajes.
-   Process: limpieza, validación y creación de variables analíticas.
-   Analyze: comparación de volumen, duración y comportamiento temporal
    entre `member` y `casual`.
-   Share: comunicación de hallazgos mediante visualizaciones y
    conclusiones.
-   Act: recomendaciones de marketing y propuesta de experimentación.

## Datos y procesamiento

Se utilizan archivos históricos de viajes de Cyclistic/Divvy. Los datos
se consolidan y se generan variables como:

-   `ride_length`: duración del viaje en minutos.
-   `day_of_week` y `day_name`: día de la semana.
-   `month`: mes del viaje.
-   `hour`: hora de inicio.

Como controles de calidad se verifican identificadores duplicados,
fechas válidas, segmentos válidos y duraciones de los viajes. Los
`ride_id` duplicados se deduplican y los viajes con duración inferior a
un minuto se excluyen del análisis final para evitar distorsionar los
resultados.

## Resultados y recomendaciones

El análisis compara los patrones de uso de miembros y usuarios
ocasionales y utiliza esos patrones para proponer acciones de marketing.

Las principales líneas de acción son:

1.  **Segmentación por comportamiento:** identificar usuarios
    ocasionales cuyos patrones se aproximen a los de los miembros.
2.  **Activación por momento:** utilizar días y franjas horarias
    relevantes para probar comunicaciones y ofertas contextualizadas.
3.  **Experimentación:** comparar distintas propuestas de membresía
    mediante un test controlado y medir principalmente la conversión.

La recomendación es medir el recorrido completo:

**exposición → interacción → oferta → conversión → permanencia**

antes de escalar una campaña.

---

## Autor

Desarrollado por **José Aníbal Modad**  
* **GitHub:** [@turkoModad](https://github.com/turkoModad)
* **Enfoque:** Analítica de Datos, Ciclo de Análisis de Google, Business Intelligence y Estrategia de Negocio.
