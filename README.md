# Data Science - Case 01

# Análise Descritiva do Conjunto de Dados de Aluguel de Casas
O conjunto de dados utilizado nesta análise é composto por informações sobre aluguéis de casas em duas cidades, Barcelona e Porto. As variáveis incluem área, número de quartos, banheiros, vagas de estacionamento, andar, aceitação de animais, mobília, taxas de manutenção e seguros, e o total dos custos envolvidos.

## 1. Importação e Preparação dos Dados
Os dados foram importados a partir de um arquivo Excel utilizando a biblioteca pandas e, em seguida, foram renomeadas algumas colunas para uniformizar os nomes, como "parking spaces" para "parking_spaces" e "rent amount" para "rent_amount". Após isso, foi realizada a conversão dos tipos de dados para garantir a consistência das operações subsequentes, transformando variáveis monetárias e totais em float.

## 2. Análise Descritiva
A análise inicial revelou as seguintes estatísticas descritivas para as variáveis relevantes:
- Área: Variando de 10 a 24.606 metros quadrados, com uma média de 151 metros quadrados.
- Número de Quartos: A maioria das propriedades tem entre 1 e 10 quartos, com uma média de aproximadamente 2,5 quartos.
- Número de Banheiros: Variando de 1 a 10, com uma média de 2,3 banheiros.
- Vagas de Estacionamento: Variam de 0 a 12, com uma média de 1,76 vagas.
- Aluguel: O valor do aluguel varia de 420 a 45.000, com uma média de 4.396.
- Taxa de Propriedade: Variando de 0 a 366.300, com uma média de 490,5.
- Seguro Contra Incêndio: Variando de 3 a 677, com uma média de 58,2.
- Total de Custos: Variando de 660 a 372.700, com uma média de 6.033.

## 3. Filtros e Consultas
Diversos filtros foram aplicados para identificar propriedades específicas:
- Filtro 1: Selecionamos imóveis cujo custo total não exceda 4.000, que aceitam animais, e que tenham 2 ou 3 quartos. Esse filtro resultou em imóveis em Barcelona e Porto, com preços médios de 1.319 a 2.963.
- Filtro 2: Usando a função query, foi possível aplicar os mesmos critérios, confirmando os resultados.
  
## 4. Agrupamento e Análise de Dados
Realizou-se a agregação dos dados para obter a média do custo total por cidade e por combinação de número de banheiros e quartos. Observou-se que:
- Média do Custo Total por Cidade: Barcelona apresenta uma média de 2.683,50, enquanto Porto tem uma média de 2.161,95.
- Média do Custo Total por Número de Quartos e Banheiros: A combinação de 2 banheiros e 2 quartos apresenta um custo médio de 2.734,61, enquanto a combinação de 3 banheiros e 2 quartos tem um custo médio de 3.057,44.

## 5. Visualização dos Dados
Gráficos foram gerados para melhor visualização:
- Distribuição do Custo Médio por Número de Quartos: O custo médio aumenta com o número de quartos, sendo mais alto para imóveis com 3 quartos.
- Distribuição do Custo Médio por Número de Banheiros: O custo médio também aumenta com o número de banheiros.
- Distribuição da Área dos Imóveis: O histograma da área mostra uma concentração de imóveis com área menor ou igual a 100 metros quadrados.
- Distribuição do Custo Total por Cidade: Um histograma comparativo foi criado para visualizar a distribuição dos custos totais em Barcelona e Porto.

## 6. Escolha do Apartamento
Após aplicar filtros adicionais, como escolher imóveis em Porto com andares e preços específicos, a análise revelou as opções mais baratas para aluguéis que aceitam animais e possuem 2 a 3 quartos, com preços variando de 1.253 a 1.600.

## 7. Conclusão
A análise dos dados forneceu uma visão abrangente sobre os preços de aluguéis e as características dos imóveis nas cidades de Barcelona e Porto. As visualizações ajudaram a identificar tendências e padrões importantes, facilitando a escolha de imóveis que atendam às necessidades específicas, como aceitação de animais e orçamentos limitados.
