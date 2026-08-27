# EDA-datos-CARS
Analítica exploratoria de datos (EDA) y modelado de series de tiempo (ARIMA) sobre un dataset técnico de especificaciones vehiculares en Python


# Car Dataset Analysis & Time Series Modeling

Este proyecto realiza un análisis exploratorio de datos (EDA) y el modelado de series de tiempo utilizando un conjunto de datos técnicos de especificaciones automotrices.

##  Resumen del Trabajo Realizado

* **Limpieza y Preparación de Datos:** Inspección, tratamiento de valores faltantes y estructuración del dataset para análisis.
* **Análisis Exploratorio de Datos (EDA):** Identificación de relaciones estadísticas entre variables clave (potencia, cilindraje, dimensiones, consumo de combustible) y la estructura de precios de los vehículos (`MSRP` e `Invoice`).
* **Visualización de Datos:** Generación de gráficos distributivos, matrices de correlación y mapas de dispersión para interpretar patrones por marca y origen vehicular.
* **Modelado de Series de Tiempo (ARIMA):** Análisis de estacionariedad (prueba Dickey-Fuller Augmentada), evaluación de autocomunicación (gráficos ACF y PACF) y ajuste de modelos ARIMA para la serie observada.

##  Tecnologías y Librerías

* **Lenguaje:** Python 3.x
* **Procesamiento de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Modelado Econométrico:** Statsmodels

## 📊 Estructura de las Variables (`COPY_CARS.csv`)

* **Identificación y Categoría:** `Make`, `Model`, `Type`, `Origin`, `DriveTrain`
* **Precios:** `MSRP`, `Invoice`
* **Especificaciones Técnicas:** `EngineSize`, `Cylinders`, `Horsepower`, `Weight`, `Wheelbase`, `Length`
* **Rendimiento:** `MPG_City`, `MPG_Highway`
