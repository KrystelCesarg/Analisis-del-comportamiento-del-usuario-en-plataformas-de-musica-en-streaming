# Análisis del Comportamiento del Usuario en Plataforma de Música en Streaming

## 🎯 Problema de Negocio
Las plataformas de streaming dependen del análisis del comportamiento de sus usuarios para mitigar el abandono de la plataforma (*churn*) y optimizar el compromiso (*engagement*) con el producto. Este proyecto analiza los registros de reproducción musical de dos ciudades distintas (Springfield y Shelbyville) para identificar variaciones de comportamiento, preferencias regionales y patrones semanales de uso con el fin de guiar estrategias de contenido localizadas.

## 📊 Conjunto de Datos
El dataset registra los logs individuales de reproducción de música e incluye las siguientes variables clave:
* `userID` (ID de usuario), `Track` (Canción), `artist` (Artista), `genre` (Género), `City` (Ciudad), `time` (Hora) y `Day` (Día de la semana).

## 🔍 Análisis y Metodología
1. **Saneamiento de Datos:** Corrección de inconsistencias estructurales en los nombres de las columnas, identificación y tratamiento de campos con valores ausentes y eliminación de duplicados.
2. **Estandarización de Texto:** Resolución de errores de escritura en variables categóricas críticas como los géneros musicales (`genre`).
3. **Analítica Exploratoria (EDA):** Segmentación de la actividad de los usuarios según su ubicación geográfica y el día de la semana para identificar tendencias estacionales y de comportamiento.

## 💡 Hallazgos Clave
* **Asimetría en el Volumen de Consumo:** Springfield registra un volumen total de reproducciones considerablemente mayor en comparación con Shelbyville.
* **Sincronización de Comportamiento:** A pesar de la diferencia en los volúmenes totales de escucha, las tendencias de comportamiento a lo largo de la semana están altamente sincronizadas entre ambas ciudades.
* **Pico de Compromiso en Fin de Semana:** El viernes se consolidó como el día de mayor actividad y *engagement* para ambas regiones urbanas.

## 🚀 Recomendaciones Estratégicas
* **Campañas de Marketing Localizadas:** Concentrar los esfuerzos de comunicación y recomendaciones de contenido los jueves por la tarde para capitalizar el repunte natural de escucha que ocurre los viernes.
* **Replicabilidad de Estrategias de Engagement:** Dado que los patrones de comportamiento semanales son consistentes entre ambas poblaciones, las estrategias de retención y activadores de uso que tengan éxito en Springfield pueden replicarse con total confianza en Shelbyville para impulsar su crecimiento.

## 🛠️ Herramientas y Tecnologías
Python 3 (Pandas - Manipulación, agregación y limpieza de datos).
