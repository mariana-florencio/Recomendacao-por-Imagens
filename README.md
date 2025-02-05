# Sistema de Recomendacao de Imagens com EfficientNetB0

Este projeto implementa um sistema de recomendacao de imagens utilizando a rede neural convolucional EfficientNetB0. O modelo e treinado para extrair embeddings de imagens e recomendar as mais similares com base na similaridade cosseno.

## Tecnologias Utilizadas

Python;
TensorFlow;
TensorFlow Datasets;
Keras;
NumPy;
Scikit-learn;
Matplotlib.

## Como Funciona

1. Carregamento do dataset tf_flowers do TensorFlow Datasets;

2. Processamento das imagens para padrao 224x224;

3. Extracao de features das imagens usando o modelo EfficientNetB0 (sem a camada de classificacao);

4. Armazenamento dos embeddings das imagens do dataset;

5. Recomendacao das imagens mais similares a uma imagem de entrada usando similaridade cosseno;

6. Visualizacao das imagens recomendadas.

