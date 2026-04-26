#  Análisis de Datos — Dataset de Obesidad

Análisis exploratorio y preprocesamiento de un dataset de obesidad usando Python y Jupyter Notebook. Incluye estandarización de variables numéricas y conversión de variables categóricas a numéricas.

---

##  Estructura del repositorio

```
Analsis-de-datos/
│
├── ObesityDataSet_raw_and_data_sinthetic.csv   # Dataset original (raw + sintético)
├── Parcial2.ipynb                               # Notebook principal con el análisis
└── README.md
```

---

##  Objetivo

Realizar un proceso completo de **preprocesamiento de datos** sobre un dataset de obesidad, que incluye:

- Exploración y comprensión del dataset
- Identificación y manejo de variables categóricas y numéricas
- **Estandarización** de variables numéricas (media 0, desviación estándar 1)
- **Conversión de variables categóricas a numéricas** (Label Encoding / One-Hot Encoding)
- Preparación del dataset para uso en modelos de Machine Learning

---

##  Dataset

**Archivo:** `ObesityDataSet_raw_and_data_sinthetic.csv`

El dataset contiene datos reales y sintéticos sobre hábitos alimenticios y condición física de personas, con el objetivo de estimar niveles de obesidad. Incluye variables como:

| Variable | Tipo | Descripción |
|----------|------|-------------|
| Gender | Categórica | Género del individuo |
| Age | Numérica | Edad |
| Height | Numérica | Altura (metros) |
| Weight | Numérica | Peso (kg) |
| family_history_with_overweight | Categórica | Historial familiar de sobrepeso |
| FAVC | Categórica | Consumo frecuente de alimentos calóricos |
| FCVC | Numérica | Frecuencia de consumo de vegetales |
| NCP | Numérica | Número de comidas principales |
| CAEC | Categórica | Consumo de alimentos entre comidas |
| SMOKE | Categórica | Fuma |
| CH2O | Numérica | Consumo de agua diario |
| NObeyesdad | Categórica | **Nivel de obesidad (target)** |

---

##  Tecnologías utilizadas

- **Python 3**
- **Jupyter Notebook**
- **pandas** — manipulación y análisis de datos
- **NumPy** — operaciones numéricas
- **scikit-learn** — estandarización (`StandardScaler`) y codificación (`LabelEncoder`)
- **Matplotlib / Seaborn** — visualización de datos

---

##  Instalación y uso

### 1. Clonar el repositorio

```bash
git clone https://github.com/danielreyes04/Analsis-de-datos.git
cd Analsis-de-datos
```

### 2. Instalar dependencias

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```


## 🔍 Proceso de análisis

### 1. Carga y exploración del dataset
- Lectura del CSV con `pandas`
- Revisión de tipos de datos, valores nulos y estadísticas descriptivas

### 2. Conversión de variables categóricas
- Aplicación de `LabelEncoder` o `pd.get_dummies()` para transformar variables de texto en valores numéricos

### 3. Estandarización de variables numéricas
- Uso de `StandardScaler` de scikit-learn para normalizar las columnas numéricas y llevarlas a una escala común

---

## Autor

**Daniel Reyes**
- GitHub: [@danielreyes04](https://github.com/danielreyes04)

---
