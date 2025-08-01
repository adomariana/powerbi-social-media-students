# powerbi-social-media-students
Análisis exploratorio con Power BI sobre el uso de redes sociales y su impacto en estudiantes, basado en datos públicos de Kaggle.

# 📊 Análisis de Datos Públicos en Power BI  
### Actividad 1 - Curso Calidad de Datos (SADIO)  
**Estudiante:** Mariana Adó  
**Docente:** Roxana Martínez  

Este proyecto presenta un análisis exploratorio visual a partir del dataset [**Social Media Addiction vs. Relationships**](https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships), que contiene datos anónimos de estudiantes entre 18 y 25 años sobre el uso de redes sociales y su impacto en distintos aspectos de su vida académica y personal.

---

## 📁 Archivos incluidos

- `Actividad 1_Mariana_Ado.pbix`: archivo de Power BI con el informe interactivo.
- `Actividad 1 Mariana Ado.pdf`: documento explicativo con los pasos realizados y análisis de resultados.

---

## 🔍 Descripción del dataset

El conjunto de datos incluye variables como:
- Edad, género y país.
- Estado civil y nivel académico.
- Horas diarias de sueño.
- Uso diario de redes sociales (cantidad de horas, plataformas utilizadas).
- Índice de adicción a las redes sociales (1 a 10).
- Percepción del impacto en el rendimiento académico.

📎 Dataset original disponible en:  
[https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships](https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships)

---

## 🔧 Pasos realizados (basado en CRISP-DM)

1. **Comprensión del negocio:**  
   Se buscó identificar posibles relaciones entre el uso de redes sociales, el rendimiento académico y el bienestar de jóvenes estudiantes.

2. **Comprensión de los datos:**  
   Revisión exploratoria del dataset original de Kaggle y sus principales variables.

3. **Preparación de los datos:**
   La preparación de los datos se realizó utilizando **Power Query**, la herramienta de transformación de datos integrada en Power BI.  
   - Traducción de categorías al español.  
   - Corrección de errores en variables numéricas (horas mal formateadas).  
   - Creación de medidas y columnas calculadas.

5. **Modelado y visualización:**  
   - Construcción de dashboard en Power BI.  
   - Uso de gráficos de barras, segmentaciones y gráfico de dispersión.

6. **Análisis de resultados:**  
   Se observaron algunos patrones relevantes:
   - Mayor uso de redes sociales se asocia con menos horas de sueño.
   - Percepción negativa del rendimiento académico vinculada al uso intensivo.
   - Diferencias según edad, género y nivel académico.

📄 Para un análisis más detallado con gráficos y explicaciones, ver el archivo [`Actividad 1 Mariana Ado.pdf`](./Actividad%201%20Mariana%20Ado.pdf).

---

## ▶️ Cómo visualizar el informe en Power BI

1. Asegurate de tener **Power BI Desktop** instalado.  
   Podés descargarlo gratis desde:  
   👉 https://powerbi.microsoft.com/desktop/

2. Descargá el archivo `Actividad 1_Mariana_Ado.pbix` desde este repositorio.

3. Abrí Power BI Desktop y seleccioná **Archivo → Abrir** para explorar el informe.

4. Interactuá con los gráficos, filtrá por edad, género o nivel académico y observá los patrones en los datos.

---

## 📌 Observaciones

- El análisis es exploratorio y descriptivo.
- Aún resta traducir los nombres de países al español.
- Puede extenderse a modelos predictivos o agrupamientos en futuras iteraciones.
