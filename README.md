# 🔍 Clasificación de Tipos de Cobertura Forestal

## 🤝 Colaboradores

- [Jfriera03](https://github.com/Jfriera03)
- [MasoalM](https://github.com/MasoalM)

## 📌 Descripción

Este proyecto implementa **modelos de aprendizaje automático** para la clasificación de tipos de cobertura forestal. Se utilizan diversas técnicas de clasificación supervisada para analizar y predecir la vegetación en función de características geográficas y ambientales.

## 🛠️ Tecnologías y Herramientas

- **Lenguaje:** Python 🐍
- **Librerías utilizadas:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`.
- **Estructuras de datos empleadas:**
  - DataFrames de `pandas` para manipulación de datos.
  - Arrays de `numpy` para cálculos numéricos.
  - Modelos de `scikit-learn` para clasificación.

## 📌 Arquitectura del Código

El código está estructurado en un **Notebook Jupyter** (`.ipynb`), en el que se incluyen:

1. **Carga y exploración de datos:** Análisis exploratorio del conjunto **Forest Cover Type Dataset**.
2. **Preprocesamiento de datos:** Limpieza, transformación y selección de características.
3. **Entrenamiento de modelos:** Comparación entre varios algoritmos de clasificación.
4. **Evaluación de modelos:** Análisis de métricas y visualización de resultados.
5. **Discusión de resultados:** Comparación crítica de los modelos y su rendimiento.

## 🚀 Instalación y Uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Jfriera03/clasificacion-cobertura-forestal.git
   ```
2. Accede al directorio del proyecto:
   ```bash
   cd clasificacion-cobertura-forestal
   ```
3. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
   ```
4. Abre el Notebook Jupyter:
   ```bash
   jupyter notebook Práctica3.ipynb
   ```

## 🎮 Modelos Implementados

Los siguientes modelos de clasificación han sido implementados y comparados:

### 🔹 Perceptrón
- Algoritmo basado en redes neuronales simples.
- Sensible a datos no linealmente separables.

### 🔹 Regresión Logística
- Modelo estadístico para clasificación binaria y multiclase.
- Útil en problemas con relaciones lineales entre variables.

### 🔹 Máquinas de Vectores de Soporte (SVM)
- Clasificación utilizando hiperplanos óptimos.
- Permite el uso de diferentes **kernels** para mejorar precisión.

### 🔹 Árboles de Decisión
- Estructura jerárquica para toma de decisiones.
- Fácil interpretación y ajuste de hiperparámetros.

### 🔹 Bosques Aleatorios (Random Forest)
- Conjunto de árboles de decisión para mejorar la generalización.
- Reduce el sobreajuste comparado con modelos individuales.

## 🏗️ Implementación Técnica

### 📌 Selección de Características
- Se analizan correlaciones entre atributos para reducir dimensionalidad.
- Métodos explorados: **Coeficiente de Pearson**, **PCA**.

### 📌 Ajuste de Hiperparámetros
- Optimización mediante **búsqueda en cuadrícula (Grid Search)** y **validación cruzada**.
- Comparación de diferentes configuraciones para cada modelo.

### 📌 Evaluación de Modelos
Se utilizan métricas para medir el rendimiento:
- **Precisión (Accuracy)**.
- **Matriz de confusión** para análisis detallado.
- **Curvas ROC y AUC** para modelos probabilísticos.

### 📌 Visualización de Resultados
- Se generan gráficos con `matplotlib` y `seaborn`.
- Comparaciones entre modelos mediante diagramas de barras y curvas de rendimiento.
