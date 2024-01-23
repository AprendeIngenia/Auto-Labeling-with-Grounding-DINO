# Auto-Labeling-with-Grounding-DINO
Hola chicos en este repositorio encontraran la programación y los comandos completos para automatizar el proceso de etiquetado de en sus datasets.

### Conceptos introductorios:
- Para iniciar recomendamos ver algunos conceptos introductorios con el fin de entender un poco mejor todo el funcionamiento, por eso te dejamos la explicacion en este [video.](https://youtu.be/I5o9y-ZwLQg)
- Recuerda que puedes encontrar toda la informacion de Grounding DINO en el siguiente [enlace](https://github.com/IDEA-Research/Grounded-Segment-Anything/tree/main).

### Auto labeling with Grounding DINO:
- Grounding DINO es un modelo avanzado desarrollado recientemente por investigadores de Facebook AI Research, Microsoft Research Asia y Carnegie Mellon University. Su principal innovación consiste en combinar las capacidades de aprendizaje visual y lingüístico dentro de un único marco de entrenamiento, permitiendo así vincular referencias lingüísticas directamente con regiones específicas de una imagen. En otras palabras, Grounding DINO puede comprender los conceptos expresados mediante el lenguaje natural y localizar esos conceptos dentro de una escena visual.
- El modelo consta de dos partes principales:

  - Una red neuronal vision-language (VL) multimodal que ha sido preentrenada utilizando datos de captions de imágenes provenientes de diversas fuentes públicas. La arquitectura VL incluye una parte visual basada en Vision Transformer (ViT) y otra parte lingüística formada por Transformer. Ambas partes interactúan entre sí durante el entrenamiento para mejorar su capacidad conjunta de relacionar texto y contexto visual.

  - Un método de postprocesamiento llamado "iterative refinement" que permite al modelo pulir sus predicciones hasta llegar a una mayor precisión y coherencia. Este procedimiento funciona iterativamente, corrigiendo gradualmente las predicciones incorrectas mientras mantiene aquellas que ya han sido clasificadas correctamente. Gracias a ello, Grounding DINO logra obtener resultados más precisos y robustos que otros modelos similares.

- En este caso utilizaremos Grounding DINO para etiquetado semiautomático de datasets de detección de objetos:
  - Podrás aprovechar el poder de Grounding DINO para generar propuestas de bounding boxes altamente precisas, reduciendo drásticamente el tiempo necesario para el etiquetado manual. Además, el modelo también puede ser empleado para inferir categorías de objetos presentes en cada región propuesta, aqui te dejamos el [codigo](https://github.com/AprendeIngenia/Auto-Labeling-with-Grounding-DINO/blob/7238a0dbfe87e31a0ec5fb81b7c6febd678cba13/Labeling_with_Grounding_DINO.ipynb) para que experimentes con el.
 
![YoloV8](https://github.com/AprendeIngenia/Auto-Labeling-with-Grounding-DINO/assets/85022752/ea0aa2cf-9f76-49b8-be2c-6acb65620230)

# Recuerda que puedes contribuir a que siga desarrollando:
Simplemente suscribiendote a mi canal de YouTube:
- [Canal YouTube](https://www.youtube.com/channel/UCzwHEOCbsZLjfELperJ6VeQ/videos)

### Siguiendome en mis redes sociales: 
- [Instagram](https://www.instagram.com/santiagsanchezr/)
- [Twitter](https://twitter.com/SantiagSanchezR)

