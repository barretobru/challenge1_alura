# Desafio Allure Store – Análise de Dados com Python

Este projeto é parte do desafio proposto pela plataforma Alura para o curso de Ciência de Dados. O objetivo é auxiliar o Sr. João, dono de uma rede de quatro lojas, a decidir qual loja vender com base em dados reais de desempenho.

## Objetivo

Analisar os dados de quatro lojas da rede Alura Store e recomendar, com base em evidências, qual loja apresenta o pior desempenho e deve ser vendida.

## Dados Utilizados

Os dados estão disponíveis em arquivos `.csv` e contêm informações sobre:

- Produtos vendidos
- Categorias
- Preços e fretes
- Avaliações dos clientes
- Tipos de pagamento
- Localização e data da compra

## Métricas Analisadas

- Faturamento total  
- Categoria mais popular
- Média de avaliação dos clientes
- Produto mais vendido e produto menos vendido
- Custo médio do frete

## Tecnologias Utilizadas

- Python 3
- Google Colab
- Pandas
- Matplotlib
- Markdown (para o relatório)

## Resultado

Após a análise, foi possível observar que:

- A Loja 4 apresentou o menor faturamento, a menor média de avaliação (entre as lojas com menor desempenho) e menor destaque em produtos vendidos, mesmo com o menor custo médio de frete.

Recomendação final: Vender a Loja 4.

## Estrutura do Projeto

.
├── Base de Dados/  
│   ├── loja1.csv  
│   ├── loja2.csv  
│   ├── loja3.csv  
│   └── loja4.csv  
├── analise_allure_store.ipynb  
├── df_resumo.csv (opcional)  
└── README.md  

## Como Executar

1. Abra o arquivo `analise_allure_store.ipynb` no Google Colab
2. Execute todas as células (Menu > Ambiente de execução > Executar tudo)
3. Analise os gráficos e o relatório no final do notebook

## Desenvolvido por

Bruna Barreto  
Desafio Allure Store – Alura Data Science  
2025
