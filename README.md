## Power_BI_Analyst
Projetos iniciais.

## Projeto Desafio Dio módulo 3
Criação de Database e relatório utilizando MySQL e Power BI

Resumo:
O desafio consistiu em criar um banco de dados MySQL, em seguida esse banco de dados foi conectado ao Power BI e utilizado para elaboração de um relatório. Os dados foram limpos e transformados no Power Query, e em seguida foi feita a análise dos dados e sua visualização através de gráficos. As tranformações feitas foram:

Criação de uma nova tabela contendo informações dos gerentes e seus dependentes;
Criação de uma relação entre a tabela *departament* e *employee* utilizando a mescla;
Modificação de nomenclatura de cabeçalhos;
Substituição de valores nulos por 0;
Mesclagem da tabela *departament* com a tabela *local_departament*;
Separação de endereço em rua, cidade e estado;
Junção das colunas Fnane, Minit e Lname formando uma nova com o nome completo.

Benefícios:

Transformação dos dados, retirando informações irrelevantes e aumentando assim a velocidade de carregamento;
Análise de dados e integração de diferentes fontes para uma visão holística.
Criação de gráficos intuitivos e com as principais métricas e KPI para facilitar a compreensão dos dados e facilitando tomada de decisões, gerando insights valiosos.






## Projeto desafio módulo 4
Criação do diagrama dimensional - star schema - com base no diagrama relacional

Foco: Professor – objeto de análise

Criação do esquema em estrela com o foco na análise dos dados dos professores. Sendo assim, a tabela fato refleti diversos dados sobre professor, cursos ministrados, departamento e disciplina.





## Projeto desafio módulo 5

Foi utilizado a tabela única de Financial Sample para criar as tabelas dimensão e fato do modelo baseado em star schema.
O processo consiste na criação das tabelas com base na tabela original. A partir da cópia foram selecionadas as colunas que irão compor a visão da nova tabela. Sendo assim, a partir da tabela principal foram criadas as tabelas:

Dim_Produtos (ID_produto, Produto, Média de Unidades Vendidas, Médias do valor de vendas, Mediana do valor de vendas, Valor máximo de Venda, Valor mínimo de Venda)

Dim_Produtos_Detalhes(ID_produtos, Discount Band, Sale Price, Units Sold, Manufactoring Price)

Dim_Descontos (ID_produto, Discount, Discount Band)

Dim_Detalhes (*)

Dim_Calendário – Criada por DAX com calendar()

F_Vendas (SK_ID , ID_Produto, Produto, Units Sold, Sales Price, Discount Band, Segment, Country, Salers, Profit, Date (campos))



## Projeto desafio modulo 6

Criação de um relatório financeiro com foco na experiência do usuário, levando em consideração os seguintes pontos:

· Posicionamento

· Contraste

· Proporção áurea

· Segmentação dos dados


próximo passo:

· Inserção de botões de navegabilidade

· foi Modificado os botões de navegabilidade a fim de destacar o focalizar e selecionar

· Criação dos menus de navegabilidade em cada página

· O relatório é composto por 3 páginas















