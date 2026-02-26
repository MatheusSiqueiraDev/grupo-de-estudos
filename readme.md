# 🚀 Projeto do Grupo de Estudos – API Loja & Clientes

## 📌 Objetivo

Desenvolver uma **API REST** que simule o funcionamento de uma loja online, contendo:

- Cadastro de usuários
- Gestão de produtos
- Realização de pedidos
- Controle de permissões entre **Usuário** e **Lojista**

Cada participante pode utilizar a tecnologia que preferir (Node.js, Java, C#, Python, Go, etc.).

---

# 🏗️ Requisitos da API

## 📍 Entidades Principais

### 👤 Usuário
- id
- nome
- email
- senha
- tipo (USER ou LOJISTA)

### 📦 Produto
- id
- nome
- descrição
- preço
- estoque

### 🧾 Pedido
- id
- usuário
- lista de produtos
- valor total
- status

---

# 🔗 Endpoints Obrigatórios

## 👤 Usuário

- `POST /users` → Cadastrar usuário  
- `PUT /users/{id}` → Editar usuário  
- `DELETE /users/{id}` → Excluir usuário  
- `GET /users/{id}` → Consultar usuário  

## 📦 Produto

- `POST /products` → Cadastrar produto  
- `PUT /products/{id}` → Editar produto  
- `DELETE /products/{id}` → Excluir produto  
- `GET /products` → Listar produtos  

## 🧾 Pedido

- `POST /orders` → Fazer pedido  
- `GET /orders/{id}` → Consultar pedido  
- `GET /orders` → Listar pedidos  

---

# 🔐 Regras de Permissão

## 👤 Usuário Comum

- Pode se cadastrar  
- Pode editar suas próprias informações  
- Pode deletar apenas sua própria conta  
- Pode fazer pedido  
- Pode consultar apenas seus próprios pedidos  

## 🏪 Lojista

- Pode cadastrar produtos  
- Pode editar produtos  
- Pode excluir produtos  
- Pode consultar qualquer pedido  
- Pode excluir qualquer usuário  

---

# 💡 Requisitos Técnicos

- A API deve seguir padrão REST
- Deve possuir autenticação (JWT ou similar)
- Separação de camadas (Controller, Service, Repository)
- Banco de dados relacional ou não relacional
- Tratamento de erros adequado
- Documentação da API (Swagger é diferencial)

---

# 🎨 Front-End

O front-end é livre:

- Web (React, Angular, Vue)
- Mobile (Flutter, React Native)
- CLI
- Ou apenas Postman/Insomnia

Seja criativo 🚀

---

# 🌱 Como Participar

## 1️⃣ Faça um Fork do Projeto

1. Acesse o repositório original no GitHub  
2. Clique no botão **Fork** (canto superior direito)
3. Escolha sua conta
4. O projeto será copiado para o seu perfil

> O fork cria uma cópia do repositório original na sua conta do GitHub.

---

## 2️⃣ Clone o Seu Fork

No terminal:

```bash
git clone https://github.com/MatheusSiqueiraDev/grupo-de-estudos
```

# 💬 Comunidade & Code Review

Quer evoluir mais rápido? 🚀  

Participe do nosso grupo no Discord para:

- 💻 Fazer code review
- 📢 Apresentar seu projeto
- 🤝 Tirar dúvidas com o grupo
- 🧠 Discutir arquitetura e boas práticas
- 🔥 Evoluir como desenvolvedor(a)

## 🎯 Como funciona?

- Cada participante pode solicitar code review.
- Podemos marcar apresentações rápidas do projeto.
- Feedback será focado em:
  - Organização de código
  - Arquitetura
  - Boas práticas
  - Clareza e legibilidade

## 🔗 Entre no Discord

👉 [Clique aqui para entrar no grupo](https://discord.gg/6n527gZ3pJ)

---

Bora construir projetos de nível profissional juntos 🚀