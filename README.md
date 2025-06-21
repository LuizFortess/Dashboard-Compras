-Dashboard de Análise de Compras
Este dashboard em Power BI foi desenvolvido para oferecer uma análise detalhada do comportamento de compras, permitindo insights sobre gastos, produtos e desempenho de fornecedores. O objetivo é fornecer uma visão clara e interativa dos dados para tomada de decisões estratégicas.

Principais Recursos e Análises
O dashboard apresenta as seguintes visualizações e informações chave:

Total Gasto: Cartão que exibe o valor total acumulado das compras, oferecendo um KPI rápido do volume financeiro.
Produto Mais Comprado: Cartão que destaca o produto campeão de vendas em termos de quantidade, ideal para identificar itens de alta demanda.
Comparativo de Gastos (Original vs. Oferta) por Mês: Gráfico de colunas que visualiza a diferença entre o valor original dos produtos e o valor gasto com ofertas/descontos, mês a mês. Isso permite identificar a economia gerada e o impacto das promoções ao longo do tempo.
Total com Desconto e Quantidade Comprada por Região de Destino: Gráfico de mapa que correlaciona os gastos com desconto e a quantidade de itens comprados por região geográfica, ajudando a entender padrões de consumo regional e a eficácia de ofertas em diferentes áreas.
Total Gasto por Fornecedor: Gráfico de colunas horizontais que classifica os fornecedores pelo volume total de gastos, facilitando a identificação dos principais parceiros e a otimização de relacionamentos comerciais.
Fonte de Dados
Os dados utilizados para a construção deste dashboard foram obtidos de um arquivo Excel, simulando um extrato de compras, baixado da internet para fins de análise e demonstração.

Aspectos Técnicos e Desafios
Implementação de DAX: O dashboard faz uso de funções DAX para criar medidas e cálculos personalizados, garantindo precisão e relevância nas análises. (Se você usou DAX para cálculos específicos de "total original" vs. "total com oferta", ou para ranqueamento, pode detalhar mais aqui se quiser!)
Design e Clareza Visual: Um dos principais desafios foi conceber um design que fosse intuitivo e visualmente claro, mesmo com diversas informações sendo apresentadas. A escolha das cores, layout e tipos de gráficos foi feita para otimizar a experiência do usuário e facilitar a interpretação dos dados.
Interatividade
Para proporcionar uma experiência analítica completa, o dashboard oferece:

Filtros Dinâmicos: Possibilidade de filtrar os dados por diversos critérios, como tipos de produtos e períodos.
Interatividade entre Visuais: Os cartões, mapas e gráficos respondem interativamente aos cliques, permitindo explorar os dados em diferentes níveis de detalhe (por exemplo, ao clicar em uma região no mapa, os outros gráficos se ajustam para mostrar dados apenas daquela região).
Navegação Flexível: O layout permite uma transição fluida entre as análises horizontais e verticais, facilitando a exploração de diferentes perspectivas dos dados.
Melhorias Futuras
Visando aprimoramento contínuo, algumas funcionalidades futuras que poderiam ser exploradas incluem:

Integração de mais fontes de dados para enriquecer as análises.
Expansão da variabilidade de interatividade, adicionando recursos como drill-through mais complexos ou relatórios aninhados.
Implementação de alertas baseados em limites de gastos ou metas.
