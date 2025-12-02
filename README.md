# Full_stack_cadastro

Aplicação **Full Stack** para cadastro de pessoas, composta por um **front-end em React + Vite** e um **back-end em Node.js + Express + Prisma + MongoDB**.

Este projeto foi desenvolvido para fins de estudo, organização de dados e demonstração de habilidades full stack.

---

## 🚀 Tecnologias utilizadas

### **Front-end**

- React
- Vite
- Axios
- HTML/CSS/JS
- Hooks (useState, useEffect)

### **Back-end**

- Node.js
- Express
- Prisma ORM
- MongoDB
- Cors
- Body-parser

---

## 📌 Funcionalidades

- Cadastro de pessoas
- Listagem de registros
- Integração total entre front-end e back-end
- Persistência dos dados em banco MongoDB
- Rotas modernas usando Express
- Prisma como ORM para facilitar a modelagem e manutenção

---

## 📁 Estrutura do Projeto

Full_stack_cadastro/
│
├── front-end/
│ ├── src/
│ ├── public/
│ ├── package.json
│ └── vite.config.js
│
├── back_end/
│ ├── prisma/
│ │ └── schema.prisma
│ ├── server.js
│ ├── package.json
│ └── .env (não versionado)
│
└── README.md

---

## 🖥️ Como rodar o front-end

No diretório **/front-end**:

```bash
npm install
npm run dev

 A aplicação abrirá em:

👉 http://localhost:5173/


🛠️ Como rodar o back-end

No diretório /back_end:
npm install
npx prisma generate
node server.js

O servidor iniciará em:

👉 http://localhost:3000/


🔌 Endpoints da API
Criar pessoa
POST /usuarios




Body (JSON):
{
  "nome": "Seu Nome",
  "idade": 30
}


Listar pessoas
GET /usuarios


🛢️ Banco de Dados

Banco: MongoDB

Gerenciado via Prisma

Configure seu .env dentro de /back_end:
DATABASE_URL="mongodb+srv://..."


Prints da aplicação (![alt text](image.png))





```
