# 🧠 API Tickets – Fundamentos do Node.js

Este projeto foi desenvolvido com Node.js, com o objetivo de aplicar os principais conceitos de servidores HTTP nativos, manipulação de dados e criação de uma API sem frameworks externos.

## 📚 Conteúdo 

Neste projeto foram abordados:

- Criação e configuração de servidores HTTP utilizando Node.js puro
- Implementação de rotas com parâmetros dinâmicos
- Manipulação de dados via `fs` com persistência em arquivo JSON
- Middlewares para interceptação e modificação de requisições


---

## 🚀 Funcionalidades da API

### 📌 Endpoints disponíveis

#### Criar ticket
```http
POST /tickets
GET /tickets
GET /tickets?status=open
PUT /tickets/:id
PATCH /tickets/:id/close
DELETE /tickets/:id
