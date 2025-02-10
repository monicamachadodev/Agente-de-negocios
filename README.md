<img src="https://github.com/monicamachadodev/Agente-de-negocios/blob/main/robo-trading.png">

# Agente de Negociação com Q-Learning

Este repositório contém um projeto de implementação de um agente de negociação utilizando o algoritmo de Q-Learning, uma técnica de aprendizado por reforço.
> O **objetivo** é criar um agente capaz de aprender a negociar em um ambiente simulado, tomando decisões que maximizem sua recompensa ao longo do tempo.

## Descrição do Projeto

O projeto consiste em um notebook Jupyter `agente-q-learning-para-negociacao.ipynb` que implementa um agente de negociação utilizando Q-Learning. O ambiente de negociação é simulado, e o agente aprende a tomar decisões de compra, venda ou manutenção de posições com base em recompensas e penalidades.

### Estrutura do Código

- **Ambiente de Negociação**: Simula um mercado financeiro onde o agente pode realizar operações de compra e venda.
- **Agente de Q-Learning**: Implementa o algoritmo de Q-Learning para aprender a melhor política de negociação.
- **Treinamento**: O agente é treinado em múltiplos episódios, onde ele interage com o ambiente e atualiza sua tabela Q.
- **Avaliação**: Após o treinamento, o desempenho do agente é avaliado em um conjunto de testes.

## Estrutura do Projeto
- dataset.csv: Arquivo contendo os dados históricos de preços das ações.
- agente-q-learning-para-negociacao.ipynb: Código fonte do agente de Q-Learning.
  
## Configurações e Hiperparâmetros
- num_episodios: Número de episódios para treinamento.
- alfa: Taxa de aprendizado do Q-Learning.
- gama: Fator de desconto para recompensas futuras.
- epsilon: Taxa de exploração para a política epsilon-greedy.

## Resultados

Após intensivo treinamento, o robô de negociação apresentou resultados promissores ao realizar experimentos de compra e venda de ações na bolsa de valores. O modelo foi testado em dados não vistos para avaliar seu desempenho em condições do mundo real, e o lucro final é exibido.

## Conclusão

Os resultados obtidos reforçam a eficácia do robô de negociação na bolsa de valores, proporcionando uma ferramenta valiosa para tomadas de decisões financeiras automatizadas.

## Requisitos

Para executar o notebook, você precisará das seguintes bibliotecas Python:

- `numpy`
- `pandas`
- `matplotlib`
- `gym` (para criar o ambiente de negociação)

Você pode instalar as dependências usando o seguinte comando:

```bash
pip install numpy pandas matplotlib gym
```

## Como Executar

1. Clone o repositório:

```bash
Copy
git clone https://github.com/monicamachadodev/Agente-de-negocios.git
```
2. Navegue até o diretório do projeto:

```bash
Copy
cd Agente-de-negocios
```
3. Abra o notebook Jupyter:

```bash
Copy
jupyter notebook agente-q-learning-para-negociacao.ipynb
```
4. Execute as células do notebook para treinar e avaliar o agente.

## Contribuições

Contribuições são bem-vindas! Se você tiver sugestões de melhorias ou encontrar algum problema, sinta-se à vontade para abrir uma issue ou enviar um pull request.

