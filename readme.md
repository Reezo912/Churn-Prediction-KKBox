# Churn Prediction - KKBox Challenge

[![Python](https://img.shields.io/badge/Python-3.12+-blue.svg)](https://www.python.org/)
[![Polars](https://img.shields.io/badge/Polars-1.0+-orange.svg)](https://pola-rs.github.io/polars/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Work%20in%20Progress-yellow.svg)](https://github.com/yourusername/Churn-Prediction-KKBox)

## 📋 Descripción

Este proyecto es un **work in progress** para el análisis y predicción de churn (cancelación de suscripciones) utilizando el dataset de la competicion **WSDM - KKBox's Churn Prediction Challenge** de Kaggle.

## 🎯 Objetivo

El objetivo es predecir si un usuario cancelará su suscripción en KKBox (servicio de música) basándose en sus patrones de comportamiento, transacciones y datos demográficos.

## 📊 Dataset

El dataset [WSDM - KKBox's Churn Prediction Challenge](https://www.kaggle.com/c/kkbox-churn-prediction-challenge) incluye:

- **members_v3.csv**: Datos demográficos de los usuarios (6.7M registros)
- **train.csv**: Etiquetas de churn para entrenamiento (45MB)
- **transactions_v2.csv**: Historial de transacciones y pagos (110MB)
- **user_logs.csv**: Logs de actividad de los usuarios (28GB)

## 🛠️ Tecnologías Utilizadas

- **Python**: Lenguaje principal
- **Polars**: Librería de análisis de datos optimizada para grandes volúmenes (alternativa a Pandas)
- **Jupyter Notebooks**: Para el desarrollo y análisis exploratorio

## 📁 Estructura del Proyecto

```
Churn-Prediction-KKBox/
├── data/
│   ├── raw/           # Datos originales descargados de Kaggle
│   └── processed/     # Datos procesados (pendiente)
├── src/               # Código fuente (pendiente)
├── preprocess.ipynb   # Notebook de preprocesamiento
├── requirements.txt   # Dependencias del proyecto
└── README.md         
```

## 🚀 Instalación

1. **Clonar el repositorio:**
```bash
git clone <url-del-repositorio>
cd Churn-Prediction-KKBox
```

2. **Instalar dependencias:**
```bash
pip install -r requirements.txt
```

3. **Descargar el dataset:**
```bash
kaggle competitions download -c kkbox-churn-prediction-challenge -p data/raw
```

## 📈 Estado Actual del Proyecto

### ✅ Completado
- [x] Configuración del entorno de desarrollo
- [x] Descarga del dataset de Kaggle
- [x] Carga inicial de datos con Polars
- [x] Análisis exploratorio básico de la estructura de datos
- [x] Verificación de duplicados y calidad de datos

### 🔄 En Progreso
- [ ] Preprocesamiento completo de datos
- [ ] Feature engineering
- [ ] Análisis exploratorio detallado

### 📋 Pendiente
- [ ] Modelado de machine learning
- [ ] Validación cruzada
- [ ] Optimización de hiperparámetros
- [ ] Evaluación de modelos
- [ ] Generación de submissions

## 🎓 Aprendizaje

Este es mi primer proyecto utilizando **Polars**, una librería moderna y eficiente para el análisis de datos que ofrece:
- Mejor rendimiento que Pandas para datasets grandes
- API similar a Pandas para facilitar la transición
- Optimizaciones automáticas de memoria y CPU

## 📝 Notas de Desarrollo

- Los datos son bastante grandes (28GB para user_logs), por lo que se requiere optimización en el procesamiento
- Polars se está utilizando en modo "lazy evaluation" para mejor rendimiento
- Se está explorando la estructura de datos para entender las relaciones entre tablas

## 🤝 Contribuciones

Este es un proyecto de aprendizaje personal. Las sugerencias y feedback son bienvenidos.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 🔗 Enlaces Útiles

- [Competencia en Kaggle](https://www.kaggle.com/c/kkbox-churn-prediction-challenge)
- [Documentación de Polars](https://pola-rs.github.io/polars/)
- [WSDM Challenge](https://www.kaggle.com/c/kkbox-churn-prediction-challenge)