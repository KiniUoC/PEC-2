# PEC 2: Estudio de Técnicas de Visualización

###  **Enlace al portal de visualizaciones: https://kiniuoc.github.io/PEC-2/**

Este repositorio contiene la entrega de la Práctica de Evaluación Continua 2 (PEC 2) para la asignatura **M2.859 | [cite_start]Visualización de Datos** del Máster de Ciencia de Datos de la UOC[cite: 2413].

## Objetivo de la Práctica

El objetivo principal de esta práctica es "salir de la zona de confort" de los gráficos básicos (barras, líneas, sectores) y explorar en profundidad tres técnicas de visualización asignadas.

El enfoque metodológico, tal como se pide en  el enunciado, consiste en trabajar "desde la técnica hacia los datos":
1.  **Investigar** a fondo la técnica (definición, ventajas, tipo de datos).
2.  **Seleccionar** un conjunto de datos abierto adecuado.
3.  **Implementar** la visualización usando la herramienta más apropiada (Flourish, Tableau, R/Python).
4.  **Publicar** el resultado en una URL accesible públicamente.

## Visualizaciones

Este proyecto (alojado en GitHub Pages) sirve como portal unificado para las tres técnicas:

---

### 1. Técnica (Grupo I): Gráfico de Área (Area Chart)

* **Descripción:** Un gráfico de área utilizado para mostrar la evolución del volumen de una variable cuantitativa a lo largo del tiempo.
* **Caso de Uso:** Visualización de la evolución del consumo de energía renovable en España (Datos: Our World in Data).
* **Herramienta:** Flourish.
* **Enlace:** **https://public.flourish.studio/story/3422275/**

---

### 2. Técnica (Grupo II) : Diagrama de Gantt

* **Descripción:** Un tipo de gráfico de barras que ilustra el cronograma de un proyecto, mostrando la duración y solapamiento de las tareas.
* **Caso de Uso:** Planificación de las fases y tareas de este mismo proyecto (Datos: Propios).
* **Herramienta:** Tableau Public.
* **Enlace:** **https://public.tableau.com/app/profile/xavier.cort.s.mars./viz/PEC2-DiagramaGantt_Xavier_CM/PEC2DiagramadeGantt?publish=yes**

---

### 3. Técnica (Grupo III): Gráfico de Horizonte (Horizon Graph)

* **Descripción:** Una técnica avanzada para visualizar múltiples series temporales en un espacio compacto, resolviendo el problema del "gráfico de espagueti".
* **Caso de Uso:** Comparación de la evolución de emisiones de CO2 per cápita en 6 regiones/países (Datos: World Bank).
* **Herramienta:** R (ggplot2 + ggHoriPlot) y GitHub Pages.
* **Visualización:**
    ![Gráfico de Horizonte de Emisiones de CO2](horizon_plot.png)
