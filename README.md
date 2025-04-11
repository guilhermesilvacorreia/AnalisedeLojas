# Lojas Análises

Este projeto realiza uma análise integrada dos dados de vendas de quatro lojas. São avaliados indicadores como faturamento, distribuição de categorias, avaliações de clientes, frequência dos produtos vendidos e custo do frete. Além disso, o projeto utiliza dados geográficos (latitude e longitude) para mapear a distribuição das vendas, permitindo identificar padrões regionais e insights estratégicos.

## Sumário

- [Recursos do Projeto](#recursos-do-projeto)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Como Executar](#como-executar)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Problemas Conhecidos e Soluções](#problemas-conhecidos-e-soluções)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Recursos do Projeto

- **Análise Financeira:** Cálculo do faturamento total das lojas.
- **Análise de Produtos:** Contagem e distribuição das categorias de produtos, identificação dos produtos mais e menos vendidos.
- **Avaliação dos Clientes:** Cálculo da média das avaliações de clientes por loja.
- **Logística:** Cálculo do custo médio do frete por loja.
- **Análise Geográfica:** Visualização da distribuição das vendas por meio de gráficos de dispersão e heatmaps (mapas de calor) usando dados de latitude e longitude.
- **Visualizações:** Geração de gráficos variados com Matplotlib, Seaborn e, opcionalmente, mapas interativos com Folium.

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado:

- [Python 3](https://www.python.org/downloads/)
- [Jupyter Notebook](https://jupyter.org/) ou [Google Colab](https://colab.research.google.com/)

As seguintes dependências em Python também são necessárias:

- pandas
- matplotlib
- seaborn
- folium (opcional, para criação de mapas interativos)

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/guilhermesilvacorreia/AnalisedeLojas.git
   cd loja-analytics
2. Instale as dependências (preferencialmente em um ambiente virtual):
   ```bash
      pip install pandas matplotlib seaborn folium
## Como Executar
Você pode executar o projeto de duas maneiras:

### Localmente (Jupyter Notebook)
1. Abra o terminal ou prompt de comando na pasta do projeto.
2. Execute:
   ```bash
     jupyter notebook
3. Abra o notebook principal (por exemplo, AluraStoreBr(1).ipynb) e execute as células na sequência.

### Google Colab
1. Faça upload do notebook (.ipynb) para o Google Colab.
2. Execute as células interativamente.


## Estrutura do Projeto

```bash 
    loja-analytics/
│
├── AluraStoreBr(1).ipynb        # Notebook principal com o código de análise e geração de gráficos
├── README.md                  # Este arquivo
 
 
 

 

   
    
   