## pandas_lib

# O dataset que utiizamos para este projeto é composto por informações de vendas de uma loja virtual que atua em todo o território nacional, vendendo produtos de diferentes departamentos. Além disso, a loja atua em diferentes canais de venda, como loja fisica, marketplace, entre outros.

PREMISSAS DE NEGÓCIO:
Ao realizar a análise dos dados, é importante pensar que existem algumas particularidades que devem ser consideradas. A primeira premissa é sobre um erro do sistema, onde, em algumas compras o campo UF (Unidade Federativa) era dado como nulo. Para a solução desse problema, foi decidido que essas compras deveriam ser consideradas pertencentes ao estado do Mato Grosso do Sul (MS). A segunda premissa é que, o preço de um produto com frete sempre deve ser inferior ao preço unitário do mesmo sem o gasto de frete.

MÉTRICAS:
 Com base nesse contexto e nas premissas estabelecidas, podemos avaliar as seguintes métricas:

 1. Departamentos mais vendidos
 2. Média de preço com frete por Departamento
 3. Quantidade de vendas por mês
 4. Média de renda para cada tipo de canal de venda.
 5. Média de idade de clientes por bandeira
 6. 
