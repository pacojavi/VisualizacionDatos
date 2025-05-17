# Análisis de Datos Ambientales en Madrid

Este repositorio contiene un análisis exploratorio y visual de datos ambientales del municipio de Madrid. 
Se abordan tres dimensiones principales: calidad del aire, niveles de ruido y variables meteorológicas, 
utilizando `Altair` para la construcción de visualizaciones interactivas.

## 📂 Contenido

- `notebook_altair_FJAA.ipynb`: Notebook con todo el análisis.
- Gráficos exportados en HTML:
  - `chart_pm10.html`
  - `chart_barras_apiladas.html`
  - `grafico.html`
  - `scatter.html`
  - `mapa_base.html`
  - `detalle_temp.html`
  - `detalle_pres.html`
  - `detalle_hum.html`
  - `detalle_pm10.html`
  - `detalle_o3.html`
  - `detalle_ruido.html`

## 🚀 Visualización directa

Los siguientes gráficos pueden visualizarse directamente si se activa GitHub Pages:

- [Evolución PM10](./chart_pm10.html)
- [Mapa de estaciones](./mapa_base.html)
- [Panel de detalle: temperatura](./detalle_temp.html)

## ⚙️ Requisitos

Instalación de dependencias mínimas:

```bash
pip install -r requirements.txt
```

## 📊 Librerías utilizadas

- `pandas`
- `altair`
- `vega_datasets`
- `jupyter`
- `numpy`
- `scikit-learn`
- `geopandas` *(opcional, si se ejecutan celdas de cruce espacial)*

## 🔗 Ejecutar en línea (Binder)

[![Abrir en Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/usuario/repositorio/main?filepath=notebook_altair_FJAA.ipynb)

---
Trabajo desarrollado en el marco de un análisis técnico avanzado con fines educativos y de exploración ambiental urbana.
