# 🎵 Análisis de hábitos de escucha musical

## 📌 Descripción del proyecto

Las plataformas de streaming musical generan grandes volúmenes de información sobre las preferencias y hábitos de consumo de sus usuarios. En este proyecto se analizan datos de reproducción musical de dos ciudades, **Springfield** y **Shelbyville**, con el objetivo de identificar posibles diferencias en los patrones de escucha según la ubicación y el día de la semana.

A través de un proceso de limpieza, transformación y análisis exploratorio de datos, se busca comprender cómo varía la actividad de los usuarios y responder preguntas de negocio basadas en evidencia.

---

## 🎯 Objetivo

Determinar si existen diferencias en la actividad de escucha musical entre los usuarios de Springfield y Shelbyville, así como analizar cómo cambia el comportamiento de escucha a lo largo de la semana.

---

## 📂 Conjunto de datos

El dataset contiene información sobre reproducciones musicales realizadas por usuarios de ambas ciudades.

### Variables analizadas

| Variable | Descripción                     |
| -------- | ------------------------------- |
| userID   | Identificador único del usuario |
| Track    | Nombre de la canción            |
| artist   | Artista de la canción           |
| genre    | Género musical                  |
| City     | Ciudad del usuario              |
| time     | Hora de reproducción            |
| Day      | Día de la semana                |

---

## 🛠️ Herramientas utilizadas

* Python
* Pandas
* Jupyter Notebook
* Git
* GitHub

---

## 🔎 Metodología

### 1. Comprensión de los datos

Se realizó una exploración inicial para conocer la estructura del conjunto de datos y detectar posibles problemas de calidad.

### 2. Limpieza y preparación

Durante esta etapa se llevaron a cabo las siguientes actividades:

* Corrección de nombres de columnas.
* Identificación y tratamiento de valores ausentes.
* Eliminación de registros duplicados.
* Estandarización de categorías con errores de escritura.

### 3. Análisis exploratorio

Se analizaron los patrones de escucha considerando:

* Diferencias entre ciudades.
* Actividad musical según el día de la semana.
* Comportamiento general de los usuarios.

### 4. Interpretación de resultados

Finalmente, se evaluaron los hallazgos para determinar si existían diferencias en los hábitos de escucha entre Springfield y Shelbyville.

---

## 📊 Principales hallazgos

* Springfield registró un mayor volumen total de reproducciones en comparación con Shelbyville.
* Se observaron variaciones en la actividad musical dependiendo del día de la semana.
* Los viernes presentaron una de las mayores cantidades de reproducciones en ambas ciudades.
* A pesar de las diferencias en el volumen total de escucha, ambas ciudades mostraron patrones de comportamiento similares durante la semana.

---

## 🚧 Retos encontrados y aprendizajes

Este proyecto representó una excelente oportunidad para comprender la importancia de la preparación de datos antes de realizar cualquier análisis.

Uno de los principales retos fue trabajar con información que contenía inconsistencias, valores ausentes y registros duplicados. Resolver estos problemas permitió entender cómo la calidad de los datos puede influir directamente en los resultados obtenidos.

También fue una experiencia valiosa para desarrollar habilidades de análisis exploratorio, ya que no sólo se trató de ejecutar código, sino de interpretar los resultados y transformarlos en conclusiones comprensibles.

Además, reforcé conceptos fundamentales relacionados con la manipulación de datos utilizando Pandas, así como la importancia de documentar cada paso del proceso analítico.

---

## 🔄 Próximas mejoras

Como parte de mi desarrollo profesional en análisis de datos, algunas mejoras futuras para este proyecto incluyen:

* Incorporar visualizaciones interactivas.
* Analizar patrones horarios de escucha.
* Explorar los géneros musicales más populares por ciudad.
* Realizar análisis estadísticos complementarios para validar los hallazgos.
  
---

## 👩‍💻 Autor

**Krystel C. Garcia**

Proyecto desarrollado como parte de mi formación en Análisis de Datos, aplicando técnicas de limpieza, transformación y análisis exploratorio de datos utilizando Python y Pandas.

