# Trabalho-final-Teoria-dos-grafos

Autora: Beatriz Emily Silva Aguiar
Matrícula: 22154303

Este repositório contém o código, os resultados e o relatório desenvolvidos para o trabalho final da disciplina de Teoria dos Grafos (IComp/UFAM). O objetivo do estudo foi modelar sinais motores como grafos e aplicar uma Graph Convolutional Network (GCN) para classificar participantes do dataset PADS entre controles saudáveis e pacientes com Doença de Parkinson.

##A construção do grafo inclui:

extração de características em janelas temporais;

modelagem de cada participante como um grafo com 61 vértices (canais sensoriais);

construção das arestas via k-NN (similaridade funcional);

representação utilizando PyTorch e PyTorch Geometric.

O notebook principal (physionet_study.ipynb) demonstra toda a pipeline de pré-processamento, construção dos grafos, definição do modelo e treinamento da GCN.

##Download do Dataset

Para executar os experimentos, é necessário baixar o dataset PADS (Parkinson’s Disease Analysis Data Set) diretamente do PhysioNet. O download pode ser feito no link:
https://physionet.org/content/parkinsons-disease-smartwatch/1.0.0/scripts/
