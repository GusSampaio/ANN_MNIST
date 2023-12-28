# ANN_MNIST
## Objetivo - Descrição em Português
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
