# API de Cadastro de Usuários

Este repositório contém uma API desenvolvida em JavaScript utilizando Node.js, MongoDB e a biblioteca Prisma. A API fornece um CRUD completo (Create, Read, Update, Delete) para gerenciamento de usuários.

## Status do Projeto

🚧 Em desenvolvimento 🚧

Esta API está em fase de desenvolvimento e será utilizada em um projeto posterior construído com React.js.

## Tecnologias Utilizadas

- **Node.js** - Ambiente de execução JavaScript no servidor
- **MongoDB** - Banco de dados NoSQL
- **Prisma** - ORM para interação com o banco de dados
- **Express.js** - Framework minimalista para APIs em Node.js

## Funcionalidades

- Criar novos usuários (Create)
- Listar todos os usuários cadastrados (Read)
- Atualizar informações de um usuário (Update)
- Remover usuários do sistema (Delete)

## Como Executar o Projeto

1. **Clone o repositório**
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. **Instale as dependências**
   ```sh
   npm install
   ```

3. **Configure o banco de dados**
   - Certifique-se de ter o MongoDB instalado e rodando
   - Configure as variáveis de ambiente no arquivo `.env`:
     ```env
     DATABASE_URL=mongodb+srv://usuario:senha@cluster.mongodb.net/seuBanco
     ```

4. **Execute as migrações do Prisma**
   ```sh
   npx prisma migrate dev
   ```

5. **Inicie a API**
   ```sh
   node server.js
   ```

## Rotas da API

- **GET** `/usuarios` - Retorna a lista de usuários
- **POST** `/usuarios` - Cria um novo usuário
- **PUT** `/usuarios/:id` - Atualiza um usuário pelo ID
- **DELETE** `/usuarios/:id` - Remove um usuário pelo ID

## Contribuição

Se desejar contribuir com este projeto, fique à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

