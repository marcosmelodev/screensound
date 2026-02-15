#  🎵 ScreenSound – Gerenciamento de Músicas

Aplicação backend em Java desenvolvida para gerenciamento de músicas, artistas e álbuns, com persistência em banco de dados relacional.
O projeto foi criado com foco em Programação Orientada a Objetos, Spring Data JPA e modelagem de relacionamentos, simulando um cenário real de aplicação backend.


###  📌 Visão Geral

O ScreenSound é uma aplicação que permite cadastrar, consultar, editar e remover músicas, explorando o relacionamento entre entidades e o uso de um banco de dados relacional para persistência dos dados.

O projeto foi desenvolvido como parte do estudo de persistência de dados e consultas com JPA, aplicando boas práticas comuns no desenvolvimento backend com Java.


###  ⚙️ Funcionalidades

*  Cadastro de músicas com informações como:

    *  Título

    *  Artista

    *  Gênero

    *  Duração

*  Listagem de músicas cadastradas

*  Filtro de músicas por artista ou gênero

*  Atualização de dados de músicas existentes

*  Remoção de músicas

*  Modelagem de relacionamento entre músicas e álbuns
  

###  🧱 Estrutura e Conceitos Aplicados

*  Entidades JPA para mapeamento objeto-relacional

*  Relacionamentos (@OneToMany, @ManyToOne)

*  Repositórios Spring Data JPA

*  Consultas derivadas e personalizadas

*  Separação de responsabilidades

*  Persistência em banco de dados relacional
  

###  🛠️ Tecnologias Utilizadas

*  Java

*  Spring Boot

*  Spring Data JPA

*  PostgreSQL

*  Maven
  

###  ▶️ Como Executar
**Pré-requisitos**

*  JDK instalado

*  PostgreSQL configurado

*  Maven

**Passos**

1.  Clone o repositório:

        git clone https://github.com/marcosmelodev/screensound.git

2.  Configure o banco de dados PostgreSQL no arquivo application.properties ou application.yml.

3.  Execute a aplicação pela IDE ou via Maven.


###  🎯 Objetivo do Projeto

Este projeto faz parte do meu portfólio backend e tem como objetivos principais:

*  Consolidar fundamentos de Java e Spring Data JPA

*  Praticar persistência e consultas em banco de dados

*  Trabalhar modelagem de entidades e relacionamentos

*  Simular desafios comuns do dia a dia de um desenvolvedor backend


###  👨‍💻 Autor

Marcos Melo

Estudante de Análise e Desenvolvimento de Sistemas
