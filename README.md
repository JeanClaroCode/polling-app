# Enquete em Tempo Real com Fastify, Prisma e Redis

Sistema de enquetes em tempo real desenvolvido com Fastify, Prisma e Redis, utilizando PostgreSQL para armazenamento eficiente.

## Tecnologias Utilizadas

- **Framework Web:** Fastify
- **Banco de Dados:** PostgreSQL (via Prisma)
- **Cache:** Redis
- **Comunicação em Tempo Real:** WebSocket
- **Gerenciamento de Dependências:** npm
- **ORM (Object-Relational Mapping):** Prisma
- **Validação de Dados:** Zod
- **Integração com Banco de Dados:** Prisma Client
- **Controle de Votação:** Redis e Prisma
- **Persistência de Dados:** Prisma Client
- **Containerização:** Docker

## Funcionalidades e Aprendizados
- Desenvolvimento de uma aplicação de enquetes em tempo real com Fastify.
- Utilização do Prisma como ORM para interação eficiente com PostgreSQL.
- Implementação de WebSocket para atualizações em tempo real durante as votações.
- Uso de Redis para gerenciamento de cache, controle de votação e armazenamento de rankings.
- Possibilidade de votar apenas uma vez em cada enquete.
- Opção de alterar o voto, com exclusão do voto anterior ao selecionar uma nova opção.
- Geração dinâmica de um ranking das opções mais votadas.
- Integração de Docker para facilitar a implantação e execução do projeto.
- Utilização de Zod para validação de dados e aplicação de princípios SOLID.
- Arquitetura eficiente com controle de votação, persistência de dados e atualizações em tempo real.

## Como Executar
1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```

2. Entre no diretório do projeto:
    ```bash
    cd nome-do-repositorio
    ```

3. Inicie os serviços usando Docker Compose:
    ```bash
    docker-compose up
    ```

4. O servidor estará disponível em http://localhost:3333.

## Autor
- GitHub: [@JeanClaroCode](https://github.com/JeanClaroCode)
- LinkedIn: [Jean Claro](https://www.linkedin.com/in/jeanclaro/)
