# Gerenciamento de Indicadores Tudo Aqui

<br>
<div align="center">
<img src="dash/0.Tudo Aqui_Menu.png" />
</div>
<br>

## Contexto do Negócio 

A TUDO AQUI é uma empresa brasileira do setor de e-commerce que vem apresentando crescimento em suas operações. No entanto, grande parte das decisões estratégicas da organização ainda é baseada em percepções intuitivas da diretoria, sem o suporte de análises estruturadas de dados e indicadores de desempenho.

A ausência de uma cultura analítica resultou em decisões equivocadas que impactaram negativamente os resultados financeiros da empresa, evidenciando a necessidade de maior precisão no processo decisório.

Diante desse cenário, o CEO identificou a necessidade de implementar uma estratégia de Business Intelligence (BI) para ampliar a visibilidade sobre os dados corporativos e transformar informações em insights relevantes para o negócio. O principal objetivo é permitir uma tomada de decisão mais assertiva, baseada em indicadores confiáveis e acompanhamento contínuo da performance da empresa.

Como parte dessa transformação, a organização passou a adotar uma abordagem Data Driven, substituindo decisões baseadas em suposições por análises orientadas por dados, com foco em crescimento sustentável, redução de riscos e melhoria dos resultados estratégicos.

As frentes analisadas serão respectivamente: Produto, Pagamentos, Pedidos, Avaliações, Vendedores e Vendas.  

## Visão Produto 

A visão inicial foi gerada pela necessidade do corpo diretivo entender a importância de tomar decisões pautadas em dados. 

Para análse da Visão Produto serão respondidas as seguintes questões: 
1. Quantidade de Produtos Cadastrados;
2. Quantidade Total de Categorias;
3. Quantidade Total de Fotos;
4. Quantidade de Produtos por Categoria;
5. Quantidade de Fotos por Categoria.

<br>
<div align="center">
<img src="dash/1.Tudo Aqui_Análise de Produtos.png" />
</div>
<br>

## Visão Pagamento 

Após entender como estão os produtos, surgiu a necessidade de ampliar as análises sobre como estão os pagamentos. 

Na análise da Visão Pagamento as questões apresentadas foram: 
1. Quantidade de pedidos;
2. Valor total de pagamentos;
3. Quantidade de pagamentos
4. Quantidade de pagamentos por tipo de pagamento (um por cartão);
5. Valor total de pagamentos (por status do pedido);
6. Quantidade de pagamentos (por tipo de pagamento);
7. Hierarquia de valor médio de pagamentos por status do pedido e por tipo de 
pagamento;
8. Detalhes dos pedidos por tipo de pagamento e pela quantidade de 
pagamentos;
9. Número do pedido;
10. Tipo de Pagamento;
11. Status do Pedido.

<br>
<div align="center">
<img src="dash/2.Tudo Aqui_Análise de Pagamentos.png" />
</div>
<br>

## Visão Pedidos 

Nesta visão, o CEO quer saber como a empresa está avançando em relação as metas estabelecidas para o ano atual e como 
a empresa está posicionada em relação aos dados de anos anteriores, ou seja, a partir desse ponto o CEO deseja explorar 
análises de inteligência temporal. 

E para isso as seguintes questões serão respondididas:
1. Quantidade de pedidos;
2. Quantidade de clientes;
3. Quantidade de pedidos do ano de 2017;
4. Quantidade de pedidos do ano de 2018;
5. Taxa de Crescimento (2017 - 2018);
6. Quantidade de pedidos x Meta Anual;
7. Quantidade de pedidos x Meta Mensal de 2018;
8. Quantidade de Pedidos por Estado do Cliente;
9. Detalhes da quantidade de pedidos e meta de pedidos por Ano, Mês, Estado do Cliente e Cidade do Cliente;
10. Data de Compra;
11. Ano / Mês (de compra);
12. Estado do Cliente;
13. Cidade do Cliente;
14. Status do Pedido.

<br>
<div align="center">
<img src="dash/3.Tudo_Aqui_Análise de Pedidos.png" />
</div>
<br>

## Visão Avaliações

Nesta visão, o CEO deseja saber quais são os principais influenciadores para avaliações que são classificadas como ruins, 
médias e boas, analisar profundamente os estados de SP e RJ e criar uma análise de clusterização da quantidade média de 
avaliações em acordo com as regras que eles te passarão. 

Aqui, serão consideradas questões como: 

