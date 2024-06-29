# Análise e Classificação de Imagens com Redes Neurais Convolucionais

Este repositório contém um notebook que explora a aplicação de redes neurais convolucionais (CNNs) para a classificação de diferentes datasets de imagens. Foram utilizados quatro datasets distintos e diversas abordagens de redes neurais, incluindo modelos criados do zero, AlexNet, VGG, ResNet18 e Inception V3. A análise detalhada e os resultados de cada experimento são apresentados neste notebook.

## Descrição dos Datasets

1. **Color Rectal Histology**:
   - **Descrição**: Imagens histológicas de 150x150 pixels.
   - **Classes**: 8 classes (tumor, stroma, complex, lympho, debris, mucosa, adipose, empty).
   - **Abordagens**: CNN criada do zero, AlexNet, ResNet18 pré-treinada.
   - **Conclusões**: ResNet18 pré-treinada apresentou os melhores resultados, indicando a eficácia da transferência de aprendizado.

2. **Brazilian Coffee Scenes**:
   - **Descrição**: Imagens de sensoriamento remoto de plantações de café com 64x64 pixels.
   - **Classes**: 2 classes (café ou não-café).
   - **Abordagens**: CNN criada do zero, AlexNet, ResNet18 pré-treinada.
   - **Conclusões**: CNN criada do zero teve resultados satisfatórios, enquanto a ResNet18 pré-treinada evidenciou overfitting.

3. **UCMerced**:
   - **Descrição**: Imagens de sensoriamento remoto de 256x256 pixels.
   - **Classes**: 21 classes.
   - **Abordagens**: CNN criada do zero, VGG, ResNet18 pré-treinada.
   - **Conclusões**: ResNet18 pré-treinada teve desempenho superior, sem sinais de overfitting, destacando a eficácia da transferência de aprendizado.

4. **Describable Textures Dataset (DTD)**:
   - **Descrição**: Imagens genéricas de texturas com tamanhos variados (300x300 a 640x640 pixels).
   - **Classes**: 47 classes.
   - **Abordagens**: CNN criada do zero, VGG, ResNet18 pré-treinada, Inception V3.
   - **Conclusões**: Inception V3 apresentou os melhores resultados, mas ainda com sinais de overfitting. A transferência de aprendizado mostrou-se crucial para este dataset complexo.
