# Análisis de Datos de Aguacates 🥑

## 📌 Propósito
El objetivo de este proyecto es realizar un análisis completo del mercado de aguacates, incluyendo:
- Limpieza y preparación de datos
- Análisis descriptivo y exploratorio
- Modelado predictivo (clasificación y regresión)

## 📊 Características del Dataset
| Variable       | Descripción |
|----------------|-------------|
| Fecha          | Fecha de observación |
| PrecioPromedio | Precio promedio de un aguacate (USD) |
| Tipo           | Convencional u Orgánico |
| Año            | Año de registro |
| Región         | Ciudad o región de observación |
| VolumenTotal   | Total de aguacates vendidos |
| 4046           | Total vendido con PLU 4046 |
| 4225           | Total vendido con PLU 4225 |
| 4770           | Total vendido con PLU 4770 |

## 📚 Tabla de Contenidos

### 1. Carga y Limpieza de Datos
- Importación de bibliotecas
- Carga del dataset
- Manejo de valores nulos
- Transformación de tipos de datos
- Normalización de formatos

### 2. Análisis Descriptivo
- Estadísticos básicos
- Distribución de variables
- Correlaciones iniciales

### 3. EDA (Análisis Exploratorio)
#### 🥑 Orgánico vs Convencional
- Comparación de precios
- Comparación de volúmenes de venta
- Participación de mercado

#### 📈 Tendencia Temporal
- Evolución de precios por tipo
- Popularidad de orgánicos (crecimiento anual)
- Estacionalidad:
  - Meses con mayor disponibilidad
  - Meses con precios más bajos

#### 🌎 Análisis Regional
- Regiones con mayor volumen de ventas
- Regiones con precios más altos/bajos
- Diferencias regionales en preferencia (orgánico vs convencional)

### 4. Modelado Predictivo
#### 🔍 Modelos de Clasificación
- Objetivo: Predecir tipo (orgánico/convencional) basado en otras variables
- Algoritmos probados:
  - Regresión Logística
  - Random Forest
  - XGBoost
- Métricas de evaluación

#### 📉 Modelos de Regresión
- Objetivo: Predecir precio promedio
- Algoritmos probados:
  - Regresión Lineal
  - Decision Trees
  - SVR
- Evaluación de resultados

## 🛠 Tecnologías Utilizadas
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebooks

## 📂 Estructura del Proyecto


## Estructura del Proyecto
```bash
.
├── data/
│   ├── avocado.csv    # Dataset principal
│   └── data.py       # Funciones de manejo de datos
├── notebooks/
│   └── avocado.ipynb # Cuaderno de análisis principal
├── pyproject.toml    # Configuración de dependencias
├── README.md         # Documentación principal
└── uv.lock           # Lock file de dependencias