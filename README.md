# 👁️ Proyecto **Centinela** — Fase 1: *CERV-D (Retinopatía Diabética)*
### Redes Neuronales — Deep Learning · Maestría en Ciencia de Datos

Este cuaderno resuelve la Fase 1 del Proyecto Integrador *Centinela* de principio a fin, construyendo la línea base tabular con un Perceptrón Multicapa (MLP) sobreescribiendo el andamiaje guía.

**El escenario.** Como ejercicio académico aplicado a la gestión analítica, asumimos el rol de consultores para la Dirección de Riesgo de una EPS. El objetivo es priorizar el tamizaje oftalmológico para pasar de un modelo reactivo a uno proactivo. La Fase 1 construye la línea base: un MLP tabular que, procesando variables morfológicas ya extraídas matemáticamente de la imagen del fondo de ojo, estima si un paciente tiene riesgo visual inminente.



---
**Contenido**
0. Preparación del entorno
1. El problema y los datos reales (UCI ML Repo · Debrecen)
2. Exploración mínima (EDA) → cada hallazgo decide algo
3. Arquitectura del MLP (≥ 2 capas ocultas, salida en *logit*)
4. Pérdida, optimizador y bucle de entrenamiento explícito (150 épocas)
5. Funciones de diagnóstico y curvas de la línea base
6. Desafío · Inducir y corregir el sobreajuste con *Dropout*
7. Evaluación en prueba, análisis de errores y ética
8. Cierre · Autoevaluación contra la rúbrica
