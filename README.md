# 👁️ Proyecto **Centinela** - *CERV-D (Retinopatía Diabética)*
### Redes Neuronales — Deep Learning · Maestría en Ciencia de Datos

URL Repositorio: https://github.com/edwinyhovany/centinela/

Integrantes

**-Edwin Yhovany Garzon Amezquita**

**-Jeferson Torrado Bayona**

**El escenario.** Como ejercicio académico aplicado a la gestión analítica, asumimos el rol de consultores para la Dirección de Riesgo de una EPS. El objetivo es priorizar el tamizaje oftalmológico para pasar de un modelo reactivo a uno proactivo. La Fase 1 construye la línea base: un MLP tabular que, procesando variables morfológicas ya extraídas matemáticamente de la imagen del fondo de ojo, estima si un paciente tiene riesgo visual inminente.


Este proyecto contiene los entregables y cuadernos que resuelven el proyecto. En la Fase 1 se construye la línea base tabular con un Perceptrón Multicapa (MLP) y en la Fase 2 Proyecto Integrador generando las ramas: **Rama A** (clasificación de imágenes con CNN / *transfer learning*), **Rama B** (series temporales con RNN/LSTM/GRU) y **Rama C** (fusión multimodal)

---
**Contenido Fase 1***

0. Preparación del entorno
1. El problema y los datos reales (UCI ML Repo · Debrecen)
2. Exploración mínima (EDA) → cada hallazgo decide algo
3. Arquitectura del MLP (≥ 2 capas ocultas, salida en *logit*)
4. Pérdida, optimizador y bucle de entrenamiento explícito (150 épocas)
5. Funciones de diagnóstico y curvas de la línea base
6. Desafío · Inducir y corregir el sobreajuste con *Dropout*
7. Evaluación en prueba, análisis de errores y ética
8. Cierre · Autoevaluación contra la rúbrica

**Contenido Fase 2**

0. Preparación del entorno (semilla, *device*, paleta USTA, política de datos)
1. **Rama A — CNN (imágenes):** datos sintéticos de formas · `DataLoader` provisto · `# TODO` modelo / *transfer learning* / *training loop* / Grad-CAM
2. **Rama B — RNN/LSTM (series):** serie sintética · ventaneo provisto · `# TODO` arquitectura recurrente / *training loop*
3. **Rama C — Fusión multimodal:** función de fusión de ejemplo provista · `# TODO` cabeza de fusión / entrenamiento conjunto · *caveat* de co-registro y *leakage*
4. Checklist de entrega + rúbrica unificada de la Fase 2
