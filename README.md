# Perceptron Manual com a Base Iris

Atividade acadêmica de **Aprendizagem de Máquina** com implementação manual de um **Perceptron de 2 entradas + bias**, sem uso de NumPy ou bibliotecas de machine learning.

## Objetivo
Desenvolver um notebook simples e didático que apresente:

- uso de uma base do Kaggle
- análise básica do dataset
- escolha de duas entradas para o Perceptron
- implementação manual da função do Perceptron
- treinamento dos pesos e do bias
- testes de funcionamento
- gráficos para apoiar a análise e o aprendizado

## Base utilizada
**Iris Dataset**

Arquivo utilizado:
- `Iris.csv`

## Problema proposto
Neste projeto, a base foi adaptada para um problema de **classificação binária**:

- `Iris-setosa` = 1
- `Iris-versicolor` = 0

A classe `Iris-virginica` foi removida para manter o modelo alinhado ao funcionamento de um Perceptron simples.

## Entradas escolhidas
As duas variáveis selecionadas foram:

- `PetalLengthCm`
- `PetalWidthCm`

Essas entradas foram escolhidas porque apresentam boa separação visual entre as classes analisadas.

## O que o notebook apresenta
- leitura manual do CSV
- informações básicas do dataset
- preparação da base binária
- gráficos das variáveis escolhidas
- função degrau
- função de previsão do Perceptron
- treinamento manual
- testes com amostras
- gráfico do histórico de erros
- fronteira de decisão

## Tecnologias utilizadas
- Python
- `csv`
- `matplotlib`

## Como executar
1. Coloque os arquivos na mesma pasta:
   - `perceptron_manual_iris_limpo.ipynb`
   - `Iris.csv`

2. Abra a pasta no VS Code.

3. Abra o notebook.

4. Selecione o kernel Python correto.

5. Execute as células em ordem, de cima para baixo.

## Resultado esperado
Como as duas entradas escolhidas possuem boa separação linear, o modelo tende a aprender rapidamente e apresentar alta acurácia na base utilizada.

## Observação
Este projeto tem foco didático e foi desenvolvido para demonstrar, de forma clara e simples, a lógica de funcionamento de um Perceptron manual.

## Autoria
Projeto desenvolvido para atividade acadêmica de Aprendizagem de Máquina.
