# Analisis de Uso de Servicios Moviles | ConnectaTel
Proyecto de análisis de datos con Python enfocado en el comportamiento de clientes de una empresa de telecomunicaciones. Se realizaron procesos de limpieza, EDA, segmentación de usuarios, detección de outliers y generación de recomendaciones de negocio basadas en datos.

## 📖 Descripción

Este proyecto analiza el comportamiento de uso de los servicios móviles de los clientes de **ConnectaTel**, una empresa de telecomunicaciones con operaciones en México y Colombia.

A partir de datos de clientes, planes contratados y registros de llamadas y mensajes, se realizó un proceso de exploración, limpieza y análisis de datos para identificar patrones de consumo, segmentar usuarios y generar recomendaciones que apoyen la toma de decisiones comerciales.

---

## 🎯 Objetivo del proyecto

Analizar el uso de los servicios móviles para:

- Comprender los patrones de consumo de llamadas y mensajes.
- Detectar posibles problemas de calidad en los datos.
- Identificar comportamientos atípicos mediante análisis exploratorio.
- Segmentar a los clientes por edad y nivel de uso.
- Generar insights y recomendaciones que contribuyan a optimizar la oferta comercial y mejorar la experiencia del cliente.

---

## 📂 Datasets utilizados

El análisis se realizó utilizando tres conjuntos de datos:

| Dataset | Descripción |
|----------|-------------|
| **plans.csv** | Información de los planes disponibles, incluyendo precio mensual, minutos y GB incluidos, así como costos por consumo adicional. |
| **users_latam.csv** | Información de los clientes: edad, ciudad, fecha de registro y plan contratado. |
| **usage.csv** | Registros de uso de los servicios móviles, incluyendo llamadas y mensajes enviados por los usuarios. |

---

## 🔎 Etapas del análisis

El proyecto se desarrolló siguiendo las siguientes etapas:

1. Exploración inicial de los datos.
2. Revisión de la calidad de los datos.
3. Identificación y tratamiento de valores faltantes y sentinels.
4. Conversión y validación de fechas.
5. Análisis exploratorio de variables numéricas y categóricas.
6. Análisis de distribuciones mediante histogramas y boxplots.
7. Identificación de valores atípicos utilizando el método IQR.
8. Segmentación de usuarios por grupo de edad y nivel de uso.
9. Elaboración de insights y recomendaciones de negocio.

---

## 🚀 Cómo ejecutar el notebook

### Google Colab 

1. Descarga este repositorio o clónalo en tu equipo.
2. Accede a **Google Colab**.
3. Selecciona **Archivo → Subir notebook**.
4. Abre el archivo `.ipynb`.
5. Sube los archivos:
   - `plans.csv`
   - `users_latam.csv`
   - `usage.csv`
6. Ejecuta las celdas en orden desde el inicio.

---

## ▶️ Guía de reproducción

Para reproducir el análisis:

1. Coloca los archivos `.csv` en la misma carpeta que el notebook.
2. Ejecuta las celdas de importación de librerías.
3. Carga los tres conjuntos de datos.
4. Ejecuta la limpieza y validación de los datos.
5. Continúa con el análisis exploratorio y la generación de visualizaciones.
6. Revisa el análisis ejecutivo y las recomendaciones finales.

---

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- Seaborn
- Matplotlib
- Google Colab / Jupyter Notebook

---

## 📈 Principales resultados

- Se identificaron y corrigieron problemas de calidad de datos antes del análisis.
- La mayor parte de los clientes pertenece al segmento de **uso medio**.
- Los **adultos** representan el grupo con mayor participación dentro de la base de clientes.
- Las distribuciones de llamadas y mensajes presentan un sesgo hacia la derecha, indicando que la mayoría de los usuarios tiene un consumo moderado.
- Los valores atípicos corresponden a usuarios con un consumo elevado y se conservaron por representar comportamientos reales del negocio.

---

## 👩‍💻 Autor

**Martha Eréndira Martínez Márquez**

Proyecto desarrollado como parte del Bootcamp de Data Analytics de TripleTen.
