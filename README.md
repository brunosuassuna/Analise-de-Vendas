# 🚀 **Vendas Analytics com PySpark | Pipeline Completo de Dados**

![PySpark](https://img.shields.io/badge/PySpark-v3.5+-orange)
![Databricks](https://img.shields.io/badge/Databricks-Runtime-red)
![License](https://img.shields.io/badge/license-MIT-blue)

Este projeto apresenta um pipeline completo de **geração**, **processamento** e **visualização** de dados de vendas sintéticos utilizando **PySpark**, **Pandas** e **Plotly**. O objetivo é demonstrar a aplicação de técnicas de **engenharia de dados** e análise de **métricas de negócio** em um cenário simulado, com foco em desempenho, clareza e design profissional.

## 📁 **Estrutura do Projeto**
```bash
├── 📄 README.md                # Documentação principal
├── 📂 notebooks/              # Notebooks Jupyter
│   └── 📄 vendas_dashboard.ipynb     # Notebook principal de análise
├── 📂 src/                    # Código-fonte do projeto
│   ├── 📄 data_processing.py         # Funções de ETL
│   ├── 📄 visualization.py           # Código de visualizações
│   └── 📄 utils.py                   # Funções auxiliares
├── 📂 data/                   # Diretório de dados
│   ├── 📂 raw/                       # Dados brutos
│   └── 📂 processed/                # Dados tratados
└── 📂 config/                 # Configurações do projeto
    └── 📄 settings.json             # Parâmetros e caminhos configuráveis
```


## 🚀 Tecnologias Utilizadas

- **PySpark:** Para processamento distribuído de dados.

- **Pandas:** Para manipulação de DataFrames e transformação em gráficos.

- **NumPy:** Geração de dados e cálculos estatísticos.

- **Plotly:** Visualizações interativas e profissionais.

- **Google Colab / Jupyter / Databricks:** Ambiente de execução (recomendado).

## 🧪 Funcionalidades

**✅ Geração de Dados Sintéticos**

- Simulação de vendas com base em padrões sazonais e variações reais do mercado.
- Dados consistentes para todos os meses de um ano.

**✅ Processamento de Dados com PySpark**
### **Cálculo de métricas como:**

- Total de vendas (unidades)
- Receita total
- Ticket médio
- Valor médio por item
- Receita por cliente
- Contagem de transações

**✅ Visualização Interativa com Plotly**
- **Gráfico de barras:** Evolução mensal das vendas.

- **Heatmap:** Padrão sazonal ao longo do ano.

- **Gráfico de dispersão:** Correlação entre receita total e ticket médio.

- **Matriz de correlação:** Análise estatística entre as variáveis de negócio.

## **📊 Exemplos de Insights**
- Aumento significativo nas vendas nos meses de novembro e dezembro, simulando sazonalidade de fim de ano.
- Correlação positiva entre volume de vendas e número de transações.
- Análise clara de comportamento mensal e sazonal, com suporte visual intuitivo.

## 🧠 Conclusão
Este projeto demonstra como aplicar técnicas de engenharia de dados, geração de dados sintéticos e visualização interativa para obter insights de negócio. Ele serve como base para aplicações mais robustas com dados reais, podendo ser expandido com análise preditiva, integração com APIs ou ferramentas de BI.

## 📌 Como Executar
**Clone este repositório:**
```bash
git clone https://github.com/brunosuassuna/Analise-de-Vendas.git
```

- Execute em ambiente Jupyter, Google Colab ou Databricks com PySpark configurado.

- Instale as bibliotecas necessárias (se não estiverem instaladas):

- pip install pyspark pandas numpy plotly

  ## ✉️ Contato
- **Email:** brunosuassuna.dev@gmail.com
- **LinkedIn:** www.linkedin.com/in/brunosuassuna


