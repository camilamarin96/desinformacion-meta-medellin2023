# Análisis de Segmentación y Desinformación en Publicidad Política en Meta – Elecciones Medellín 2023

Este repositorio contiene el código y los datos utilizados para el trabajo de grado enfocado en analizar las estrategias de segmentación utilizadas en publicidad política en la plataforma Meta (Facebook e Instagram) durante las elecciones a la Alcaldía de Medellín en 2023, con especial énfasis en los patrones de desinformación.

## 📁 Estructura del repositorio

### Archivos principales

- `1. Conexión_API_Facebook`: Código para conexión con la API de Meta y proceso de scrapeo de anuncios políticos.
- `2.TranscripciónWhisperOCR`: Procesamiento de imágenes y audios utilizando OCR (Tesseract) y Whisper de OpenAI para extraer texto de los anuncios.
- `3.Aplicacióndelibrerías_ipynb`: Aplicación de modelos de lenguaje y herramientas NLP para limpieza, tokenización y análisis textual.
- `4.Regresión_logística_Desinformación`: Análisis cuantitativo mediante regresión logística para identificar factores asociados a la presencia de desinformación.
- `5.Graficación`: Visualización de datos para comunicar hallazgos clave.
- `6.Metricas_validacion_cruzada`: Evaluación extendida del modelo de regresión logística mediante validación cruzada estratificada.
- `7.Reproduccion_Analisis_Desinformacion`: Pipeline de reproducibilidad  diseñado para que evaluadores externos puedan replicar los resultados principales del estudio.

### Datasets incluidos

- `Candidatos_probabilidad_consolidado.csv`: Base de datos con los anuncios publicados directamente por candidatos a la Alcaldía.
- `Páginas_probabilidad_consolidado.csv`: Base de datos con anuncios publicados por páginas que apoyaban a candidatos o temas asociados.
- `Aleatorizacion-DataSetCompleto (1) (1)-2.xlsx`: Base de datos con anuncios clasificados después de la aplicación de librerías

## 🔍 Objetivo del estudio

En este orden de ideas, este trabajo busca analizar el papel de los anuncios pagos en la propagación de información falsa, manipulada o inexacta durante la campaña para la Alcaldía de Medellín en 2023. Los objetivos específicos buscan 1) examinar cómo los candidatos segmentaron sus anuncios para impulsar sus publicaciones, 2) identificar el contenido pautado que contenía información manipulada, falsa o errónea y 3) describir las estrategias relacionadas con el lenguaje utilizado en la difusión de desinformación durante las elecciones.

## 🧰 Herramientas utilizadas

- Python 3.10
- Librerías: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `transformers`, `spanlp`, `whisper`, entre otras.
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

**María Camila Marín Álvarz**  
Comunicadora social – Trabajo de grado presentado para obtener el título de Politóloga]  
2025

---

