# Predicción del Éxito de Atracciones Turísticas

Bienvenido/a a mi proyecto de Deep Learning 🤖 enfocado en predecir si una atracción turística (POI) generará **bajo, medio o alto engagement**. El reto combina visión por computador y datos estructurados para anticipar qué lugares captarán más la atención de los usuarios.

## ¿Qué hace este repo?

1. **Carga y limpia los datos**: Partimos de un CSV con descripciones, imágenes y métricas de interacción de cada POI.
2. **Crea la métrica objetivo** (`engagement_score`) y su categoría (`eng_cat`).
3. **Preprocesa** imágenes, texto y variables numéricas/categóricas.
4. **Entrena** un modelo híbrido (CNN + fully connected) usando PyTorch.
5. **Guarda** los pesos finales en formato `.pt` y `.onnx`.

## Estructura rápida del repo

```
├── 01_EDA_POI.ipynb          # Exploración de datos
├── 02_Target_Engagement.ipynb # Cálculo de métrica objetivo
├── 03_Preprocesado_POI.ipynb  # Limpieza y feature engineering
├── 04_Training_POI_NN.ipynb   # Entrenamiento del modelo
├── hybridpoi_best.pt          # Pesos del modelo (PyTorch)
├── hybridpoi_best.onnx        # Versión ONNX del modelo
└── README.md                  # Este documento
```

## Requisitos rápidos

- Python >= 3.9

Instala todo con:

```bash
pip install -r requirements.txt  # o instala manualmente las libs de arriba
```

## Selfie de Red Neuronal!! 

![hybridpoi_best onnx](https://github.com/user-attachments/assets/681346cf-c721-48d2-b840-224e2a8e35c2)


## Autor

Nauzet Fenandez Lorenzo – [Nauzet.fdez@gmail.com](mailto\:Nauzet.fdez@gmail.com)

¡Cualquier feedback o PR es bienvenido! ❤️

