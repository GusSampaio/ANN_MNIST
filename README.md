# ANN_MNIST
Este projeto consiste em um estudo de caso sobre uma Rede Neural Artificial (RNA) projetada para reconhecer dígitos em imagens 28x28. Cada imagem contém um algarismo associado a um rótulo previamente conhecido.

## Objetivo
O objetivo principal deste projeto é proporcionar uma compreensão aprofundada do funcionamento de redes neurais artificiais, explorando especialmente a influência das taxas de aprendizado no desempenho do modelo. Além disso, o projeto visa fornecer insights sobre todo o ciclo de vida da rede neural, desde sua criação até o pós-processamento dos resultados.

## Visão Geral
### Arquitetura da Rede Neural:

A rede neural é composta por três camadas lineares.
A primeira camada (linear1) tem entrada de tamanho 28x28 e 128 neurônios.
A segunda camada (linear2) tem 128 neurônios de entrada e 64 neurônios de saída.
A terceira camada (linear3) possui 64 neurônios de entrada e 10 neurônios de saída, correspondendo aos possíveis dígitos de 0 a 9.


### Treinamento
Utilização do otimizador SGD (Gradiente Descendente Estocástico) com uma taxa de aprendizado inicial de 0.01 e momentum de 0.5.
Aplicação de uma função de perda NLL (Negative Log Likelihood).
Implementação de uma função de treinamento que itera sobre o conjunto de dados de treinamento, ajusta os pesos da rede e monitora o desempenho por meio da perda acumulada.

### Avaliação
Exibição de métricas relevantes, como a precisão do modelo no conjunto de validação.

### Melhorias Contínuas
Exploração de diferentes hiperparâmetros, técnicas de regularização e estratégias de treinamento para otimizar o desempenho da rede neural.
Monitoramento de métricas ao longo do treinamento para ajustar o modelo conforme necessário.

### Execução do Projeto
Para executar este projeto, basta instalar as bibliotecas presentes no arquivo 'requirements.txt' ou rodar no Goggle Colab.

### Contribuições
Contribuições são bem-vindas! Se você identificar melhorias, problemas ou tiver sugestões, sinta-se à vontade para contribuir para este projeto.
