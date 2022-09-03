# Prova de Conceito Spring/ORM/BD (Programa Porto Digital)

### Conceitos

#### O que é uma Prova de conceito ?

> Uma prova de conceito (ou em inglês Proof of Concept - PoC) nada mais é a prática de criar uma mini aplicação para testar algum conceito, o objetivo desse repositório é apresentar um guia para criação de uma prova de conceito para testar/aprender/treinar conceitos de Spring Framework, ORM e Banco de dados.

#### O que é um ORM ?

> Object-Relational Mapping (ORM), em português, mapeamento objeto-relacional, é uma técnica para aproximar o paradigma de desenvolvimento de aplicações orientadas a objetos ao paradigma do banco de dados relacional. 

#### O que é Spring ?

> Spring é um framework Java criado com o objetivo de facilitar o desenvolvimento de aplicações, explorando, para isso, os conceitos de Inversão de Controle e Injeção de Dependências.

##### Links uteis

- [Site oficial Spring Framework (Inglês)](https://spring.io/)
- [O que é Spring ? (Português)](https://www.treinaweb.com.br/blog/o-que-e-o-spring)

### Definição PoC

> A proposta da PoC é a criar uma mini aplicação utilizando baseado no seguinte modelo ER

![Diagrama sem nome drawio](https://user-images.githubusercontent.com/11702372/188249122-068aaeec-cde3-473e-a185-5ab790ebb947.png)

> O modelo é simples e possui apenas 3 entidades, uma relação 1 para N e uma relação N para N. Atentar para a relação forte e para as chaves primárias.

#### O que fazer nessa PoC ?

**Recomendação**: Antes de começar os passos a seguir entender/ler o que é o [Maven](https://www.devmedia.com.br/introducao-ao-maven/25128)

Passos:
1. Criar um script SQL para construir as tabelas que representem as entidades e relações descritas no modelo
2. Criar um projeto usando Spring 

> Dica: Ler [esse](https://dicasdejava.com.br/spring-boot-como-criar-a-estrutura-de-uma-aplicacao-web-do-zero-com-spring-initializr/) artigo sobre primeira aplicação em spring

3. Criar os objetos que representem as estruturas das tabelas 

> Dica: Ler [esse](https://www.devmedia.com.br/modelagem-de-dados-tutorial/20398) artigo sobre modelagem de dados

4. Ler sobre JPA e Spring Data para criar o CRUD e fazer funcionar as operações.

#### Configuração básica Spring Initialize 

![image](https://user-images.githubusercontent.com/11702372/188285975-0738abca-f7d7-46e9-b0ed-4e9fc42e5d15.png)

> Pode mudar a versão do java e as informções do project metadata, porém não recomendo alterar as outras configurações agora.

#### Links Uteis

- [Spring Initializr](https://start.spring.io/)
- [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
- [Consuming a RESTful Web Service](https://spring.io/guides/gs/consuming-rest/)
- [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)
- [Accessing JPA Data with REST](https://spring.io/guides/gs/accessing-data-rest/)
