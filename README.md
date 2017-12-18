# APIRest
API Rest, para fornecer toda informaçao relevante de Moçambique

### Introdução

Todo o Programador, preci

### 1. O que é a APIRest?

A [APIRest é uma API Rest e não restFul](https://pt.stackoverflow.com/questions/45783/o-que-%C3%A9-rest-e-restful), desenhado e desenvolvido por estudantes do Curso de Informática da Universidade Eduardo Mondlane, para fornecer dados principalmente para a comunidade estudantil.

Esses dados incluem toda a divisão Administrativa de Moçambique, Todas Instituições de Formação e Permite o armazenamento de diversos tipos de fotos.

### 2. O que a MozAPIRest disponibiliza?

Os seguintes dados: 

* Divisão Administrativa de Moçambique
* Instituições de Formação
* Serviço de Armazenamento de Fotos.
* Outras Propostas..

### 3. Quem pode fazer uso desses dados?

Qualquer um, ou qualquer aplicação pode fazer uso dos dados da API, desde que tenha a chave de desenvolvedor gerado ao se criar a conta do utilizador.

Por questoes de segurança, as chaves dos desenvolvedores dão acesso a uma parte da API por default, mas pode extender o acesso para as outras partes se o dev desejar e é necessario registar a aplicação que está consumindo os dados da API.

Visto  que os  dados são fornecidos como API, qualquer outra aplicação pode fazer uso das rotas disponiveis para a sua chave e buscar os dados que ele deseja, ex.: a lista de todas as cidades de Moçambique ou a lista de todos bairros da Provincia de Gaza.

Todas aplicações só podem acessar(buscar) os dados usando os metodos `GET` ou `POST`, mas nenhuma aplicacao tem permissao para fazer insert.


### 4. Como esses dados sao registados e actualizados?

Os dados são registados no site da API por qualquer desenvolvedor ou entidade competente, mas posteriormente os mesmos devem ser confirmados por entidades competentes. Essa medida, visa evitar inconsistencia de dados.

Todos os dados na API, possuem um estado (`confirmado` e `não confirmado`), Os confirmados são os que ja foram confirmados pelas entidades competentes.

As entidades competentes e as pessoas indicadas farão a verifição de se os dados cadastrados são verdadeiros e não duplicados e de seguida poderão marcar esses dados como confirmados.

A actualização de um certo dado é feita pela entidade competente ou pelo desenvolvedor que o cadastrou. Os outros desenvolvedores não possuem nenhuma permissão de modificacão dos dados por outros cadastrados.


### 5. Como personalizar os dados a minha necessidade?

## Dados a serem registados e disponibilizados na/pela API

* Divisão Administrativa de Moçambique
* Instituições de Formação
* Serviço de Armazenamento de Fotos.

### Divisão Administrativa de Moçambique

Dados ou funcionalidades a serem implementadas:

* Registo de Provincias
* Registo de Cidades
* Registo de Distritos
* Registo de Postos Administrativos
* Registo de Distritos Urbanos
* Registo de Bairros

* Registo de Pessoas e organizações responsaveis em validar os dados da DA de Moz.

### Instituições de Formação

Dados ou funcionalidades a serem implementadas:

* Registo de Universidades
* Registo de Escolas
* Registo de Institutos
* Registo de Escolinhas
* Registo de Centros de formação profissional
* Registo de Outros Centros

* Registo de Pessoas e Organizações responsaveis em validar os dados

### Serviço de Armazenamento de Fotos.

Dados ou funcionalidades a serem implementadas:

* Registo de Fotos de Pessoas das Provincias
* Registo de Fotos dos locais das Provincias
* Registo de Fotos de Obras das Provincias
* Registo de Fotos de Trabalhos/Portfolios de Moçambicanos
* Registo de Fotos de Curiosidades de Moçambique
* Registo dos responsaveis em validar os dados

### A API a ser desenvolvida deve ter as seguintes funcionalidades:
* Registar os dados das divisoes administrativas de Moçambique
* Registar os dados das instituicoes de formaçao de Moçambique
* Atribuir privilegios a cada Utilizador que cadastra os dados na API
* Atribuir privilegios organizacionais aos utilizador
* Permitir que certas organizacoes responsaveis cadastrem e validem os dados
* Para utilizadores clientes da API  deve se gerar um Token, ou codigo para validacao.
* Garantir a segurança minima de dados
* Garantir-se que nao se mostra nenhum erro ao utilizador
* 
