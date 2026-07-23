# 👁️ Proyecto **Centinela** — Fase 3: *CERV-D (Retinopatía Diabética)*
### Redes Neuronales — Deep Learning · Maestría en Ciencia de Datos

URL Repositorio: https://github.com/edwinyhovany/centinela/

Integrantes

**Edwin Yhovany Garzon Amezquita**

**Jeferson Torrado Bayona**


Este cuaderno resuelve la Fase 3 del Proyecto Integrador *Centinela* de principio a fin, pasa de comparar TensorFlow/Keras 3 y PyTorch lado a lado, por la aceleración en GPU con precisión mixta, los pipelines de datos eficientes y termina en el guardado y la exportación a ONNX lista para desplegar, reproduciendo en código las ideas de los Capítulos 3.1 a 3.3.

---

**Contenido**

0. Preparación del entorno (semilla, *device*, paleta USTA, política de datos)
1. Etapa A — Pipeline de datos reproducible: estructura tf.data/DataLoader de ejemplo · # TODO pipeline real con Data Augmentation, prefetch/cache y partición sin fuga (leakage)
2. Etapa B — Entrenamiento acelerado (GPU + precisión mixta): utilidades de timing y checkpointing a Drive · # TODO entrenar con AMP, early stopping y checkpoints; reportar speed-up
3. Etapa C — Exportación y despliegue offline (borde): benchmark de inferencia + plantilla ONNX con modelo dummy funcional · # TODO exportar a ONNX/LiteRT, cuantizar y validar paridad (np.allclose); medir latencia/tamaño
4. Sección final — Checklist de entrega + rúbrica de la Fase 3 (criterios y pesos que suman 100 %)
