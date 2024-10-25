# DSList

O DSList é um projeto desenvolvido durante um intensivão de Java Spring, ministrado pelo professor Nélio Alves. O objetivo do projeto é criar uma API para gerenciar listas de jogos, permitindo operações como busca de jogos, manipulação de listas e troca de posições dos jogos em uma lista.

## Estrutura do Projeto

A API possui dois controladores principais:

1. **GameController**
   - **GET /games**: Retorna uma lista de todos os jogos disponíveis.
   - **GET /games/{id}**: Retorna os detalhes de um jogo específico.

2. **GameListController**
   - **GET /lists**: Retorna uma lista de todas as listas de jogos.
   - **GET /lists/{listId}/games**: Retorna os jogos de uma lista específica.
   - **POST /lists/{listId}/replacement**: Move um jogo de uma posição para outra na lista especificada.

## Tecnologias Utilizadas

- **Java**
- **Spring Boot**
- **JPA/Hibernate**
- **H2 Database**
