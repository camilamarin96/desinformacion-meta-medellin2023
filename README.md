# Análisis de Segmentación y Desinformación en Publicidad Política en Meta – Elecciones Medellín 2023

Este repositorio contiene el código y los datos utilizados para el trabajo de grado enfocado en analizar las estrategias de segmentación utilizadas en publicidad política en la plataforma Meta (Facebook e Instagram) durante las elecciones a la Alcaldía de Medellín en 2023, con especial énfasis en los patrones de desinformación.

## 📁 Estructura del repositorio

### Archivos principales

- `conexion_api_scrapeo.ipynb`: Código para conexión con la API de Meta y proceso de scrapeo de anuncios políticos.
- `ocr_y_whisper.ipynb`: Procesamiento de imágenes y audios utilizando OCR (Tesseract) y Whisper de OpenAI para extraer texto de los anuncios.
- `aplicacion_librerias.ipynb`: Aplicación de modelos de lenguaje y herramientas NLP para limpieza, tokenización y análisis textual.
- `regresion_logistica.ipynb`: Análisis cuantitativo mediante regresión logística para identificar factores asociados a la presencia de desinformación.
- `graficacion.ipynb`: Visualización de datos para comunicar hallazgos clave.

### Datasets incluidos

- `candidatos_consolidado.csv`: Base de datos con los anuncios publicados directamente por candidatos a la Alcaldía.
- `paginas_consolidado.csv`: Base de datos con anuncios publicados por páginas que apoyaban a candidatos o temas asociados.

## 🔍 Objetivo del estudio

El proyecto busca identificar si existen patrones de segmentación diferenciada (por edad, sexo y región) en anuncios con características desinformativas y qué candidatos o páginas los implementaron. Se aplican modelos de lenguaje, clasificación y análisis estadístico.

## 🧰 Herramientas utilizadas

- Python 3.10
- Librerías: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `transformers`, `spanlp`, `tesseract`, `whisper`, entre otras.
- Modelos: RoBERTuito, clasificación fine-tuned.
- Plataformas: Meta Ad Library API, Google Colab.

## 📜 Créditos y referencias

- Pérez Palau, Daniel, Xiomara Blanco, Almudena Ruiz-Iniesta, Oscar De Gregorio Vicente, Juan José Cubillas, Elias Said-Hung, y Julio Montero-Diaz.  
  *Informe técnico desarrollo de algoritmo de clasificación de odio por tipo, en medios informativos digitales españoles en X (Twitter), Facebook y portales web*. figshare, 2024.  
  https://doi.org/10.6084/M9.FIGSHARE.26314360.V1

- Pérez, J. M., Furman, D. A., Alonso Alemany, L., & Luque, F. M. (2022).  
  *RoBERTuito: A pre-trained language model for social media text in Spanish*.  
  Proceedings of the Thirteenth Language Resources and Evaluation Conference (pp. 7235–7243). European Language Resources Association.

- Puentes, J. F. (2022).  
  *spanlp: NLP tools for Spanish (v1.0.0)* [Computer software]. GitHub.  
  https://github.com/jfreddypuentes/spanlp

## 🧑‍💻 Autora

**María Camila [Tu Apellido]**  
Comunicadora social – Trabajo de grado presentado para [Nombre de tu universidad]  
2025

---

Si encuentras útil este repositorio, no dudes en darle ⭐ o compartirlo.

