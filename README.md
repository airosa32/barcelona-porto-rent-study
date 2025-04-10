🏡 Análise de Aluguel de Imóveis em Barcelona e Porto

📌 Descrição Geral
Este projeto realiza uma análise descritiva de um conjunto de dados com informações sobre aluguéis de casas nas cidades de Barcelona 🇪🇸 e Porto 🇵🇹. O objetivo é entender os padrões de preço, características dos imóveis e apoiar decisões baseadas em dados para quem busca imóveis com critérios específicos.

📥 1. Importação e Preparação dos Dados
- 📊 Leitura do arquivo Excel com `pandas`.
- 🔄 Renomeação de colunas para padronização (`rent amount` → `rent_amount`, etc.).
- 🧮 Conversão de colunas para tipos numéricos (e.g., float para valores monetários).

📈 2. Análise Descritiva
- 📐 Área: 10 a 24.606 m² | Média: 151 m².
- 🛏️ Quartos: 1 a 10 | Média: 2,5 quartos.
- 🚿 Banheiros: 1 a 10 | Média: 2,3 banheiros.
- 🚗 Estacionamento: 0 a 12 vagas | Média: 1,76 vagas.
- 💸 Aluguel: 420 a 45.000 | Média: 4.396.
- 🏢 Taxa de Propriedade: 0 a 366.300 | Média: 490,5.
- 🔥 Seguro Contra Incêndio: 3 a 677 | Média: 58,2.
- 💰 Total de Custos: 660 a 372.700 | Média: 6.033.

🔎 3. Filtros e Consultas
- Filtro: Imóveis com custo total ≤ 4.000, que aceitam animais, com 2 ou 3 quartos.
- Resultado: Imóveis em ambas as cidades, com preços médios entre 1.319 e 2.963.

🧮 4. Agrupamento e Análise
- Média do Custo Total por Cidade:
    • Barcelona: 2.683,50
    • Porto: 2.161,95
- Por Quartos e Banheiros:
    • 2 quartos e 2 banheiros: 2.734,61
    • 2 quartos e 3 banheiros: 3.057,44

📊 5. Visualização dos Dados
- Custo médio por número de quartos 🛏️
- Custo médio por número de banheiros 🚿
- Distribuição da área dos imóveis 📏
- Distribuição do custo total por cidade 🏙️

🏠 6. Escolha do Apartamento
- Análise de imóveis em Porto com filtros adicionais.
- Resultados: Imóveis mais baratos com aceitação de animais e 2 a 3 quartos, entre 1.253 e 1.600.

✅ 7. Conclusão
A análise dos dados revelou padrões valiosos sobre preços e características dos imóveis em Barcelona e Porto. Com isso, é possível tomar decisões mais informadas ao buscar um imóvel, especialmente com filtros como aceitação de pets e limite de orçamento.

🔗 Projeto desenvolvido com Python e Pandas, visualizações feitas com Matplotlib e Seaborn.
