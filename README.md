# Agente de Q-Learning para Negociação de Ações

## Problema de Negócio

Construir um robô (modelo em Linguagem Python) baseado em Inteligência Artificial que aprenda a operar na bolsa de valores a partir de experimentos de compra e venda de ações. Dado um saldo inicial o modelo deve apresentar o resultado (lucro) a ser obtido depois de ações de compra e venda.

## Objetivo

O objetivo principal deste projeto é explorar e entender a aplicação do algoritmo de Q-Learning na área de finanças, especificamente na negociação de ações. O agente é treinado para tomar decisões de compra e venda com base nas mudanças nos preços das ações ao longo do tempo.

## Pré-requisitos

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
### Bibliotecas:
  
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
```bash
pip install plotly pandas numpy
```
## Estrutura do Projeto
- dataset.csv: Arquivo contendo os dados históricos de preços das ações.
- agente-q-learning-para-negociacao.ipynb: Código fonte do agente de Q-Learning.
  
## Executando o Código

Clone ou faça o download do repositório.

Certifique-se de ter os pré-requisitos instalados.

Execute o script agente-q-learning-para-negociacao.ipynb:
```bash
agente-q-learning-para-negociacao jupiter notebook
```
## Configurações e Hiperparâmetros
- num_episodios: Número de episódios para treinamento.
- alfa: Taxa de aprendizado do Q-Learning.
- gama: Fator de desconto para recompensas futuras.
- epsilon: Taxa de exploração para a política epsilon-greedy.

## Resultados

Após intensivo treinamento, o robô de negociação apresentou resultados promissores ao realizar experimentos de compra e venda de ações na bolsa de valores. O modelo foi testado em dados não vistos para avaliar seu desempenho em condições do mundo real, e o lucro final é exibido.

## Conclusão

Os resultados obtidos reforçam a eficácia do robô de negociação na bolsa de valores, proporcionando uma ferramenta valiosa para tomadas de decisões financeiras automatizadas.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) ou enviar pull requests com melhorias.

[![PyPi license](https://badgen.net/pypi/license/pip/)](https://pypi.org/project/pip/)
