# 🚚 MadCenter - Sistema de Gerenciamento de Entregas e Rotas

Sistema web desenvolvido para auxiliar o gerenciamento de pedidos, clientes e rotas de entrega, proporcionando mais organização e eficiência no processo logístico.

---

## 📖 Sobre o Projeto

O **MadCenter** é uma aplicação web criada como atividade da disciplina de **Programação Web**, utilizando uma arquitetura moderna baseada em **Node.js**, **Express** e **Supabase**.

O sistema permite o gerenciamento de pedidos e entregas através de uma interface intuitiva, contando com autenticação de usuários, operações CRUD e integração com banco de dados em nuvem.

---

## 🎯 Objetivo

Desenvolver uma aplicação completa utilizando tecnologias atuais de desenvolvimento web, aplicando conceitos de:

* Arquitetura Cliente-Servidor
* Autenticação de Usuários
* Gerenciamento de Estado
* Componentização
* CRUD Completo
* Integração com Banco de Dados
* Organização e Boas Práticas de Projeto

---

# 🛠 Tecnologias Utilizadas

### Front-end

* HTML5
* CSS3
* JavaScript

### Back-end

* Node.js
* Express.js

### Banco de Dados

* Supabase

### Ferramentas

* Git
* GitHub
* Visual Studio Code

---

# ✨ Funcionalidades Implementadas

## 🔐 Autenticação

* Login de usuário
* Controle de sessão
* Gerenciamento de estado com Pinia

## 📦 Gerenciamento de Pedidos

* Cadastro de pedidos
* Listagem de pedidos
* Edição de pedidos
* Exclusão de pedidos

## 🚚 Gerenciamento de Rotas

* Organização das entregas
* Controle das rotas cadastradas

## 👨‍💼 Gerenciamento de Motoristas

* Cadastro e gerenciamento dos motoristas
* Associação às rotas

## 📊 Dashboard

* Visualização das informações do sistema
* Navegação entre as telas

---

# 🗂 Estrutura do Projeto

```text
MadCenter/

├── frontend/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── router/
│   │   ├── services/
│   │   ├── stores/
│   │   └── views/
│   └── package.json
│
├── backend/
│   ├── src/
│   ├── routes/
│   ├── controllers/
│   ├── services/
│   └── package.json
│
└── README.md
```

---

# 🖥️ Telas do Sistema

* Login
* Dashboard
* Cadastro de Pedidos
* Listagem de Pedidos
* Cadastro de Motoristas
* Gerenciamento de Rotas

> Adicione aqui os prints do sistema:

```markdown
![Login](./prints/login.png)

![Dashboard](./prints/dashboard.png)

![Pedidos](./prints/pedidos.png)

![Rotas](./prints/rotas.png)
```

---

# ⚙️ Como Executar o Projeto

## Clonar o repositório

```bash
git clone LINK_DO_GITHUB
```

## Front-end

```bash
cd frontend
npm install
npm run dev
```

## Back-end

```bash
cd backend
npm install
npm start
```

## Configuração do Supabase

Criar um arquivo `.env` contendo:

```env
SUPABASE_URL=SUA_URL
SUPABASE_KEY=SUA_CHAVE
```

---

# 🏗 Arquitetura

O projeto segue uma arquitetura Cliente-Servidor:

```text

    Express API
        │
        ▼
    Supabase
```

---

# 🎥 Vídeo Demonstrativo

A demonstração completa do sistema pode ser acessada no link abaixo:

**Vídeo:**
https://drive.google.com/file/d/1ZDrEsiqBG1vXn29PJGMHGCUJGdEMdzTn/view?usp=sharing

---

# 👨‍💻 Integrantes

* **Nicolas Alexandrino**
* **Italo Gabriel**

---

# 📚 Disciplina

**Programação Web**

Trabalho Prático — Desenvolvimento de Sistema Web com Node.js + Express + Supabase.

---

# 📄 Licença

Projeto desenvolvido exclusivamente para fins lucrativos do Grupo TriCod3x.
