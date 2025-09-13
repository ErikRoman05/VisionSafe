# VisionSafe - Proyecto IA para Detección de Violencia en Videos

**VisionSafe** es una solución de inteligencia artificial que permite la **detección de violencia en videos en tiempo real**. Este proyecto fue desarrollado como parte de la feria **Innovatech 2025**, donde **ganó el primer lugar** en la categoría de innovación tecnológica. Su objetivo es ayudar a sistemas de seguridad y monitoreo mediante la detección automática de violencia en videos.

**Colaboradores**:
- **Junior Huanca**
- **Fernando Rivero**

## Descripción del Proyecto

VisionSafe utiliza un **modelo de IA entrenado** para analizar videos y detectar situaciones de violencia. Al identificar estos eventos, el sistema **activa una alerta sonora**. El modelo se entrena con **videos etiquetados** que contienen incidentes violentos y se utiliza en sistemas de vigilancia para monitoreo en vivo.

### Funcionalidades:
- **Detección de Violencia**: Detecta incidentes violentos en videos.
- **Alerta Sonora**: Emite una alerta sonora cuando se detecta violencia.
- **Entrenamiento del Modelo**: Se entrena con datos etiquetados para mejorar la precisión de la detección.

## Imágenes del Proyecto


![Captura de pantalla 1](https://github.com/ErikRoman05/VisionSafe/blob/main/Captura%20de%20pantalla%202025-09-13%20141429.png)
_Ejemplo de cómo se detecta la violencia en tiempo real en la cámara._

![Captura de pantalla 2](https://github.com/ErikRoman05/VisionSafe/blob/main/Captura%20de%20pantalla%202025-09-13%20141458.png)
_Violencia detectada con una puntuación de 0.71._

![Captura de pantalla 3](https://github.com/ErikRoman05/VisionSafe/blob/main/Captura%20de%20pantalla%202025-09-13%20142604.png)
_Entrenamiento del modelo y seguimiento de precisión durante las épocas._

![Captura de pantalla 4](https://github.com/ErikRoman05/VisionSafe/blob/main/Captura%20de%20pantalla%202025-09-13%20142616.png)
_Grafica de la pérdida durante el entrenamiento._

![Captura de pantalla 5](https://github.com/ErikRoman05/VisionSafe/blob/main/Captura%20de%20pantalla%202025-09-13%20142616.png)
_Grafica de precisión durante el entrenamiento._

![Captura de pantalla 6](https://github.com/ErikRoman05/VisionSafe/blob/main/Captura%20de%20pantalla%202025-09-13%20142643.png)
_Matriz de confusión del modelo entrenado._

## Descarga del Modelo Entrenado

Puedes descargar el modelo entrenado desde [Google Drive](https://drive.google.com/file/d/1FyYKeQJkybbwuoaw8uOMF0Fj2QBjaLfJ/view?usp=sharing).

## Requisitos

Para ejecutar este proyecto, necesitas tener instaladas las siguientes herramientas y librerías:

### Herramientas utilizadas:
- **TensorFlow**: Framework de aprendizaje profundo para la construcción y entrenamiento de modelos de IA.
- **Keras**: API de alto nivel para construir y entrenar redes neuronales, que se integra con TensorFlow.
- **OpenCV**: Biblioteca utilizada para procesar imágenes y videos en tiempo real.
- **Pygame**: Usada para generar la alerta sonora cuando se detecta violencia.
- **NumPy**: Librería para manejar matrices y operaciones matemáticas de manera eficiente.
- **Matplotlib**: Usada para visualizar resultados durante el entrenamiento del modelo.




