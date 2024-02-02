# Machine Learning

Repositório referente à disciplina de Machine Learning! Este espaço é dedicado à execução dos trabalhos desenvolvidos como parte do curso. Durante esta disciplina, exploramos diversas técnicas fundamentais em Machine Learning, desde a compreensão dos algoritmos até a aplicação prática em conjuntos de dados reais. No decorrer deste repositório, você encontrará implementações de algoritmos, análises exploratórias, experimentos de modelagem e avaliações de desempenho. Este repositório abrigará uma variedade de trabalhos, cada um focado em aspectos específicos do aprendizado de máquina

### Projeto 1: Algoritmos de Regressão Linear

Este projeto apresenta implementações dos algoritmos de Regressão Linear utilizando duas abordagens distintas: Gradiente Descendente e Solução Analítica. As classes `GradientDescent` e `AnalyticalSolution` foram desenvolvidas para realizar a regressão linear em conjuntos de dados, aceitando qualquer quantidade de atributos.

#### Gradiente Descendente

A classe `GradientDescent` utiliza o método do gradiente descendente para ajustar os pesos do modelo. Durante o treinamento, a curva de erro é registrada para análise. Após o treinamento, são fornecidos os valores finais dos pesos, o erro de treinamento e a visualização da curva de erro. Além disso, é possível realizar previsões em conjuntos de teste e avaliar o desempenho com o coeficiente de determinação (R²).

#### Solução Analítica

Por outro lado, a classe `AnalyticalSolution` emprega a solução analítica, calculando os pesos diretamente através da inversa da matriz de características. Assim como na abordagem do Gradiente Descendente, esta classe permite a previsão em conjuntos de teste e avaliação do desempenho.

#### Conjunto de Dados Utilizado

O conjunto de dados utilizado neste projeto é proveniente da UCI e refere-se à "Combined Cycle Power Plant". Este conjunto contém informações sobre temperatura ambiente (AT), vácuo (V), pressão atmosférica (AP), umidade relativa (RH) e energia líquida produzida (PE). A análise é conduzida com normalização das variáveis.

Este projeto oferece uma compreensão prática dos algoritmos de Regressão Linear, explorando diferentes métodos para a obtenção de resultados precisos em conjuntos de dados do mundo real.
