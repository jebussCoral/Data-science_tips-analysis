# Data-science_tips-analysis

# Data Science | Tips Analysis

Análisis exploratorio de datos (**EDA**) sobre un dataset clásico de propinas en un restaurante.  
El objetivo es usar técnicas básicas de análisis de datos con **Python (pandas, seaborn, matplotlib)**  
y presentar hallazgos de forma clara y visual.

---

##  Dataset
- **Fuente:** `tips` dataset incluido en Seaborn.  
- **Filas:** 244 registros  
- **Columnas:** 7 variables (`total_bill`, `tip`, `sex`, `smoker`, `day`, `time`, `size`)  
- **Descripción:** Cada fila representa una cuenta en un restaurante, con información del total, la propina y las características del cliente.  

---

## Análisis realizado
1. **Distribución de propinas** → la mayoría se concentran entre 2 y 3.  
2. **Propina por día** → los **domingos** tienen la media más alta.  
3. **Propina por género** → los hombres dejan ligeramente más que las mujeres.  
4. **Cuenta total vs propina** → existe una correlación positiva (cuanto más alta la cuenta, mayor la propina).  
5. **Tamaño del grupo** → los grupos grandes dejan más propina, aunque con mayor variabilidad.  

---

## Herramientas utilizadas
- Python 3.11  
- Jupyter Notebook  
- pandas  
- matplotlib  
- seaborn  

---

##  Archivos en este repositorio
- `analisis_tips.ipynb` → Notebook con el análisis completo.  
- `analisis_tips.html` → Informe exportado en formato HTML.  
- `README.md` → Este documento de presentación.  

---

## Conclusiones principales
- La propina promedio aumenta con el total de la cuenta y con el tamaño del grupo.  
- Existe cierta diferencia por género y día de la semana, aunque no tan marcada.  
- El dataset, aunque pequeño, es ideal para **aprender y practicar técnicas básicas de análisis de datos**.  

---

👤 Autor: *Jesus David Coral*  
📅 Fecha: Agosto 2025  
