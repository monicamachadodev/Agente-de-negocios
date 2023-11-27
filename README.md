# Agente de Q-Learning para Negociação de Ações

Este projeto consiste na implementação de um agente de Q-Learning para a tomada de decisões em um ambiente simulado de negociação de ações. O agente aprende a realizar ações (comprar, vender ou manter) com base nos preços de fechamento históricos das ações da Apple (AAPL).

## Objetivo

O objetivo principal deste projeto é explorar e entender a aplicação do algoritmo de Q-Learning na área de finanças, especificamente na negociação de ações. O agente é treinado para tomar decisões de compra e venda com base nas mudanças nos preços das ações ao longo do tempo.

## Pré-requisitos

- Python 3.11
- Bibliotecas: `plotly`, `pandas`, `numpy`

```bash
pip install plotly pandas numpy
```
# Estrutura do Projeto
dataset.csv: Arquivo contendo os dados históricos de preços das ações.
agente_qlearning.py: Código-fonte do agente de Q-Learning.
LICENSE: Arquivo de licença do projeto.
README.md: Este arquivo.

# Executando o Código

Clone ou faça o download do repositório.

Certifique-se de ter os pré-requisitos instalados.

Execute o script agente_qlearning.py:
```bash
python agente_qlearning.py
```
# Configurações e Hiperparâmetros
num_episodios: Número de episódios para treinamento.
alfa: Taxa de aprendizado do Q-Learning.
gama: Fator de desconto para recompensas futuras.
epsilon: Taxa de exploração para a política epsilon-greedy.
Ajuste esses hiperparâmetros conforme necessário para otimizar o desempenho do agente.

# Resultados
Após o treinamento, o agente é testado em dados não vistos, e o lucro final é exibido.

# Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) ou enviar pull requests com melhorias.

# Licença
Este projeto é distribuído sob a Licença MIT.
