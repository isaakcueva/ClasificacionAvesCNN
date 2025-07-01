# 🦜 Sistema de Aprendizaje Automático para la Clasificación de Aves de la Región Andina del Ecuador
Sistema de clasificación automática de aves de la región andina del Ecuador usando redes neuronales convolucionales.
---
📋 Descripción
Este proyecto implementa un clasificador de imágenes basado en CNN para identificar especies de aves andinas del Ecuador. Incluye modelos entrenados tanto en RGB como en escala de grises, con una aplicación web desarrollada en Django para interacción del usuario.
Este trabajo de titulación representa el esfuerzo de aplicar técnicas de aprendizaje profundo en un problema real de clasificación de imágenes para aves de la Región Andina del Ecuador. Se espera que esta solución pueda servir como base para futuras implementaciones en entornos educativos, científicos o de producción.
🚀 Instalación
1. Clonar el repositorio
bashgit clone https://github.com/isaakcueva/ClasificacionAvesCNN.git
cd ClasificacionAvesCNN
2. Crear entorno virtual
bashpython -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
3. Instalar dependencias
bashpip install -r requirements.txt
4. Descargar modelo entrenado
⚠️ Importante: El modelo .h5 no está incluido por limitaciones de tamaño.

Crear carpeta models/ en la raíz del proyecto
Descargar el modelo desde: Modelos CNN - Clasificador de Aves
Colocar el archivo .h5 en la carpeta models/

📊 Contenido del Proyecto

aves_dataset.zip - Dataset original de imágenes de aves
aves_classifier.zip - Código fuente del sistema de clasificación
logs-rgb.zip - Logs de entrenamiento del modelo RGB
logs-gris.zip - Logs de entrenamiento del modelo en escala de grises
Trabajo_Titulación_IC.ipynb - Notebook completo con documentación del proceso

🔧 Uso
Notebook Principal
bashjupyter notebook Trabajo_Titulación_IC.ipynb
Aplicación Web (Django)
bashpython manage.py runserver
Acceder en: http://127.0.0.1:8000/
🏗️ Estructura
proyecto/
├── aves_dataset.zip
├── aves_classifier.zip
├── logs-rgb.zip
├── logs-gris.zip
├── models/                 # ⚠️ Crear manualmente
│   └── modelo.h5          # ⚠️ Descargar de Kaggle
├── requirements.txt
└── Trabajo_Titulación_IC.ipynb
🎯 Características

Clasificación de múltiples especies de aves andinas
Modelos entrenados en RGB y escala de grises
Interfaz web intuitiva
Documentación completa del proceso de entrenamiento
Logs detallados de performance

👤 Autor
Isaac Cueva
🙏 Dedicatoria
Dedicado a Dios y a mi familia. Por su constante apoyo en este largo proceso de crecimiento profesional.
💙 Agradecimientos
Agradecimiento especial al Ing. Charles Escobar, por su apoyo en el desarrollo de este proyecto.
🔗 Enlaces de Interés

Repositorio del Proyecto: https://github.com/isaakcueva/ClasificacionAvesCNN
Dataset RGB Aumentado: https://www.kaggle.com/datasets/isaakcueva/dataset-aves-da-rgb
Dataset Escala de Grises: https://www.kaggle.com/datasets/isaakcueva/dataset-aves-da-escala-de-grises
Modelos CNN Entrenados: https://www.kaggle.com/datasets/isaakcueva/modelos-cnn-clasificador-aves
