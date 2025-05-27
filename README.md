## **Projeto de Regressão Random Forest para Manutenção Preditiva em Fábrica de Pneus**

### **1\. Introdução**

Este relatório detalha a implementação de um modelo de regressão Random Forest para a manutenção preditiva de equipamentos em uma fábrica de pneus. O objetivo do projeto é prever a probabilidade de falhas nos equipamentos com base em dados de produção e manutenção, permitindo ações preventivas que otimizem a produção e reduzam o tempo de inatividade.

### **2\. Metodologia**

A metodologia adotada envolve as seguintes etapas:

1. **Coleta de Dados:** Os dados foram coletados em um DataFrame do Pandas, incluindo informações sobre a data, produção, defeitos, tipo de manutenção e produção acumulada. Para o modelo de regressão Random Forest, foram utilizados dados fictícios de manutenção e falhas, onde as variáveis independentes (X) representam os dias desde a última manutenção e a produção, e a variável dependente (y) indica a ocorrência de falha (1 para falha, 0 para sem falha).  
2. **Pré-processamento de Dados:** Os dados foram organizados em um formato adequado para o treinamento do modelo, com as variáveis independentes e a variável dependente claramente definidas.  
3. **Treinamento do Modelo:** Um modelo de regressão Random Forest foi treinado utilizando os dados fictícios. O Random Forest é um algoritmo de aprendizado de máquina que constroi múltiplas árvores de decisão e combina suas previsões para obter uma estimativa mais precisa e robusta.  
4. **Avaliação do Modelo:** O modelo foi avaliado utilizando os dados de treinamento para verificar sua capacidade de prever a probabilidade de falhas.  
5. **Predição:** O modelo treinado foi utilizado para prever a probabilidade de falha para novos dados de produção e manutenção.

### **3\. Implementação**

A implementação do modelo foi realizada em Python utilizando as bibliotecas Pandas, Scikit-learn e Numpy.

### **4\. Resultados**

O modelo de regressão Random Forest foi capaz de prever a probabilidade de falha dos equipamentos com base nos dados de produção e manutenção. No exemplo fornecido para o projeto, a probabilidade de falha para um equipamento com 6 dias desde a última manutenção e produção de 350 pneus foi de 0.78.

### **5\. Conclusão**

A utilização de um modelo de regressão Random Forest para a manutenção preditiva em uma fábrica de pneus se mostrou eficaz na previsão da probabilidade de falhas nos equipamentos. Essa abordagem permite que a fábrica tome medidas preventivas, como a programação de manutenções, antes que as falhas ocorram, otimizando a produção e reduzindo os custos associados ao tempo de inatividade.
