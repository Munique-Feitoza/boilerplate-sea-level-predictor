# Sea Level Predictor

Este projeto analisa o aumento do nível do mar global desde 1880, utilizando as bibliotecas **Pandas**, **Matplotlib** e **SciPy** em Python. Ele faz parte do curso de **Análise de Dados com Python** da [freeCodeCamp](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/sea-level-predictor).

## 📊 Objetivo

Analisar o aumento do nível do mar e prever sua evolução até 2050, com base nos dados históricos. O objetivo do projeto é:

- Utilizar dados de aumento do nível do mar desde 1880.
- Criar um gráfico de dispersão com a evolução do nível do mar.
- Traçar uma linha de tendência para prever o aumento até 2050.
- Analisar o impacto de diferentes períodos (todos os dados históricos e dados a partir de 2000) nas previsões.

A visualização é feita através de um gráfico de dispersão e duas linhas de tendência para prever o aumento do nível do mar:

- **Gráfico de dispersão (scatter plot)** mostrando o nível do mar ao longo dos anos.
- **Linhas de tendência (line of best fit)** para prever a evolução até 2050 com base em diferentes períodos de dados.

## 📁 Estrutura do Projeto
```
📦 sea-level-predictor/
├── sea_level_predictor.py  # Arquivo principal com as funções de cálculo e visualização  
├── main.py                 # Script de teste  
├── test_module.py          # Testes unitários  
├── epa-sea-level.csv       # Conjunto de dados históricos do nível do mar  
└── README.md               # Este arquivo  
```

## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone <url-do-seu-repositório>
cd sea-level-predictor
```

2. Instale as dependências (se necessário):

```bash
pip install pandas matplotlib scipy
```

3. Execute o script de teste:

```bash
python main.py
```

## ✅ Requisitos
- Python 3.x
- pandas
- matplotlib
- scipy

## 🧪 Testes
Os testes são executados automaticamente ao rodar o main.py, que importa as funções de test_module.py.

## 📚 Fonte dos Dados
Os dados foram fornecidos pela US Environmental Protection Agency e representam as mudanças no nível do mar global de 1880 até 2014, com dados de CSIRO (2015) e NOAA (2015).

Projeto baseado no curso gratuito da [FreeCodeCamp](https://www.freecodecamp.org/portuguese/learn/data-analysis-with-python/data-analysis-with-python-projects/sea-level-predictor).
