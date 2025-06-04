# projeto1-eda

![image](https://github.com/user-attachments/assets/2d9d67d1-5e8e-402c-b07d-b103621b71c2)

# Projeto 1 - Como as desigualdades de gênero impactam mulheres no mercado de trabalho?

Este projeto realiza uma Análise Exploratória de Dados (EDA) sobre a presença das mulheres na força de trabalho global, com foco em indicadores como nível de escolaridade, região geográfica e taxa de desemprego, ao longo dos últimos anos. Os dados são oriundos do Gender Data Portal – World Bank Group, e visam evidenciar padrões de desigualdade de gênero e seus possíveis determinantes educacionais e econômicos.

⸻

## Objetivos
	•	Analisar a participação feminina na força de trabalho com recortes por região e escolaridade.
	•	Investigar a taxa de desemprego entre mulheres, segmentada por nível educacional.
	•	Observar variações regionais e tendências temporais nesses indicadores.
	•	Identificar correlações entre fatores socioeconômicos e a inserção formal da mulher no mercado de trabalho.

⸻

## Fontes de Dados

Os dados foram extraídos diretamente das APIs públicas do Gender Data Portal (World Bank Group). Foram utilizadas as seguintes séries históricas:
	•	Labor force participation rate, female (% of female population ages 15+)
	•	Unemployment rate, female (% of female labor force)

As variáveis estão desagregadas por:
	•	Gênero
	•	Nível educacional: Primário, Secundário e Terciário
	•	Região geográfica (definida pelo Banco Mundial)
	•	Faixa de renda nacional (baixa, média e alta renda)

⸻

## Tecnologias Utilizadas

A análise foi conduzida em Python 3.11+, com execução no ambiente do Google Colab.

Principais bibliotecas utilizadas:
	•	pandas – manipulação e transformação de dados
	•	plotly – criação de visualizações interativas
	•	requests – integração com a API do World Bank
	•	numpy – apoio em estatísticas e operações vetorizadas

⸻

## Metodologia e Visualizações

A análise envolveu as seguintes etapas:
	1.	Coleta automatizada de dados via API REST
	2.	Limpeza e padronização dos DataFrames
	3.	Agrupamentos estatísticos por categoria (região, escolaridade, renda)
	4.	Visualizações interativas com foco em comparação temporal e regional
	5.	Observações descritivas baseadas em tendências, dispersões e medianas

Visualizações geradas:
	•	Séries temporais (2010 a 2022) da participação e desemprego feminino por nível educacional e região
	•	Gráficos de barras comparativos entre categorias de escolaridade, renda e participação no mercado
	•	Boxplots regionais com distribuição e variabilidade por faixa de escolaridade

⸻

## Conclusões Principais
	•	Existe uma correlação positiva entre nível educacional e participação feminina no mercado de trabalho.
	•	Regiões mais desenvolvidas (como Europa e América do Norte) apresentam maior taxa de participação de mulheres com ensino superior.
	•	Países de baixa renda mostram menor escolarização feminina e maior desigualdade de acesso ao trabalho formal.
	•	A educação superior atua como vetor de inclusão produtiva e pode reduzir disparidades regionais de gênero.

⸻

## Reprodutibilidade

O notebook principal pode ser executado diretamente no Google Colab.
Todos os dados são públicos, e as chamadas à API do World Bank não requerem autenticação.

⸻

Licença

Este projeto está licenciado sob a MIT License.
Você pode usá-lo, modificá-lo e distribuí-lo livremente com os devidos créditos.

