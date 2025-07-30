# 🔗 Link Shortener

Um projeto fullstack de encurtador de links com estatísticas de acesso. Criado com o objetivo de servir como portfólio, este projeto demonstra habilidades em backend, frontend, banco de dados, autenticação, segurança e deploy.

## 🚀 Funcionalidades

- Encurtar links longos
- Redirecionamento automático com base no hash
- Contador de cliques por link
- Interface web moderna
- Login de usuário (opcional)
- Dashboard com estatísticas

## 🛠️ Tecnologias

### Frontend:
- React
- TailwindCSS

### Backend:
- Node.js + Express
- PostgreSQL
- JWT para autenticação

### Deploy:
- Vercel (Frontend)
- Render ou Railway (Backend)
- Railway/Supabase (Banco de Dados)

## 📁 Estrutura de Pastas

```
link-shortener-project/
├── backend/                  # API RESTful
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── index.js
│
├── frontend/                 # Interface em React
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   └── tailwind.config.js
│
├── docs/                     # Documentação e imagens
├── .env.example              # Variáveis de ambiente (modelo)
└── README.md
```

---

# 📦 backend/README.md

## 🔙 Link Shortener API

API desenvolvida com Node.js, Express e PostgreSQL para encurtar URLs, redirecionar, registrar acessos e autenticar usuários.

### 🔧 Tecnologias
- Node.js
- Express
- PostgreSQL
- Prisma ORM (opcional)
- JWT (auth)

### 📄 Principais rotas:
- `POST /shorten` — Recebe URL e retorna link encurtado
- `GET /:hash` — Redireciona para URL original
- `GET /stats/:hash` — Estatísticas do link
- `POST /login` — Login do usuário

### 🚀 Como rodar localmente
```bash
cd backend
npm install
cp .env.example .env
npm run dev
```

---
