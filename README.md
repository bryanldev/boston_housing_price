# Projeto 2 do Nanodegree Fundamentos de AI & Machine Learning - Udacity

## Visão geral do projeto
**Estimando Preços dos Imóveis de Boston**: neste projeto, você aplicará conceitos básicos de Machine Learning em dados coletados de preços de casas em Boston, em Massachusetts, para prever o preço de venda de uma casa nova. Primeiro, você irá explorar os dados para obter atributos importantes e estatísticas descritivas sobre o conjunto de dados. Depois, dividirá adequadamente os dados entre dois subconjuntos, o de testes e o de treinamento, e determinará uma métrica adequada para esse problema. Você, então, analisará o desempenho de um algoritmo de aprendizagem com parâmetros variados e tamanho do conjunto de treinamento. Isso permitirá que você escolha o modelo ótimo que melhor generaliza os dados desconhecidos. Por último, você testará o modelo ótimo em uma nova amostra e comparará os preços de venda previstos com as suas estatísticas.

## Descrição
O mercado imobiliário de Boston é altamente competitivo e você quer ser o melhor corretor de imóveis da região. Para competir com seus colegas, você decidiu elencar alguns conceitos básicos de Machine Learning para ajudar você e seu cliente a acharem o melhor preço de venda para a casa dele. Com sorte, você se deparou com o conjunto de dados de habitação de Boston, que contém dados agregados de várias características para casas das comunidades da Grande Boston, incluindo o valor médio das casas para cada uma das regiões. Sua tarefa é construir um modelo ótimo baseado na análise das estatísticas com as ferramentas disponíveis. Esse modelo será, então, usado para estimar o melhor preço de venda para a casa de seus clientes.

### Software e bibliotecas
Este projeto usará o seguinte software e bibliotecas de Python:

- Python 3
- NumPy
- Pandas
- Scikit-learn >= 0.20
- Matplotlib
- Seaborn
- Jupyter Notebook

**Nota:** Este notebook é uma versão atualizada do programa original da Udacity, feito por mim. Atente-se para as seguintes mudanças:
- scikit-learn 0.20.2
- Uso da biblioteca Seaborn
- O módulo *visuals.py* sofreu algumas alterações para se adequar às mudanças da nova versão do scikit-learn.

### Dados
O conjunto de dados do mercado imobiliário de Boston consiste em 489 pontos de dados, sendo que cada ponto possui 3 atributos. Este conjunto de dados é uma versão modificada do conjunto de dados do mercado imobiliário de Boston encontrado no [Repositório de machine learning da UCI](https://archive.ics.uci.edu/ml/index.php).

#### Atributos
1. `RM`: número médio de cômodos por casa
2. `LSTAT`: porcentagem da população considerada de baixa renda
3. `PTRATIO`: razão estudante/professor da cidade

#### Variável alvo
4. `MEDV`: valor mediano das casas
