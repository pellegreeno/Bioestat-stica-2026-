# Bioestatística – Tarefa 13

## Integrantes
- Ana Carolina Sartori – 17081013
- Cris Serpa Guimarães – 16860671
- Julia Sztejnhaus Pamio – 17072621
- Maria Eduarda Pellegrino – 17074112

---

## Fontes consultadas

### Base de dados
**Iris Dataset – UCI Machine Learning Repository**  
A base utilizada contém medidas de comprimento e largura das sépalas e pétalas de flores do gênero *Iris*, além da identificação da espécie.

- **Link:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/53/iris)
- **Data de acesso:** 05/10/2026

### Referências bibliográficas
- BUSSAB, W. O.; MORETTIN, P. A. **Estatística Básica**. Saraiva Educação, 2017.
- MORETTIN, P. A. **Estatística e Ciências do Comportamento**. Editora Edgard Blücher, 2010.
- TRIOLA, M. F. **Introdução à Estatística**. LTC, 2018.
- ZAR, J. H. **Biostatistical Analysis**. Pearson, 2010.

---

## Como Reproduzir a Análise

A análise foi realizada em **Python**, utilizando o **Google Colab**.

### 1. Acessar o código
Abra o notebook disponibilizado neste repositório no Google Colab.

### 2. Importar as bibliotecas
As bibliotecas utilizadas são:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`

*As bibliotecas podem ser importadas diretamente no Google Colab, sem necessidade de instalação adicional.*

### 3. Carregar os dados
O dataset Iris é carregado diretamente da base da UCI por meio da URL:
> `https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data`

O código organiza as cinco colunas da base como:
- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`
- `class`

### 4. Executar o notebook
Execute as células do notebook na ordem em que aparecem. A análise inclui:
- Exploração inicial e estatísticas descritivas dos dados;
- Teste F de Fisher para comparação das variâncias entre *Iris-versicolor* e *Iris-virginica*;
- Teste t de Student para comparação das médias do comprimento das pétalas;
- Cálculos de probabilidade utilizando a distribuição Normal;
- Teste de normalidade utilizando a distribuição Qui-quadrado;
- Estudo e representação gráfica das distribuições Normal, t de Student, Qui-quadrado e F de Fisher;
- Cálculos de probabilidades acumuladas, intervalos, probabilidades de cauda e percentis para as quatro distribuições.

### 5. Reprodução dos resultados
Após executar todas as células, os resultados estatísticos, probabilidades e gráficos serão produzidos diretamente no notebook. 

> **Nota:** Não é necessário realizar download ou tratamento manual do dataset, pois os dados são carregados diretamente da fonte utilizada na análise.
