# Análisis de Clientes: ConnectaTel 📊

## 🎯 Objetivo del Proyecto
Este proyecto tiene como objetivo evaluar el comportamiento de los clientes de **ConnectaTel**, una empresa de telecomunicaciones en Latinoamérica. El análisis se centra en datos registrados hasta el año **2024**, buscando construir perfiles estadísticos, detectar comportamientos atípicos (outliers) y segmentar a los usuarios para proponer estrategias de retención y mejoras comerciales.

## 📂 Datasets Utilizados
El análisis integra tres fuentes de datos principales:
* **`plans.csv`**: Detalles de los planes (precios, minutos/GB incluidos y costos por excedentes).
* **`users.csv`**: Información demográfica (edad, ciudad, fecha de registro, plan y churn).
* **`usage.csv`**: Registro del uso real de servicios (cantidad de llamadas y mensajes).

## 🛠️ Etapas del Análisis
El flujo de trabajo se dividió en las siguientes fases:
1. **Carga y Exploración**: Validación inicial de estructuras y tipos de datos.
2. **Limpieza de Datos**: Tratamiento de valores nulos, corrección de valores centinela (como edades `-999`) y filtrado de fechas inconsistentes (registros del año 2026).
3. **Fusión de Datos**: Consolidación de tablas para crear un perfil de usuario unificado.
4. **Análisis Estadístico**: Uso de histogramas y boxplots para identificar patrones de distribución y valores atípicos.
5. **Segmentación y Conclusiones**: Clasificación de clientes por edad y nivel de uso para generar recomendaciones estratégicas.

## 🚀 Cómo ejecutar el proyecto
Para reproducir este análisis en tu entorno local o en la nube:
1. Clona este repositorio.
2. Asegúrate de tener instaladas las librerías: `pandas`, `matplotlib` y `seaborn`.
3. Sube el notebook (`.ipynb`) a **Google Colab** o ábrelo en **Jupyter Notebook**.
4. Coloca los archivos `.csv` en la misma ruta que el notebook.
5. Ejecuta las celdas en orden secuencial para observar el procesamiento y las visualizaciones.

## 💡 Principales Hallazgos
* Se identificaron **outliers** en el consumo de mensajes y llamadas que representan a los usuarios de mayor valor para la empresa.
* No existe una diferencia significativa en el volumen de uso entre los planes Básico y Premium, lo que sugiere la necesidad de rediseñar los beneficios del plan superior.
* La base de clientes es demográficamente equilibrada, con un núcleo sólido de usuarios de mediana edad.

---
