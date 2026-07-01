```markdown
# Gym Members Exercise Dataset

## Descripción

Este conjunto de datos proporciona una visión detallada de las rutinas de ejercicio, atributos físicos y métricas de rendimiento de miembros de un gimnasio. Contiene **973 registros**, incluyendo indicadores clave como la frecuencia cardíaca, las calorías quemadas y la duración de las sesiones de entrenamiento. Además, incorpora información demográfica y niveles de experiencia, permitiendo realizar análisis sobre patrones de entrenamiento, progresión física y tendencias relacionadas con la salud.

---

# Información del Dataset

- **Número de registros:** 973
- **Tipo de datos:** Mixto (variables numéricas y categóricas)
- **Área de aplicación:** Ciencia de datos, análisis deportivo, salud y fitness.

---

# Variables

| Variable | Tipo | Descripción |
|----------|------|-------------|
| Age | Numérica | Edad del miembro del gimnasio. |
| Gender | Categórica | Género del miembro (Male/Female). |
| Weight (kg) | Numérica | Peso en kilogramos. |
| Height (m) | Numérica | Estatura en metros. |
| Max_BPM | Numérica | Frecuencia cardíaca máxima durante el entrenamiento. |
| Avg_BPM | Numérica | Frecuencia cardíaca promedio durante el entrenamiento. |
| Resting_BPM | Numérica | Frecuencia cardíaca en reposo. |
| Session_Duration (hours) | Numérica | Duración de la sesión de entrenamiento en horas. |
| Calories_Burned | Numérica | Calorías quemadas durante la sesión. |
| Workout_Type | Categórica | Tipo de entrenamiento (Cardio, Strength, Yoga, HIIT, etc.). |
| Fat_Percentage | Numérica | Porcentaje de grasa corporal. |
| Water_Intake (liters) | Numérica | Consumo de agua durante el entrenamiento (litros). |
| Workout_Frequency (days/week) | Numérica | Frecuencia semanal de entrenamiento. |
| Experience_Level | Ordinal | Nivel de experiencia (1 = Principiante, 2 = Intermedio, 3 = Experto). |
| BMI | Numérica | Índice de Masa Corporal (IMC). |

---

# Objetivos del Análisis

Este conjunto de datos permite responder preguntas como:

- ¿Qué tipo de entrenamiento quema más calorías?
- ¿Existe una relación entre la duración del entrenamiento y las calorías quemadas?
- ¿Cómo influye el nivel de experiencia en el rendimiento físico?
- ¿El consumo de agua afecta el desempeño durante el entrenamiento?
- ¿Qué variables predicen mejor la cantidad de calorías quemadas?

---

# Análisis Exploratorio de Datos (EDA)

## Análisis Univariado

- Distribución de edades.
- Distribución del IMC.
- Distribución del porcentaje de grasa corporal.
- Distribución de calorías quemadas.
- Frecuencia de cada tipo de entrenamiento.

## Análisis Bivariado

- Duración del entrenamiento vs. Calorías quemadas.
- IMC vs. Porcentaje de grasa corporal.
- Edad vs. Frecuencia cardíaca máxima.
- Tipo de entrenamiento vs. Calorías quemadas.
- Género vs. IMC.

## Análisis Multivariado

- Matriz de correlación.
- Pairplot entre variables numéricas.
- Análisis de Componentes Principales (PCA).
- Agrupamiento mediante K-Means.

---

# Aplicaciones de Machine Learning

## Regresión

Posibles variables objetivo:

- Calories_Burned
- BMI
- Fat_Percentage
- Avg_BPM

Modelos recomendados:

- Regresión Lineal
- Random Forest Regressor
- Gradient Boosting
- XGBoost
- Redes Neuronales

Métricas de evaluación:

- MAE
- RMSE
- R²

---

## Clasificación

Variables objetivo:

- Workout_Type
- Experience_Level
- Gender

Modelos recomendados:

- Regresión Logística
- Árboles de Decisión
- Random Forest
- Support Vector Machine (SVM)
- XGBoost Classifier

Métricas de evaluación:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

---

# Preguntas de Investigación

1. ¿Qué tipo de entrenamiento produce un mayor gasto calórico?
2. ¿La duración del entrenamiento influye significativamente en las calorías quemadas?
3. ¿Los atletas con mayor experiencia presentan menor frecuencia cardíaca en reposo?
4. ¿Existe una relación entre el IMC y el porcentaje de grasa corporal?
5. ¿Qué factores tienen mayor impacto sobre las calorías quemadas?
6. ¿La frecuencia semanal de entrenamiento mejora los indicadores físicos?
7. ¿Cómo afecta la edad a la frecuencia cardíaca máxima?
8. ¿El consumo de agua está relacionado con un mejor rendimiento?
9. ¿Es posible predecir el nivel de experiencia utilizando variables fisiológicas?
10. ¿Qué variables presentan la mayor correlación entre sí?

---

# Visualizaciones Recomendadas

- Histograma de edades.
- Histograma del IMC.
- Boxplot de calorías por tipo de entrenamiento.
- Scatter Plot entre duración y calorías quemadas.
- Scatter Plot entre IMC y porcentaje de grasa.
- Heatmap de correlaciones.
- Pairplot de variables numéricas.
- Gráfico de barras de frecuencia por tipo de entrenamiento.
- Comparación del IMC por género.
- Distribución del nivel de experiencia.

---

# Preprocesamiento de Datos

Antes de construir modelos predictivos se recomienda:

- Verificar valores faltantes.
- Eliminar registros duplicados.
- Detectar y tratar valores atípicos (outliers).
- Codificar variables categóricas (`Gender` y `Workout_Type`).
- Escalar variables numéricas cuando sea necesario.
- Dividir el conjunto de datos en entrenamiento y prueba.

---

# Relaciones Esperadas

- **Correlación positiva:** Duración del entrenamiento → Calorías quemadas.
- **Correlación positiva:** Frecuencia cardíaca promedio → Calorías quemadas.
- **Correlación positiva:** IMC → Porcentaje de grasa corporal.
- **Correlación positiva:** Frecuencia de entrenamiento → Nivel de experiencia.
- **Correlación negativa:** Nivel de experiencia → Frecuencia cardíaca en reposo.

---

# Conclusión

Este conjunto de datos es adecuado para desarrollar un flujo completo de ciencia de datos, incluyendo análisis exploratorio, visualización, modelado predictivo y evaluación de modelos. Su diversidad de variables permite estudiar el impacto de distintos factores sobre el rendimiento físico y la salud, siendo especialmente útil para predecir el gasto calórico, analizar hábitos de entrenamiento e identificar patrones relacionados con la condición física de los usuarios.
```
