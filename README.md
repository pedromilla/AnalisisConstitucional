## Análisis Constitucional 2023 para Chile: Un Desglose Exhaustivo

En el contexto del Procesamiento de Lenguaje Natural (PLN) y la exploración de datos, este proyecto tiene como objetivo realizar un análisis de la propuesta de texto constitucional propuesto para Chile en el año 2023. A continuación, se detalla cada fase del proceso, destacando las técnicas y herramientas empleadas para obtener información valiosa.

## 1. Extracción y Estructuración del Texto Constitucional:

Comenzamos nuestro análisis extrayendo el texto constitucional de un archivo PDF y estructurándolo en formato DataFrame. La herramienta PyMuPDF se utilizó para esta tarea, permitiéndonos navegar a través de las páginas del documento y extraer el contenido relevante.

## 2. Limpieza y Exploración de Datos:

Antes de realizar análisis más profundos, llevamos a cabo una limpieza de datos para garantizar la coherencia y calidad del texto. Identificamos y eliminamos información no relevante, como encabezados de página, y exploramos las características fundamentales, como capítulos y artículos, para tener una visión general del contenido constitucional.

## 3. Análisis Estadístico:

Implementamos un análisis estadístico detallado sobre el texto, calculando métricas como el número de capítulos, artículos, palabras y caracteres. Utilizamos herramientas como pandas y matplotlib para visualizar estos datos de manera comprensible, proporcionando una comprensión cuantitativa de la extensión y complejidad del documento constitucional.

## 4. Procesamiento de Texto:

Aplicamos técnicas de procesamiento de texto, utilizando la biblioteca spaCy, para limpiar y normalizar el contenido constitucional. Creamos funciones específicas para eliminar caracteres no deseados, números y stopwords, y lematizamos el texto para obtener una representación más precisa de las palabras clave.

## 5. Modelado de Tópicos:

Implementamos un modelo de tópicos utilizando la técnica Latent Dirichlet Allocation (LDA) junto con TF-IDF. Esta fase nos permitió identificar temas clave presentes en el texto constitucional y generar una comprensión más profunda de los aspectos temáticos que aborda el documento.

## 6. Visualizaciones y Wordclouds:

Complementamos nuestro análisis con visualizaciones gráficas, incluyendo wordclouds de términos más frecuentes y representaciones visuales de la distribución de palabras clave en el texto constitucional. Estas visualizaciones ayudan a destacar elementos destacados y patrones importantes.

## 6. Generación de Resúmenes Automáticos:

Utilizando el modelo preentrenado BERT2BERT, desarrollamos un proceso para generar resúmenes automáticos del contenido constitucional. Ajustamos parámetros como la longitud máxima y mínima del resumen, así como el número de beams, para obtener resúmenes coherentes y significativos.

Este estudio representa un esfuerzo integral para desglosar y entender el texto constitucional propuesto para Chile en 2023, utilizando herramientas avanzadas de procesamiento de lenguaje natural y análisis de datos. Cada etapa del proceso contribuye a una comprensión más completa de los elementos clave presentes en el documento, facilitando la toma de decisiones informada y estratégica.
