
![salesimg](https://github.com/manubava/Previs-o-de-Vendas-Rossmann/assets/134617068/50aec2eb-4a89-4fcb-90b6-96edd2944637)

# Previs-o-de-Vendas-Rossmann

Este projeto é uma implementação de um modelo preditivo para prever as vendas diárias das lojas da rede Rossmann. O modelo é baseado em dados históricos de vendas, informações sobre as lojas e características temporais.

## Descrição do Problema

A Rossmann, uma grande cadeia de drogarias na Europa, está interessada em prever as vendas diárias de suas lojas em até seis semanas com antecedência. Eles estão buscando uma solução que possa ajudar a tomar decisões informadas sobre estratégias de estoque, promoções e planejamento de pessoal.

## Conjunto de Dados

O conjunto de dados utilizado neste projeto contém informações históricas de vendas diárias de várias lojas da Rossmann, juntamente com dados adicionais sobre as lojas. O conjunto de dados é composto por duas tabelas principais: `train.csv` e `store.csv`.

- `train.csv`: Contém informações de vendas diárias por loja, juntamente com a data correspondente. Também inclui informações sobre feriados e promoções.
- `store.csv`: Contém informações detalhadas sobre cada loja, como tipo de loja, tamanho, competição, entre outros.

## Pré-processamento e Modelagem

O projeto envolve várias etapas, incluindo:

1. Análise exploratória dos dados para compreender a distribuição das vendas, identificar tendências e relações com outras variáveis.
2. Pré-processamento dos dados, incluindo tratamento de valores ausentes, codificação de variáveis categóricas e criação de novas variáveis relevantes.
3. Divisão dos dados em conjunto de treinamento e conjunto de teste.
4. Criação e treinamento do modelo preditivo. Neste projeto, utilizou-se um modelo de regressão XGBoost para realizar as previsões.
5. Avaliação do modelo usando métricas de desempenho, como o Erro Médio Absoluto (MAE) e o Erro Percentual Absoluto Médio (MAPE).
6. Implantação do modelo em um ambiente de produção, onde as previsões podem ser geradas em tempo real.

## Como Executar o Projeto

1. Certifique-se de ter todas as dependências instaladas. Você pode instalar as dependências listadas no arquivo `requirements.txt` usando o comando: `pip install -r requirements.txt`.
2. Baixe os conjuntos de dados `train.csv` e `store.csv` e coloque-os no diretório de dados.
3. Execute o notebook `rossmann_prediction.ipynb` passo a passo. Ele contém todo o código necessário para pré-processamento dos dados, treinamento do modelo e geração das previsões.
4. Após a execução, você obterá um modelo treinado e será capaz de gerar previsões para as vendas diárias de lojas futuras.

## Resultados e Avaliação

O modelo treinado foi avaliado utilizando métricas de desempenho, como MAE e MAPE. Os resultados obtidos demonstraram uma boa capacidade de previsão das vendas diárias das lojas da Rossmann.

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões de melhorias, correções de bugs ou novas funcionalidades, fique à vontade para enviar um pull request.

## Contato

Para qualquer dúvida ou sugestão, entre em contato:

- Nome: Emanuelle Bavaresco Teodoro
- E-mail: bavaemanuelle@gmail.com

Sinta-se à vontade para adicionar mais informações relevantes, como uma seção de requisitos do sistema, exemplos de uso, capturas de tela ou qualquer outra coisa que achar útil para o usuário do projeto Rossmann.
