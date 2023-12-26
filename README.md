## Proyecto Imágenes

Este repositorio contiene códigos utilizados para el entrenamiento de modelos de detección de objetos en imágenes. A continuación, se describen los principales archivos y pasos necesarios para ejecutar el proyecto:

### Archivos Principales:
1. **codigo_swin_mmdetection_mm_pretrained.ipynb:** Jupyter Notebook que contiene el código para el entrenamiento utilizando el modelo preentrenado con el archivo de configuración específico `mask-rcnn_swin-t-p4-w7_fpn_1x_coco_con_mmpretrained.py`.

2. **codigo_swin_mmdetection_swin_pretrained.ipynb:** Jupyter Notebook similar al anterior, pero con la variante de haber sido ejecutado con el archivo de configuración `mask-rcnn_swin-t-p4-w7_fpn_1x_coco_con_swin_pretrained.py`.

### Configuración:
- Ambos códigos son análogos y solo difieren en el archivo de configuración utilizado.
- Antes de ejecutar, se debe reemplazar los archivos en el directorio que carga el código. Específicamente, los archivos a reemplazar son `coco_instance.py`y `mask-rcnn_swin-t-p4-w7_fpn_1x_coco.py`.
- Para esto hay que o copiar el contenido de los archivos en este github y remplazar el que contienen el archivo de los repositorios, o cambiarles el nombre a los de este repositorio y cargarlos manualmente remplazando los archivos originales.
- coco_instance.py debe ser remplazado por coco_instance_modificado_para_minneapple.py

### Ejecución:
1. Remplazar los archivos mencionados en el directorio del código.
2. Cargar los dos archivos JSON de entrenamiento y validación, como indica el código.
3. Ejecutar el script completo y permitir que el entrenamiento se lleve a cabo.

**Nota:** Asegurarse de tener todas las dependencias y bibliotecas necesarias instaladas antes de ejecutar los códigos. Consultar el entorno y requisitos en la documentación del proyecto si es necesario.
