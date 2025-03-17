# Cardiac-Detectio
Cardiac Detection

Este repositório contém um notebook para detecção de regiões cardíacas em imagens médicas no formato DICOM, utilizando técnicas de deep learning.

Dataset Utilizado

Imagens médicas no formato DICOM

O dataset inclui bounding boxes para marcação de regiões de interesse (ROI)

Técnicas Utilizadas

Pré-processamento:

Carregamento de imagens com pydicom

Redimensionamento e normalização das imagens

Aplicação de aumentações: ajuste de contraste, rotação e movimentação

Detecção de Regiões Cardíacas:

Utiliza bounding boxes para destacar áreas relevantes

Visualização das imagens segmentadas com Matplotlib

Modelo de Machine Learning:

Implementação de uma Rede Neural Convolucional (CNN) para treinamento e detecção

Resultados Obtidos

O modelo foi treinado para identificar regiões cardíacas em imagens médicas, utilizando bounding boxes para demarcação.

Métricas utilizadas para avaliação:

IoU (Intersection over Union)

Acurácia do modelo

Licença

Este projeto está sob a licença MIT.
