# Proyecto: Análisis de Evasión de Clientes - Telecom X

## Propósito del análisis
Telecom X enfrenta una tasa creciente de cancelaciones de servicios. Este proyecto tiene como objetivo identificar las causas principales de esta evasión de clientes (Churn) mediante un flujo de trabajo de análisis de datos profesional.

El análisis proporciona un diagnóstico claro sobre el comportamiento de los usuarios, permitiendo que el equipo de Data Science desarrolle modelos predictivos y que el área de negocio implemente estrategias de retención efectivas.

## Estructura del proyecto
El proyecto está organizado de la siguiente manera para facilitar su comprensión y replicabilidad:

**Notebook Principal:** Contiene todo el proceso de ETL, EDA y conclusiones.

* **Extracción:** Carga de datos JSON y normalización de columnas anidadas.

* **Tratamiento:** Limpieza de nulos, corrección de formatos y creación de la métrica Cargo diario.

* **EDA:** Visualizaciones estratégicas con Matplotlib y Seaborn.

* **Reporte final:** Traducción de gráficas a insights y recomendaciones.

## Tecnologías utilizadas
* Python
* Pandas
* Matplotlib & Seaborn
* Google Colab

## Insights obtenidos
Durante el análisis exploratorio, se destacaron tres factores críticos que impulsan la evasión:

* **Antigüedad:** Se detectó que el mayor riesgo de abandono ocurre en los primeros 6 meses de vida del cliente.

* **Método de Pago:** Los clientes con pagos automáticos son significativamente más leales que aquellos que realizan pagos manuales (cheque electrónico).

* **Tipo de Contrato:** Los contratos mes a mes presentan la mayor volatilidad, especialmente cuando se combinan con cargos mensuales altos.

* **Servicios:** La vinculación del cliente aumenta cuando se incluyen servicios de soporte técnico y seguridad online, creando una mayor barrera de salida positiva.

## Instrucciones para ejecutar el Notebook

Para replicar este análisis, sigue estos pasos:

**1. Abrir en Google Colab:** Sube el archivo .ipynb o ábrelo directamente desde el enlace del repositorio.

**2. Instalar dependencias:** Asegúrate de tener instaladas las bibliotecas necesarias ejecutando la primera celda:

* import pandas as pd
* import seaborn as sns
* import matplotlib.pyplot as plt

> Conexión con la Base de Datos: El notebook está configurado para conectarse automáticamente a la URL del repositorio de GitHub que contiene el archivo JSON. No es necesario descargar archivos locales.

**3. Ejecución:** Ejecuta las celdas en orden secuencial para observar el proceso de limpieza, la generación de gráficas y los resultados finales.
