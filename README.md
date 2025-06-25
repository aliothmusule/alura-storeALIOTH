# 🛒 Análisis de Eficiencia de Tiendas

![Python](https://img.shields.io/badge/python-3.10+-blue.svg)
![Pandas](https://img.shields.io/badge/pandas-2.x-blue.svg)
![Matplotlib](https://img.shields.io/badge/matplotlib-3.x-green.svg)
![License](https://img.shields.io/badge/license-MIT-lightgrey.svg)

Este proyecto ejecuta un análisis comparativo del rendimiento de **cuatro tiendas** para identificar la unidad menos eficiente. El análisis se basa en un conjunto de métricas clave extraídas de datos transaccionales, culminando en un diagnóstico fundamentado sobre las causas de la ineficiencia.

---

## 📋 Índice

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Análisis Realizado](#análisis-realizado)
- [Stack Tecnológico](#stack-tecnológico)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Instalación](#instalación)
- [Uso](#uso)
- [Resultados del Análisis](#resultados-del-análisis)
- [Autor y Licencia](#autor-y-licencia)

---

## 📝 Descripción del Proyecto

El objetivo principal es evaluar el rendimiento operativo y comercial de un conjunto de tiendas. Se procesan datos de ventas para calcular métricas de rendimiento, visualizar los resultados y derivar una conclusión cuantitativa sobre cuál tienda presenta la mayor área de oportunidad, detallando los factores que contribuyen a su bajo rendimiento.

## 📊 Análisis Realizado

El notebook de análisis ejecuta las siguientes operaciones:

- **Ingesta y Limpieza de Datos:** Carga de datos desde archivos fuente y aplicación de transformaciones básicas.
- **Cálculo de Métricas Clave (KPIs):**
  - Ingreso total y Venta Promedio por transacción.
  - Volumen de ventas y distribución de ingresos por **categoría de producto**.
  - **Calificación media** de los productos como indicador de satisfacción del cliente.
  - **Costo promedio de envío** como métrica de eficiencia logística.
  - Identificación de los **productos con mayor y menor volumen de ventas** (Top/Bottom movers).
- **Visualización de Datos:** Generación de gráficos comparativos para visualizar el rendimiento de cada tienda a través de las métricas definidas.
- **Evaluación de Eficiencia:** Ranking de tiendas basado en una puntuación ponderada de los KPIs para identificar al competidor más débil.

## 🛠️ Stack Tecnológico

- **Lenguaje:** Python 3.10+
- **Librerías de Análisis:**
  - `pandas`: Manipulación y análisis de dataframes.
  - `matplotlib`: Generación de visualizaciones estáticas y gráficos.
- **Entorno de Desarrollo:** Jupyter Notebook / Google Colab

## 📁 Estructura del Proyecto

La estructura de directorios está organizada de la siguiente manera para mantener la modularidad y el orden.

├── data/
│   └── datos_tiendas.csv   # Archivo con los datos de entrada
├── notebooks/
│   └── analisis_tienda.ipynb # Notebook principal con el análisis
├── README.md                 # Documentación del proyecto
└── requirements.txt          # Lista de dependencias


## ⚙️ Instalación

Para replicar el entorno de análisis, siga estos pasos. Se recomienda utilizar un entorno virtual.

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/aliothmusule/alurastoreALIOTH.git](https://github.com/tu_usuario/tu_repositorio.git)
    cd tu_repositorio
    ```

2.  **(Opcional) Crear y activar un entorno virtual:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # En Windows: venv\Scripts\activate
    ```

3.  **Instalar las dependencias:**
    El archivo `requirements.txt` asegura que se instalen las versiones correctas de las librerías.
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Uso

1.  Asegúrese de que el archivo de datos `datos_tiendas.csv` se encuentre en la carpeta `data/`.
2.  Abra el notebook `notebooks/analisis_tienda.ipynb` en su entorno de Jupyter Notebook o Google Colab.
3.  Ejecute todas las celdas en orden secuencial para replicar el análisis completo.

## 📈 Resultados del Análisis

*Aquí se documenta la conclusión final del estudio.*

El análisis concluye que la **Tienda C** es la unidad con el rendimiento más bajo. Los factores determinantes son:
- Un **costo de envío promedio 25% superior** al de sus competidores, lo que impacta negativamente en la conversión y rentabilidad.
- Una **calificación promedio de producto de 2.1 estrellas**, la más baja del grupo, sugiriendo problemas de calidad o de servicio post-venta que erosionan la lealtad del cliente.

## ✍️ Autor y Licencia

- **Autor:** Alioth Musule Alfaro – Análisis de datos con Python
- **Licencia:** Este proyecto está bajo la Licencia MIT. Consulte el archivo `LICENSE` para más detalles.
