# 🧠 Proyecto Final - Optimización de Stock con BigQuery, Python y Power BI

Este proyecto corresponde al trabajo final del bootcamp de **Data Analytics de Soy Henry**.  

🔍 **Objetivo del proyecto**  
Determinar el **stock óptimo** de los más de **12.000 productos** que comercializa una empresa con **80 sucursales**, así como definir **estrategias para optimizar el capital de trabajo**, reduciendo costos de almacenamiento, logística y faltantes.

El dataset fue obtenido de Kaggle:  
📂 [Inventory Analysis Case Study – Kaggle](https://www.kaggle.com/datasets/bhanupratapbiswas/inventory-analysis-case-study)

---

## ✅ Etapas del proyecto

1. **Conexión a la base de datos en BigQuery**  
   Subida y estructuración del dataset para consultas eficientes.

2. **Análisis Exploratorio Inicial (EDA)**  
   - Tamaño y estructura de tablas  
   - Tipos de datos  
   - Estadísticas descriptivas (máximo, mínimo, media, moda)  
   - Detección de nulos y outliers  
   *(realizado en Python)*

3. **Procesamiento de datos (ETL)**  
   - Filtrado de columnas y registros  
   - Reemplazo de valores faltantes  
   - Detección y tratamiento de valores atípicos  
   - Aplicación de técnicas de Machine Learning (regresión lineal) para completar datos faltantes críticos

4. **Cálculo de Stock Óptimo**  
   Fórmula aplicada:  
   `Stock Óptimo = Stock Base + Stock de Seguridad`

5. **Análisis Exploratorio Final (EDA 2)**  
   - Visualización de variables clave mediante gráficos  
   - Detección de tendencias  
   *(realizado con Python y Power BI)*

6. **Visualización de resultados y estrategias**  
   - Dashboard final en Power BI con KPIs clave  
   - Conclusiones y recomendaciones de mejora

---

## 📁 Archivos del repositorio

- `📥 Anclaje_cloud.ipynb`: script para cargar, consultar y modificar datos en BigQuery.
- `📈 proyecto_final.ipynb`: análisis exploratorio, limpieza de datos, regresión y cálculo del stock óptimo.
- `📊 Power_bi_Amalia2.pbix`: visualización de resultados finales. *(agregar enlace si está publicado online)*
- `🗎 README.md`: este archivo.

---

## 🧪 Tecnologías y librerías utilizadas

- **Lenguaje:** Python 3.13  
- **Entorno:** Jupyter Notebook  
- **Base de datos:** Google BigQuery  
- **Visualización:** Power BI  
- **Librerías:**  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `scikit-learn`  
  - `category_encoders`

---

## 👥 Autores

- **Amalia Granata**  
- Jenny Ortiz  
- Luis Ladino  
- Noelia Calligaro