1. Quantidade de avaliações únicas;
2. Quantidade de avaliações únicas para o score 4 e 5;
3. Média de tempo em dias das avaliações que não receberam retorno no mesmo dia que a avaliação foi criada;
4. Média de tempo em horas das avaliações que não receberam retorno no mesmo dia que a avaliação foi criada;
5. Quantidade de avaliações únicas para o score 4 e 5 dos clientes dos estados SP e RJ apenas do ano de 2018;
6. Taxa de crescimento entre os anos de 2018 e 2017 para os clientes score 4 e 5 dos estados SP e RJ;
7. Um gráfico de dispersão clusterizado por estado do cliente, quantidade de avaliações únicas e a média de tempo em dias das avaliações que  não receberam retorno no mesmo dia que a avaliação foi criada;
8. Um gráfico de Pizza que exibe a quantidade de avaliações únicas pela classificação da avaliação;
9. Um gráfico com os principais influenciadores entre a classificação das avaliações e estado do cliente;
10. Data de criação da avaliação;
11. Ano e mês da criação da avaliação;
12. Estado do Cliente;
13. Cidade do Cliente;
14. Classificação da Avaliação;
15. Tipo de Avaliação.

<br>
<div align="center">
<img src="dash/4.Tudo Aqui_Análise de Avaliações.png" />
</div>
<br>

## Visão Vendedores 

Nesta visão, os Stakeholders desejam ver os top 10 estados dos vendedores que mais vendem, um mapa com a 
concentração de vendedores por regiões do Brasil, uma tabela detalhada e bem visual com as principais métricas 
e indicadores solicitados e um gráfico com acompanhamento dinâmico das metas esperadas. 

E seguindo as análises foram levantadas as questões a seguir: 

1. Quantidade total de vendedores Detalhes de Vendedores;
2. Total de vendas;
3. Total de vendas dos itens com valor superior a R$500.000 Detalhes de Itens Vendidos);
4. Quantidade de vendedores que venderam itens com valor superior a R$500.000;
5. Quantidade de vendedores que venderam dentro ou acima da meta;
6. Um gráfico de Funil para apresentar os Top 10 estados dos vendedores que mais vendem;
7. Um gráfico de Mapa que contenha a quantidade de vendedores e demonstre essa informação por país, estado e cidade dos vendedores 
Detalhes Geográficos);
8. Um gráfico de acompanhamento dinâmico de meta média por Item que permita alterar dinamicamente os valores das metas na tela do 
Dashboard;
9. Uma tabela com os detalhes por vendedor e seus respectivos estados que contenha o total de vendas, o total de vendas de itens acima de R$ 500.000, a representação do valor de vendas de cada vendedor em relação ao todo, a representação do valor de vendas de cada vendedor 
em relação ao que está filtrado nas segmentações e quais vendedores venderam dentro ou acima da meta;
10. ID do Vendedor;
11. Cidade do Vendedor;
12. Estado do Vendedor.

<br>
<div align="center">
<img src="dash/5.Tudo Aqui_Análise de Vendedores.png" />
</div>
<br>

## Visão Vendas 

Algumas das análises esperadas para esta visão são: Pareto 80-20, Cohort, Vendas Acumuladas (YTD), Comparativo de 
Vendas por Ano, Taxa de Crescimento Acumulado, entre outras.

Para o atual cenário, foram levantadas as questões abaixo: 

1. Total de Vendas;
2. Total Acumulado YTD (Ano Atual);
3. Total Acumulado YTD (Ano Anterior);
4. Taxa de Crescimento Acumulado (Ano Atual x Ano Anterior);
5. % de Desconto de Frete Regra: Itens com preço igual ou superior a 10.000, possuem 50% de desconto no frete;
6. Uma Análise de Pareto 80-20 com o Total de Vendas por Estado de Compra;
7. Total de Vendas Acumuladas mês a mês exibindo todos os anos na tela;
8. Uma análise de % Retenção de vendedores com COHORT;
9. Uma análise que exiba o Total de Vendas do Ano Atual x Ano Anterior mês a mês em conjunto com a taxa de crescimento exibindo todos os anos na tela;
10. Segmentação estilo entre da Data de Envio (considere a shipping_limit_date);
11. Ano / Mês;
12. ID do Pedido;
13. ID do Comprador;
14. ID do Vendedor;
15. ID do Produto. 

<br>
<div align="center">
<img src="dash/6.Tudo Aqui_Análise de Vendas.png" />
</div>
<br>
