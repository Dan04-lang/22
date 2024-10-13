Comecei importando tabelas de Clientes, Vendas e Produtos de arquivos ou bancos de dados. Em seguida, estabeleci as relações entre as tabelas: ex:vincule Clientes (ClientID) com Vendas (ClientID) e Produtos (ProductID) com Vendas (ProductID) para permitir a comunicação entre os dados.

Após a modelagem, utilizei DAX para criar medidas, como o total de vendas (TotalVendas = SUM(Vendas[Valor])) e a média de vendas por produto (MediaVendasProduto = AVERAGE(Vendas[Valor])). Com essas medidas, criei visualizações, como gráficos de barras para exibir o total de vendas por cliente e apliquei filtros interativos, como slicers, para segmentar os dados por data, produto ou cliente.





