# Proyecto-Evoluci-n-de-la-Salud-Materno-Infantil-en-Argentina
📊 Evolución de la Salud Materno-Infantil en Argentina (1990–2023)
📌 Descripción

Este proyecto analiza la evolución de tres indicadores clave en Argentina y sus provincias:

Natalidad (2000–2023)

Mortalidad infantil (1990–2023)

Mortalidad fetal (2006–2023)

Los datos provienen de DEIS (Dirección de Estadísticas e Información en Salud) y se procesaron con Python (pandas, matplotlib, plotly).

📈 Principales hallazgos
🔹 Tendencias nacionales

La mortalidad infantil se redujo de más del 25‰ en 1990 a valores cercanos al 8‰ en 2023 → una mejora histórica.

La natalidad muestra una tendencia descendente en casi todo el país desde 2000.

La mortalidad fetal también disminuyó, aunque con variabilidad entre provincias.

🔹 Desigualdades regionales

Provincias del NEA y NOA (Chaco, Formosa, Santiago del Estero) presentan tasas de mortalidad infantil más altas que el promedio nacional.

La Ciudad Autónoma de Buenos Aires (CABA) y Patagonia muestran los valores más bajos en mortalidad infantil.

La natalidad es más elevada en provincias del norte (ej. Misiones, Formosa, Santiago del Estero) y más baja en CABA y Buenos Aires.

🔹 Año 2023 (ranking provincial)

Natalidad más alta: Formosa, Misiones, Santiago del Estero.

Natalidad más baja: CABA, Buenos Aires, Tierra del Fuego.

Mortalidad infantil más alta: Chaco, Formosa, Corrientes.

Mortalidad infantil más baja: CABA, Neuquén, Tierra del Fuego.

Mortalidad fetal más alta: Tucumán, San Juan, Santiago del Estero.

Mortalidad fetal más baja: CABA, Santa Cruz, Río Negro.

🗺️ Visualizaciones

El proyecto incluye:

Series temporales nacionales (líneas comparativas).

Mapas coropléticos interactivos (Plotly) para 2023.

Rankings top/bottom 5 por provincia.

Los mapas se exportan como HTML interactivos y los rankings como Excel.

⚙️ Tecnologías utilizadas

Python 3.11

Pandas / Numpy

Matplotlib / Plotly

Jupyter Notebook

📂 Archivos principales

analisis_nacional_argentina.ipynb → Notebook con análisis de series nacionales.

rankings_provincias_2023.xlsx → Rankings y tablas provinciales.

mapa_natalidad_2023.html / mapa_mortalidad_infantil_2023.html / mapa_mortalidad_fetal_2023.html → Mapas interactivos.

🚀 Próximos pasos

Proyecciones a 2030 de cada indicador.

Dashboard interactivo en Power BI o Streamlit.

Incorporar variables socioeconómicas para explicar diferencias regionales.
