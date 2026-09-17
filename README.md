# 🧠 Data Science & Machine Learning Solutions — Modelado Predictivo & People Analytics
> **Modelos de Machine Learning aplicados a problemas de negocio de alto impacto: Retención de Talento (Employee Churn) y Modelado Estadístico Predictivo.**

[![Python](https://img.shields.io/badge/Python-3.x-3776ab.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Notebooks-Jupyter-F37626.svg)](https://jupyter.org/)
[![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-F7931E.svg)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 📌 El Desafío de Negocio

El valor de la Ciencia de Datos radica en transformar datos históricos en decisiones estratégicas que ahorren costos o generen nuevas fuentes de ingresos. Este repositorio aborda dos casos de estudio con impacto cuantificable:

### Caso 1: Retención de Talento & Prevención de Fuga Laboral (People Analytics)
- **Problema**: La renuncia inesperada de personal clave genera costes astronómicos en contratación, curva de aprendizaje y pérdida de productividad (estimado entre un 50% y un 200% del salario anual del empleado saliente).
- **Necesidad**: Identificar de forma anticipada qué colaboradores tienen alta probabilidad de rotación y cuáles son las causas raíz (horas extras excesivas, insatisfacción salarial, estancamiento profesional, etc.).

### Caso 2: Modelado Predictivo y Simulación de Eventos Complejos
- **Problema**: Pronosticar el resultado de enfrentamientos multivariables donde múltiples factores interrelacionados (rendimiento histórico, goles, localía, rankings) influyen en el resultado final.
- **Necesidad**: Construir un pipeline desde la recolección desestructurada de datos históricos en la web hasta modelos de probabilidad (distribución de Poisson y machine learning) para simulación estocástica de escenarios.

---

## 💡 Las Soluciones Implementadas

### 1. People Analytics: Modelo de Predicción de Abandono de Empleados (`ABANDONO_EMPLEADOS`)
- **Análisis Exploratorio de Datos (EDA)**: Detección de patrones de correlación entre horas extras, satisfacción laboral, estado civil, distancia al trabajo y rotación.
- **Preprocesamiento e Ingeniería de Variables**: Imputación de datos, balanceo de clases, escalado y codificación de variables categóricas.
- **Modelado Predictivo con Machine Learning**: Entrenamiento y evaluación de clasificadores predictivos para generar un **índice de riesgo individual de deserción laboral**, permitiendo a Recursos Humanos activar planes de retención personalizados antes de que el empleado presente su renuncia.

### 2. Pipeline de Extracción y Predicción Deportiva / Torneos (`PREDICCIÓN DEL MUNDIAL`)
- **Pipeline Web Scraping con BeautifulSoup & Selenium**: Recolección automatizada de tablas históricas de partidos de copas mundiales desde 1930 hasta la actualidad.
- **Tratamiento y Normalización de Datos con Pandas**: Limpieza rigurosa de inconsistencias en nombres de selecciones, goles a favor/contra y puntuaciones históricas.
- **Modelado Basado en Distribución de Poisson y Machine Learning**: Estimación de tasas de anotación esperadas por partido, simulaciones de fases de grupos y cuadros eliminatorios con probabilidades matemáticas.

---

## 📈 Impacto y Retorno de Inversión (ROI)

| Área de Aplicación | Enfoque Tradicional | Con Soluciones de Machine Learning | Beneficio Estratégico |
|---|---|---|---|
| **Retención de Personal** | Entrevistas de salida reactivas (cuando el empleado ya se va) | Alertas tempranas de riesgo de abandono basadas en datos | **Ahorro de miles de dólares en costos de rotación y reemplazo** |
| **Identificación de Factores Críticos** | Suposiciones subjetivas de jefaturas | Análisis de importancia de variables (*Feature Importance*) | **Políticas de compensación y clima laboral dirigidas a las causas reales** |
| **Proyecciones de Rendimiento** | Opiniones de expertos o conjeturas | Modelos estocásticos de simulación matemática | **Cuantificación precisa de probabilidades y escenarios de riesgo** |

---

## ✨ Estructura del Repositorio

```text
├── ABANDONO_EMPLEADOS/
│   ├── analisis.ipynb                   # Cuaderno interactivo de EDA, modelado predictivo e insights
│   └── data/
│       └── AbandonoEmpleados.csv        # Dataset de métricas de personal y rotación
│
├── PREDICCIÓN DEL MUNDIAL/
│   ├── Database/                        # Datasets históricos limpios y estructurados
│   ├── Dictionaries/                    # Mapeo de grupos y fases eliminatorias
│   ├── analissar.py                     # Análisis estadístico y cálculo de fuerzas ofensivas/defensivas
│   ├── prediction.py                    # Motor de predicción y cálculo de probabilidades (Poisson)
│   ├── prediction_worldcup2022.py       # Simulación completa del torneo fase por fase
│   ├── worldcup_1990.py                 # Scripts de scraping y extracción histórica
│   └── worldcups_1930-2018.py           # Pipeline de extracción multianual
│
└── README.md                            # Documentación general
```

---

## 🛠️ Stack Tecnológico

- **Lenguaje**: Python 3.
- **Entorno de Análisis**: Jupyter Notebooks.
- **Machine Learning & Modelado**: Scikit-Learn, SciPy (Poisson distribution).
- **Procesamiento de Datos**: Pandas, NumPy.
- **Visualización**: Matplotlib, Seaborn.
- **Extracción de Datos**: BeautifulSoup4, Selenium WebDriver, Requests.

---

## 🚀 Cómo Explorar y Ejecutar los Modelos

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/Enybyy/data-science-machine-learning.git
   cd data-science-machine-learning
   ```

2. **Crear entorno virtual e instalar dependencias:**
   ```bash
   python -m venv venv
   # Activar entorno
   pip install jupyter pandas numpy scikit-learn matplotlib seaborn scipy beautifulsoup4 selenium
   ```

3. **Lanzar Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Abre y ejecuta `ABANDONO_EMPLEADOS/analisis.ipynb` para ver el pipeline completo paso a paso con gráficos explicativos.

---

## 📬 ¿Quieres aplicar Machine Learning a los datos de tu empresa?

Ofrezco servicios de consultoría y desarrollo en **Ciencia de Datos, modelos predictivos para retención de clientes/empleados (Churn), scoring crediticio, pronósticos de demanda y optimización algorítmica**.

- **GitHub**: [@Enybyy](https://github.com/Enybyy)
- **Perfil Profesional**: Eliud RM — Data Science & Software Solutions
- *Conversemos sobre cómo convertir los datos de tu organización en ventajas competitivas reales.*
