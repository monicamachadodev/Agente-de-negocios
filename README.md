# Agente de Q-Learning para Negociação de Ações

Este projeto consiste na implementação de um agente de Q-Learning para a tomada de decisões em um ambiente simulado de negociação de ações. O agente aprende a realizar ações (comprar, vender ou manter) com base nos preços de fechamento históricos das ações da Apple (AAPL).

## Problema de Negócio

Construir um robô (modelo em Linguagem Python) baseado em Inteligência Artificial que aprenda a operar na bolsa de valores a partir de experimentos de compra e venda de ações. Dado um saldo inicial o modelo deve apresentar o resultado (lucro) a ser obtido depois de ações de compra e venda.

## Objetivo

O objetivo principal deste projeto é explorar e entender a aplicação do algoritmo de Q-Learning na área de finanças, especificamente na negociação de ações. O agente é treinado para tomar decisões de compra e venda com base nas mudanças nos preços das ações ao longo do tempo.

## Pré-requisitos

- Python 3.11
- Bibliotecas: `plotly`, `pandas`, `numpy`

```bash
pip install plotly pandas numpy
```
## Estrutura do Projeto
dataset.csv: Arquivo contendo os dados históricos de preços das ações.
agente_qlearning.py: Código-fonte do agente de Q-Learning.
LICENSE: Arquivo de licença do projeto.
README.md: Este arquivo.

## Executando o Código

Clone ou faça o download do repositório.

Certifique-se de ter os pré-requisitos instalados.

Execute o script agente_qlearning.py:
```bash
python agente_qlearning.py
```
## Configurações e Hiperparâmetros
num_episodios: Número de episódios para treinamento.
alfa: Taxa de aprendizado do Q-Learning.
gama: Fator de desconto para recompensas futuras.
epsilon: Taxa de exploração para a política epsilon-greedy.
Ajuste esses hiperparâmetros conforme necessário para otimizar o desempenho do agente.

## Resultados

Após intensivo treinamento, o robô de negociação apresentou resultados promissores ao realizar experimentos de compra e venda de ações na bolsa de valores. O modelo foi testado em dados não vistos para avaliar seu desempenho em condições do mundo real, e o lucro final é exibido.

## Conclusão

Os resultados obtidos reforçam a eficácia do robô de negociação na bolsa de valores, proporcionando uma ferramenta valiosa para tomadas de decisões financeiras automatizadas.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) ou enviar pull requests com melhorias.

## Licença
Este projeto é distribuído sob a Licença MIT.
