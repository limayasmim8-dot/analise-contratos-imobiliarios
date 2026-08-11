# Análise de Contratos Imobiliários

Projeto introdutório de análise exploratória de contratos imobiliários utilizando **Python**, **Pandas** e **Matplotlib**.

## Objetivo
Explorar um conjunto de dados de contratos imobiliários para identificar padrões de preço, distribuição por cidade, métricas de área e características gerais dos imóveis.

## Estrutura do projeto

```bash
analise-contratos-imobiliarios/
├── data/
│   └── contratos_imobiliarios.csv
├── images/
│   └── graficos/
├── notebooks/
│   └── analise_contratos.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

## Tecnologias
- Python 3.11+
- Pandas
- Matplotlib
- Jupyter Notebook

## Como executar

1. Clone o repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd analise-contratos-imobiliarios
   ```

2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Linux/Mac
   .venv\Scripts\activate     # Windows
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Abra o notebook:
   ```bash
   jupyter notebook
   ```

## Análises sugeridas
- Estatísticas descritivas dos contratos
- Distribuição dos valores de venda
- Preço médio por cidade
- Relação entre área do imóvel e valor de venda
- Comparativo por tipo de imóvel

## Observação
Este pacote foi preparado como um **projeto inicial publicável no GitHub**. Se você tiver a base real dos contratos, basta substituir o arquivo `data/contratos_imobiliarios.csv` e atualizar os gráficos/notebook conforme necessário.
