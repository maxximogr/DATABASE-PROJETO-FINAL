
<h2 align= center>O PAPEL DOS BANCOS DE DADOS SQL E NOSQL NO CONTEXTO DA ENGENHARIA DE DADOS</h2>

<h3>SQL</h3>
 
 <p>
Structured Query Language ou SQL é a linguagem mais conhecida do mundo e também a mais popular. É utilizada para executar comandos em Banco de Dados Relacionais,isto é, baseado em tabelas.
É por meio dela que criamos databases, tabelas, colunas, indices, garantimos e revogamos privilégios a usuários e consultamos os dados armazenados no banco de dados. 
SQL é uma linguagem declarativa dividida em conjuntos de comandos Data Definition Language (DDL), Data Manipulation Language (DML), Data Control Language (DCL), Transactional Control Language (TCL) e Data Query Language (DQL). 
</p>
 

<h3>NoSQL</h3>

  
<p>Os bancos de dados NoSQL (ou não-relacionais) utilizam um padrão diferente de armazenamento em relação ao SQL. 
O grande diferencial dessa tecnologia é a capacidade de escalabilidade para as operações das empresas de uma forma mais simples e econômica do que no banco relacional. 
O NoSQL também proporciona uma performance melhor para o gerenciamento de dados das organizações, pois não há necessidade de agrupar os dados em um esquema de tabelas para usar as informações. 
No MongoDB, conjuntos de documentos são chamados de “Coleções” (collections). Seriam os análogos das tabelas no PostgreSQL, com a diferença fundamental de que seus documentos não precisam respeitar um schema rígido de tabela,
como nos bancos relacionais. 

Um erro muito comum é quando dizem que os bancos de dados não relacionais não armazenam
bem dados de relacionamento. Eles podem armazenar dados de relacionamento, mas apenas os
armazenam de maneira diferente dos bancos de dados relacionais. De fato, muitos consideram a
modelagem relacionamentos nos bancos de dados NoSQL mais fácil do que nos bancos de dados
SQL, porque os dados relacionados não precisam ser divididos entre as tabelas.
Os modelos de dados NoSQL permitem por exemplo, que os dados relacionados sejam feitos
em uma única estrutura de dados. Diferentemente dos bancos relacionais, a estrutura de dados
não precisa ser definida previamente, portanto, em uma mesma “tabela” você pode ter dados com
propriedades diferentes.

A utilização dos bancos de dados NoSQL veem se tornando uma saída para aplicações 
que gerenciam um grande fluxo de dados, seu modelo não estruturado faz com que uma grande 
massa de dados possa ser armazenada sem muitos problemas. Embora os bancos de dados 
NoSQL veem crescendo no mercado o modelo relacional ainda se mostra muito eficiente em 
seu desempenho.

No geral, temos 5 tipos de bancos de dados NoSQL:</p>

<h4>Documento</h4>

<p>Os dados são armazenados como documentos. Os documentos podem ser descritos como dados no formato de chave-valor, como por exemplo, o padrão JSON. 
Um exemplo de banco de dados neste formato é o MongoDB.</p>

<h4>Colunas</h4>

<p>Os dados são armazenados em linhas particulares de tabela no disco, podendo suportar várias linhas e colunas, além de permitir sub-colunas. 
Um banco de dados dessa família, por exemplo, é o Cassandra.</p>

<h4>Grafos</h4>

<p>Os dados são armazenados na forma de grafos (vértices e arestas). 
O Neo4j é um banco que utiliza grafos.</p>

 <h4>Chave-valor</h4>
 
<p>Essa família de bancos NoSQL é a que aguenta a maior carga de dados, pois o conceito dela é que um determinado valor seja acessado através de uma chave identificadora única. 
Um exemplo é o banco de dados Riak.</p>


<h3 align=center>QUAL O MELHOR BANCO DE DADOS PARA O MEU NEGÓCIO?</h3>

 
<p>As Bases de Dados Relacionais (SQL) são uma boa escolha para qualquer negócio que vai se beneficiar de sua estrutura e esquema pré-definidos. 
or exemplo, aplicações que requerem transações de várias linhas ou que rodam em sistemas legados, vão prosperar com a estrutura de Dados Relacional (SQL). 
As Bases de Dados Não-Relacionais (NoSQL) por outro lado, são uma boa escolha para negócios que possuem crescimento rápido ou bases de dados sem definições claras de esquemas. 
Caso você não consiga definir um esquema para o seu banco de dados, perceba que está sempre desnormalizando esquemas de dados. 
Caso o seu esquema passe constantemente por mudanças, a estrutura de Dados Não-Relacionais (NoSQL) pode ser a escolha certa para você.

O NoSQL não veio para substituir o SQL, mas sim para oferecer mais uma alternativa de um banco de dados mais flexível no suporte de dados. 
Sendo assim, você pode usar ambas as soluções para diferentes casos de uso. 
Por isso, o mais comum em soluções escalares de sucesso é a utilização de uma arquitetura híbrida, aproveitando o melhor dos dois modelos e assim otimizar o banco de dados da empresa.</p>
