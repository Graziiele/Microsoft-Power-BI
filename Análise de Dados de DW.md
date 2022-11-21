## Data Warehouse 


É um repositório central de informações que podem ser analisadas para tomar decisões mais adequadas. Podendo conter assim vários bancos de dados onde os dados são organizados em tabelas e colunas. Dentro de cada coluna, podemos definir uma descrição dos dados;

Referência : https://aws.amazon.com/pt/data-warehouse/

### Quais são os benefícios de usar um data warehouse? 

* Para Tomada de decicões;
* Qualidade dos dados e uma vizualizqação geral do negócio;
* Análise de dados históricos;
* Precisão dos dados 
* Análise, relatórios e big data. 

### Segue um projeto de criação de um data warehouse com o uso do MYSQL e DBschema: 

Primeiramente foi feito um estudo de modelagem de dados para a criação de um data warehouse, nesse projeto foi utilizado uma pequena base de dados de uma empresa de eletrodomesticos e nele apresenta vendas e os produtos;

Modelo lógico Dimension dimensional ( Será utilizado para estudar linguaguem DAX em power BI) 

Tabelas apresentadas:

Table dim_cliente

Table dim_localidade

Table dim_produto

Table dim_tempo

Table fato_venda 


![Modelológicotransacional2](https://user-images.githubusercontent.com/114547875/203154043-6dc8db62-ba7f-471f-b955-b57e96f6093e.png)





