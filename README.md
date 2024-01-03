# Projeto de Análise de Dados com SQLite
Este projeto tem como objetivo realizar uma análise de dados a partir de um conjunto fornecido em formato CSV. A análise será conduzida utilizando o SQLite para manipulação e consulta dos dados.


STORYTELLING

![CAPA](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/87d9bb9d-695e-4e2b-b871-c2087b8e6b31)


# Conjunto de Dados
O conjunto de dados está disponível no arquivo dados.csv e contém informações sobre histórico do cartao de credido. Cada linha representa um cliente e as colunas fornecem detalhes sobre características demográficas, financeiras e comportamentais. Abaixo estão as primeiras linhas do conjunto de dados:

![image](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/fdc5cfe8-fdc7-4cec-ab53-fce08add3164)

# Utilização do SQLite
Criando a tabela
Para criar tabela no SQLite, utilize o seguinte comando:

![QUERY1](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/4d982ce1-c1c4-4cd0-860c-e4b75f4709a7)

# ANÁLISE EXPLORÁTORIA

Saber quantas linhas tem o arquivo CSV:

![QUERY2](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/859bfa4c-83f0-4a0d-a844-8c3cf124d6d5)

![Captura de tela 2024-01-02 195009](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/b2764178-bbf9-45a1-b62c-9b3cf68a1d04)

Visualizandos as colunas e os tipos de dados:

![QUERY3](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/3256fcee-7ce7-425d-b0eb-ba6d31006b9c)

![Captura de tela 2024-01-02 195236](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/479e082a-1d9a-4b2d-ba36-766dd0ee665d)

Saber o nivil de educação dos clientes:

![QUERY4](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/f576a1dc-ac66-432a-8dde-2216a2aa0532)

![Captura de tela 2024-01-02 195429](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/b2fc08ed-91c7-4753-b1a0-a29a200a9af3)

Descobrir a faixa salárial de cada cliente:

![QUERY5](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/1df57010-862b-4e3b-8ad2-09d635dff28a)

![6](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/7e37c061-cbc4-44fe-be10-17ac799e05e5)

Quais são os tipos de cartão:

![QUERY6](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/7a1f5f86-973f-4953-b005-e85961154ac7)

![6](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/02bbd5aa-40e3-46e2-8b93-8b4dfee5a6a6)

#ANÁLISE DE DADOS

Quantos Homens e Mulheres contem nessa base de dados:

![QUERY7](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/9e0d6de9-395a-449d-afdd-fbef88a66b3d)

![chart](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/4c027234-adbc-4b2f-89b6-eb418795f6f4)

Quantos clientes temos de cada faixa salarial:

![query8](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/f7eceace-4a3d-4fbe-b515-5757a7c6e697)

![8](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/85d1f47e-76c2-4802-a391-6287dda9b94f)

Qual é a facha de idade dos clientes desse banco:

![Captura de tela 2024-01-02 201539](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/85063084-56ec-4a74-af8b-3de27ececd4b)

![Captura de tela 2024-01-02 202431](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/f395fd55-4152-4f76-b5e7-2bcb9e37e628)

Quais as características dos clintes que possum os maiores creditos:

![QUERY10](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/b8f78c0b-e0a8-4d2a-a728-0e1cff73e235)

![1](https://github.com/luisfernandogbraga/USANDO_SQL_PARA_FAZER_UMA_BREVE_ANALISE/assets/134460985/8ee3f6bb-821f-43e8-98d0-960370d81176)


#CONCLUSÃO

Alguns INSIHTS interessantes

. a maior parte dos clintes possui renda até 40k

. a maior parte dos clientes é masculino

. a escolaridade não parece influênciar no limite nem no tipo do cartão

. os clientes com maiores limites sáo em sua maioria homens

. a faixa salarial impacta diretamente no limite de crédito

. não existem clientes com salário anual acima de 60k do sexo feminino


