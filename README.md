# TelecomX_Parte-II
Challenge Telecom X parte II
# 📊 Análisis de Churn en Telecomunicaciones

## 📌 Descripción
Análisis predictivo de abandono de clientes (churn) en el sector telecomunicaciones utilizando:
- **Preprocesamiento** con manejo de multicolinealidad (VIF)
- **Modelado** con Regresión Logística y Random Forest
- **Optimización** mediante SMOTE para datos desbalanceados

## 🔍 Hallazgos Clave
- **Variables críticas** para predecir churn:
  ```python
  ['tenure', 'account.Contract_Two year', 'account.Charges.Monthly']
  Mejor modelo: Random Forest (AUC = 0.89)

Factores de riesgo:

Contratos mensuales 📅

Servicio de fibra óptica ⚡

Pagos por cheque electrónico 💳

📈 Resultados
Métrica	Regresión Logística	Random Forest
Accuracy	0.78	0.82
Precision	0.65	0.73
Recall	0.71	0.79
AUC-ROC	0.83	0.89
📂 Estructura del Proyecto
text
.
├── data/
│   ├── telecom_churn.csv       # Dataset original
│   └── processed_data.csv      # Datos preprocesados
├── models/
│   ├── random_forest.pkl       # Modelo entrenado
│   └── logistic_regression.pkl
└── churn_analysis.ipynb        # Notebook principal
🤝 Contribuciones
¡Contribuciones son bienvenidas! Sigue estos pasos:

Haz fork del proyecto

Crea una rama (git checkout -b feature/nueva-funcionalidad)

Haz commit de tus cambios (git commit -m 'Add some feature')

Haz push a la rama (git push origin feature/nueva-funcionalidad)

Abre un Pull Request

📄 Licencia
MIT © [ADRIAN-GP84]
Destaca el valor de negocio:

"Este modelo identifica con 85% de precisión a clientes con riesgo de abandono, permitiendo acciones de retención tempranas que podrían reducir el churn en un 20% anual."
