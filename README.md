# Análise Exploratória de Materiais Agrícolas
**Descrição do Projeto:**

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) sobre preços de matérias-primas agrícolas ao longo do tempo. A partir de um conjunto de dados históricos, são investigadas variações de preços, correlações entre materiais e tendências temporais, buscando identificar padrões relevantes no mercado agrícola.

**Conjunto de Dados:**

O dataset utilizado é o agricultural_raw_material.csv, contendo informações mensais sobre preços e variações percentuais de diferentes matérias-primas, como:

- Algodão
- Borracha
- Lã (fina e grossa)
- Madeira (toras e serrada)
- Polpa de madeira
- Copra
- Couro
- Compensado (plywood)

Os dados passam por um processo de limpeza e pré-processamento, incluindo:

- Remoção de símbolos (%, ,, -)
- Tratamento de valores ausentes
- Conversão de tipos de dados
- Padronização da coluna de datas

**Stack utilizada:**

- Python
- Pandas 
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

**Etapas da Análise:**

- Carregamento e exploração inicial dos dados
- Limpeza e tratamento do dataset
- Análise de correlação entre preços das matérias-primas
- Análise da variação percentual dos preços
- Visualização da evolução dos preços ao longo dos anos
- Identificação de matérias-primas de alta e baixa gama de preços

**Principais Análises Realizadas:**

- Mapas de calor para correlação entre preços e variações percentuais
- Histogramas das variações de preços
- Séries temporais para acompanhar a evolução dos valores
- Comparação entre diferentes matérias-primas
- Identificação de materiais com maior e menor volatilidade

**Conclusões:**

- Foi possível identificar matérias-primas de alta e baixa gama com base nos preços.
- Observou-se alta e baixa variação percentual entre os diferentes materiais.
- A análise temporal permitiu visualizar tendências e oscilações de preços ao longo dos anos.
- Algumas matérias-primas apresentam correlação significativa, indicando comportamentos semelhantes no mercado.
