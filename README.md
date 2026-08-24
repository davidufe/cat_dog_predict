# Classificador de Cães e Gatos

Projeto da disciplina de Aprendizado de Máquina (UFRN): comparação de modelos de classificação de imagens de cães e gatos.

## Sobre

O projeto consiste no processamento de imagens de cães e gatos, extração de características (HOG e um gerador de features baseado em CNN) e treinamento de cinco famílias de classificadores — KNN, Árvore de Decisão, Naive Bayes, MLP e um Comitê (ensemble). O desempenho dos modelos é comparado com testes estatísticos, documentados no relatório técnico.

## Tecnologias

`Python` `scikit-learn` `OpenCV`/`HOG` · Redes Neurais (CNN) · testes estatísticos

## Estrutura do repositório

- `Atividade-1-KNN.ipynb`
- `Atividade-2-DecisionTree.ipynb`
- `Atividade-3-NaiveBayes.ipynb`
- `Atividade-4-MLP.ipynb`
- `Atividade-5-Comitê.ipynb`
- `Gerador_HOG_CNN.ipynb` — extração de features
- `Relatório.pdf` — relatório técnico com a comparação estatística entre os modelos

## Como executar

Abrir `Gerador_HOG_CNN.ipynb` primeiro para gerar as features, em seguida os notebooks de cada modelo, em um ambiente Jupyter/Colab com as dependências instaladas.

## Autor

Davi Dutra Ferreira
[LinkedIn](https://www.linkedin.com/in/davidufe)
