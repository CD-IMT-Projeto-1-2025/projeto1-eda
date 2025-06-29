# Projeto 1 — Como as desigualdades de gênero impactam mulheres no mercado de trabalho?

![image](https://github.com/user-attachments/assets/2d9d67d1-5e8e-402c-b07d-b103621b71c2)

Este projeto realiza uma **Análise Exploratória de Dados (EDA)** sobre a **presença das mulheres na força de trabalho global**, com foco em indicadores como **nível de escolaridade**, **região geográfica** e **taxa de desemprego**, ao longo dos últimos anos.

Os dados foram obtidos do [**Gender Data Portal – World Bank Group**](https://genderdata.worldbank.org/), visando evidenciar **padrões de desigualdade de gênero** e seus possíveis determinantes **educacionais** e **econômicos**.

---

## Objetivos

- Analisar a participação feminina na força de trabalho com recortes por região e escolaridade.  
- Investigar a taxa de desemprego entre mulheres, segmentada por nível educacional.  
- Observar variações regionais e tendências temporais nesses indicadores.  
- Identificar correlações entre fatores socioeconômicos e a inserção formal da mulher no mercado de trabalho.

---

## Fontes de Dados

Os dados foram extraídos diretamente da **API pública** do [**World Bank Group**](https://data.worldbank.org/indicator).

### Séries utilizadas:

- `Labor force participation rate, female (% of female population ages 15+)`
- `Unemployment rate, female (% of female labor force)`
- `Women in parliament (% of total seats)`  
- `Women in ministerial positions (% of total ministers)`  
- `Women in managerial positions (% of total management)`  
- `Share of graduates who are female by field of education`

### Bases de dados e descrição:

- **`parliament_pos`**: Dados percentuais da participação de mulheres em cargos nos parlamentos e congressos do governo. Distribuídos por país, região geográfica e nível de renda.

- **`ministry_pos`**: Dados percentuais de participação de mulheres nos ministérios do governo. Distribuídos por país, região geográfica e nível de renda.

- **`management_pos`**: Dados percentuais de participação de mulheres em cargos de gerência (níveis intermediário e sênior). Distribuídos por país e região geográfica.

- **`graduates`**: Dados percentuais da formação de mulheres em diversos cursos superiores. Distribuídos por país, região geográfica e nível de renda.

### Variáveis desagregadas por:
- Gênero  
- Nível educacional: **Primário**, **Secundário** e **Terciário**  
- Região geográfica (segundo classificação do Banco Mundial)  
- Faixa de renda nacional: **média-baixa**, **média-alta** e **alta renda**

---

## Tecnologias Utilizadas

Análise conduzida em **Python 3.11+** no ambiente do **Google Colab**.

Principais bibliotecas:

| Biblioteca | Função |
|------------|--------|
| `pandas`   | Manipulação e transformação de dados |
| `plotly`   | Visualizações interativas e responsivas |
| `numpy`    | Estatísticas e vetorização de operações |

---

## Metodologia

1. Limpeza e padronização dos `DataFrames`  
2. Agrupamentos estatísticos por categoria (região, escolaridade, renda)  
3. Geração de visualizações interativas (com `plotly`)  
4. Observações descritivas baseadas em **tendências**, **dispersões** e **medianas**

### Visualizações geradas:
- Séries temporais (2010–2022) da participação e desemprego feminino  
- Gráficos de barras comparativos entre escolaridade, renda e participação no mercado  
- Boxplots regionais com variabilidade por faixa de escolaridade

---

## Conclusões Principais

- Correlação positiva entre nível educacional e participação feminina no mercado de trabalho.  
- Regiões desenvolvidas (como **Europa** e **América do Norte**) têm maior participação de mulheres com ensino superior.  
- Países de baixa renda apresentam menor escolarização e maior desigualdade no acesso ao trabalho formal.  
- A educação superior se mostra um vetor de inclusão produtiva, com impacto na redução das disparidades de gênero.

---

## Reprodutibilidade

- O notebook principal pode ser executado no [Google Colab](https://colab.research.google.com/)  
- Dados são abertos e públicos  
- Chamadas à API do World Bank não requerem autenticação

---

## Licença

Distribuído sob a [**MIT License**](LICENSE).  
Você pode usar, modificar e compartilhar este projeto livremente com os devidos créditos.
