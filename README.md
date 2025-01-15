# Predição de Preços de Apartamentos em São Paulo

Este repositório contém um projeto de análise e predição de preços de apartamentos na cidade de São Paulo, utilizando dados de 2019. O objetivo principal é explorar os dados, identificar padrões e criar um modelo preditivo capaz de estimar o preço de um apartamento com base em suas características.

## 👤 Autor
Pedro Gabriel Fonseca

## 📄 Descrição do Projeto
O projeto utiliza uma abordagem de aprendizado supervisionado para prever o preço de apartamentos com base em variáveis como localização, número de quartos, área útil, entre outras características.

## 🔧 Ferramentas Utilizadas
- **Python**  
- **Bibliotecas**:
  - `pandas`  
  - `plotly` (`plotly.express`, `plotly.graph_objects`)  
  - `matplotlib`  
  - `seaborn`  
  - `numpy`  

## 📊 Etapas do Projeto
1. **Coleta e Limpeza dos Dados**  
   - Os dados brutos foram carregados e limpos, removendo valores inconsistentes e outliers.
   
2. **Análise Exploratória de Dados (EDA)**  
   - Foram gerados gráficos interativos com `plotly` e visualizações detalhadas com `matplotlib` e `seaborn` para identificar padrões importantes nos dados.
   
3. **Predição**  
   - Um modelo de aprendizado de máquina foi treinado para prever os preços dos apartamentos com base nas variáveis analisadas.

## 🌍 Visualizações Geográficas
O projeto utiliza o **Plotly** com integração ao **Mapbox** para gerar visualizações geográficas interativas, exibindo a distribuição dos preços de apartamentos por bairros em São Paulo.

> **Nota:** É necessário configurar um token de acesso ao Mapbox para as visualizações geográficas funcionarem corretamente.

## 🚀 Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/sp-apartment-price-prediction.git
2. Navegue até o diretório do projeto:
    ```bash
    cd sp-apartment-price-prediction
3. Instale as dependências necessárias:
    ```bash
    pip install -r requirements.txt

📂 Estrutura do Repositório
    sp-apartment-price-prediction/
    │
    ├── data/                  # Contém os conjuntos de dados utilizados
    ├── analysis.ipynb         # Notebook com as análises realizadas
    ├── README.md              # Instruções e descrição do projeto
    ├── requirements.txt       # Dependências necessárias
    └── mapbox_token           # Arquivo contendo o token do Mapbox
