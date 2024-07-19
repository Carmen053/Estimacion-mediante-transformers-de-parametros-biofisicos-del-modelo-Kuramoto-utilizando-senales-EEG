# Estimacion-mediante-transformers-de-parametros-biofisicos-del-modelo-Kuramoto-utilizando-senales-EEG
Estimación mediante transformers de parámetros biofísicos del modelo Kuramoto utilizando señales EEG.


En este repositorio encontraremos los siguientes documentos:

- Datos usados para el desarrollo del modelo:
- Código necesario para desarrollar el modelo con transformers (eligiendo entre 4, 121, 256, 496 clases) : Modelo_transformer.ipynb
- Modelos transformers entrenados : TFG_carpeta_modelo.zip
- Código necesario para desarrollar el modelo con convolucionales (4 clases) : Modelo_convolucional.ipynb
- Datos usados para la prueba con nodos apagados :
    - Spectrums_removingNode.mat (Nodos apagados antes de la normalización)
    - Spectrums_removingNode_afterNormalization.mat (Nodos pagados después de la normalización)
    - Espectro_K4MD21_seed_5.mat y Espectro_K4MD21_seed_3.mat (sin nodos apagados)
- Código necesario para desarrollar las pruebas con nodos apagados : Nodos_apagados.ipynb

