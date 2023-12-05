# Projeto de Processamento Digital de Imagens (PDI)

Este projeto contém implementações de modelos de aprendizado profundo para tarefas de visão computacional, específicas para a disciplina de Processamento Digital de Imagens.

## Modelo DINO V2

### Descrição
O modelo DINO V2 é uma implementação de Vision Transformer (ViT) que se destaca por seu treinamento sem supervisão, utilizando uma abordagem inovadora de maximização de similaridade entre representações de diferentes instâncias de uma imagem.

### Arquivos Relevantes
- `dino_v2_pdi.ipynb`: Jupyter Notebook contendo o código Python para treinar e avaliar o modelo DINO V2.
- `imagens/`: Diretório contendo as imagens utilizadas para treinamento e teste.

### Requisitos
Certifique-se de ter as seguintes bibliotecas instaladas antes de executar o código:
```bash
pip install torch torchvision tqdm pandas seaborn matplotlib scikit-learn
```
### Como Executar
Execute o notebook dino_v2_pdi.ipynb em um ambiente compatível com Jupyter.

## Modelo CNN Simples

### Descrição

O modelo CNN Simples é uma Convolutional Neural Network básica projetada para tarefas de classificação de imagens. Este modelo serve como ponto de comparação com o DINO V2.

### Arquivos Relevantes

- simple_cnn_pdi.ipynb: Jupyter Notebook contendo o código Python para treinar e avaliar o modelo CNN Simples.
- imagens/: Diretório contendo as imagens utilizadas para treinamento e teste.

### Requisitos

Certifique-se de ter as seguintes bibliotecas instaladas antes de executar o código:

```bash
pip install torch torchvision tqdm pandas seaborn matplotlib scikit-learn
```

### Como Executar
Execute o notebook simple_cnn_pdi.ipynb em um ambiente compatível com Jupyter.

## Considerações

Os modelos foram implementados como parte de um projeto acadêmico para a disciplina de Processamento Digital de Imagens. Consulte os notebooks individuais para obter mais detalhes sobre o treinamento, avaliação e análise de resultados.

```bash
Este leia-me fornece uma visão geral dos modelos, seus requisitos e instruções básicas para execução. Certifique-se de personalizar as seções conforme necessário, especialmente as seções de requisitos e instruções de execução, se você estiver utilizando um ambiente diferente do Jupyter Notebook.
```

Base de dados extraida de https://www.kaggle.com/datasets/umairshahpirzada/birds-20-species-image-classification 






