# Análisis de precios de viviendas en EE. UU.

funete: https://www.kaggle.com/datasets/fratzcan/usa-house-prices?resource=download


Este notebook de Colab realiza un análisis exploratorio y predictivo sobre un dataset de viviendas en Estados Unidos. Incluye visualizaciones, correlaciones y un modelo de regresión lineal para entender qué variables estructurales influyen en el precio de los inmuebles.

---

## 📋 Contenido del Notebook

1. **Carga de datos**  
   Lectura del dataset y limpieza inicial.

2. **Análisis descriptivo y visualizaciones**  
   - Histogramas de variables clave  
   - Scatterplots y boxplots (por ejemplo: superficie vs precio, antigüedad vs precio)  
   - Cálculo de correlaciones entre variables y precio

3. **Modelo de regresión lineal múltiple**  
   Entrenamiento del modelo con variables como `sqft_living`, `bathrooms`, `view`, `condition`, `bedrooms`, `yr_built`  
   - Coeficientes estimados  
   - Métricas de desempeño (RMSE, R²)

4. **Interpretación de resultados**  
   Discusión sobre qué variables impactan más el precio, limitaciones del modelo y posibles mejoras.

---

## 🧰 Requisitos

- Python ≥ 3.7  
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
- Acceso a Google Colab (el notebook está configurado para correr ahí)

