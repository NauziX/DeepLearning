# Predicción del Éxito de Atracciones Turísticas

Bienvenid@ a mi proyecto de Deep Learning enfocado en predecir si una atracción turística (POI) generará **bajo, medio o alto engagement**. El reto combina imagenes y datos estructurados para anticipar qué lugares captarán más la atención de los usuarios.

## ¿Qué hace este repo?

1. **Carga y limpia los datos**: Partimos de un CSV con descripciones, imágenes y métricas de interacción de cada POI.
2. **Crea la métrica objetivo** (`engagement_score`) y su categoría (`eng_cat`).
3. **Preprocesa** imágenes, texto y variables numéricas/categóricas.
4. **Entrena** un modelo híbrido (CNN + fully connected) usando PyTorch.
5. **Guarda** los pesos finales en formato `.pt` y `.onnx`.

## Estructura rápida del repositorio 

```
├── 01_EDA_POI.ipynb          # Exploración de datos
├── 02_Target_Engagement.ipynb # Cálculo de métrica objetivo
├── 03_Preprocesado_POI.ipynb  # Limpieza y feature engineering
├── 04_Training_POI_NN.ipynb   # Entrenamiento del modelo
├── hybridpoi_best.pt          # Pesos del modelo (PyTorch)
├── hybridpoi_best.onnx        # Versión ONNX del modelo
├── poi_dataset.csv            # Dataset original
├── poi_dataset_engagment.csv  # Dataset con el target
├── poi_dataset_eng_pre.csv    # Dataset con el target y las feautres preparadas para modelar
├── desc_vectors.npy           # ShortDescription Tokenizado
├── cat_seqs.npy               # Categorias Embedding Ind 
├── requirements.txt           # Librerias a utilizar
├── Memoria Técnica Final del Proyecto.pdf
├── Enunciado_Práctica_DL.pdf  # Objetivos de este proyecto  
└── README.md                  # Este documento

```
### Navegación directa

- [01\_EDA\_POI.ipynb](01_EDA_POI.ipynb) – Análisis exploratorio.
- [02\_Target\_Engagement.ipynb](02_Target_Engagement.ipynb) – Definición de la métrica de engagement.
- [03\_Preprocesado\_POI.ipynb](03_Preprocesado_POI.ipynb) – Preprocesado y generación de features.
- [04\_Training\_POI\_NN.ipynb](04_Training_POI_NN.ipynb) – Entrenamiento y evaluación del modelo.


## Requisitos rápidos

- Python >= 3.9

Instala todo con:

```bash
pip install -r requirements.txt
```

## Selfie de mi red neuronal!! 

![hybridpoi_best onnx](https://github.com/user-attachments/assets/681346cf-c721-48d2-b840-224e2a8e35c2)


## Autor

Nauzet Fenandez Lorenzo – [Nauzet.fdez@gmail.com](mailto\:Nauzet.fdez@gmail.com)

¡Cualquier feedback o PR es bienvenido!

