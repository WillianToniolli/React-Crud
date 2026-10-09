# Cadastro de usuários com React

Aplicação web de cadastro de usuários com as quatro operações básicas (CRUD): **incluir, listar, alterar e excluir**. O front-end foi feito em React e consome uma API REST simulada com json-server.

Projeto desenvolvido durante meus estudos de React.

## Funcionalidades

- Formulário para cadastrar nome e e-mail
- Listagem dos usuários cadastrados em tabela
- Edição e exclusão de registros
- Navegação entre páginas com React Router
- Layout com cabeçalho, menu lateral e rodapé

## Tecnologias

**Front-end**
- React 18
- React Router
- Axios (requisições HTTP)
- Bootstrap 4 e Font Awesome

**Back-end**
- json-server (API REST simulada a partir de um arquivo `db.json`)

## Estrutura

```
backend/
  db.json          # "banco de dados" com os usuários
frontend/
  src/
    components/
      home/        # página inicial
      user/        # tela de cadastro (UserCrud)
      template/    # Header, Nav, Main, Footer, Logo
    main/          # App e rotas
```

## Como executar

Em um terminal, suba a API:

```bash
cd backend
npm install
npm start        # API em http://localhost:3001/users
```

Em outro terminal, suba o front-end:

```bash
cd frontend
npm install
npm start        # aplicação em http://localhost:3000
```

---
Desenvolvido por [Willian Toniolli](https://www.linkedin.com/in/willian-toniolli-76303617b/)
