# TelecomX-Churn-Prediction

# Telecom X - Predicción de Churn

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)

## 📌 Descripción
Proyecto de Machine Learning para predecir cancelación de clientes (churn) en una empresa de telecomunicaciones.

## 📊 Dataset
- 5000 clientes sintéticos
- 21 variables demográficas, de servicios y facturación
- Variable objetivo: **Churn** (1=canceló, 0=no canceló)

## 🤖 Modelos
| Modelo | Accuracy | AUC-ROC |
|--------|----------|---------|
| Regresión Logística | 0.78 | 0.82 |
| Random Forest | **0.83** | **0.89** |

## 🔍 Factores clave
1. **Tipo de contrato** (mensual = mayor riesgo)
2. **Antigüedad** (clientes nuevos cancelan más)
3. **Soporte técnico** (no tenerlo aumenta el riesgo)

## 💡 Recomendaciones
- Ofrecer incentivos para contratos anuales
- Contactar proactivamente a clientes nuevos
- Promover soporte técnico

## 🛠️ Tecnologías
Python, Pandas, Scikit-learn, Google Colab

## 📁 Archivos
- `notebook.ipynb`: Código completo
- `data/datos.csv`: Dataset
- `requirements.txt`: Librerías

## 🚀 Uso rápido
```bash
git clone https://github.com/NoeliaBag/TelecomX-Churn-Prediction.git
pip install -r requirements.txt
jupyter notebook
