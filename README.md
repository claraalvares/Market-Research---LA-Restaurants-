# Pesquisa de Mercado - Restaurantes na Cidade de Los Angeles

## Sobre o Projeto

Este projeto tem como objetivo analisar o mercado de restaurantes em Los Angeles (LA) para avaliar a viabilidade e a sustentabilidade de uma cafeteria inovadora com garçons robôs. O foco está em fornecer insights valiosos para atrair investidores, considerando o impacto inicial da novidade e a sustentabilidade a longo prazo.

## Objetivos

1. **Investigar as proporções de diferentes tipos de estabelecimentos em LA.**  
2. **Determinar o perfil típico de estabelecimentos de rede e não rede.**  
3. **Analisar a capacidade média de assentos por tipo de restaurante.**  
4. **Identificar tendências geográficas com base na distribuição de restaurantes pelas ruas de LA.**  
5. **Fornecer recomendações sobre o tipo ideal de restaurante e o número de assentos para a nova cafeteria.**

---

## Dados

- **Fonte**: `/datasets/rest_data_us_upd.csv`  
- **Composição**:
  - `object_name`: Nome do estabelecimento.  
  - `chain`: Indicador de rede (TRUE/FALSE).  
  - `object_type`: Tipo de estabelecimento.  
  - `address`: Endereço do estabelecimento.  
  - `number`: Número de assentos.

---

## Método

### Etapas de Trabalho

#### **Preparação dos Dados**
1. Carregar e inspecionar o dataset para identificar valores ausentes e duplicados.  
2. Ajustar tipos de dados e processar colunas conforme necessário.  

#### **Análise de Dados**
1. Explorar as proporções de tipos de estabelecimentos e redes.  
2. Identificar características comuns em redes de restaurantes.  
3. Calcular a capacidade média de assentos por tipo de restaurante.  
4. Mapear a distribuição de restaurantes em LA por ruas.  
5. Analisar tendências de número de assentos em ruas com alta densidade de restaurantes.  

#### **Conclusões e Recomendações**
1. Resumir os principais achados.  
2. Fornecer recomendações sobre o formato e a capacidade ideal para o novo restaurante.

---

## Ferramentas Utilizadas

- **Python 3.x**: Manipulação e análise de dados.  
- **Pandas**: Limpeza e análise de dados tabulares.  
- **NumPy**: Operações matemáticas.  
- **Matplotlib e Seaborn**: Visualização de dados.  
- **Jupyter Notebook**: Documentação interativa.

---

## Resultados Esperados

Os resultados desta análise servirão como base para a estratégia de lançamento e expansão da cafeteria com garçons robôs, auxiliando na atração de investidores e no planejamento da operação.

---

### Como Executar o Projeto

1. Clone o repositório;  
2. Navegue até o diretório do projeto;  
3. Abra o projeto no seu IDE favorito;  
4. Instale as dependências;  
5. Execute o script principal.

---

### Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---------------------


# Market Research - Los Angeles Restaurants

## About the Project

This project aims to analyze the restaurant market in Los Angeles (LA) to assess the feasibility and sustainability of an innovative café with robot waiters. The focus is on providing valuable insights to attract investors, considering the initial impact of the novelty and long-term sustainability.

## Objectives

1. **Investigate the proportions of different types of establishments in LA.**  
2. **Determine the typical profile of chain and non-chain establishments.**  
3. **Analyze the average seating capacity by type of restaurant.**  
4. **Identify geographical trends based on the distribution of restaurants across LA streets.**  
5. **Provide recommendations on the ideal type of restaurant and seating capacity for the new café.**

---

## Data

- **Source**: `/datasets/rest_data_us_upd.csv`  
- **Composition**:
  - `object_name`: Name of the establishment.  
  - `chain`: Chain indicator (TRUE/FALSE).  
  - `object_type`: Type of establishment.  
  - `address`: Address of the establishment.  
  - `number`: Number of seats.

---

## Method

### Workflow

#### **Data Preparation**
1. Load and inspect the dataset to identify missing and duplicate values.  
2. Adjust data types and process columns as needed.  

#### **Data Analysis**
1. Explore the proportions of establishment types and chains.  
2. Identify common characteristics of chain restaurants.  
3. Calculate the average seating capacity by type of restaurant.  
4. Map the distribution of restaurants in LA by streets.  
5. Analyze seating trends on streets with a high density of restaurants.  

#### **Conclusions and Recommendations**
1. Summarize key findings.  
2. Provide recommendations on the ideal format and seating capacity for the new café.

---

## Tools Used

- **Python 3.x**: Data manipulation and analysis.  
- **Pandas**: Cleaning and analysis of tabular data.  
- **NumPy**: Mathematical operations.  
- **Matplotlib and Seaborn**: Data visualization.  
- **Jupyter Notebook**: Interactive documentation.

---

## Expected Results

The results of this analysis will serve as a basis for the strategy to launch and expand the café with robot waiters, helping attract investors and plan operations effectively.

---

### How to Run the Project

1. Clone the repository;  
2. Navigate to the project directory;  
3. Open the project in your favorite IDE;  
4. Install dependencies;  
5. Run the main script.

---

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.
