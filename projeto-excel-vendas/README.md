# Projeto Excel - Análise de Vendas



## Objetivo

Realizar análise de dados de vendas utilizando Excel, com foco em estatística descritiva, e visualização de dados e comunicação de insights, buscando simular um cenário de análise para tomada de decisão.







## Dataset

Base de vendas fictícia (Superstore) obtida no Kaggle.







## Ferramentas

Excel (Tabelas, tabelas dinâmicas, gráficos, gráficos dinâmicos, estatística descritiva)







## Estrutura do Projeto
```
projeto-excel-vendas/

│
├── superstore.xlsx
│   ├── Banco\_de\_Dados
│   ├── Analise\_Descritiva
│   ├── Analise\_Pivot
│   └── Relatorio\_Final
│
└── README.md 
```


### O arquivo xlsx contém as planilhas

* Banco\_de\_Dados
  Contém o banco de dados bruto
* Análise\_Descritiva
  Contém os dados obtidos na primeira análise
* Análise\_Pivot
  Fica armazenadas as tabelas dinâmicas
* Relatório\_Final
  Gráficos para a análise de dados e busca de insights







## Metodologia



### Preparação de dados

* Transformados csv em xlsx
* Separações em colunas por Texto para Colunas
* Padronização de tipos de dados



### Análise Descritiva

Para compreender o comportamento central, dispersão e variabilidade das vendas, foram calculadas as seguintes medidas:

* Média
* Mediana
* Desvio padrão
* Mínimo
* Máximo



### Visualizações e Análises

#### Gráfico 1 - Evolução Mensal das Vendas por ano

Tipo: Gráfico de linhas (dinâmico)
Descrição: Mostra a evolução das vendas mensais, com uma linha para cada ano. Permite identificar padrões e variações entre períodos.



#### Gráfico 2 - Valor total de Vendas por Categoria

Tipo: Gráfico de barras (dinâmico)
Descrição: Compara o volume total de vendas entre as diferentes categorias de produtos. Evidencia diferenças relevantes de desempenho entre as categorias.



#### Gráfico 3 - Ranking Produtos Por Valor de Vendas

Tipo: Gráfico de barras (dinâmico)
Descrição: Mostra os 5 produtos com maior volume de vendas. Destaca as principais concentrações de faturamento por produto.



#### Gráfico 4 - Distribuição de número de pedidos por faixa de valor

Tipo: Histograma
Descrição: Apresenta como os pedidos se distribuem ao longo de faixas de valor de venda. Mostra que a maior parte dos pedidos ocorre em valores mais baixos, com fortíssima assimetria.



#### Gráfico 5 - Distribuição de Vendas por Categoria

Tipo: Boxplot
Descrição: Compara a distribuição de vendas por categoria. Analisa mediana, dispersão e presença de valores extremos.
Para mais legibilidade, valores extremamente discrepantes foram omitidos da visualização.



#### Gráfico 6 - Participação percentual  das Vendas por Categoria

Tipo: Gráfico de barras (dinâmico)
Descrição: Apresenta a participação percentual de cada categoria no total de vendas. KPI de concentração de faturamento



### Segmentação de dados

As visualizações dinâmicas permitem ser segmentadas por:

* Segmento de cliente;
* Região;
* Categoria;
  Isto permite análise em diferentes recortes.



### Observações pertinentes

Algumas visualizações usam tabelas dinâmicas e respondem segmentações aplicadas. Outras (como distribuições e relações estatísticas) são baseadas em dados completos para preservar a granularidade e interpretação estatística.







## Principais Insights

* Vendas apresentam relevantes variações ao longo dos meses, com diferenças anuais. Sendo seus principais picos em Setembro e Novembro;
* Diferenças significativas no valor das vendas por categoria;
* Os principais produtos que concentram grande parte das vendas;
* Uma pequena parcela dos produtos concentram a maior parte das vendas;
* A maior parte dos pedidos ocorre em faixas de menor valor;
* As categorias diferem no volume de vendas, na variabilidade e na dispersão dos valores.


