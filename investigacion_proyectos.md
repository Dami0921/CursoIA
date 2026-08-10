# Investigación de Proyectos de Inteligencia Artificial

## Proyecto Seleccionado: Sistema inteligente para la planificación y optimización de rutas de recolección y transporte de residuos (Movilidad)

### Descripción General

Nuestro proyecto busca desarrollar una solución de Inteligencia Artificial aplicada al contexto real de una empresa de recolección y transporte de residuos sólidos, con el propósito de utilizar los datos generados durante la operación para apoyar la toma de decisiones y mejorar la planificación de las rutas.

La idea principal es desarrollar un sistema que integre diferentes herramientas de Inteligencia Artificial, análisis de datos y optimización logística para abordar tres necesidades principales de la operación.

---

### 1. Predicción de generación de residuos

**¿Qué problema resuelve?**
Resuelve la falta de anticipación ante los cambios en la cantidad de residuos generados durante el año, dificultando la planificación de recursos y personal.

**¿Qué tipo de datos se necesitarían?**
- Datos históricos de toneladas recolectadas por fecha
- Variables estacionales (temporada, época del año)
- Ubicación geográfica de los puntos de recolección
- Datos demográficos de las zonas atendidas

**¿Qué modelo de IA podría ser adecuado?**
- Modelos de series temporales: ARIMA, Prophet o LSTM
- Modelos de regresión: Random Forest o XGBoost
- Estos modelos son adecuados porque pueden capturar patrones estacionales y tendencias en los datos históricos

---

### 2. Optimización y recomendación de rutas

**¿Qué problema resuelve?**
Resuelve la necesidad de diseñar o modificar rutas de forma eficiente cuando cambian las condiciones del servicio, reemplazando la planificación empírica por una basada en datos.

**¿Qué tipo de datos se necesitarían?**
- Coordenadas geográficas de los puntos de recolección
- Capacidad de carga de los vehículos
- Distancias y tiempos entre puntos
- Restricciones operativas (horarios, capacidad)

**¿Qué modelo de IA podría ser adecuado?**
- Algoritmos de optimización: VRP (Vehicle Routing Problem)
- Heurísticas: Vecino más cercano, Algoritmos genéticos
- Optimización por colonia de hormigas (Ant Colony Optimization)
- Estos algoritmos son ideales para encontrar rutas óptimas minimizando distancia y tiempo

---

### 3. Predicción de tiempos de viaje

**¿Qué problema resuelve?**
Resuelve la necesidad de estimar cuánto tiempo tomará un recorrido, permitiendo comparar rutas por duración real y no solo por distancia.

**¿Qué tipo de datos se necesitarían?**
- Tiempos históricos de viaje por ruta
- Distancias recorridas
- Número de paradas por ruta
- Datos de tráfico en tiempo real (opcional)
- Condiciones climáticas (opcional)

**¿Qué modelo de IA podría ser adecuado?**
- Random Forest o Gradient Boosting
- Redes neuronales para predicción de tiempos
- Modelos híbridos que combinen regresión con datos de tráfico
- Estos modelos capturan relaciones no lineales entre múltiples variables

---

## Proyectos Alternativos (para referencia)

### Proyecto Alternativo 1: Sistema de recomendación de películas

**¿Qué problema resuelve?**
Ayuda a los usuarios a encontrar contenido personalizado según sus preferencias y hábitos de visualización.

**¿Qué tipo de datos se necesitarían?**
- Historial de visualización
- Calificaciones de usuarios
- Metadatos de películas (género, director, actores)

**¿Qué modelo de IA podría ser adecuado?**
- Filtrado colaborativo
- Sistemas de recomendación basados en contenido
- Redes neuronales para embeddings

---

### Proyecto Alternativo 2: Clasificador de imágenes para diagnóstico médico

**¿Qué problema resuelve?**
Asiste a profesionales de la salud en el diagnóstico temprano de enfermedades a través de imágenes médicas.

**¿Qué tipo de datos se necesitarían?**
- Imágenes médicas (rayos X, resonancias, etc.)
- Diagnósticos etiquetados por expertos
- Datos demográficos de pacientes

**¿Qué modelo de IA podría ser adecuado?**
- Redes neuronales convolucionales (CNN)
- Transfer learning con modelos pre-entrenados (ResNet, EfficientNet)
- Modelos de clasificación de imágenes

---

### Proyecto Alternativo 3: Sistema de detección de fraude financiero

**¿Qué problema resuelve?**
Identifica transacciones sospechosas y posibles fraudes en tiempo real para instituciones financieras.

**¿Qué tipo de datos se necesitarían?**
- Histórico de transacciones
- Datos de usuarios y comportamientos
- Patrones de fraude conocidos

**¿Qué modelo de IA podría ser adecuado?**
- Random Forest o XGBoost para clasificación
- Redes neuronales para detección de anomalías
- Modelos de aprendizaje no supervisado

---

## Conclusión

El proyecto de optimización de rutas de recolección de residuos presenta un desafío integral que combina:
- **Análisis predictivo** (series temporales)
- **Optimización logística** (VRP)
- **Machine Learning** (regresión)

Este enfoque multidisciplinario lo convierte en una excelente oportunidad para aplicar diversos conceptos de Inteligencia Artificial en un contexto con impacto social y ambiental real.

---

**Fecha de investigación:** 9 de agosto de 2026
**Equipo:** [Nombres de los integrantes]