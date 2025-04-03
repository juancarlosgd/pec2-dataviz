# Visualización de Datos – PEC 2

Este repositorio contiene la solución a la **PEC 2 de la asignatura Visualización de Datos** del **Máster Universitario de Ciencia de Datos** en la **Universitat Oberta de Catalunya (UOC)**.

## 🔍 Descripción general

El trabajo consiste en la publicación de **tres visualizaciones interactivas** que exploran distintas técnicas de representación visual de datos, junto con su respectiva contextualización teórica. Las visualizaciones están publicadas online y se acompañan de un vídeo explicativo y un documento complementario.

---

## 📊 Visualizaciones

### 1. 📈 Line Chart

**Descripción:**  
Visualización de series temporales que muestra la evolución y correlación de la producción alimentaria en el mundo comparada con la subalimentación.  

**Tecnología usada:** Tableau Public  
**Enlace:**  
🔗 https://public.tableau.com/app/profile/juan.carlos.gomez.delgado/viz/LineChart_17434909916700/Dashboard1

---

### 2. 🗺️ Mapa con gráficos de torta

**Descripción:**  
Visualización geográfica con gráficos circulares superpuestos, que muestran la proporción de ocupación/desempleo por género en diferentes departamentos de Colombia.  

**Tecnología usada:** Tableau Public  
**Enlace:**  
🔗 https://public.tableau.com/app/profile/juan.carlos.gomez.delgado/viz/mapa_final_17436084265610/Dashboard1

---

### 3. 🌐 Árbol Hiperbólico (Hyperbolic Tree)

**Descripción:**  
Exploración jerárquica interactiva de la oferta académica actual en Colombia (programas activos con código SNIES aprobado).  

**Tecnología usada:** [d3-hypertree](https://github.com/glouwa/d3-hypertree) en JavaScript Vainilla.  
La visualización fue desarrollada de forma totalmente estática, sin frameworks adicionales, integrando datos jerarquizados en formato JSON adaptado al modelo hiperbólico.

**Enlace online:**  
🔗 [Explorar árbol hiperbólico de programas SNIES](https://juancarlosgd.github.io/pec2-dataviz/)

---

## 📁 Contenido del repositorio

- `index.html`: Página principal con navegación entre visualizaciones.
- `programas.d3.json`: Archivo de datos estructurados con jerarquía basada en nivel académico, modalidad, tipo de institución, clasificación y programas SNIES.
- Recursos gráficos e íconos utilizados en la interfaz.
- `README.md`: Este archivo.

---

## 📚 Créditos y Licencias

- Las visualizaciones fueron desarrolladas por **Juan Carlos Gómez Delgado** como parte del itinerario académico de la UOC.
- La librería [d3-hypertree](https://github.com/glouwa/d3-hypertree) es un proyecto open-source con licencia MIT.
- Los datos utilizados provienen del **DANE**, el **Ministerio de Educación Nacional de Colombia** y otras fuentes públicas.
