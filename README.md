# Comparação de Descritores de Imagem

# Comparação de Descritores de Imagem: SIFT, ORB e HOG

Este projeto tem como objetivo implementar e analisar o desempenho de três importantes algoritmos de extração de características de imagem: 
"SIFT" (Scale-Invariant Feature Transform) 
"ORB" (Oriented FAST and Rotated BRIEF)  
"HOG" (Histogram of Oriented Gradients). 
A aplicação foi desenvolvida em Python, utilizando a biblioteca OpenCV, e aplicada a uma imagem de uma placa de trânsito.

🎯 Objetivo

O objetivo principal é comparar os três descritores em termos de:
- **Quantidade de keypoints (pontos-chave) detectados**.
- **Tempo de processamento** para a detecção e extração dos descritores.
- **Qualidade visual** dos keypoints identificados.

🧠 Algoritmos Implementados

1. SIFT (Scale-Invariant Feature Transform)
*   **Características**: Invariante a escala, rotação, mudanças de iluminação e ponto de vista. É um algoritmo robusto, porém mais lento.
*   **Aplicação**: Ideal para tarefas que exigem alta precisão, como *image stitching*, *tracking* de objetos e reconhecimento 3D.

2. ORB (Oriented FAST and Rotated BRIEF)
*   **Características**: Uma alternativa mais rápida ao SIFT e SURF. É invariante a rotação e escala, sendo eficiente para aplicações em tempo real.
*   **Aplicação**: Utilizado em sistemas embarcados, robótica e aplicações *mobile* que exigem baixo custo computacional.

3. HOG (Histogram of Oriented Gradients)
*   **Características**: Descritor baseado em gradientes de orientação, muito utilizado para detecção de objetos. Não detecta keypoints, mas sim gera um vetor de características da imagem inteira.
*   **Aplicação**: Amplamente utilizado em detectores de pedestres, veículos e outros objetos rígidos.


