# Inicio

- [Inicio](#inicio)
- [Banco de Dados](#banco-de-dados)
  - [Sistemas de Banco de Dados](#sistemas-de-banco-de-dados)
    - [Reconhecer o histórico dos bancos de dados e suas tecnologias](#reconhecer-o-histórico-dos-bancos-de-dados-e-suas-tecnologias)
      - [DEFINIÇÃO DE BANCO DE DADOS](#definição-de-banco-de-dados)
      - [EVOLUÇÃO DOS SISTEMAS DE INFORMAÇÃO EM COMPUTADO](#evolução-dos-sistemas-de-informação-em-computado)
      - [REVOLUÇÃO DOS SISTEMAS DE BANCO DE DADOS](#revolução-dos-sistemas-de-banco-de-dados)
      - [PRINCIPAIS SGBDS RELACIONAIS](#principais-sgbds-relacionais)
    - [Identificar as características dos sistemas de banco de dados (SBD)](#identificar-as-características-dos-sistemas-de-banco-de-dados-sbd)
      - [DIFERENÇAS ENTRE SISTEMA DE ARQUIVOS E SISTEMA DE BANCO DE DADOS](#diferenças-entre-sistema-de-arquivos-e-sistema-de-banco-de-dados)
      - [VANTAGENS E DESVANTAGENS DA ABORDAGEM DE BANCO DE DADOS](#vantagens-e-desvantagens-da-abordagem-de-banco-de-dados)
      - [PAPÉIS EM SISTEMAS DE BANCOS DE DADOS](#papéis-em-sistemas-de-bancos-de-dados)
    - [Descrever a arquitetura dos sistemas de gerência de banco de dados (SGBD)](#descrever-a-arquitetura-dos-sistemas-de-gerência-de-banco-de-dados-sgbd)
      - [COMPONENTES DE UM SISTEMA DE BANCO DE DADOS](#componentes-de-um-sistema-de-banco-de-dados)
      - [MÓDULOS DE UM SISTEMA DE GERÊNCIA DE BANCO DE DADOS](#módulos-de-um-sistema-de-gerência-de-banco-de-dados)
      - [UM EXEMPLO DE SGBD RELACIONAL: POSTGRESQL](#um-exemplo-de-sgbd-relacional-postgresql)
  - [Projeto de Banco de Dados – Modelagem Conceitual](#projeto-de-banco-de-dados--modelagem-conceitual)
    - [Identificar as etapas de um projeto de banco de dados](#identificar-as-etapas-de-um-projeto-de-banco-de-dados)
      - [PROJETO DE BANCO DE DADOS](#projeto-de-banco-de-dados)
      - [LEVANTAMENTO DE REQUISITOS](#levantamento-de-requisitos)
      - [PROJETO CONCEITUAL](#projeto-conceitual)
      - [PROJETO LÓGICO](#projeto-lógico)
      - [PROJETO FÍSICO](#projeto-físico)
    - [Reconhecer os elementos do diagrama de entidade e relacionamento](#reconhecer-os-elementos-do-diagrama-de-entidade-e-relacionamento)
      - [ENTIDADE](#entidade)
      - [RELACIONAMENTO](#relacionamento)
      - [ATRIBUTO](#atributo)
      - [ESPECIALIZAÇÃO/GENERALIZAÇÃO](#especializaçãogeneralização)
      - [ENTIDADE ASSOCIATIVA](#entidade-associativa)
    - [Compreender a modelagem de entidades e relacionamentos](#compreender-a-modelagem-de-entidades-e-relacionamentos)
      - [OBJETIVOS AO CONSTRUIR UM DER](#objetivos-ao-construir-um-der)
      - [MODELAGEM DE ENTIDADES E RELACIONAMENTOS](#modelagem-de-entidades-e-relacionamentos)
      - [MODELAGEM DE ENTIDADE ISOLADA](#modelagem-de-entidade-isolada)
      - [MAIS SOBRE MODELAGEM DE ENTIDADES E RELACIONAMENTOS](#mais-sobre-modelagem-de-entidades-e-relacionamentos)
    - [Compreender a modelagem de atributos](#compreender-a-modelagem-de-atributos)
      - [ATRIBUTO X ENTIDADE](#atributo-x-entidade)
      - [ATRIBUTO X ESPECIALIZAÇÃO](#atributo-x-especialização)
      - [ATRIBUTO OPCIONAL](#atributo-opcional)
      - [ATRIBUTO MULTIVALORADO](#atributo-multivalorado)
      - [ATRIBUTO X REDUNDÂNCIAA](#atributo-x-redundânciaa)
      - [TRIBUTO COMPOSTO](#tributo-composto)
  - [Projeto De Banco De Dados – Modelagem Lógica E Física](#projeto-de-banco-de-dados--modelagem-lógica-e-física)
    - [Identificar os elementos do modelo relacional](#identificar-os-elementos-do-modelo-relacional)
      - [MODELO RELACIONAL](#modelo-relacional)
      - [COMPONENTES DE UMA TABELA](#componentes-de-uma-tabela)
      - [CHAVE PRIMÁRIACHAVE ESTRANGEIRA](#chave-primáriachave-estrangeira)
      - [ESQUEMA DIAGRAMÁTICO DE BANCO DE DADOS RELACIONAL](#esquema-diagramático-de-banco-de-dados-relacional)
      - [](#)
    - [Diferenciar formas normais](#diferenciar-formas-normais)
      - [NORMALIZAÇÃO](#normalização)
      - [PRIMEIRA FORMA NORMAL (1FN)](#primeira-forma-normal-1fn)
      - [SEGUNDA FORMA NORMAL (2FN)](#segunda-forma-normal-2fn)
      - [TERCEIRA FORMA NORMAL (3FN)](#terceira-forma-normal-3fn)
      - [](#-1)
    - [Aplicar o mapeamento conceitual-lógico](#aplicar-o-mapeamento-conceitual-lógico)
      - [MAPEAMENTO CONCEITUAL-LÓGICO](#mapeamento-conceitual-lógico)
      - [MAPEAMENTO DE ENTIDADES](#mapeamento-de-entidades)
      - [MAPEAMENTO DE RELACIONAMENTOS](#mapeamento-de-relacionamentos)
      - [MAPEAMENTO DE ATRIBUTOS MULTIVALORADOS](#mapeamento-de-atributos-multivalorados)
      - [MAPEAMENTO DE ESPECIALIZAÇÃO/GENERALIZAÇÃO](#mapeamento-de-especializaçãogeneralização)
    - [Identificar aspectos físicos para implementação do modelo no SGBD](#identificar-aspectos-físicos-para-implementação-do-modelo-no-sgbd)
      - [CONSULTAS](#consultas)
      - [TRANSAÇÕES](#transações)
      - [INDEXAÇÃO EM BANCO DE DADOS](#indexação-em-banco-de-dados)
      - [CONSULTAS ENVOLVENDO MAIS DE UMA TABELA](#consultas-envolvendo-mais-de-uma-tabela)
      - [DESNORMALIZAR PARA GANHAR DESEMPENHO](#desnormalizar-para-ganhar-desempenho)
  - [Criação e manipulação de objetos no PostgreSQL](#criação-e-manipulação-de-objetos-no-postgresql)
    - [Compreender o processo de instalação do PostgreSQL](#compreender-o-processo-de-instalação-do-postgresql)
      - [BREVE HISTÓRICO](#breve-histórico)
      - [ARQUITETURA DO POSTGRESQL](#arquitetura-do-postgresql)
      - [INSTALAÇÃO DO POSTGRESQL NO LINUX](#instalação-do-postgresql-no-linux)
      - [INSTALAÇÃO DO POSTGRESQL NO WINDOWS](#instalação-do-postgresql-no-windows)
      - [INTERFACES PARA INTERAGIR COM O POSTGRESQL](#interfaces-para-interagir-com-o-postgresql)
      - [CRIANDO DATABASES COM O PGADMIN 4 E COM O PSQL](#criando-databases-com-o-pgadmin-4-e-com-o-psql)
    - [Empregar comandos para criação e alteração de tabelas](#empregar-comandos-para-criação-e-alteração-de-tabelas)
      - [BREVE HISTÓRICO DA SQL](#breve-histórico-da-sql)
      - [ACESSO AO POSTGRESQL](#acesso-ao-postgresql)
      - [CRIANDO UM BANCO DE DADOS](#criando-um-banco-de-dados)
      - [CRIANDO TABELASTIPOS DE DADOS](#criando-tabelastipos-de-dados)
      - [ALTERAÇÃO DE TABELA](#alteração-de-tabela)
      - [CRIAÇÃO E ALTERAÇÃO DE TABELAS RELACIONADAS](#criação-e-alteração-de-tabelas-relacionadas)
    - [Empregar comandos para manipular linhas nas tabelas](#empregar-comandos-para-manipular-linhas-nas-tabelas)
      - [MANIPULAÇÃO DE LINHAS NAS TABELAS](#manipulação-de-linhas-nas-tabelas)
      - [INSERÇÃO DE LINHAS EM TABELA](#inserção-de-linhas-em-tabela)
      - [MECANISMO DE CHAVE PRIMÁRIA EM AÇÃO](#mecanismo-de-chave-primária-em-ação)
      - [ATUALIZAÇÃO DE LINHAS EM TABELA](#atualização-de-linhas-em-tabela)
      - [ATUALIZAÇÃO DE COLUNA CHAVE PRIMÁRIA](#atualização-de-coluna-chave-primária)
      - [REMOÇÃO DE LINHAS EM TABELA](#remoção-de-linhas-em-tabela)
    - [Empregar comandos de controle de transação](#empregar-comandos-de-controle-de-transação)
      - [TRANSAÇÕES EM BANCO DE DADOS](#transações-em-banco-de-dados)
      - [TRANSAÇÕES NO POSTGRESQL](#transações-no-postgresql)
      - [UM POUCO MAIS SOBRE ATUALIZAÇÃO TEMPORÁRIA](#um-pouco-mais-sobre-atualização-temporária)
      - [UM POUCO MAIS SOBRE TRANSAÇÃO DE LEITURA](#um-pouco-mais-sobre-transação-de-leitura)
  - [Consultas em uma Tabela no Postgresql](#consultas-em-uma-tabela-no-postgresql)
    - [Operar consultas com o comando SELECT](#operar-consultas-com-o-comando-select)
      - [ESTRUTURA BÁSICA DE UM COMANDO SELECT](#estrutura-básica-de-um-comando-select)
      - [FUNÇÕES DE DATA E HORA](#funções-de-data-e-hora)
      - [FUNÇÕES DE RESUMO OU DE AGREGAÇÃO](#funções-de-resumo-ou-de-agregação)
      - [CRIANDO TABELA A PARTIR DE CONSULTA](#criando-tabela-a-partir-de-consulta)
      - [CRIANDO VIEW A PARTIR DE CONSULTA](#criando-view-a-partir-de-consulta)
    - [Operar consultas usando a cláusula WHERE](#operar-consultas-usando-a-cláusula-where)
      - [CLÁUSULA WHERE E OPERADORES DA SQL](#cláusula-where-e-operadores-da-sql)
      - [RECUPERANDO DADOS COM SELECT/FROM/WHERE/ORDER BY](#recuperando-dados-com-selectfromwhereorder-by)
      - [RECUPERANDO DADOS COM O USO DO OPERADOR IN](#recuperando-dados-com-o-uso-do-operador-in)
      - [RECUPERANDO DADOS COM O USO DO OPERADOR BETWEEN](#recuperando-dados-com-o-uso-do-operador-between)
      - [RECUPERANDO DADOS COM O USO DO OPERADOR LIKE](#recuperando-dados-com-o-uso-do-operador-like)
      - [RECUPERANDO DADOS COM O USO DO OPERADOR NULL](#recuperando-dados-com-o-uso-do-operador-null)
      - [RECUPERANDO DADOS USANDO ORDENAÇÃO DOS RESULTADOS](#recuperando-dados-usando-ordenação-dos-resultados)
    - [Operar consultas envolvendo agrupamento de dados](#operar-consultas-envolvendo-agrupamento-de-dados)
      - [CONSULTAS COM GROUP BY E HAVING](#consultas-com-group-by-e-having)
      - [GRUPO DE DADOS](#grupo-de-dados)
      - [GRUPO DE DADOS COM GROUP BY](#grupo-de-dados-com-group-by)
      - [GRUPO DE DADOS COM GROUP BY E HAVING](#grupo-de-dados-com-group-by-e-having)
  - [Consulta com várias tabelas no POSTGRESQL](#consulta-com-várias-tabelas-no-postgresql)
    - [Operar consultas envolvendo junções interior e exterior](#operar-consultas-envolvendo-junções-interior-e-exterior)
      - [OPERAÇÃO DE JUNÇÃO DE TABELAS](#operação-de-junção-de-tabelas)
      - [OPERAÇÃO DE PRODUTO CARTESIANO](#operação-de-produto-cartesiano)
      - [JUNÇÃO INTERNA](#junção-interna)
      - [JUNÇÃO EXTERNA](#junção-externa)
    - [Operar subconsultas aninhadas e correlatas](#operar-subconsultas-aninhadas-e-correlatas)
      - [SUBCONSULTAS](#subconsultas)
      - [SUBCONSULTAS ANINHADAS](#subconsultas-aninhadas)
      - [SUBCONSULTAS CORRELATAS](#subconsultas-correlatas)
      - [CONSULTA CORRELACIONADA COM USO DE \[NOT\] EXISTS](#consulta-correlacionada-com-uso-de-not-exists)
    - [Operar consultas com o uso de operadores de conjunto](#operar-consultas-com-o-uso-de-operadores-de-conjunto)
      - [OPERADORES DE CONJUNTO](#operadores-de-conjunto)
      - [CONSULTAS COM O OPERADOR UNION](#consultas-com-o-operador-union)
      - [CONSULTAS COM O OPERADOR INTERSECT](#consultas-com-o-operador-intersect)
      - [CONSULTAS COM O OPERADOR EXCEPT](#consultas-com-o-operador-except)


# Banco de Dados

## Sistemas de Banco de Dados
### Reconhecer o histórico dos bancos de dados e suas tecnologias
#### DEFINIÇÃO DE BANCO DE DADOS
#### EVOLUÇÃO DOS SISTEMAS DE INFORMAÇÃO EM COMPUTADO
#### REVOLUÇÃO DOS SISTEMAS DE BANCO DE DADOS
#### PRINCIPAIS SGBDS RELACIONAIS
[Início](#inicio)

### Identificar as características dos sistemas de banco de dados (SBD)
#### DIFERENÇAS ENTRE SISTEMA DE ARQUIVOS E SISTEMA DE BANCO DE DADOS
#### VANTAGENS E DESVANTAGENS DA ABORDAGEM DE BANCO DE DADOS
#### PAPÉIS EM SISTEMAS DE BANCOS DE DADOS
[Início](#inicio)

### Descrever a arquitetura dos sistemas de gerência de banco de dados (SGBD)
#### COMPONENTES DE UM SISTEMA DE BANCO DE DADOS
#### MÓDULOS DE UM SISTEMA DE GERÊNCIA DE BANCO DE DADOS
#### UM EXEMPLO DE SGBD RELACIONAL: POSTGRESQL
[Início](#inicio)


## Projeto de Banco de Dados – Modelagem Conceitual
### Identificar as etapas de um projeto de banco de dados
#### PROJETO DE BANCO DE DADOS
#### LEVANTAMENTO DE REQUISITOS
#### PROJETO CONCEITUAL
#### PROJETO LÓGICO
#### PROJETO FÍSICO
[Início](#inicio)

### Reconhecer os elementos do diagrama de entidade e relacionamento
#### ENTIDADE
#### RELACIONAMENTO
#### ATRIBUTO
#### ESPECIALIZAÇÃO/GENERALIZAÇÃO
#### ENTIDADE ASSOCIATIVA
[Início](#inicio)

### Compreender a modelagem de entidades e relacionamentos
#### OBJETIVOS AO CONSTRUIR UM DER
#### MODELAGEM DE ENTIDADES E RELACIONAMENTOS
#### MODELAGEM DE ENTIDADE ISOLADA
#### MAIS SOBRE MODELAGEM DE ENTIDADES E RELACIONAMENTOS
[Início](#inicio)

### Compreender a modelagem de atributos
#### ATRIBUTO X ENTIDADE
#### ATRIBUTO X ESPECIALIZAÇÃO
#### ATRIBUTO OPCIONAL
#### ATRIBUTO MULTIVALORADO
#### ATRIBUTO X REDUNDÂNCIAA
#### TRIBUTO COMPOSTO
[Início](#inicio)


## Projeto De Banco De Dados – Modelagem Lógica E Física
### Identificar os elementos do modelo relacional
#### MODELO RELACIONAL
#### COMPONENTES DE UMA TABELA
#### CHAVE PRIMÁRIACHAVE ESTRANGEIRA
#### ESQUEMA DIAGRAMÁTICO DE BANCO DE DADOS RELACIONAL
#### 
[Início](#inicio)

### Diferenciar formas normais
#### NORMALIZAÇÃO
#### PRIMEIRA FORMA NORMAL (1FN)
#### SEGUNDA FORMA NORMAL (2FN)
#### TERCEIRA FORMA NORMAL (3FN)
#### 
[Início](#inicio)

### Aplicar o mapeamento conceitual-lógico
#### MAPEAMENTO CONCEITUAL-LÓGICO
#### MAPEAMENTO DE ENTIDADES
#### MAPEAMENTO DE RELACIONAMENTOS
#### MAPEAMENTO DE ATRIBUTOS MULTIVALORADOS
#### MAPEAMENTO DE ESPECIALIZAÇÃO/GENERALIZAÇÃO
[Início](#inicio)

### Identificar aspectos físicos para implementação do modelo no SGBD
#### CONSULTAS
#### TRANSAÇÕES
#### INDEXAÇÃO EM BANCO DE DADOS
#### CONSULTAS ENVOLVENDO MAIS DE UMA TABELA
#### DESNORMALIZAR PARA GANHAR DESEMPENHO
[Início](#inicio)


## Criação e manipulação de objetos no PostgreSQL
### Compreender o processo de instalação do PostgreSQL
#### BREVE HISTÓRICO
#### ARQUITETURA DO POSTGRESQL
#### INSTALAÇÃO DO POSTGRESQL NO LINUX
#### INSTALAÇÃO DO POSTGRESQL NO WINDOWS
#### INTERFACES PARA INTERAGIR COM O POSTGRESQL
#### CRIANDO DATABASES COM O PGADMIN 4 E COM O PSQL
[Início](#inicio)

### Empregar comandos para criação e alteração de tabelas
#### BREVE HISTÓRICO DA SQL
#### ACESSO AO POSTGRESQL
#### CRIANDO UM BANCO DE DADOS
#### CRIANDO TABELASTIPOS DE DADOS
#### ALTERAÇÃO DE TABELA
#### CRIAÇÃO E ALTERAÇÃO DE TABELAS RELACIONADAS
[Início](#inicio)

### Empregar comandos para manipular linhas nas tabelas
#### MANIPULAÇÃO DE LINHAS NAS TABELAS
#### INSERÇÃO DE LINHAS EM TABELA
#### MECANISMO DE CHAVE PRIMÁRIA EM AÇÃO
#### ATUALIZAÇÃO DE LINHAS EM TABELA
#### ATUALIZAÇÃO DE COLUNA CHAVE PRIMÁRIA
#### REMOÇÃO DE LINHAS EM TABELA
[Início](#inicio)

### Empregar comandos de controle de transação
#### TRANSAÇÕES EM BANCO DE DADOS
#### TRANSAÇÕES NO POSTGRESQL
#### UM POUCO MAIS SOBRE ATUALIZAÇÃO TEMPORÁRIA
#### UM POUCO MAIS SOBRE TRANSAÇÃO DE LEITURA
[Início](#inicio)


## Consultas em uma Tabela no Postgresql
### Operar consultas com o comando SELECT
#### ESTRUTURA BÁSICA DE UM COMANDO SELECT
#### FUNÇÕES DE DATA E HORA
#### FUNÇÕES DE RESUMO OU DE AGREGAÇÃO
#### CRIANDO TABELA A PARTIR DE CONSULTA
#### CRIANDO VIEW A PARTIR DE CONSULTA
[Início](#inicio)

### Operar consultas usando a cláusula WHERE
#### CLÁUSULA WHERE E OPERADORES DA SQL
#### RECUPERANDO DADOS COM SELECT/FROM/WHERE/ORDER BY
#### RECUPERANDO DADOS COM O USO DO OPERADOR IN
#### RECUPERANDO DADOS COM O USO DO OPERADOR BETWEEN
#### RECUPERANDO DADOS COM O USO DO OPERADOR LIKE
#### RECUPERANDO DADOS COM O USO DO OPERADOR NULL
#### RECUPERANDO DADOS USANDO ORDENAÇÃO DOS RESULTADOS
[Início](#inicio)

### Operar consultas envolvendo agrupamento de dados
#### CONSULTAS COM GROUP BY E HAVING
#### GRUPO DE DADOS
#### GRUPO DE DADOS COM GROUP BY
#### GRUPO DE DADOS COM GROUP BY E HAVING
[Início](#inicio)


## Consulta com várias tabelas no POSTGRESQL
### Operar consultas envolvendo junções interior e exterior
#### OPERAÇÃO DE JUNÇÃO DE TABELAS
#### OPERAÇÃO DE PRODUTO CARTESIANO
#### JUNÇÃO INTERNA
#### JUNÇÃO EXTERNA
[Início](#inicio)

### Operar subconsultas aninhadas e correlatas
#### SUBCONSULTAS
#### SUBCONSULTAS ANINHADAS
#### SUBCONSULTAS CORRELATAS
#### CONSULTA CORRELACIONADA COM USO DE [NOT] EXISTS
[Início](#inicio)

### Operar consultas com o uso de operadores de conjunto
#### OPERADORES DE CONJUNTO
#### CONSULTAS COM O OPERADOR UNION
#### CONSULTAS COM O OPERADOR INTERSECT
#### CONSULTAS COM O OPERADOR EXCEPT
[Início](#inicio)
