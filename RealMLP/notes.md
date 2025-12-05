## RealMLP

[Better by Default: Strong Pre-Tuned MLPs and Boosted Trees on Tabular Data](https://arxiv.org/abs/2407.04491)

# Resumo
RealMLP é uma arquitetura baseada no multi-layer perceptron para dados
tabulares que pode ser treinado tanto para classificação (dado um input com
certas categorias, ele prevê uma classe a qual esse input pertence), quanto
regressão (dado um input com certas categorias, ele prevê um específico valor
numérico para uma nova categoria deste input). Essa arquitetura é introduzidada
em um contexto em que gradient-boosted decision trees (GBDTs) dominam essas
atividades, e outras opções são geralmente mais lentas. No paper, os pesos do
modelo são treinados, assim como suas configurações padrões, por um dataset de
meta-treino com 118 datasets diferentes e avaliados por um dataset de teste
composto por 90 datasets, estes resultados são comparados com versões de
híper-paramêtros otimizados (Abstract, linha 5-9). Sob os datasets de testes, o
RealMLP, mostra um melhor custo de tempo para precisão com outros modelos
neurais e seus resultados são comparáveis com o de GBDTs. Além disso, uma
combinação de RealMLP e GBDTs com parâmetros padrões melhorados atingem ótimos
resultados sem tuning de híper-parâmetros. Por fim, as melhorias de RealMLP
podem melhorar a performance de TabR (uma outra arquitetura de deep learning
para dados tabulares) com parâmetros padrões .


