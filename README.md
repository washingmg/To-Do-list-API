# 📝 To‑Do‑List API

API RESTful em Node.js/Express, usando MySQL com Sequelize e autenticação de usuários.

> Baseado no projeto de Lucas Ângelo Oliveira Martins Rocha ([github.com/Lucas-Angelo/todosimple-api-nodejs](https://github.com/Lucas-Angelo/todosimple-api-nodejs)), licenciado sob [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/).

---

## 📚 Tecnologias

- Node.js  
- Express.js  
- Sequelize ORM  
- MySQL  
- yup (validação de dados)  
- JsonWebToken (autenticação via token)  
- Docker (opcional)  

---

## 🚀 Funcionalidades

- Registro de usuários (username + senha, validação com `yup`)  
- Login com geração de JWT  
- CRUD de tarefas (_todos_) associadas ao usuário autenticado  
- Controle de acesso: cada usuário só pode manipular suas próprias tarefas  
- Respostas padronizadas com códigos HTTP adequados (200, 201, 204, 401, 403, 422, 500)

---

## ⚙️ Pré‑requisitos

- Node.js (versão 14+)  
- MySQL rodando (ou Docker com container MySQL)
- (Opcional) Docker & Docker Compose  

---

## 🛠️ Instalação

1. Clone o repositório:

```bash
git clone https://github.com/washingmg/To-Do-list-API.git
cd To-Do-list-API
