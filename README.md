# Desafio_DIO_Dados_PowerBI
 Processando e Transformando Dados com Power BI - Desadio DIO

 Descrição do desafio módulo 3 – Processamento de Dados Simplificado com Power BI

1.	Criação de uma instância na Azure para MySQL
   
Para esta parte, como complemento ao mostrado no curso da DIO, recomendo a seguinte série de treinamento da Azure:

[SQL do Azure para Iniciantes | Microsoft Learn](https://learn.microsoft.com/pt-br/shows/azure-sql-for-beginners/)

E também os seguintes roteiros de treinamento:

https://learn.microsoft.com/pt-br/training/browse/?products=azure&resource_type=learning%20path&levels=beginner

2.	Criar o Banco de dados com base disponível no github
   
O arquivo script_cria_db_company2.sql   cria o database “azure_company”, as tabelas e já insere os dados e testa também. No final tem uma série de queries neste database.

3.	Integração do Power BI com MySQL no Azure
   
Nesta etapa é configurado o acesso ao MySQL. Se for a primeira vez pode ser necessário abaixar e instala o drive odbc. No meu caso a instalação estava no “localhost” não sendo mais necessário o acesso ao Azure, apenas ao MySQL. Em uma aplicação real, o melhor seria deixar os dados no Azure, criar usuários com o acesso restrito ao dados de interesse e usar o direct query de forma que todas as atualizações na cloud refletiriam no PowerBI.

4. Verificar problemas na base a fim de realizar a transformação dos dados
   
Feito o relacionamento entre as tabelas no próprio PowerBI

