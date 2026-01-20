# CadenaDeTiendasAluraStore
Proyecto de análisis de datos orientado a la toma de decisiones. Se analizaron datos de ventas, ingresos, reseñas y rendimiento de cuatro tiendas de Alura Store utilizando Pandas y Matplotlib. A través de métricas clave y visualizaciones, se identificó la tienda menos eficiente y se entregó una recomendación basada en datos.

# Análisis de Ventas – Proyecto Alura Store

Este proyecto analiza los datos de ventas de la cadena **Alura Store** utilizando Python. El objetivo principal es comparar el rendimiento de las 4 tiendas en términos de ingresos, métricas de ventas, satisfacción del cliente y distribución geográfica, con el fin de identificar cuál tienda sería menos eficiente para vender y liberar recursos para un nuevo emprendimiento.

---

## Objetivos del Proyecto

- Comparar el desempeño de ventas entre las tiendas.
- Analizar métricas clave como ingresos, volumen de ventas, calificaciones y costos logísticos.
- Identificar los productos más y menos vendidos por tienda.
- Visualizar el comportamiento de las ventas según su ubicación geográfica.
- Generar insights accionables para la toma de decisiones.

---

## Estructura del Repositorio
CadenaDeTiendasAluraStore/
│
├── data/
│ ├── tienda_1.csv
│ ├── tienda_2.csv
│ ├── tienda_3.csv
│ └── tienda_4.csv
│
├── images/
│ ├── ingresos_tiendas.png
│ ├── categorias_tiendas.png
│ ├── mapas_tiendas/
│ │ ├── tienda1_heatmap.png
│ │ ├── tienda2_heatmap.png
│ │ ├── tienda3_heatmap.png
│ │ └── tienda4_heatmap.png
│ └── ...
│
├── notebooks/
│ └── analisis_alura_store.ipynb
│
├── README.md
└── requirements.txt


---

## Tecnologías Utilizadas

- Python 3.10+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Folium (opcional para mapas interactivos)
- Jupyter Notebook

---

## Instalación

1. Clona este repositorio:

```bash
git clone https://github.com/javieratorres/CadenaDeTiendasAluraStore.git
cd CadenaDeTiendasAluraStore

2. Crea y activa un entorno virtual:
python -m venv venv
source venv/bin/activate  # Windows: venv\\Scripts\\activate

Instala las dependencias:
pip install -r requirements.txt

## Ejecución del Análisis

notebooks/analisis_alura_store.ipynb

Puedes abrirlo con:
jupyter notebook

### Análisis Realizados
1. Análisis de Facturación

Comparación de ingresos totales por tienda para evaluar el rendimiento comercial general.

2. Ventas por Categoría

Conteo y visualización de las ventas agrupadas por categoría de producto en cada tienda.

3. Productos Más y Menos Vendidos

Rankings de productos según volumen de ventas por tienda.

4. Costo Promedio de Envío

Comparación del costo de envío promedio por tienda.

5. Valoración Media por Tienda

Promedio de calificaciones de clientes para evaluar satisfacción.

6. Análisis Geográfico (Extra – Mapas de Calor)

Exploración de patrones geográficos basados en latitud y longitud de las ventas.

Ejemplo de visualización:

### Principales Hallazgos

Tienda 1: mayor ingreso total, pero con fuerte concentración geográfica.

Tienda 2: cobertura geográfica más amplia con buena distribución de ventas.

Tienda 3 y Tienda 4: análisis pendientes (se agregará al README una vez disponibles los mapas y métricas).

Tienda 4 presenta menor facturación general en comparación con las demás.

### Limitaciones del Análisis

El período temporal de los datos no fue considerado.

No se incluyeron costos operativos totales.

El análisis geográfico no está cuantitativamente integrado a otras métricas.

Variables externas como competencia regional o socioeconómicas no fueron incorporadas.

### Líneas Futuras de Análisis

Evaluar tendencias por períodos (mensual/anual).

Integrar métricas de rentabilidad (costo vs ingreso).

Expandir análisis geográfico cuantitativo.

Construir modelos predictivos para escenarios de ventas.

### Autora

Javiera Alejandra Torres Vergara
Estudiante de Data Science

Proyecto realizado como parte del desafío Alura Store.

### Licencia

Este proyecto está bajo Licencia MIT.








