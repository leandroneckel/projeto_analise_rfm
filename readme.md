# Análise RFM

A análise RFM (Recency, Frequency, Monetary) é uma técnica de segmentação de clientes utilizada para identificar quais clientes são mais valiosos para uma empresa através da avaliação de três dimensões específicas: quão recentemente um cliente fez uma compra (Recency), com que frequência eles compram (Frequency) e quanto eles gastam (Monetary). 

Recency ajuda a entender a relevância atual do cliente, Frequency destaca a lealdade do cliente, e Monetary indica o valor financeiro do cliente para a empresa. 

Ao combinar estas dimensões, a análise RFM permite às empresas personalizar estratégias de comunicação, marketing e vendas para atender e engajar diferentes segmentos de clientes de maneira mais eficaz, focando em manter clientes rentáveis e potencializar o valor ao longo do tempo.

## Base de dados 

Fonte [Kaggle](https://www.kaggle.com/datasets/aslanahmedov/market-basket-analysis)

* BillNo: número de 6 dígitos atribuído a cada transação. Nominal.
* Itemname: Nome do produto. Nominal.
* Quantity: As quantidades de cada produto por transação. Numérico.
* Date: O dia e a hora em que cada transação foi gerada. Numérico.
* Price: Preço do produto. Numérico.
* CustomerID: número de 5 dígitos atribuído a cada cliente. Nominal.
* Country: Nome do país onde cada cliente reside. Nominal.

## Descrição do projeto

O objetivo deste projeto é fazer a segmentação de clientes por meio de uma análise RFM.

A base de dados é processada de forma a encontrar a recência, a frequência e o valor mediano da compra de cada cliente. Após isto, as variáveis são categorizadas de acordo com seus quartis e grupos de clientes são gerados baseados nas combinações das categorias. Por fim, são obtidos 16 categorias de clientes.

O mapa de calor gerado onde se apresenta as medianas de recência, frequência e valor de fatura de cada categoria de clientes permite ao gestor do negócio uma tomada de decisão em termos de direcionamento de marketing, políticas de desconto, entre outros, visando maior rentabilidade de seu negócio