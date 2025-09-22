# ✈️ Análisis de Retrasos de Vuelos en EE.UU.

Este proyecto analiza retrasos de vuelos en Estados Unidos utilizando Python y Jupyter Notebooks.  
El objetivo es identificar patrones de retrasos por **origen, destino y causas principales**, y generar recomendaciones para mejorar la puntualidad.

---

## 📂 Estructura del repositorio
├── data/
│ ├── flights_202301.csv
│ ├── flights_merged.csv
│ ├── flights_typed.csv
│ ├── AIRLINE_CODE_DICTIONARY.csv
│ └── DOT_CODE_DICTIONARY.xlsx
│
├── notebooks/
│ ├── Proyecto3_Vuelos.ipynb
│ └── Proyecto3_Vuelos_voila_v2.ipynb
│
├── outputs/
│ ├── Analisis_Retrasos.pptx
│ ├── Analisis_Retrasos.pdf
│ └── requirements_voila.txt
│
└── README.md


---

## 🚀 Metodología

1. **Carga y limpieza de datos**  
   - Integración de múltiples datasets de vuelos (DOT, aerolíneas, aeropuertos).  
   - Estandarización de columnas y tipos de datos.  

2. **Análisis exploratorio (EDA)**  
   - Retrasos por ruta, origen y destino.  
   - Identificación de causas más frecuentes.  
   - Cálculo del tiempo promedio de retraso.  

3. **Visualización de resultados**  
   - Gráficas interactivas en notebooks.  
   - Presentación ejecutiva en PowerPoint/PDF.  

---

## 📊 Principales hallazgos

- Algunos **aeropuertos regionales y turísticos** presentan los mayores porcentajes de retrasos.  
- El **tiempo promedio de retraso** varía considerablemente por ruta y condiciones climáticas.  
- Se identificaron **causas recurrentes** ligadas a clima, congestión y factores operativos.  

---

## 📑 Presentación

Vista previa de la presentación de resultados:  

[![Ver presentación](outputs/ppt_preview/slide1.jpg)](outputs/Analisis_Retrasos.pdf)  

> 📌 Haz clic en la imagen para abrir la presentación completa en PDF.  

---

## 🔧 Requerimientos

Instala las dependencias necesarias desde el archivo `requirements_voila.txt`:

```bash
pip install -r outputs/requirements_voila.txt


