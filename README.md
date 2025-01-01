# Desarrollo de un Sistema de Identificación y Clasificación Automatizado de Residuos para Fomentar la Recolección y Reciclaje Eficiente para el Medio Ambiente

Este proyecto presenta el diseño y desarrollo de un sistema automatizado de identificación y clasificación de residuos mediante visión por computadora, con el objetivo de optimizar las prácticas de reciclaje en espacios públicos. Ante la creciente necesidad global de una gestión de residuos eficiente, este proyecto aprovecha tecnologías avanzadas para agilizar la clasificación de materiales reciclables, reduciendo las in eficiencias y errores comunes en los procesos manuales de separación. El sistema está basado en el modelo de aprendizaje profundo YOLOv8, seleccionado por su robustez en tareas de detección de objetos. Los datos de entrenamiento provienen principalmente del conjunto de la database TACO y se complementaron con imágenes de Kaggle, centradas en tres categorías de residuos: metal, plástico y papel-cartón. La preparación de datos incluyó una anotación detallada mediante la herramienta LabelMe y técnicas de preprocesamiento para convertir las imágenes en un formato compatible con YOLOv8.

## Requisitos Previos
- **Requisitos:**
  - Python 3.8 o superior instalado
  - pip (gestor de paquetes de Python) instalado
  - Una webcam funcional (para captura de video en vivo)
  - GPU con soporte CUDA (opcional, para una inferencia más rápida del modelo YOLO)

- **Pasos de Instalación:**
  1. Clonar el repositorio y mover al directorio correspondiente:
     ```bash
     git clone https://github.com/csuvg/PG-2024-20358
     ```

  2. Instalar las dependencias necesarias:
     ```bash
     cd PG-2024-20332/Trash\ Classification/src/
     pip install -r requirements.txt
     ```

  3. Ejecutar el script para verificar que todo funcione correctamente:
     ```bash
     cd PG-2024-20332/Trash\ Classification/src/FinalModel/
     python detection.py
     ```

## Demo

[Demostración visual del proyecto en acción.](https://github.com/PG-2024-20358/blob/main/Trash%20Classification/demo/demo.mp4)

## Informe Final 

[Informe final del proyecto de graduación](https://github.com/PG-2024-20358/blob/main/Trash%20Classification/docs/informe_final.pdf)

