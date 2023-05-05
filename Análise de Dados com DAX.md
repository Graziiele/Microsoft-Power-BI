<div align="center">

## O que é Linguaguem DAX no Power BI?

![DAX_Easy-Resize com (1)](https://user-images.githubusercontent.com/114547875/236562434-5dc216ff-4679-4b8e-ac32-048547df9139.jpg)

</div>

DAX (Data Analysis Expressions) é uma linguagem de fórmulas utilizada no Power BI. A linguagem DAX é usada para criar fórmulas que permitem realizar cálculos complexos em conjuntos de dados, como cálculos de medidas, colunas calculadas, tabelas dinâmicas e gráficos.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Power BI - Lingugem DAX (Data Analysis Expression) - Estudos

* [DAX Guide](https://dax.guide/) - Material de Apoio utulizado 
* [Power BI](https://powerbi.microsoft.com/pt-br/) - Baixe Aqui 


#### Nesse projeto para estudo da linguagem Dax, utilizei o dataset e Data Warehouse feito na Modelagem de dados e Data Warehouse. O qual o objetivo é fornecer soluções de Business Intelligence, utilizando o Microsoft Power BI, DbSchema e MYSQL WorkBench. E também tem como objetivo os estudos de algumas funcções DAX (Foi utilizada Criação de nova medida, colunas e tabelas).
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

VendaLojaA = CALCULATE(SUM('dimensional fato_venda'[valor_venda]) , 'dimensional dim_localidade'[nm_localidade] = "Loja A")

![image](https://user-images.githubusercontent.com/114547875/203333847-5b7cb90b-61bc-47b6-9c11-ee3fb8946e12.png)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Lucro = 'dimensional fato_venda'[valor_venda] - 100 

![image](https://user-images.githubusercontent.com/114547875/203334481-1e13ed22-917e-474f-be8c-f2885f17ec8e.png)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

TB_Top5 = TOPN(5, 'dimensional fato_venda', 'dimensional fato_venda'[valor_venda], DESC)

![image](https://user-images.githubusercontent.com/114547875/203334908-c5b2ba84-f80a-420f-901a-c38e23a4b4d0.png)

VendasApple = CALCULATETABLE('dimensional fato_venda', 'dimensional dim_produto'[nm_marca_produto] = "Apple")


----------------------------------------------------------------------------------------------------------------------------------------------------------------------








