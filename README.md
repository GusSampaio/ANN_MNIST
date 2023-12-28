# ANN_MNIST
## Objetivo - Descrição em Português 🇧🇷
O objetivo principal deste projeto é proporcionar uma compreensão aprofundada do funcionamento de redes neurais artificiais, explorando especialmente a influência das taxas de aprendizado no desempenho do modelo. Além disso, o projeto visa fornecer insights sobre todo o ciclo de vida da rede neural, desde sua criação até o pós-processamento dos resultados.

## Visão Geral
### Arquitetura da Rede Neural

A rede neural é composta por três camadas lineares.
A primeira camada (linear1) tem entrada de tamanho 28x28 e 128 neurônios.
A segunda camada (linear2) tem 128 neurônios de entrada e 64 neurônios de saída.
A terceira camada (linear3) possui 64 neurônios de entrada e 10 neurônios de saída, correspondendo aos possíveis dígitos de 0 a 9.

### Treinamento
Foi utilizado o otimizador SGD (Gradiente Descendente Estocástico) com uma taxa de aprendizado inicial de 0.01 e momentum de 0.5.
A função de perda utiliziada foi a NLL (Negative Log Likelihood). Esta função que itera sobre o conjunto de dados de treinamento, ajusta os pesos da rede e monitora o desempenho por meio da perda acumulada.
A perda monitora é relativa tanto ao conjunto de treino quanto ao conjunto de avaliação. Desta forma, é possível observar se o número de épocas, infraestrutura da rede e outros detalhes estão coerentes e funcionais durante o treinamento.

### Avaliação
Algumas métricas foram consideradas para avaliar o modelo. 
- Primeiramente foi medida a acurácia do modelo;
- Em seguida, a curva ROC e o valor AUC para cada classe prevista;
- Por fim, a matriz de confusão observada.

### Melhorias Contínuas
Possíveis melhorias poderiam envolver, por exemplo, aumento de dados de forma a possbilitar o modelo a aprender números em ângulos diferentes.
Além de também explorar diferentes hiperparâmetros, técnicas de regularização e estratégias de treinamento para otimizar o desempenho da rede neural.

### Execução do Projeto
Para executar este projeto, basta instalar as bibliotecas presentes no arquivo 'requirements.txt' ou rodar o arquivo .ipynb no Goggle Colab.

### Contribuições
Contribuições são bem-vindas! Se você identificar melhorias, problemas ou tiver sugestões, sinta-se à vontade para contribuir para este projeto.

## Objective - Description in English 🇺🇸
The main objective of this project is to provide an in-depth understanding of the functioning of artificial neural networks, especially exploring the influence of learning rates on model performance. Furthermore, the project aims to provide insights into the entire neural network lifecycle, from its creation to post-processing of results.

## Overview
### Neural Network Architecture

The neural network is made up of three linear layers.
The first layer (linear1) has input size 28x28 and 128 neurons.
The second layer (linear2) has 128 input neurons and 64 output neurons.
The third layer (linear3) has 64 input neurons and 10 output neurons, corresponding to the possible digits from 0 to 9.


### Training
The SGD (Stochastic Gradient Descent) optimizer was used with an initial learning rate of 0.01 and momentum of 0.5.
The loss function used was NLL (Negative Log Likelihood). This function that iterates over the training dataset, adjusts the network weights, and monitors performance through accumulated loss.
The monitor loss is relative to both the training set and the evaluation set. This way, it is possible to observe whether the number of epochs, network infrastructure and other details are coherent and functional during training.

### Assessment
Some metrics were considered to evaluate the model.
- Firstly, the accuracy of the model was measured;
- Then the ROC curve and the AUC value for each predicted class;
- Finally, the observed confusion matrix.

### Continuous Improvements
Possible improvements could involve, for example, data augmentation in order to enable the model to learn numbers at different angles.
In addition to also exploring different hyperparameters, regularization techniques and training strategies to optimize the performance of the neural network.

### Project Execution
To run this project, simply install the libraries present in the 'requirements.txt' file or run the .ipynb file in Goggle Colab.

### Contributions
Contributions are welcome! If you identify improvements, problems or have suggestions, please feel free to contribute to this project.
