# Análisis de Temperaturas en Estaciones Meteorológicas de Chile

Este proyecto corresponde a un examen de programación en Python aplicado al análisis de datos meteorológicos.  
Se utiliza un dataset de estaciones meteorológicas de Chile para estudiar las temperaturas mínimas, máximas y la variación térmica en distintas regiones del país.  

---

## 📂 Contenido del repositorio

- `Examen_Programacion_Python.ipynb`: Notebook principal con todo el desarrollo, análisis y visualizaciones.
- `README.md`: Este archivo, con la descripción del proyecto y las instrucciones de uso.
- (Opcional) `data/`: Carpeta donde colocar el dataset si se incluye en el repositorio.

---

## 📊 Objetivos del análisis

1. Implementar funciones para:
   - Calcular el rango diario de temperatura.
   - Clasificar días como fríos, templados o calurosos según temperatura máxima.
   - Obtener cuantiles mensuales de temperaturas máximas por estación.

2. Responder preguntas clave:
   - Fecha con la mayor variación térmica en la estación C.M.A. Eduardo Frei Montalva (Antártica).
   - Número de días calurosos registrados en el año 2012.
   - Estación y mes con la temperatura máxima más alta.
   - Estación y mes con la temperatura máxima más baja.
   - Mes más frío y mes más caluroso por estación.

3. Visualizaciones:
   - Serie temporal de **TMaxima** y **TMinima** para la estación **Chacalluta, Arica Ap.**
   - Gráfico de barras de la media y desviación estándar de **TMaxima** por mes.
   - Identificación de días extremadamente cálidos (≥ P99).
   - Boxplot del rango de temperaturas por mes y estación.

---

## 🛠️ Tecnologías utilizadas

- Python 3.x
- Bibliotecas:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

---

## 📥 Dataset

El notebook trabaja con un dataset meteorológico que incluye registros diarios de temperatura mínima, máxima y fecha de diversas estaciones de Chile.  

⚠️ **Nota:** Por temas de tamaño/licencia, el dataset **no se incluye** directamente en este repositorio.  
Debes colocarlo en la carpeta `data/` o modificar la ruta en el notebook.  

---

## 🚀 Instrucciones de uso

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/usuario/analisis-temperaturas.git
   cd analisis-temperaturas

2. Crear un entorno virtual e instalar dependencias:
   python -m venv venv
  source venv/bin/activate   # En Linux/Mac
  venv\Scripts\activate      # En Windows
  pip install -r requirements.txt

4. Ejecutar Jupyter Notebook y abrir el archivo:
   jupyter notebook Examen_Programacion_Python.ipynb

## 📌 Conclusiones principales

- La mayor variación térmica se registró en la Antártica, donde las condiciones extremas favorecen diferencias marcadas entre el día y la noche.

- En 2012 se contabilizaron 19 días calurosos en Chile.

- El mes más frío y más caluroso varían según la estación, mostrando la diversidad climática del país.

- La estación Chacalluta, Arica Ap. registró tanto la temperatura máxima más alta como la más baja en el análisis, reflejando la importancia de revisar la consistencia de los datos.
